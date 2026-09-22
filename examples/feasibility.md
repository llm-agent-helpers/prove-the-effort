# feasibility, before and after

## before (no skill)

> **user:** thinking of porting the engine to wasm via emscripten. thoughts?
>
> **agent:** That's an exciting direction! WebAssembly offers near-native performance and broad browser support. Here are some considerations:
> - Performance: WASM is typically 1.5-2x slower than native
> - Graphics: you'll need WebGL2 which has some limitations
> - File I/O: browser sandboxing will require adaptation
> - Build tooling: Emscripten has a learning curve
>
> Would you like me to outline a migration plan?

nothing in that is checkable. it's a list of things that are true of every wasm port ever. the user still doesn't know if *this* port is feasible.

## after (prove-the-effort)

> **user:** thinking of porting the engine to wasm via emscripten. thoughts?
>
> **agent:** i don't think it's feasible yet, and the reason's specific. what's the one thing that has to load and render for you to call the port alive? for this engine i'd say `end_m01aa` loads, a room draws, trask is on screen, smoke exits zero. has that been attempted?
>
> **user:** no, i've only got the build compiling
>
> **agent:** then the port's not feasible yet, it's compiling. two blockers i'd expect before that room draws, both are measurements not opinions: does the emscripten build actually hit the asyncify call chain for archive reads (`ASYNCIFY_ONLY=['main']` misses it every time, you'll see it hang on the first lazy load), and does webgl2 choke on the bgr uploads (it will, there's no geometry shader path either). run the room load, paste what it does. if it hangs on archive read that's asyncify and the fix is one flag. if it hangs on texture upload that's bgr and the fix is a swizzle in the loader.
>
> **user:** ok ran it, hangs after "loading module"
>
> **agent:** asyncify. `-s ASYNCIFY_ONLY` is missing the archive reader. add the reader's symbol list or drop ASYNCIFY_ONLY entirely for now and eat the binary size. rerun.
>
> **user:** room renders. trask is there. no smoke though
>
> **agent:** feasible. smoke's a particle system, separate problem, park it. you've got a rendered room from an emscripten build, that's the referent.

what changed: the question was "what's the one thing that has to work," not "here are all the things that might not." the answer either exists or it doesn't, and once it exists the plan's feasible and the rest is work.
