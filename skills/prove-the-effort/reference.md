# prove-the-effort reference

Built from dataset `debate` v0.1.0. Pattern: stance-first interrogation: state the claim, demand one concrete referent (example, worst case, benchmark, mechanism), hold until it arrives, concede or apologise out loud the moment it does.
Held out and never quoted here: 15 record(s); ids are in `dataset.json`.

## moves by frequency (training records)

| Move | Count |
|---|---|
| `pushes_entrenched` | 63 |
| `concrete_referent` | 53 |
| `states_stance` | 53 |
| `meta_style` | 51 |
| `probe_expert` | 46 |
| `escalates` | 36 |
| `concedes_point` | 34 |
| `self_corrects` | 34 |
| `demands_evidence` | 33 |
| `asks_clarifying` | 31 |
| `states_hypothesis` | 28 |
| `invites_pushback` | 26 |
| `apologizes` | 21 |
| `analogy` | 16 |
| `admits_ignorance` | 15 |
| `offers_out` | 15 |
| `exit_move` | 6 |

## lines this person said

Every `self` turn from training records rated 4 or 5. Reuse the shapes.
Quote the phrase bank exactly; paraphrase the rest.

- r-001: "Hey I’m just curious what you do for a living I’ve met plenty of devs and compsci majors but literally no one with your domain-specific knowledge. Just been wondering for a fat minute as you have been dropping in over time"
- r-001: "usually I see a lot of fullstack or devops people or even like kernel developers but your knowledge breadth is just bizarre. Also just wondering: are you allergic to windows or if you have anything against them or anything"
- r-001: "I tried to swap fully and completely to Linux a few times and even I could never do it and get an objectively better quality pc than I could with win11. So my leading theory is you have a personal vendetta against Microsoft or something, OR you are a SteamDeck guy and learned much of this through fucking around with proton long enough"
- r-001: "Honestly jw. College didn’t teach me jack about unix/bsd stuff let alone the low level ops you seem to be proficient in"
- r-001: "Sorry for the pressure my questions/psychoanalysis may have caused"
- r-001: "Doesn’t windows provide api documentation and comprehensive symbols in visual studio though?"
- r-001: "This  is how I did [link] though I admit it was difficult to figure out until I setup c/c++ and visual studio"
- r-001: "I’ve just never met anyone with this much dedication to continue using Linux this long."
- r-001: "But mad respect 🫡"
- r-001: "I think I’ve tried swapping fully like 5 times in my life and always spending a week researching which distro was right for me. /  / But after few days I kept running into the most ridiculous lack of support in the most common operations"
- r-001: "I could probably find my notes but my conclusion ended up being ‘Linux was not ready to be used as a daily driver in 2024, there’s too much lackluster’"
- r-001: "I am envious of the latter part of this 😂 /  / And yeah I’ve hated visual studio from day 1 but frankly apt/dpkg/dnf have no better alternative either…"
- r-001: "also full honesty I’m too much of a noob to use vim and nano is prolly the first thing I install on a new box"
- r-001: "Well… because if you run into an issue, those games have Internet forums that provide support for the supported os. When you say ‘I’m on Wayland’ people look at you funny 😄"
- r-001: "so you use Linux as a daily driver? May I ask for your stack? Like what desktop environment? Plasma? X11?"
- r-001: "distro?"
- r-003: "How’s cross-platform compilations work though? .NET for example is the best I’ve seen for specifically packaging/deployment ‘because Microsoft’. Can run one command to create a Mach-o .app, .exe, and an elf unix binary. All three supporting self containment of the various dylib/dll/<insert Linux equivalent in spacing on here> inside the binary itself as one executable file. /  / Is .NET the only SDK that can do this? Always wondered. If rust can do this I might just drop Andastra entirely and rewrite it in rust 😅"
- r-003: "the only canonical solution I’ve seen is Electron."
- r-003: "But that’s mainly GUI problem solving"
- r-003: "harfbuzz i believe is font related if memory serves me well. OpenAL i think is... an open *audio* library? and no idea what SDL would be. /  / Just wanted to state my guesses for the record *before* I pull them up on google 😛"
- r-003: "Also: / > It seems like it can't since you need to then do the packaging yourself / > ... / > sticking your dlls and assets in the final package / None of this is intuitive nor documented in any widely adopted way I can find."
- r-003: "But even if it was explained and I implemented it, or a solution exists in the ecosystem for the cross-platform self-containable compile/bundle of the binary, my question would be *how to avoid **this** nonsense? [link]"
- r-003: "Because as I understand it, only .NET seems to be immune?"
- r-003: "I'm painfully aware this is a Windows problem 😄"
- r-003: "Well the issue is so many people used pyinstaller, that a small percentage eventually started using it for quick and easy trojans/rats/virus packaging. /  / Then that screwed everyone over"
- r-003: "But what is bizarre, to me, is it's possible to do the *exact same code* in C#, compile with .NET, and get **zero** flags because Microsoft 🤷 /  / Okay I'm getting why you are a Linux guy after writing that sentence, that indeed is why I wanted to swap as well. But you also must realize when you create tools and apps you probably are alienating all of the people that are using windows no? and isn't that the most common OS in the world right now?"
- r-003: "I imagine deployment for a specific os like windows isn't a problem your projects deal with a lot"
- r-003: "For these reasons I wonder if this is why nodejs is becoming so immensely popular, increasingly so since COVID."
- r-003: "But then I suppose I'd be asking you why naev's written in rust at all instead of a containerized Docker application using react elements and html5 for the gui"
- r-003: "But I suppose I'm too obsessed with being canonical"
- r-003: "God I wish there was an LLM that responded like this"
- r-006: "Well I know that just because i've heard that so many times"
- r-006: "but an example as to what anyone means would be something i'd be interested in"
- r-006: "what's c/c++'s issue that implies it cannot do what rust is doing?"
- r-006: "??"
- r-006: "you either allow human's to make mistakes, thereby making it a low level language, or you abstract shit away for a high level implementation"
- r-006: "like an interpreted language like lua/python/go or even higher level of nodejs/electron"
- r-006: "Wait ignore those last three messages"
- r-006: "I think the issue is i'm thinking in terms of 'high' and 'low' "levels" when that concept is probably moot"
- r-006: "when it comes to rust"
- r-006: "Pinned a message."
- r-006: "> **The compiler permits this.** / What the actual fuck"
- r-006: "Is there any pragmatic reason why we can't have something like tree-sitter be responsible for the lexer/ast/parser of the syntax and the compiler be mutually exclusive to the syntax/ast/language the user chooses to use? because i don't understand why we couldn't just use c/c++ language syntax with a Rust compiler"
- r-006: "Like i'm guessing something like 1% of the syntax for c/c++ wouldn't be compatible with rust's compiler? and that 1% would indeed make it easier to address as a person trying to migrate away."
- r-006: "I'm somewhat aware that this is an ignorant query, with a lack of understanding as to the complexity of what would be involved but i really would like to know the answer to that question somehow haha"
- r-006: "So C/C++'s syntax and language, like statements and each line of code, is typically more ambiguous than rust?"
- r-006: "[link]"
- r-006: "I see we had the same idea of writing an example. Great minds think alike. Unfortunately I don't speak rust or c/c++ yet so i asked a llm […]"
- r-009: "Look I’m saying the game expects windows, yet you’re ‘fixing’ things to expect proton. You’re just going to be going through a million more. Why not spend the time improving proton/wine/mesa which you’ve proven with these issues is not targeting windows correctly? /  / Most games and apps implement for the platform they’re targeting and any implicit behavior is implicit behavior that isn’t second-guessed at deploy time. /  / So yeah you could keep targeting every 4 byte sequence or word/byte/float under the sun for any and all games or you could apply global fixes to proton/mesa/wherever the actual issue is /  / TLDR: implicit behavior is to be implemented according to the target."
- r-009: "For context explain and list all the small convoluted ‘fixes’ you’ve done recently in last few weeks."
- r-009: "the BioWare devs probably have zero idea they existed. Cus they didn’t when they worked on them due to being a windows targetted engine. Shouldn’t proton be adhering to the expected target anyway?"
- r-009: "Just my two cents."
- r-009: "you’d potentially be helping thousands of games and more optimally"
- r-009: "rather than just this one"
- r-009: "I’m not convinced these specifics are important. Seems proton/wine are doing a trash job of implementing windows if you’re running into this many issues is what im hypothesizing"
- r-009: "Nice"
- r-009: "I mean even windows does a trash job of implementing windows. So the theory is valid windows is covered in backcompat duct tape"
- r-009: "I just don’t think you’re understanding. I’m saying you’re fixing symptoms not the problem. The problem is kotor implemented for a windows target. But you’re trying to fix Kotor rather than proton/wine which clearly aren’t re-implementing windows expected behavior properly?"
- r-009: "I think you even confirmed this at one point as you were talking about red herrings"
- r-009: "Without actually describing specifics"
- r-009: "But also maybe I’m not following because you are a different man to track the regression of all of this with 🤣"
- r-009: "that SteamDeck thread is like 3 years old. Like that’s some dedication!"
- r-009: "Probably because this is the most popular play tests. The core devs move on after vanilla works."
- r-009: "Doesn’t mean everything I said is untrue"
- r-009: "Nah I’m telling you man you can! Just change your approach!"
- r-009: "trust"
- r-009: "KOTORMax needs deprecation so bad"
- r-009: "omg"
- r-009: "what a piece of junk"
- r-012: "[…] OH: /  / [link]"
- r-012: "We already have Rust done 😄"
- r-012: "I have not verified or tested most of this at all really."
- r-012: "But I did do a lot of iterations to ensure some level of accuracy."
- r-012: "is kaitai useless to you?"
- r-012: "Just wondering, not butthurt. It seemed like a good idea exactly for this scenario."
- r-012: "```rs /  / #[derive(Default, Debug, Clone)] / pub struct Gff { /     pub _root: SharedType<Gff>, /     pub _parent: SharedType<Gff>, /     pub _self: SharedType<Self>, /     header: RefCell<OptRc<Gff_GffHeader>>, /     _io: RefCell<BytesReader>, /     f_field_array: Cell<bool>, /     field_array: RefCell<OptRc<Gff_FieldArray>>, /     f_field_data: Cell<bool>, /     field_data: RefCell<OptRc<Gff_FieldData>>, /     f_field_indices_array: Cell<bool>, /     field_indices_array: RefCell<OptRc<Gff_FieldIndicesArray>>, /     f_label_array: Cell<bool>, /     label_array: RefCell<OptRc<Gff_LabelArray>>, /     f_list_indices_array: Cell<bool>, /     list_indices_array: RefCell<OptRc<Gff_ListIndicesArr […]"
- r-012: "```rs /  /     /** /      * Array of field index arrays (used when structs have multiple fields) /      */ /     pub fn field_indices_array( /         &self /     ) -> KResult<Ref<'_, OptRc<Gff_FieldIndicesArray>>> { /         let _io = self._io.borrow(); /         let _rrc = self._root.get_value().borrow().upgrade(); /         let _prc = self._parent.get_value().borrow().upgrade(); /         let _r = _rrc.as_ref().unwrap(); /         if self.f_field_indices_array.get() { /             return Ok(self.field_indices_array.borrow()); /         } /         if ((*self.header().field_indices_count() as u32) > (0 as u32)) { /             let _pos = _io.pos(); /             _io.seek(*self.header().f […]"
- r-012: "[link]"
- r-012: "This usable for you?"
- r-012: "to clarify if i see an answer like 'it's functional but not optimal' or 'this is ugly code' or 'this doesnt work and i want to implement it myself' there's probably good reason to remove this pr. Haha"
- r-012: "I thought it'd allow anyone to bootstrap in whatever language they want"
- r-012: "Looking at some of the generations, though, at least the python ones are somewhat ugly"
- r-012: "Then again, i'm looking at MDL the largest format"
- r-012: "is there a build/run/deploy tool like `uv` but for rust itself lol"
- r-012: "compiled languages always seem to have some hacky workaround for that. Like `dotnet run`"
- r-012: "Oh whatt i thought cargo was just how to actually use it the normal way."
- r-012: "I need to see an actual benchmark […]"
- r-014: "[…] Stoicism talks about cementing for example. I think stoicism is the correct ideology for my point. Been a while"
- r-014: "Anyway at the stage we are at, there's nothing we can do to become bigger. Except grabbing those orbs."
- r-014: "Also I don't debate often. Are these points I'm bringing up: / - Ridiculously clumsy / - On point / - Borderline dumb"
- r-014: "Somewhat hard for me to tell these days."
- r-014: "Well I could be running into a gas station trying to rob them thinking that butter is going to keep me invisible."
- r-014: "Does that have the same response from you?"
- r-014: "So you're a coward"
- r-014: "is what you're saying"
- r-014: "ME TOO"
- r-014: "Mainly I just don't know how not to be a coward"
- r-014: "Coudl argue that's a lie"
- r-014: "You're upset with the system."
- r-014: "You don't want to chase the orbs. You want free will."
- r-014: "Therefore you've chosen your own lttle piece of meaningless subcisting."
- r-014: "Which may or may not make you completely happy. To not be chasing all that down"
- r-014: "You are 27 after all can imagine that and the current tech job market would have you burnt out"
- r-014: "This is where I think english language isn't specific enough. Hard can mean a lot of different things. /  / For example if I was making a game, i could make it possible to beat it by solving a math problem or something. /  / I also could put 10 maxed-out stats of enemies in front of you and you could brainlessly click through them all"
- r-014: "Which is easier"
- r-014: "Meaningless i'll give you isn't the right word."
- r-014: "I was reaching for similar wordsd to the one i wanted out of laziness"
- r-014: "I gotta stop doing that"
- r-014: "So anyway I think this is where I am and i have no idea what I realistically want."
- r-015: "For example if i'm not medicated it doesn't matter if i spent hte last 8 months doing LeetCode every morning or going for runs. I go brrrr and the connections don't form, insights don't pop or if they do i can't follow them anywhere"
- r-015: "Yes."
- r-015: "Why can't documentation be written like this?"
- r-015: "why can't all information be learned like this?"
- r-015: "this is why i like learning from ai"
- r-015: "so explain why '"
- r-015: "'true knowledge is lost' with ai?"
- r-015: "Cus i've never understood that"
- r-015: "Whole time we've been talking I've had this going:"
- r-015: "Loaded up the same prompt 80 times and then jumped here with a burrito"
- r-015: "Well... yeah. What's wrong with that? If I want a refresher in something like again trigonometry or how a kubernetes cluster works, i'll ask ai."
- r-015: "Before that i'd go to stackoverflow, wikipedia, or whatever"
- r-015: "and then usually get utterly confused and never find what i'm looking for"
- r-015: "Now I always get direct exact information i'm asking for. So the rate I learn is only limited by teh quality of my questions"
- r-015: "This is how I learned growing up. My dad and I would stay up late from 9pm to 11pm debating and arguing  about things and one of us would choose devil's advocate. /  / it's probably the only way i learn. /  / Like, literally **EVERYTHING**. EVERYTHING is irrelevant, arbitrary, and unimportant. Unless it has a purpose."
- r-015: "For example what was the last large stack you learned, from a walkthrough or a youtube video or something"
- r-015: "That you actually would recommend"
- r-015: "Probably shouldn't ask that just to prove a point but if it's good i'll disgress i haven't been giving it a fair shot. But usually it's just like: / - what is this monstrosity / - why is it so large / - what's the point. / - what problem is this solving / - is this *really* the best way to solve it /  / Those questions aren't answered on page one and i zone out"
- r-015: "There's too much irrelevant info out there isn't ther?"
- r-015: "> I normally learn by doing / EXACTLY THIS"
- r-015: "if i see one more bit of info locked behind a youtube vid..."
- r-015: "i literally will spend that day writing a transcriber myself"
- r-015: "Example? […]"
- r-016: "It's called osmething like the 'Golden Standard' Like we generally like people that are charismatic or attractive, even if they e.g. are on death row for doing some evil sh*t."
- r-016: "Huh I can't remember the name of that law"
- r-016: "### **Halo Effect** / When someone’s charisma, attractiveness, confidence, or communication style makes us assume they’re also smart, trustworthy, competent, or morally good — even when there’s no evidence for that. /  / It’s exactly what your friend was describing:   / liking someone *because* they present well, even if they’re objectively wrong or even harmful."
- r-016: "The only way I would do that is if someone I trusted vouched for it."
- r-016: "I don't want to be full of shit though"
- r-016: "Do you?"
- r-016: "is there some benefit i'm missing out on?"
- r-016: "How old do you think i am btw? Not sure if i mentioned. Or if that'll change anything."
- r-016: "This video specifically?"
- r-016: "I already know all this"
- r-016: "Describe why I need to do this and what problem I'm solving"
- r-016: "if there's benefit that'd be motivation for me to do it"
- r-016: "I don't really see any. But is that the point?"
- r-016: "To get me to blindly jump in and hope it's not a waste of my time?"
- r-016: "that seems counter-intuitive doesn't it?"
- r-016: "Sorry if i'm being annoying or rude rn with this."
- r-016: "From my perspective, 99% of them are useless, something I already know, or something I've forgotten about and is a healthy reminder of that. /  / I don't know about the last point in that sentence though. I wonder if that's the same dopamine hit that people aging hit where they just want nostalgic shit all the time and can't learn anything new. That scares me"
- r-016: "So yeah everything's an experiment. I might login to my email and see an email from a Nigerian prince and it's somehow *not* a scam."
- r-016: "Should I be checking every time though?"
- r-016: "> I just notice that you assume a lot about things sometimes / > By assuming you can generalise legitimate things away or miss important parts or even cool things you'd never have noticed / Yes I do have this problem. Her's what's actually happening though: / - I have a train of thought. I finish teh train of though because it's leading to something new that i haven't done or thought of before usually. / - **important part**: I go *back* and check if i missed something."
- r-016: "Hence all the pins. […]"
- r-017: "I'd like to see someone flash a switch 2"
- r-017: "Well you know what could help others? / Targetting a majority of people rather than your proprietary stuff."
- r-017: "Because, doesn't that result in this meme:"
- r-017: "And that increases the learning curve, for everyone."
- r-017: "So in a way is your stuff beneficial"
- r-017: "is what i'm asking"
- r-017: "and i'm not saying that to be rude or prove a point. But just to skip over to the point that i may not understand yet"
- r-017: "When I say i may not understand i do say that genuinely. It probably does sound rude. I genuinely like being proven wrong it just doesn't happen often."
- r-017: "Well you could actually sue the bastard"
- r-017: "rather than try to flash it tediously over years."
- r-017: "or you could setup your own business that provides a product that outsells the worse implementation for the rest of the world to enjoy"
- r-017: "so they don't have to see the pain and torture that you've gone through with all this flashing"
- r-017: "By doing all this low level stuff you're implying everyone needs to be doing that and that just becomes the status quo"
- r-017: "Which is *not* a good thing."
- r-017: "Then companies like Apple corner the market."
- r-017: "You're not."
- r-017: "That's what i'm saying. You doing it is making it *expected*."
- r-017: "it becomes background noise. People think 'oh yeah someone will do that. I can expect this'."
- r-017: "Then one day you're gone. And that amount of work doesn't get contributed 10 years from now for the next Y-phone replacement for the iPhone"
- r-017: "The same thing you can see happening with jailbreaking the latest iphones"
- r-017: "it's becoming increasingly harder and harder to do it. The effort level increases. It's becoming *expected* behavior"
- r-017: "That is my theory, anyway. With zero metrics, referencse, and research. […]"
- r-020: "I don't understand why pyinstaller cannot do this? is it just a lot of work to target another platform/architecture when you're not on that architecture/platform? PyInsatller only builds a binary for the os/arch you're on i mean."
- r-020: "Docker images also have the same issue."
- r-020: "Why is this only an issue with docker images and pyinstaller (if indeed there's a correlation)?"
- r-020: "In short I don't understand how to package for another os/arch/platform when not running that os/arch/platform 😄"
- r-020: "is that explained for rust anywhere?"
- r-020: "Apologies if this is a dumb question"
- r-020: "What the fuck ***XP***?"
- r-020: "I'm swapping to rust there's no question"
- r-020: "Remember our debate about native code vs stuff in electron?"
- r-020: "I am on your seide now after learning about rust-wasm stuff"
- r-020: "interesting.."
- r-020: "Huh? the response said the opposite"
- r-020: "WASM is slow."
- r-020: "Sort of....."
- r-020: "well my theory has always been that it's the static way they're doing that stuff and the static strings that exist at similar offsets between builds is causing the heuristical detections to operate."
- r-020: "like within the pe header or otherwise"
- r-020: "i don't understand why dotnet/apparently rust don't have the same problem lol […]"
- r-023: "[…] Hey one more question if you don't mind? Why is there so much crap installable through apt/dpkg/yum/rpm/<other distro package installer here>"
- r-023: "Like I found a package for numpy in debian/ubuntu and was genuinely confused. Why would i ever want to install the system package instead of through pip normally???"
- r-023: "As a python dev that severely confused me when i was trying to get the toolset working on linux"
- r-023: "Why is there so mnay distro specific packages for things that generally do not need specific targetting??"
- r-023: "And how the fuck do I understand and keep track of how distros are supposed to be doing that crap when I'm developing my python app for windows and all i know is i need numpy 2.0 or greater lol"
- r-023: "are they just optimzied for the distro and generally optional"
- r-023: "or is it for system level shit only and if i'm making an app that a user doesn't need for their distro for the distro to function, i don't need to worry about `apt` or whatever their packages are?"
- r-023: "i think i answered my own question haha also means everything i am doing in deps_toolset.ps1 on pykotor is wrong"
- r-023: "[link]"
- r-023: "Lmfao"
- r-023: "This is one of my biggest pet peeves with linux"
- r-023: "HOW DO I KNOW WHAT I NEED TO INSTALL"
- r-023: "most of this was 'i get this error what package do i need in ubuntu???'"
- r-023: "then i ask 'exact 1:1 package in alpine'"
- r-023: "repeat for other distros"
- r-023: "literally how does anyone do this? i spent a month on this before ultimately compromising"
- r-023: "But how do I know? all i know is i have a pyqt5 application for example that uses cpython. I had to do an absolute crapton of guesswork to figure out 'okay maybe this package??? it says 'qt' in the name. Ok this one says 'pulseaudio' i guess that 's why the media player doesn't work'"
- r-023: "Literally how"
- r-023: "and there's a billion distros all with their own naming and packaging for each of these"
- r-023: "For example this is **JUST** arch linux: /  / ```ps1 /         "arch": [ /             "mesa", /             "libxcb", /             "qt5-base", /             "qt5-wayland", /             "xcb-util-wm", /             "xcb-util-keysyms", /             "xcb-util-image", /             "xcb-util-renderutil", /             "python-opengl", /             "libxcomposite", /             "gtk3", /             "atk", /             "mpdecimal", /             "python-pyqt5", /             "qt5-multimedia", /             "qt5-svg", /             "pulseaudio", /             "pulseaudio-alsa", /             "gstreamer", /             "libglvnd", /             "ttf-dejavu", /             "fontconfig", / […]"
- r-023: "debian equivalents? /  / ```ps1 /         "debian": [ /             "libicu-dev", /             "libunwind-dev", /             "libwebp-dev", /             "liblzma-dev", /             "libjpeg-dev", /             "libtiff-dev", /             "libquadmath0", /             "libgfortran5", /             "libopenblas-dev", /             "libxau-dev", /             "libxcb1-dev", /             "python3-opengl", /             "python3-pyqt5", /             "libpulse-mainloop-glib0", /             "libgstreamer-plugins-base1.0-dev", /             "gstreamer1.0-plugins-base", /             "gstreamer1.0-plugins-good", /             "gstreamer1.0-plugins-bad", /             "gstreamer1.0-plugins-ugl […]"
- r-023: "Slightly different names, for the same crap"
- r-023: "lol"
- r-023: "Why do I not have to do this for windows???"
- r-023: "Why does my qt5 app just *work* without having to worry about sys level packages on windows like this? […]"
- r-026: "speaking of you any idea why this guy was such a dick to me? [link] /  / just generally not sure why he was publicly bashing me like that. Accusing me of not putting any effort forth or w/e. The article was obviously ai enhanced but i don't know really why other people are just saying i'm bad at 'conflict resolution'. I tried to frame it within the scope of a discussion on AI but he'd follow up with dumb claims like 'so you didn't write an article, you just had ai generate it'. All I wanted was to help new users get started developing and doing stuff with openkotor even if they didn't have a programming background. I'm at a loss as to why it couldn't simply be that."
- r-026: "Just makes me wonder if I can even talk or mention anything AI related anymore"
- r-026: "I didn't care if he read it."
- r-026: "Yeah I guess"
- r-026: "I didn't like that he publicly slandered my article though"
- r-026: "So the issue was I was trying to rationalize and explain my position and stance on its usage, and frame it as a discussion, whilst in the public view it'd just be an argument I wouldn't drop"
- r-026: "I guess it was obvious there was no intent or desire to discuss it openly"
- r-026: "Definitely sucks not everyone is just inherently willing to do that lol"
- r-026: "I don't deal with children often I guess lo"
- r-026: "l"
- r-026: "> The other guy was going into it with bad intentions from the start, no amount of rational or logical positioning / discussion would go anywhere / Yeah this seems obvious idk why i didn't understand that tho"
- r-026: "Thanks though"
- r-026: "Maybe i just wanted to be heard"
- r-026: "That's a wild eye opener to many it's something i often forget though"
- r-026: "Yeah I try. Just have zero idea how to deal with people that aren't I guess. […]"
- r-028: "I've always wondered why Worrorrnorz's house was a different module."
- r-028: "You know, that super small hut in the kashyyyk village."
- r-028: "It's small enough you'd think it'd just be part of the main village module. I wonder if they had to split it off due to the constraints at the time. It'd be interesting to see why they did that if we ever could get a good estimate of how much memory was being used in that module."
- r-028: "Can you elaborate on this? i don't know what you mean by 'bake' and what artifacts are caused from that"
- r-028: "for clarity can i expect the head of a HDD to operate the same as a laser for these CDs?"
- r-028: "Gotcha."
- r-028: "My college only taught the HDD internals, CDs were already defunct even back then lol"
- r-028: "So here's a question i've asked LLMs a billion times over the past few years. WHat is VRAM and why is it different from RAM, exactly?"
- r-028: "Like what makes llms so much performant on vram than ram? And why can't it be modular so we can go out and simply buy some? Seems to be this embedded thingamajig on the card that requires buying a new card, unfortunately. Is there a reason we aren't seeing modular systems like this? my theory is because of nvidia being so proprietary and ahead of its time really"
- r-028: "intervention?"
- r-028: "From this explanation it seems you're taking POV of the gpu."
- r-028: "but when we code we're operating from the POV of the cpu"
- r-028: "so it's weird to read it like that"
- r-028: "i've always treated the GPU like some remote entity"
- r-028: "I'd like to understand this better."
- r-028: "is it alright if I ping you some of these questions in something like openkotor's #dev-space channel..? it seems we do the community a disservice by talking about this in dms"
- r-028: "Well what I'd like to understand is why inference is so much faster in GPU and why they always say VRAM is the bottleneck"
- r-028: "Why can't it use CPU? […]"
- r-031: "ahhahh"
- r-031: "omg i have 32gb of ram and nothing open and for some reason all my apps are out of memory. i hate 11 so much haha"
- r-031: "i can't even type in discord without it reloading"
- r-031: "it did not used to be this bad"
- r-031: "i think what it actually turns out to be is all the various subprocess python.exe/node.exe s that run in the background."
- r-031: "7"
- r-031: "i literally just watched my message '7' take 20 seconds to send."
- r-031: "i'm going to reboot"
- r-031: "I can't even move y mouse"
- r-031: "i can't even move my mouse except for 5 secondxs at a time per minute"
- r-031: "Haha it did not used to be this bad"
- r-031: "Ok I’ll cut to the chase and respect your time. How do I turn off core parking on Linux? What should I set my swap to?"
- r-031: "and what issues will I realistically have in plain language that’ll make me regret using immutable? Is it just more tedious or is there literally things I can’t do?"
- r-031: "like would suck to setup for a week and then find out I can’t play rocket league or something"
- r-031: "also… flash player?"
- r-031: "I know I know but I can’t use ruffle"
- r-031: "sharex?"
- r-031: "Example?"
- r-031: "Just one would be fantastic. […]"
- r-032: "Broadly speaking, how good/bad is wine?"
- r-032: "is it like i'm going to see a 0.6x multiplier on native performance?"
- r-032: "or is it just unstable but the same amount of fps in general?"
- r-032: "and uh... memory usage? isn't it spinning up a whole vm 😭"
- r-032: "Damn this was my last request"
- r-032: "hope i sent off a good last one haha"
- r-032: "So....."
- r-032: "reone/kotor.js/xoreos are EMULATORS for the KOTOR game?"
- r-032: "or am i misusing that word?"
- r-032: "so what the heck is an emulator again?"
- r-032: "ok so if i was making wine then it'd be an emulator around kotor."
- r-032: "ok i see"
- r-032: "is it possible to virtualize a GPU for testing opengl stuff in ci/cd?"
- r-032: "sorry i'll ask that later."
- r-032: "WOAH"
- r-032: "no way"
- r-034: "what i need is an explanation of what exactly a native app is, vs electron. What specifically is bloat in chromium. Like i want to see a figma that takes it to the bare bones"
- r-034: "Wtf is in it that's so important."
- r-034: "Just give me react and i'm good"
- r-034: "Literally"
- r-034: "haha"
- r-034: "i'm not even posturing man i've tried literally everything to make a native ui look good even sell my soul"
- r-034: "it just don't"
- r-034: "[link]"
- r-034: "i mean to be fair i haven't tried EVERY high level abstraction library that does ui"
- r-034: "like i have NOT tried wxWidgets yet"
- r-034: "I've not tried just using GL to render the window. I imagine that's overkill."
- r-034: "like kivy i mean"
- r-034: "QUickly explain libuv and skia? only parts of those i'm not getting"
- r-034: "I'm still not understanding which part of this is the shitty bloat. Which parts are required for react 😂 i mean i was needing chromium broken down i f i was being completely honest out here i knoew how electron basically worked"
- r-034: "it's like you broke atoms into electrons. I need quarks bro"
- r-034: "did they ever figure out what a quark is made of?"
- r-034: "oops my bad what i'm trying to say is this part makes sense to me."
- r-034: "what doesn't make sense is this part:"
- r-034: "I need that broken into 50 pieces"
- r-036: "Sure but couldn't we take ghidra to that?"
- r-036: "And if it's not software, then couldn't we just dismantle the physical parts?"
- r-036: "And more importantly why aren't we using this to figure out how to make our own GPUs outside of nvidia. I really need to watch that video you sent me 'lets make a gpu'. that must be a wild ride"
- r-036: "Man I went to college three times for a total of 3 years. Total scam i learnt nothing.. i mean my mental health sucked and that's why i don't have the degree but it also was just like 'why am i here if i'm not learning anything...'. the classes were boring, i couldn't remember if i did an assignment or not because it felt exactly the same as another useless assignment."
- r-036: "ahh anyway. who cares? we've cracked DENUVO. Why is this any more difficult?"
- r-036: "Explain that specifically in detail, step by step"
- r-036: "Haha"
- r-036: "I got a trash response from an llm on that"
- r-036: "WHATTTT"
- r-036: "well that sounds like a good script for a movie"
- r-036: "Only a few people have the information?"
- r-036: "sounds like the O5 council"
- r-036: "😂"
- r-036: "wouldn't you expect one dude to pull a snowden though?"
- r-036: "just one guy gets drunk enough"
- r-036: "after enough years"
- r-036: "and who's assembling the cards? wouldn't they be able to literally see it be put together enough to know what it's doing"
- r-036: "Like on the assembly line of course"
- r-036: "What's a fab?"
- r-036: "like a mount?"
- r-036: "holster?"
- r-036: "slot? […]"
- r-037: "Also one more crazy question. If you were stuck in a room with all the tools you need to flash your mobo. You have a FULL pc with everything you could possibly dream in a tech shop. EXCEPT you don't have ram. You need to boot onto the computer and access chrome, because the building is locked by a password. That password only exists on a website which must be accessed with a chromium-based browser. /  / Do you survive and escape? or do you die of starvation/dehydration three days later?"
- r-037: "ASUS MSI Gigabyte BIOS Flashback requirements no RAM!"
- r-037: "lol"
- r-037: "## There is a proof-of-concept (detailed in a March 31, 2026 Hackaday article) where someone modified coreboot (open-source x86 firmware) to skip DRAM initialization entirely and run code using only the CPU's on-die cache (L2/L3) as temporary "RAM." On older Intel hardware, they got a simple Snake game running and outputting over serial."
- r-037: "whatttttt"
- r-037: "- **How it works technically:** Early in boot, CPUs support "Cache-as-RAM" mode where cache lines act like tiny scratchpad memory before DRAM is brought online. Coreboot historically used this for its own early stages."
- r-037: "I don't understand why ram is needed 🤷"
- r-037: "Why can't it just continually io from the hdd/ssd/nvme"
- r-037: "[link] my pc can't run this apparently because my gpu is too old."
- r-037: "Why do I need ram i don't get it at all"
- r-037: "Just write/read from disk directly?"
- r-037: "What is software. Just logic gates no?"
- r-037: "PHYSICALLY and TANGIBLY it is DOING something correct?"
- r-037: "So.... you could just switchboard the wazoo out of it until you have something that can interface with your disk"
- r-037: "Random Access Memory shouldn't be required...? unless you're saying in that way i would be using ram."
- r-037: "I'm sure there's a few gaps in my plan 😄"
- r-039: "reading this was a weird flash of deja vu for me"
- r-039: "not because i've read exactly this before either in any other similar contexts either"
- r-039: "> I exist in those systems not because I agree with them but out of necessity / ...is it actually necessary?"
- r-039: "i don't have any credit or a bank account."
- r-039: "i'm basically Buddha"
- r-039: "lol"
- r-039: "if i could afford a RV and internet i'd live with that"
- r-039: "One moment, while I look this up..."
- r-039: "> a potential shift where large tech platforms act like digital landlords, controlling access to essential online spaces and extracting value from users ("digital peasants") through data and attention, rather than through traditional market exchanges. While still operating within a capitalist framework, it signifies a move towards a system where power is concentrated in the hands of platform owners who dictate the rules and benefit disproportionately from user activity, creating a hierarchical structure reminiscent of feudalism within the digital economy, a change from the more market-driven model often associated with traditional capitalism."
- r-039: "so *that's* why none of em are pushing for ipv6 yet..."
- r-039: "cgnat controls the masses doesn't it."
- r-039: "if nobody can host a listening port..."
- r-039: "listening server on any port...*"
- r-039: "then everyone's forced to route through inducers or other middlemen that can be a finite amount"
- r-039: "like a finite amount of non-cgnat internet connections is easier to control than everyone having the freedom to use their internet"
- r-039: "It's an indirect way to control it"
- r-039: "If you force everyone on CGNAT then i2p shuts down for example"
- r-039: "TOR basically works because people have listening ports available in various parts of the world"
- r-039: "that we can route through"
- r-039: "i.e. 'relays'"
- r-039: "feel free to correct if i'm wrong […]"
- r-040: "> So I do know what you mean by CGNAT causing issues like this, but it's less of a concentrated effort to avoid ipv6 and more of a money reason / You have a tendency that i've noticed to focus on the explicit/obvious parts"
- r-040: "But you SEVERELY neglect the potential"
- r-040: "Take the lawsuit with Palworld and Nintendo. It's not just about those two companies, they are about to set a precedent for the whole gaming industry"
- r-040: "so i understand IPv6 is a migration and will be expensive. But what i've come to understand lately, is that CGNAT is stripping our freedom"
- r-040: "and i fear it will become the **norm** very soon. A listening server on home internet will be a remnant of the past"
- r-040: "That scares me. Because that means everything is controlled by the..."
- r-040: "not the oligarchy. What's the word i'm looking for"
- r-040: "So yeah there's no incentive to swap to ipv6.... they're already trying to remove section 230 lol"
- r-040: "as a consumer **we need to make it happen asap**"
- r-040: "corporatocracy"
- r-040: "Oh. I guess I'm missing something then"
- r-040: "Let me reread"
- r-040: "Apologies if that's what happened"
- r-040: "i got so confused by this point"
- r-040: "technofeudalism is a fun word of the day for me"
- r-040: "> My fibre connection doesn't and still uses ipv4 (not cgnat) which is mainly due to money reasons and engineering costs / > CGNAT is a bandaid, which companies lean on as the costs for moving to ipv6 don't make sense to them.  / Yeah."
- r-040: "> there isn't something blocking ipv6 other than the lack of will. / > It's the same reason we still have COBOL in banks, just technical debt compounding with institutional inertia. / > I think this whole thing is a great example of Hanlon's Razor in action 🙂 / > all of these ISPs are also publically traded companies, they are notorious for investing into things with a low ROI as well / Sure?"
- r-040: "I mean can we sidebar. i kind of need you to understand my point in order to move on. Like i know the challenges of ipv6 migration are as long as our arms but my focus really was on the implicit freedom lost as we slowly roll out cgnat instead of a unique ip to consumers?"
- r-040: "i just think that's a really important point that people miss and it's honestly the most relevant right now."
- r-040: "Otherwise yeah everything you said is a bit more detailed than my understanding of the ipv4/ipv6 problem"
- r-040: "I feel *lately* that someone is going to capitalize on the cgnat push. Someone like Google or Microsoft. Or LE?"
- r-040: "LE would probably be *for* cgnat because it deanonymizes the internet and makes tracking a bit easier for em"
- r-040: "That was kind of my point i guess 😄 i mean maybe they don't have much power in the way of standardizing CGNAT all around."
- r-040: "but if they did that would be extremely bad […]"
- r-043: "You don’t need to dumb things down so heavily. I know a lot just also realize how much I don’t know. I think you lack depth on things sometimes? It’s not like wsl is open source /  / Some people swear by it being a native Linux kernel. Some say it is still bottlenecked by the hyper-v. /  / As for me I don’t understand why they call two different things hyper-v and hypervisor as that adds unnecessary confusion/ambiguity. /  / Hyper-v iirc is the faster one than windows hypervisor"
- r-043: "Dude kde plasma in wslg looks so nice. I might even block explorer.exe on boot and use that instead"
- r-043: "Why isn’t everyone doing this? Fuck wine lol this is so much cleaner"
- r-043: "took me about a day to configure the provisional stuff"
- r-043: "I was considering aeon for a fat minute"
- r-043: "Dunno if I’m weird but I’m mixing gnome apps with kde apps 💀"
- r-043: "Using wsl means I get native windows and linux performance. If I install linux, that means I get emulated windows performance. Why would I ever want to do the latter?"
- r-043: "Prove it"
- r-043: "nah actually though how do I benchmark that stuff"
- r-043: "This might as well be gibberish. What’s the highlights?"
- r-043: "where’s windows in this diagram lol"
- r-043: "Root partition?"
- r-043: "Well I was hoping the diagram would just clearly show me where the bottleneck or resource bloat was."
- r-043: "is wsl2 running a native linux kernel or not"
- r-043: "and how would I test that down to the ms"
- r-043: "I don’t even have the hypervisor enabled. Hyper-v is something different"
- r-043: "I’ll prove it one sec"
- r-043: "I don't even have Windows Hypervisor Platform enabled"
- r-043: "From stackoverflow I've learned it's slower. […]"
- r-044: "[…] YES"
- r-044: "OMFG"
- r-044: "WHY IS NO OTHER DEV WANTING THIS BESIDES ME LMAO"
- r-044: "just give me something pre-configured from a seasoned veteren out of the box"
- r-044: "i'm so tired of these slim distros that have literally nothing"
- r-044: "why is it like that lmfao."
- r-044: "what's the most bloated linux distro in the game right now?"
- r-044: "give me that"
- r-044: "usually i need to `apt install` like a billion things. So many deps. So many upgrades. Just honestly nothing is preconfigured and it's bullshit"
- r-044: "Yeah i really LOVE nix"
- r-044: "i just wanted to try something else because maintainability of nix is higher"
- r-044: "requires more effort/upkeep"
- r-044: "rpm-ostree was explained to me as the best of both worlds"
- r-044: "also considering aeon"
- r-044: "[link] / [link] / [link] / [link]"
- r-044: "top 4 choices 😛"
- r-044: "idk what this means"
- r-044: "look anytime i install an operating system it requires months of painstakingly installing things, going through the settings, configuring everything, personalizing everything. /  / The goal would be to make **any and all of that** provisional/declarative so I can get all of that **out of the box**"
- r-044: "if immutability isn't the way to do that then i guess i don't want immutability"
- r-044: "something that won't break and is conventional"
- r-044: "every year or so i reinstall windows and it takes about a month to get it to the point it was before"
- r-044: "why is nix the only option sorry? […]"
- r-045: "Nevermind lol a lot of dumb shit went down."
- r-045: "sorry for bothering you with it"
- r-045: "I don’t think anybody cared for the idea. I should let people come to me if they want to use my idea instead. Seems to be the strat in OpenKotOR."
- r-045: "ugh yeah you’re probably right"
- r-045: "wish people could see what I see sometimes though. It’s baffling to watch behavior ensue that I can literally explain because nobody wants to be me the guy that requests things all the time and waits a week or even longer. Lol. Dunno when I became the butt of the joke but that’s bizarre. Doesn’t feel constructive to take it out on anyone but my god I can’t stand most people because of this wishy/washy crap. I am never going to leave but it sounds like I’ll meet less friction if I just stop using openkotor’s name. I’ve no problem using th3w1zard1, OldRepublicDevs, etc if I don’t have autonomy to use the name. But there’s literally things I’ve waited over a week for lol. I’m not the problem wa […]"
- r-045: "but like I said it’s fine."
- r-045: "Respectfully, I think that’s a brainless answer frankly. There’s plenty ample time I give people to respond to the things I don’t know for certain. People take that as me being brainless because I’m asking so much. Leading me to try to take autonomy about the things I don’t see as problematic. Which leads to pushback. /  / so *like I said* the simplest logical solution is to avoid the irrational problem by not using openkotor’s name since I don’t own that and I have no autonomy to act on it"
- r-045: "lol I must really post too much"
- r-045: "respectfully it doesn’t feel like I’m heard ever. It’s hard not to be frustrated by this when it feels so non sequitur with what I’ve written. /  / I am always saying ‘earliest convenience’ I am always saying ‘no worries’"
- r-045: "And I ask for straightforward details/disclosures about how people want it to be ran. To allow me to align. Literally I get nothing I can use. Like it’s somehow an alien concept for anyone to be coherent. I’m not going to sit around waiting to do things that are fun just to use an OpenKotOR name lol. Basic systems/entropy theory. I might as well just do what everyone else is doing and use the th3w1zard1 name and link externally. /  / But all that does is hide the real problem and show I can’t solve it either despite me having the solution to do so. Because no one wants to give me mind to hear me out ever. /  / Yeah it’s frustrating. Genuinely kills my flow most of the time. Never do mean to […]"
- r-045: "I don’t like avoiding issues or doing wishy/washy stuff."
- r-045: "I don’t understand how people operate under a regime like that frankly. I pride myself on puritan lifestyle of putting effort in, searching for the truths in life, and solving problems."
- r-045: "Look in what universe is this a pacing problem respectfully."
- r-045: "How many open requests exist in the discord."
- r-045: "how many of them are me. And how many have waited multiple weekends?"
- r-045: "Look it’s just clear to me the issue is my utilization and autonomy of the OpenKotOR name. I can just use another name and do my own independent thing separate of the org. Like I was doing. /  / The way this typically works is we get aligned based off of some manifesto. But no one wants to read mine and nobody wants to contribute one. I have nothing to align to, and that gives me nothing to go off of except people’s emotions and fears. Which is frankly just a brainless way to run a community. If there’s a more respectful and true way to say this please let me know. Just I was raised to always be constructive. Fight losing battles. Etc. Be right and be open to being wrong"
- r-045: "Just how I was raised. None of that means im a dick. Like I said you’ve found a good friend in me I don’t have a mean bone in my body"
- r-045: "Nah"
- r-045: "This conversation just doesn’t feel real lol. What on earth are you seeing as I type this? Just pure confusion? I guess a real conversation id expect some point I made to be responded to and collaborated with some earlier point or some  mindset. The simplicity and amount of space you’re giving me is what led to me talking about a ‘brainless reply’. Just what else do I even say? What? How can I point out how ridiculous your reply was in a constructive way without you misunderstanding behind the non-immediately-recognizable statement.  /  / I’m basically giving you the alphabet, and wondering how to get to Z, and you chime in to talk about fruit. Why is fruit being mentioned in any context? (T […]"
- r-045: "I don’t get it at all"
- r-049: "No worries, i totally get it. I don't think you were out of line or anything"
- r-049: "Just definitely feel free to let me know if i'm getting that out of line. Scrolling through some of those previous comments that ticked you off was somewhat embarrassing 🥶"
- r-049: "I'm still struggling to implement fedora if you have a moment? A few various things are just irking me atm"
- r-049: "So when I ran wiindows i was pretty used to running a ton of things, and seeing my ram constantly at 31GB/32GB, with the pagefile being 50 some gigabytes as well over time. /  / However I can't run anywhere near what i used to be able to run on linux. I get crashes every now and then which i can only assume is because i'm running out of memory. /  / The default installation implemented a swap of like 4gb/8gb or something?"
- r-049: "how do i make it dynamic so it's IMPOSSIBLE to run out of ram and crash out like that?"
- r-049: "is it possible to use swap on demand like the pagefile i'm used to? lol"
- r-049: "or how do i manage this?"
- r-049: "The other biggest issue i'm having is the fact that i just couldn't bear to use fedora so i swapped back to windows 11"
- r-049: "see the image"
- r-049: "i'm totally jk... i'm using a windows 11 theme for kde 💀"
- r-049: "Other issues: / - Half of my chipset devices don't work (bluetooth, etc). / - I've no idea how I managed to get the GPU driver installed but for the first two hours i was stuck at 1076x768 and it was awful. I literally gave up an hour in and just prompted ai until i finally had a fix."
- r-049: "Well why can't it just dynamically adjust the swap based on how much ram is used? that should be default imo"
- r-049: "Also I installed homebrew for shits and giggles. I don't plan on installing anything through it though"
- r-049: "Also how do I test WinUI3 stuff? i think that may have been the whole reason i swapped back to windows. Cus i could always get linux through wsl was how i was thinking"
- r-049: "How much input lag does proton give?"
- r-049: "going through wine and all that"
- r-049: "i don't want to add more swapfiles as that slows my pc down. i'd prefer if it'd just automatically handle it at a high level? i don't understand why this isn't widely desired best practices in the kernel already lol who actually is watching their ram usage every 5 seconds?"
- r-049: "the whole thing Linus said is"
- r-049: "**don't fuck with userspace**"
- r-049: "no?"
- r-049: "Letting ram go amock is fucking with userspace :kappa: […]"
- r-051: "[…] Frankly I think you just need to digest what I've said and what I stand for. It may be a hard pill to swallow if you've lived your life a certain way for a long time. Trust me i've tried living every way under the sun in my life i don't waste time if i can help it"
- r-051: "i've tried everything and i only do what works for me. The only reason I have this conversation with you at all is to potentially prove myself wron g wit hsomething you say, and to potentially inform someone i respect of food for thought"
- r-051: "it has nothing to do with being right"
- r-051: "or posturing"
- r-051: "i just want us both to succeed and make our dreams come true."
- r-051: "I've literally partied 8 days of my entire life"
- r-051: "Even when I play video games like Rocket League i'm reminiscing in the memories."
- r-051: "But yes if there was a GLOBAL movement that MATTERED and i thought it was worth pursuing, i'd happily pour my last bitcoin into that shit"
- r-051: "in my 30s i just found that doing it your way was not getting me the results i wanted"
- r-051: "if i go viral i can touch more people, influence the masses a bit more, etc"
- r-051: "i care nothing about being rich other than using it as power to give back"
- r-051: "I do not know what other way i can state this but do try to keep in mind i'm trying my best to read what you're saying, understand you, and provide an honest answer"
- r-051: "I just think differently."
- r-051: "Life is 90% how one reacts to things, and 10% the stuff that happens"
- r-051: "TLDR focus on this part: /  / > # it's that the rule is built so the good never actually arrives / It's more, **every day my reach increases**"
- r-051: "am i expectedx to live the way you're living at age 1 for example? no i need to learn how to walk lol"
- r-051: "this kind of elitism on morals and the proper way to do things is literally why linux still targets the tech savvy users and less so the dumb guy normal people that just want to see a photo of their cat from their grandma and check their email."
- r-051: "nobody thinks in how people think/learn. And the reason elon musk doesn't donate more? Over sense of comfort"
- r-051: "and crab mentality"
- r-051: "crab mentality fucking sucks"
- r-051: "holyyyyyy"
- r-051: "once the boomers start retiring and passing away maybe we can change that"
- r-051: "But fr if everyone thought like you and me the world would be a better place"
- r-051: "I think on that we can agree wholeheartedly"
- r-051: "If everyone was like the two of us, we wouldn't be disagreeing at all honestly lol"
- r-051: "because we'd be living probably the same morals"
- r-051: "I talked to someone the other day about the starvation of africa and the shit going down in the middle east and he was like 'nah they gotta get themselves outta that i'm not going to worry and waste my life worrying about them'. The entitlement to say that is ridiculous lol"
- r-051: "that's another human being out there"
- r-051: "🤷 i hope this reaches you because i'd like you on my side or at least find an argument that'll convince me if i'm wrong. Those are the only two opportunities i can give you"
- r-051: "Either: / - Help me understand why you're right by telling me what specific part of what i'm saying is wrong / or / - Join my cause and realize i'm pretty much correct, just a bit naive with how i'm preaching this. /  / Offer direction rather than hardwalling my moral compass […]"
- r-052: "Why is there so much hardening around security anyway?"
- r-052: "like... i mean... you ever feel like they take it overboard?"
- r-052: "it's starting to feel like i can't even sign into things *correctly* as my *own* userver. How on earth is someone smart enough to hack into someone else's account they ain't supposed to get into?"
- r-052: "i'm somewhat joking but also it's so obnoxious"
- r-052: "What really bothers me is specifically"
- r-052: "..."
- r-052: "i forgot the name"
- r-052: "xD"
- r-052: "CORS"
- r-052: "whyyyy"
- r-052: "why is that default"
- r-052: "it only hurts the client that's dumb enough to not use it"
- r-052: "so why as a *server hoster* do i need to use it???"
- r-052: "yes BUT"
- r-052: "THOSE ARENT MY PROBLEM"
- r-052: "lol"
- r-052: "that's like saying"
- r-052: "hmm"
- r-052: "ok i have a metaphor"
- r-052: "hang on this metaphor is hilarious"
- r-052: "My issue with CORS is that it treats the server owner as morally responsible for what a completely different client decides to do. /  / To me, that logic feels like this: I’m asleep in my own house, I forgot to lock the front door, and some random guy wanders in during the night, ignores multiple obvious signs that he shouldn’t be there, trips over the basement stairs, and somehow I’m the irresponsible one because I didn’t install a childproof gate for trespassers. /  / That’s what CORS feels like. The browser willingly goes to another server, willingly executes code from somewhere else, then acts like the destination server is responsible for protecting the user from the browser’s own decis […]"
- r-052: "so again, those are *not* my problem lol"
- r-052: "But yet i feel obligated to enable CORS because so many things will break if i don't have all pieces set the same way. And their defaults are always strict cors"
- r-052: "I tried standing out and setting it always to * but man that has me exhausted lol i just had another docker image update that broke one of my services due to that env var not being respected in the newer version […]"
- r-055: "Why do so many apps talk about xwayland, x11, Wayland? Which ones do I want to be using given the choice?"
- r-055: "I know what Wayland/x11 are"
- r-055: "How much stuff still isn’t ported and why are they slower?"
- r-055: "For example sometimes I run (somewhat unrelatedly) d3d11 games through vulkan api using d3vk (or whatever it’s called) and those api calls are like 10% as the speed of turning d3vk off. Noticed this in about THREE standard games during my tests. /  / So I’m just wondering why I ever would want d3vk"
- r-055: "and more importantly why can’t it just figure out what defaults to use out of the box?"
- r-055: "it EASILY should be able to run a benchmark itself"
- r-055: "Based on like… three different app launches and the statistics observed over each of the three times launched"
- r-055: "And figure out what settings to automatically enable"
- r-055: "Most of my games I feel like I spend an hour each to get the right settings"
- r-055: "Who on earth has time for this on a daily driver?"
- r-055: "also why is there like 7 wrappers around wine and why do none of them use the same prefix? Seriously why do I need containerization with wine at allllllll it’s not like when I run pure windows I need to containerize each app. Bro containerization has been pissing me off lately lol everything has a flatpak/snap and they’re hot garbage with only like 70% of the original functionality"
- r-055: "for example most apps I can’t run on startup without a manual setup."
- r-055: "Or the thing with discord the other day. LITERALLY was just trying to boot into discord and start a voice call. Ended up getting fucked because I needed to restart the app 😂"
- r-055: "there’s no command to just reset audio devices within an app"
- r-055: "Yes this is a rant. Lol. Intentionally trying to ask why anybody by choice would use Linux as a daily driver 😂 maybe in doing something wrong"
- r-055: "But until you convince me or I convince you welcome to another episode of ‘Wizard tries to use Linux, part 1002’ 😂"
- r-055: "maybe today I fix WARP lol"
- r-055: "Yes we can unpack"
- r-055: "But FIRST"
- r-055: "explain. Do you, as an expert, EVER GET TO A POINt where there’s NOT SIMPLY MORE TO UNPACK 😂"
- r-055: "Because hang on"
- r-055: "Hang on"
- r-055: "Hang in there"
- r-055: "It SEEMS to me like it’s retroactively designed to continually be fixed as you go. As in… after you get everything working you have this carefully constructed jenga tower of proprietary nonsense only you understand. / … and if works fine. /  /  / … until you want to run kotor on proton. ‘Let’s boot an old gold of a game and enjoy nostalgia’ /  / Then, you acquire the invalid emitter crash problem. And your day or r&r turns into ‘ima patch this bug for the next joe’  /  / Does that mindset EVER end to the point you can just use ur pc like a normal human being without expecting something to go wrong? /  / Cus as a seasoned user of windows. Linux. And a smidge of mac… it seems literally only wi […] […]"
- r-056: "y'know the more i hear the phrase 'best practices' the more they seem like shit practices"
- r-056: "i'm not even kidding the more i hear that phrase the worst they become"
- r-056: "there's zero universe that should exist where that fucking swap file doesn't dynamically grow if needed to prevent OOM"
- r-056: "THat's actually such an oversight"
- r-056: "btw when I insult the mongoloids that make this stuff i do so on purpose... because they're unlikely to respond directly if i don't attack the decision and come across as a script kiddie from the get go"
- r-056: "i just enjoy triggering keyboard warriors like that"
- r-056: "i almost always end with 'ah that makes sense you're right'"
- r-056: "but until they do i'm 100% just out here thinking they're mongoloids because it's a stupid standard. But yeah it probably has a reason for being that way... i'm sure someone else has considered making it dynamic or having it configurable to that end"
- r-056: "literally windows ftw for that"
- r-056: "Look at it this way"
- r-056: "What happens when Linux runs OOM?"
- r-056: "hang on"
- r-056: "does it: / - A: crash/freeze or force terminate some of your programs losing you potentially hours of work / - B: handle it programmatically for the user and warn them that the kernel just prevented a critical issue, thereby saving the user work and time"
- r-056: "i'm not just talking about this one scenario lol. A seems to be how linux distros want to faciliate most of the stuff for some reason"
- r-056: "I literally run windows because it does so much in terms of B"
- r-056: "is anyone in the linux community trying to like... change the mindsets cus currently the overconfiguration potential just leaves a lot of gaps like this"
- r-056: "they say debian is stable as a rock... but i'm pretty sure this issue would still exist there"
- r-056: "yes you could say it's a user error"
- r-056: "but also why is linux advertising to non tech savvy users and acting like the original hurdles of trying to use/run linux are gone"
- r-056: "the desktop environment looks much nicer but other than that it's still kind of the same design principles. Design principles that require tons of configuring and pentesting everything under the sun to make sure some unexpected issue doesn't happen"
- r-056: "why is there no attempt to salvage […]"
- r-058: "The fact someone even needed to ask this is exactly the problem lmao"
- r-058: "The brainpower that led to the question is exactly a problem. Simply typing ‘paint’ should bring up the alternative. It should have never gotten this far"
- r-058: "When Discord, Google, Microsoft, GitHub, etc. say "Use a security key", on Windows the OS can respond with Windows Hello (your PIN or biometrics) because Microsoft implemented a full platform authenticator that browsers can talk to. / On Linux (including Fedora 44 KDE), is there a similar way to authenticate?"
- r-058: "I managed to fix the cloudflare-warp thing. It was not easy and I probably made it worse. Thoughts?"
- r-058: "I ran: /  / ```bash / sudo dnf install -y [link] [link] [link] [link] [link] / ```"
- r-058: "*almalinux* lol"
- r-058: "Yo man what's good i wanted to apologize (again) about the above.... i seem to become heated in the spirit of discussion and debate and i seem to be unable to track when you're in it for the interest and curiosity and passion or if it's just becoming a burden. I'll try to be more mindful moving forward. It really did seem like you weren't interested in an open discussion so that's why I got so heated. /  / If you'd like to cut out debate/discussion and just keep this 'hey can you teach me linux' we can do that too..."
- r-058: "Hey man! In the interest of respecting your time I found a solution you may be interested in! /  / So kinoite/silverblue doesn't *specifically* need to use flatpaks. I found this solution which works really *really* well. /  / >  / > ## 🧊 Fedora Silverblue / Kinoite Model (immutable OS) / >  / > This workflow is describing Fedora’s **immutable desktop variants**: / >  / > * **Silverblue** (GNOME-based) / > * **Kinoite** (KDE Plasma-based) / >  / > These systems use **`rpm-ostree`** instead of traditional package management. / >  / > ### 🔒 Key idea: the host OS is immutable / >  / > * The base system is **read-only and versioned** / > * You don’t normally install dev tools or packages directl […]"
- r-058: "full guide: [link]"
- r-062: "Hey I'd like to run an idea by you"
- r-062: "I believe the problem with pykotor isn't python, but the amount of imperitive code being used. Imperitive isn't a word that's typically used in software dev but I've gotten pretty used to using declarative code as I manage my kubernetes cluster. /  / I think the issue is not the weak vs strong types in python vs c#. I believe it's the explicit nature of every function being overly complex, causing to entire program to have a ton of points of failure"
- r-062: "every skill, task, and concept in life has a balance. Staying within that balance involves knowing what's on both sides. / - **Extreme left**: Terraform, Kubernetes, HCL, and helm use declarative code (almost configuration files).  The downside is it is pretty difficult to configure and customize the exact way you may like. / - **Extreme right**: What we have going on in PyKotor. A bunch of functions with duplicated code basically everywhere. Tons of installation.resource() constructor calls, location calls, each editor almost defines its own implementation of the same thing."
- r-062: "this is a good example of what i'm talking about. [link]"
- r-062: "I am reaching out because I'm aware this is like 20% of a solution for a kotor library, a blunt direction to meander in. Wondering if you have a more canonical way to do something like that?"
- r-062: "For example you'd think there'd be some GUI library that'd let you create editors for classes, without having to write code-behind. Like define a class, and be able to create, from *just* that class, a functional editor."
- r-062: "sorry if this isn't interesting"
- r-062: "The problem with the toolset/pykotor. Your hypothesis is about weak typing"
- r-062: "Yes, that's correct, almost exactly lol"
- r-062: "But as I'm working with the .net stuff and almost the exact 1:1 code i'm realizing that's not exactly the problem."
- r-062: "<[link] this file is a pretty good example of what I mean."
- r-062: "Ideally this editor/window shouldn't need code-behind at all."
- r-062: "For example some research I've done, I've found projects that'd use wxWidgets (somewhat cool alternative to qt) to dynamically create a gui from cli (code behind): /  / <[link]"
- r-062: "> Turn (almost) any Python command line program into a full GUI application with one line"
- r-062: "I am getting the vibe you're not interested at all. Just wondering what you're doing in Kotor.NET?"
- r-062: "if it's a dumb idea I might drop andastra to start helping with kotor.js 🙂"
- r-062: "That would be the tradeoff, finding the balance would be the strat"
- r-062: "Yeah that's the extreme left i defined here, the same problem with kubernetes/helm/hcl"
- r-062: "How is that possible"
- r-062: "it's been totally opposite for me."
- r-062: "Kotor.NET would benefit us all in the long run. Don't doubt yourself man!"
- r-062: ".NET is great for backends, tooling is amazing because dotnet runtime has almost seamless release/publishing […]"
- r-064: "[…] more specifically could be ran on [link]"
- r-064: "as in, modders will use *that* instead of the shittier frontend we make"
- r-064: "Also that would allow them to use Copilot to mod. which would be disgustingly broken (as in stupidly op)"
- r-064: "What the fuck else is there? you just shit on vim and emacs"
- r-064: "Didn't mean that aggressively just genuinely confused what ide you use for .net if not microsoft's"
- r-064: "- The intent was to let modders use vs code which i thought was a great ide / - You said you hate it / - Given i don't know how else anyone can even code in .net i wondered what you use"
- r-064: "there's no shot you use visual studio the bulky thing from 2022..."
- r-064: "wait really?"
- r-064: "I have 32gb of ram and even that isn't enough to run that on most days lol"
- r-064: "Brother I have 5"
- r-064: "wat"
- r-064: "Nah that's wild haha"
- r-064: "But yeah we already have a frontend regardless it's gucci. A language server would allow one to alternatively use it with whatever editor they want however"
- r-064: "even eMacs"
- r-064: "brb my cat's going nuts"
- r-064: "Ah you're right. But it's larger, and takes ages to open anything […]"
- r-065: "nobody will explain what I did wrong"
- r-065: "Why do my posts keep getting deleted"
- r-065: "I spent so much time writing those up and I wanted input"
- r-065: "But no I think DESPITE ME LITERALLY CREATING THE FUCKING ORG [partner] thought it was within his right to set me to Member"
- r-065: "so I’m no longer an admin"
- r-065: "Actually such brainless thinking to stand in the way of the ONLY GUY MAKING PROGRESS OUT HERE"
- r-065: "Please explain?"
- r-065: "he has full push access why doesn’t he just remove FUNDING.yml himself?"
- r-065: "He instead went to [partner]"
- r-065: "And has the gall to say I DONT HAVE CONFLICT RESOLUTION SKILLS. Dude actually pansied out of a conversation that him and I could have easily resolved. One fucking file…"
- r-065: "I don’t get it"
- r-065: "Right but I didn’t get responses last time. He says he responded and he pinged me. But [partner] DELETED THE THREAD"
- r-065: "so I didn’t even *see* that"
- r-065: "More or less I’m so tired of asking for permission to do anything around here it feels like I need to ask to upload a fucking sticker or gif"
- r-065: "Which he made fun of me for doing!"
- r-065: "which it was"
- r-065: "He escalated to [partner]!"
- r-065: "I called him out on that too and he won’t apologize."
- r-065: "So whole day it felt like everyone is against me"
- r-065: "We literally could have resolved that so easily"
- r-065: "He LITERALLY HAS PERMS to fix it himself"
- r-065: "just delete FUNDING.yml"
- r-065: "WHICH I TOLD HIM ABOUT"
- r-065: "THAT WAS THE FIRST THING I TOLD HIM. ‘My bad the anger feels unwarranted. You can just delete funding.yml there’s no need to escalate. I can do it when I’m on my pc next’ […]"
- r-067: "[…] Cook with another’s food."
- r-067: "Why else is it open source?"
- r-067: "am I not allowed to fork it and do stuff with it? 💀"
- r-067: "they publicly deleted the fork before I even had a chance to look at [partner]’s issue at my computer. Still haven’t logged in today"
- r-067: "But he literally complained about one file"
- r-067: "Three lines in one file"
- r-067: "Did he really have to delete the whole fork? I spent a bit of time on it and now I don’t even have access anymore"
- r-067: "It’s no worries this is why I am going back to my Puritan roots so I can understand why. Through effort I’ll get there"
- r-067: "So how did I violate his open source license of <none> and why won’t he answer my question about that?"
- r-067: "it is hard to align to his wishes when he’s given me nothing to align to"
- r-067: "My father was a Puritan and I’ve recently started to appreciate the simple mindedness a bit more. It gives me a simple way to finally interface with all of this communication confusion i have in the professional world. So those licenses kinda need to exist, and I take them seriously for sure. Going into this AI world the law is all we have in terms of ethicality otherwise it’d be argued ai steals everything. And they already lost that case afaict."
- r-067: "I’m just embracing a new world one that I don’t have a say in 🤷‍♂️ if anything this is a learning opportunity for him to specify a license"
- r-067: "in that way I did him a favor"
- r-067: "I’d never say that to him because it’d make him angry"
- r-067: "but from a utilitarian standpoint, if a gaslighter did what I did to him and had BAD intentions things would have been a lot uglier especially if they DID make money off of it"
- r-067: "So in that way I just prevented a disaster. 🤷‍♂️. Overall utility is benevolent and positive. Light side points have been earned."
- r-067: "TLDR; use AGPL to avoid the SaaS loophole of others selling your work."
- r-067: "And if you don’t want AI to steal your work, swap to codeberg"
- r-067: "explain how I’m the asshole when overall utility is benevolent and good."
- r-067: "this is an important lesson for him to learn. Because not all people are kind. I’ve learnt the hard way. But he didn’t have to treat me like a jerk. All I did was point out a problem. I offered to remove it and he went to [partner] over my head to remove my permissions on the org"
- r-067: "The org I literally created and let him rename"
- r-067: "the same org I spent 20-30 hours on this week streamlining all the settings on while I multitasked that wasm thing while also multitasking the discord bot stuff."
- r-067: "so in all I had a pretty productive weekend and I managed to teach too. Just sucks I have to pay the price"
- r-067: "no I’m not insane I totally get why he’s virtue signaling. I’m just through pretending like I need to conform and he’s right when I know for a fact I triple checked my math already on everything I just said. Look up the character House M.D. for example he is a benevolent guy that cares about people and helps them grow. Everything a role model should be going into this ai craze. As EVERYONE is scared. I make mistakes so people can protect themselves from true horrors"
- r-067: "And that will be my contribution I guess"
- r-067: "Maybe. But that was my thinking going into it. I have timestamps to prove it 😉 and if [partner] didn’t delete my thread I’d have whole ass facts […]"
- r-069: "What’s the purpose of the door hooks exactly?"
- r-069: "what exactly are aabb/bwm and what do they relate to walkmeshes (wok/pwk/dwk)? like i understand parts of the answer but not the full ‘eureka’ lol"
- r-069: "[link]"
- r-069: "my team has looked through most of the open source projects, taken the whole game apart in ghidra, and you still seem to have more answers than we could realistically figure out"
- r-069: "No joke one guy reversed the entire thing, naming and documenting each and every function in swkotor, over a two year period."
- r-069: "Had zero idea."
- r-069: "I would like you to read the conversation. Not that you’ll have the eureka. But to understand the problem. Would you mind? Should only be about 10 messages or so"
- r-069: "You already a member of the discord?"
- r-069: "TEN years?"
- r-069: "[link]"
- r-069: "Start of the convo is [link]"
- r-069: "I feel like I’m a novice mage standing in the presence of Gandalf lol"
- r-069: "bringing him into this I mean"
- r-069: "Huh some of the convo is in another channel"
- r-069: "[link]"
- r-069: "Okay much of your messages somewhat make sense as to why kotormax is suggested"
- r-069: "While I understand 3ds max is a good way to achieve the desired results what I’d like to have is a full mental understanding of what’s going on on the lowest level. 3dsmax, kaurora, kotormax, all of that is closed source 🙁"
- r-069: "I have no idea why I said this at the time."
- r-069: "Maybe everyone else are the insane ones"
- r-069: "the warp point seems to be desynced. but it does seem to be a consistent linear offset that each component is skewed by, which implies it should be possible to deterministically do this in pure code, instead of manually editing the boundaries/coordinates/points/etc in the kits. / i seriously respect all the time and effort [partner] put into this especially the kits. Each one created from scratch. / But my theory is the game developers did not manually create kits for each level... they had a level editor, similar to this indoor map builder (like it must have been two dimensional based on puzzle pieces that you can drag in, rather than a 3d implementation). / this by far is the most complica […] […]"
- r-073: "[…] Bruh"
- r-073: "Started a call that lasted 0 minutes."
- r-073: "you're hiliarious"
- r-073: "brb"
- r-073: "that question i don't want to point awareness on but lol i think peoplpe are just blatantly ripping and sharing the assets/resources around with each other regardless of if they've bought the game or not. /  /  / We just assume they have bought it and would never have reason to assume otherwise."
- r-073: "ah you know my blunt/straightforward communication style did not help me here"
- r-073: "you think we're coasting on ambiguity rn?"
- r-073: "Yeah lemme clarify. I'm about to reply to your message with this: /  / > sorry that was a bit ambiguous. You're saying you *don't* want to discuss the topic of allowing the community to donate to our open source projects? Or you *don't* want to **regulate the #🧵asset-transfer channel**. / >  / > Way you wrote it is kinda ambiguous."
- r-073: "Conversation kinda got away from me."
- r-073: "Expecting a C&D and worrying about it imo is somewhat... paranoid, i think."
- r-073: "i hate politics"
- r-073: "no ok you're not following the dots that's my bad though i explained poorly. /  / Worst case scenario (low probability of happening): / - Accepting donations triggers awareness from Disney / - They look for things to 'get' us on. #asset-transfer falls under that category.  / - I immediately jumped to that last point to get ahead of the topic. I raelize now that added more confusion"
- r-073: "but basically the longer these conversations focus on legality/ethicality/C&D the more paranoid everyone will be about any progress/awareness in general. /  / we should take a stance. That was what the whole re group chat was about. I don't like C&D/legality being brought up every 5 minutes personally. Are you worried about that? and if so why?"
- r-073: "I don't personally understand why it's a concern. There are **dozens** of other engine rewrites and communities out there that *do* accept donations, and generally garner community involvement in whatever way they intend to contribute. /  / Many people do join with stuff like this: [link] /  / or saying '"
- r-073: "'i don't have much dev experience i wish i could contribute some other way'"
- r-073: "Yeah that's my bad man I wasn't even **THINKING** about the first damn response being the question of ethics/legality"
- r-073: "because it's not illegal/unethical. Lol. /  / Sometimes I wonder if I was born with a permanent foot in my mouth"
- r-073: "To reciprocate on the push back, I won't fail to point out potential flaws with your strategies if I believe them to be a hinderance overall. I don't push back yet. I wonder if there *is* an issue with jumping straight to a legality/ethicality/C&D topic so often. The users of our discord are currently being given exposure therapy of expecting it at this point, basically Pavlov lol. /  / That is why I did the april fool's joke, to loosen people up a bit and remember to have fun with it. Since nobody intends on doing anything illegal. [link] /  / We've been pretty smart so far."
- r-073: "Yeah even during my mania last week on those new meds I looked back and I still remembered to send a 'if theres any issues on my account please remove the admin role from my account as we see fit'. /  / Yeah that could have been worse for sure lol. Basically just adjusting to a new SSRI (anti anxiety). had no idea how my body would react to it 😄 /  / Looks like I simply acted like an overzealous/energetic dumbass for awhile and mostly embarrassed myself more than I did cause any harm to the community. /  / Anyway my point is everyone here is responsible lol. /  / Perhaps the **first** step would be only putting **sponsored** status on **SOME** repositories. And maybe not pointing TOO much at […]"
- r-073: "it shouldn't be advertised. It should be something that's requested."
- r-073: "[link] delete this message if you want 🤣 /  / > why do I send you messages like this? /  / I'm aware i'm up-front no nonsense and loud/overzealous. Removing my messages may make the information and demeanor I bring more tolerable. /  / I'm just not sure how blatant I want to be about the annoyance with legality/ethicality lol. The wishy/washy stuff inhibits progress :/ […]"
- r-074: "Yeah well I guess I want an understanding. / - Why did you reach out? / - What was going through your head? / - Why *this* change instead of another change. Like you didn't mention the discord emoji I added or anything. Or the discord bots I've been putting together."
- r-074: "Allow me to guess"
- r-074: "I think you see anything on the surface web as a threat/liability"
- r-074: "so what you're wanting is to somewhat centralize and deliberate about our public image"
- r-074: "but honestly this was so much of an annoyance to me i'll probably just use OldRepublicDevs and if you ever want to merge you can reach out. That'd be more efficient."
- r-074: "Thoughts? Does that solve the problems I was creating?"
- r-074: "Look it's like, I check in, I feel like a dick for posting so much requests."
- r-074: "And people tell me 'stop posting so much'"
- r-074: "So I try to do things. Harmless things. And it's all 'wizard stop doing things without checking in' lol."
- r-074: "it's not my fault you guys have full time jobs and/or i like doing this more than y'all. Been like a week since [partner] responded to anything and idk even where [partner]/[partner] went 😂. /  / All this to say sorry 🤷 i'll stop using the openkotor name didn't mean to start an issue. Thought you'd welcome it seeing how much github is turning a large group of repositories for ***'train-your-ai-here-off-our-codebases!'*** lol. I think [partner] is using [link]"
- r-074: "anyway do you want this huggingface group to be removed/my messages removed or what? you got kinda quiet on me. Lmao"
- r-074: "I don't know what you want from me sry. reread if you need clarification on where i'm coming from 🤷"
- r-074: "good because i wasn't offering to leave either"
- r-074: "Don't know where that came from"
- r-074: "Fill this out lol? might be easier than whatever we're doing here."
- r-074: "i'm not really expecting you to that would be hilarious. But I definitely have a few projects I want to use something like this for lol."
- r-074: "i use ai because i clearly have a communication issue and nobody reads what I write anyway. I just assumed summarizing my information with ai would be appreciated 🤷"
- r-074: "I feel the same way about literally all of this"
- r-074: "Most is still unresponded to. I mean it's a two way street. This conversation just isn't constructive. I'm not trying to start problems either."
- r-074: "Example? […]"
- r-076: "Why not help with the rewrite engines instead of duct taping the old buggy engine"
- r-076: "exe level patches introduces a level of complexity I’m not convinced is necessary or viable. I already think even the widescreen + 4gb patches are too much. What you should do is hook in a DLL that lets users create their own code caves"
- r-076: "back when I was doing client-side modifications we created [link] for that exact reason. Too many game-level memory modifications conflict in convoluted ways"
- r-076: "Maybe you have addressed these issues already in kotor-patch-manager I’m sorry I still haven’t had a chance to read most of this"
- r-076: "Especially when a readme isn’t even written"
- r-076: "It does seem like a lot of our goals are aligned"
- r-076: "Your biggest problem if you want users using it will be intuitive design and reduced friction. I’m not convinced exe level patches won’t steepen accessibility requirements and add unnecessary complication. Many users e.g. proton require much of the engine to remain vanilla. You’d need to look at mesa and its gl library/workarounds for the engine or you’d be alienating 80% of the platforms for example"
- r-076: "Many users are hardened to how kotor modding has always been and are reluctant to try new things, hence why holopatcher intends to reuse TSLPatcher specifications. If you already have 2da level patches and other stuff done it’d be a large benefit to include tslpatcher’s changes.ini specifications. Using ai I recently ported most of it here last weekend: <[link] one of the largest problems I’ve been working with is the inability to reuse other projects and garner collaboration, mainly do to the programming language used. Something like Kaitai struct would solve that problem. A base library for most things Kotor would be a huge help"
- r-076: "Kaitai is a way to define binary structures and compile to dozens of language including but not limited to go/python/c/c#/typescript"
- r-076: "I’m sure there’s a better alternative to Kaitai struct, unfortunately haven’t had much time to look into it. But general accessibility level requirements for developing for kotor at this time is steep and usually involves reinventing the wheel at some level. My goals are to change/improve this somewhat"
- r-076: "Engine rewrites solve the alienation problem and improve accessibility and they also garner popularity in general. You have a good reason for being so openly against it? At the very least it’d help understand the engine you’re reversing"
- r-076: "2.5 years is a long time to devote to reversing a game engine for memory modification at the DLL level is all I’m saying."
- r-076: "Optimality and efficiency are important to me. I’m a fullstack developer in my day job and the amount of time I can devote to kotor projects isn’t as much as it was unfortunately [link]"
- r-076: "Came across this in passing and thought it may interest you: [link]"
- r-076: "> Lest I create a framework nobody uses /  / Many people do recreate the wheel due to a lack of a base lib which I was addressing earlier."
- r-076: "But yeah I just believe the 20 year old engine isn’t worth the manpower required to delay its future funeral. Unless you can prove you can do things such as: / - increase the party cap count and the total amount of characters that can be brought with a companion / - embed the game to be played directly from a website / - introduce many of nvidia’s improvements or a translation lib for directx / - solve the dialog skip bug plagueing users in the second game /  / I currently don’t think (some of) the directions you’re going is optimal. In general, my stance always involves respecting anyone who can prove me wrong in any topic of theory (learning opportunity for me) :)."
- r-076: "I was pretty vague earlier but what I meant was ideally these should be hand in hand since the same reversing process is required for both"
- r-076: "Lmao that xkcd is gold"
- r-076: "Much of this is contradictory. You either can do what you enjoy and like doing, tinkering around, or you can do what the community will be happy to be involved with. And if you feel you could do both maybe create a repo to hold some inner secrets of the engine so rewrites can use as reference. That’d be optimal and get me on board, furthering some of your projects goals too. Guess I’m saying the xkcd isn’t entirely accurate"
- r-076: "I’ve checked out your RE briefly but not fully for all that stuff you commented for the gog exe"
- r-076: "Signature based patching at very least would be optimal. Zero reason whatsoever to hardcode addresses except out of laziness. That way k2 developers could contribute, too"
- r-076: "[link]"
- r-076: "Kaitai can generate real code for plethora of languages. So I’m not understanding how that xkcd is relevant. It doesn’t create another standard. For example if someone wants Python code they run the Kaitai compiler and they get Python code that they can modify further to their hearts content. /  / Though to be fair i'm not entirely certain Kaitai is the most maintained/best project to use to achieve kaitai's goals. Is that exactly what you meant earlier with the xkcd comic?"
- r-076: "[link]"
- r-076: "I wrote you a readme. Let me know if it helps or if I can improve it at all 👍 . […]"
- r-079: "TSL has a dialog skipping bug that happens when the event tick time counter gets set to 0 or a negative number due to a memory leak. It happens randomly after prolonged playtime. /  / Originally I specified something like *if someone hits dialogue skip early they have an unfair advantage*. Basically any unskippable dialogue is immediately skipped regardless when it happens. That'd shave literal minutes"
- r-079: "Also, finding this and patching it would solve the largest complaints in tsl to date i imagine"
- r-079: "We're talking hundreds of lines of dialogues skipping through in a blink of an eye lol"
- r-079: "Only way to resolve it as a normal player is simply restart the game.."
- r-079: "whattt"
- r-079: "whattttttt"
- r-079: "that's crazy man haha"
- r-079: "is this documented anywhere?"
- r-079: "Fast text is an acceptable idiom. whoever coined that is acceptable"
- r-079: "> Fast Text is a glitch in KotOR in which the sound files for conversations are not properly loaded, making all dialog in conversations advance instantly with the exception of user-chosen dialog options. While Fast Text happens naturally as memory usage increases, it can also be forced with an application of AMG as follows: / Seems different than what I reverse engineered. My findings says a timer tick rate that's defined as 60000 is incorrectly overflowed and treated as a negative number (effectively zero). Potentially I looked into this incorrectly though, until you've sent this i've had no real way to test it"
- r-079: "speedrunning community is op."
- r-079: "I love this so much"
- r-079: "is it possible it's different in tsl?"
- r-079: "Figuring this out would be probably your biggest breakthrough as far as the community is concerned. This has been plaguing people for two decades in TSL."
- r-079: "In my case, next would be crash after character creation 😂"
- r-079: "- <[link] / - <[link] /  / why are there two explanations for the same thing in different pages 🤦"
- r-079: "Oh I should read. Sorry about that"
- r-079: "I will say this has a lot more tangible proof than my theory about the tick rate counter does. […]"
- r-080: "Yes. I'm a bottom up learner unfortunately."
- r-080: "Like for example, instead of reading cloudflare's api documentation (thousands of pages) I jump in knowing nothing and skim to find what i'm looking for.  /  / is this bad practice generally? if so how could i find some sort of middle ground i wonder"
- r-080: "also: /  / - Walkmesh Visualizer by glasnonck /  / this small project saved my bacon in multiple scenarios over the last few months 🙂"
- r-080: "Can't stand videos either, really..."
- r-080: "I've found the best way to learn/do anything is to just start doing it, and research/learn from hurdles I jump over. /  / I'm painfully aware the world doesn't teach like this generally."
- r-080: "Without oversharing, yes I'm diagnosed ADHD. Has caused more problems as I go into adulthood rather than 'sitting still in school' stigmas that are implemented there. /  / I simply struggle to pay attention to things unless it's immediately relevant and important to something i'm *doing*."
- r-080: "AABBs cause you any trouble...?"
- r-080: "Took me three full days to figure out."
- r-080: "Well technically I was also doing DWK/PWK/WOK/BWM/AABB and the LYT components."
- r-080: "> The truth of the matter is you have to learn how to learn, which a lot of schools are not good at doing for students. And the practice required can also be VERY frustrating / God this sounds so painfully obvious when you phrase it like this. Not sure what I was doing but it did sound innate on some level."
- r-080: "AABBs are mostly there for optimization purposes anyway."
- r-080: "BWM I mean."
- r-080: "> I will say that, in my experience from teaching, that "learning styles" are kinda a myth. / What makes you think this btw? I promise to contemplate objectively, I've seen this before but I've always dismissed it as neurotypical oversimplification of the brain's active processes."
- r-080: "Generally don't like making excuses for myself. To be candid the amount of AI summarization's i've been relying on lately hasn't been something I'm proud of when I hadn't been this dependent previously. So figuring this out would help that problem out significantly, going into 2026 🙂"
- r-080: "Many articles exist about how ai is apparently ruining our attention spans. Which is somewhat obvious. Large amount of respect for you reverse engineering much of this swkotor.exe without such workflow optimizations"
- r-080: "Okay but there's a balance. AI is just a workload optimizer, allowing one to focus on the stuff they *actually* enjoy."
- r-080: "What I don't like doing is browsing 10,000 pages of documentation to find one thing."
- r-080: "for example, when setting up my k8s cluster for <[link]"
- r-080: "For the same reason, you use ghidra. You could just disassemble manually and translate hex dumps yourself otherwise, ghidra is already cognitively off-loading much things."
- r-080: "So strictly speaking the only difference is where one chooses to draw the line. […]"
- r-081: "Dumb question but given you have all the functions documented and commented and signatures setup properly, how difficult would it be to get debug symbols out of this?"
- r-081: "lol"
- r-081: "Something I could load into visual studio, attach to swkotor.exe, and be able to breakpoint at specific functions or code i suppose? or at least have basic c/c++ ide functionality like 'find references'"
- r-081: "Ah I see."
- r-081: "I can't think of any reason it wouldn't recompile into identical assembly though? Compiler optimizations are already implicit in the decompiled code.  I'd assume that the msvc version would be the only variable...?"
- r-081: "if you're trying to repack and re-encrypt the drm i don't think that would be possible to get a sha256 match to the original though. I briefly played around with that (wrote an unpacker and a decrypter that'll turn a steam swkotor.exe into a gog swkotor.exe, but it never would idempotently match 1:1 in roundtrip  fashion)"
- r-081: "i imagine a bunch of issues would pop up as you said. I'm not familiar with c/c++'s compiler that well, but the 'thunk' functions would be a potential pain"
- r-081: "Not sure why the c/c++ compiler seemingly arbitrarily just creates functions that do nothing except jump to another function. I believe that's what a thunk is anyway"
- r-081: "I did want to talk about <[link] though. /  / Would it not be simpler to just migrate the `GlxyMap` struct somewhere where larger amounts of unallocated/unreferenced memory exists, so you could size it however large you'd like to? /  / What wasn't making sense to me is, if the struct is sized 0x10, and a bunch of code in various functions in the EXE utilizing the galaxy map struct are using a array.Length() call on that struct or something, couldn't you just update all references somewhat easily? or is that code not unified into a single function/potentially 0x10 is hardcoded in multiple places? That part wasn't clear, really, but in my experience when trying to resize structs like this I ne […]"
- r-081: "huh i don't know why that was such a mouthful. Basically: /  / ```c /  / struct GlxyMap { /   // ... / } /  / void fun_00342457 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / int fun_00324357 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / void fun_0039787 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / void fun_00323427 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / ```"
- r-081: "or is it actually more like dozens of functions under the sun are hardcoding the size 0x10"
- r-081: "Actually this directly clarifies it"
- r-081: "But we could, i'd need to find a mic"
- r-081: "Okay if I'm understanding correctly, the core issue seems to be that expanding a fixd-size array inside the struct (e.g. from 16 to a larger number) shifts all subsequent member offsets. Since compiled C++ code uses hardcoded offsets like `struct_ptr + 0x1C` for member access, this breaks every reference to later fields. So treating the `available_planets` field as an `int*` pointing to a separately allocated array, which would presumably be dynamically sized?"
- r-081: "Probably worth mentioning the galaxy map itself is small, 16 would already be polluting the space"
- r-081: "The camera area in the room directly behind the galaxy map would be a good place to put extra planets/warps. Since this is a DLG."
- r-082: "Hey man how does all the game’s AABB/BWM/walkmeshes work, exactly? Why’s it so different from other games? And more importantly, how EXACTLY do you think the devs created all the levels in both games? Do you think they had a level editor or that they hand wrote all the models/walkmeshes? what do you think their tools looked like for level editing? You think they were manually aligning coordinates/planes/boundaries? just wondering why I can’t programmatically make them fit together in a way that makes sense, which implies they *were* manually packaged/bundled. like a human guessing and checking measurements in the game to avoid seams/alignment problems between doors and the walls for example, […]"
- r-082: "But thank you for this.. honestly good advice. Definitely feels like I should be able to figure it out"
- r-082: "Also the other day this clicked, as a great idea. Don’t remember why 🙂. validation/verification reasons I imagine?"
- r-082: "Could ask in a forum and ping you if you prefer"
- r-082: "It’s my understanding the reason level editors exist in dragon age, the Witcher, jade empire, nwn etc is due to their tileset approach. Odyssey does something bizarrely different"
- r-082: "Well I was asking if you had any plans to release this"
- r-082: "Apologies for the confusion"
- r-082: "Happy holidays, btw!"
- r-082: "I think I’ve learned something new every single interaction I’ve had with you. This one being about how important exact specifics, and details, are in writing"
- r-082: "but the second point is what I’ve been asking about 🙂"
- r-082: "Verifying gff implementations with what the game does in its own loader would save me hours ~~penetrating~~ pentesting each toolset version in the game for various combinations of various values in various fields between gff  formats"
- r-082: "Eh everytime I look at the functions ` readare` or `readutc` in pykotor I still think I’m missing a field, or something is incorrectly assumed to be default, or I have the wrong field type for a certain field."
- r-082: "Basically the same problem KOTOR tool suffers from, which is why that tool isn’t safe to be used for editing, only extraction."
- r-082: "Why the f*ck did my iPhone think it was acceptable to replace the word *pen-testing* with *penetrating*"
- r-082: "Would implicit defaults (when a field isn’t specified) be all together in a single function or spaced out depending on context? For example the field ‘OldHitTest’ in DLG. Still don’t know what that one does haha"
- r-082: "A lot of the toolset just assumes a default is zero or -1 without any verification whatsoever"
- r-082: "You seem to be missing a gff field type (or two)"
- r-084: "[…] But yes it does not currently run and I have zero clue why 😂"
- r-084: "What I’m saying is I need a more exhaustive broken down  roadmap"
- r-084: "I think."
- r-084: "as even my own isn’t working right now"
- r-084: "Just too much code lol"
- r-084: "I think testing various parts of the engine in modular parts would be useful, such as save serialization"
- r-084: "Not sure how to do as such with the engine loop."
- r-084: "But yes awhile back you mentioned you don’t have interest in the engine rewrites. I still argue both should be worked on in tandem since it’s helpful collab for everyone as shown 😄"
- r-084: "Here is an existing project for another game that somewhat backs my point: [link]"
- r-084: "I must have read your mind"
- r-084: "lol"
- r-084: "Well i was vague because i am not sure what my next step is for Andastra specifically and was looking for some steps that’d benefit both of us"
- r-084: "I believe the correct term is spitballing. I apologize for being terrible at it."
- r-084: "Yes!"
- r-084: "There were a few reasons it was overall necessary"
- r-084: "Much of the community is working with .NET and I’m hoping that and its toolset will garner some more open collaboration"
- r-084: "Many people get turned off to JavaScript, c/c++, Python, it’s somewhat obnoxious how relevant that xkcd has been becoming"
- r-084: "explain the first part lol […]"
- r-085: "Could I possibly get you to proofread some writing I'm doing for the game?"
- r-085: "I'm about to drop a large, large roadmap for the future of the toolset and i want to verify my motivation is being understood and explained properly"
- r-085: "goal would be to revolutionize and reform the modding ecosystem but that may be a bit ambitious. Though given the amount of stuff I'm about to release I do think that's an accurate statement 🙂"
- r-085: "Bro i value utmost brutal honesty. You can be as mean as you want."
- r-085: "But as much time/effort as you're willing to put in I guess?"
- r-085: "Also you're not going to believe this..."
- r-085: "but here's another developer's reaction"
- r-085: "Thanks man. I mean don't feel obligated if at all possible. Would prefer you to determine that yourself, based on your own interest levels"
- r-085: "Wow"
- r-085: "well is it honest?"
- r-085: "When I got into all this I was just annoyed researching a bunch of scattered integrations: things that provided pieces of a solution. Either with problems that I had to discover on my own that are so niche it's ridiculous or problems that are generally gatekept behind the veterens / so i'd like it to be more accessible to the next person that comes along like myself /  / I know 99% of the people I meet will not be that person. But that one person that comes along like myself will. And that's why I do it 🙂 /  / To that end i'd like pykotor (and potentially andastra in the coming future) be basically on the production level of comprehension for a  development SDK as if Bioware themselves were […]"
- r-085: "^ that is my overall goal 😂 i don't know if the document is facilitating that or not"
- r-085: "How do I see your comments/reviews? So far I just see my writing."
- r-085: "I don't use 'bloodbath' or google docs so it's probably a button i'm not seeing"
- r-085: "Oh you went full proofread/revision/editor on this"
- r-085: "Yeah my writing is terrible. I did not really need that focused on."
- r-085: "Just the ideas and concepts as a whole I wanted advice on. […]"
- r-087: "This sounds like postgresql. Looks like an annoying attempt to get new people vendor locked into amazon's stuff"
- r-087: "I miss the days when were unifying things under conventions/standards. Like usb-c might be the biggest example of that that'll happen in our lifetime i'm afraid"
- r-087: "One sec"
- r-087: "You take that back!"
- r-087: "What's wrong with usb-c? i'm not an engineer but seems great.. i mean i'm not picky I thought lightning was already good. /  / the whole 'right side up -> doesn't work, flip it to wrong side -> doesn't work, flip it back to right side -> *finally works*' was an annoying problem to deal with previously."
- r-087: "just happy they unified and it's reversible lol"
- r-087: "Sounds like a skill issue on those manufacturers"
- r-087: "They're getting paid to weld copper and silver... how hard could that possibly be. Sorry they're having *so much issue* changing over from micro/macro usb or whatever they previously were making"
- r-087: "I'm kidding but i'd like to know why it's an issue"
- r-087: "tldr: straight Nonsense (until I hear otherwise)"
- r-087: "um?"
- r-087: "I wonder why"
- r-087: "jk"
- r-087: "what do you remember about it?"
- r-087: "maybe I could search it semantically from that description"
- r-087: "youtube's search has been horrible lately"
- r-087: "In ghidra I notice you have kotor_MAC and kotor2_MAC. Which mac version is this? the macstore version?"
- r-087: "from what I recall there's two versions. Well actually three, one of them is just a .appimage pack of wine wrapper around the windows version 😂"
- r-088: "Anyway, I think the next step into ghidra RE outside of kotor.js/openkotor would be to develop an algorithm that can sig scan for the matching similar function in the other programs."
- r-088: "Something like 70% of the programs should be exactly 1:1 matches, while the others may simply have simple small changes of some sort. You don't re-invent a game engine overnight, which would otherwise be required for k1 -> tsl in the timespan they've had, so most of the engine will more-or-less be the same. The problem seems to be I can't *prove* it with any iterative method I've concocted so far"
- r-088: "Yeah I could just take random 8-byte sequences of bytecode from each ghidra function and try to find the same byte sequence in the other programs but that isn't a satisfying solution. I'd like something that will actually use more ghidra functionality so I can get more involved with working with their extension API"
- r-088: "Because redoing all the work you've previously done, with the other games/platforms, does not sound like a good use of time"
- r-088: "But failing that it seems ghidra supports another sort of external server, mainly: / - PostgreSQL / - Elastic / - Some other form I can't recall"
- r-088: "This would only happen if things changed at compile time."
- r-088: "You any reason to suspect something like that happened?"
- r-088: "e.g. different flags being used, optimizer strategies differed between msvc compilers but this was back in 2001/2003 so i'd have to look into what all was available. I don't know when visual studio came out lol"
- r-088: "I just haven't seen it in my experience is all"
- r-088: "Usually I can copy like e.g. 12 or so byte sequences and find them in the other disassembly. Halo 1 pc -> Halo 1 CE, Battlefront 1 -> 2, battlefield hardline -> bf4"
- r-088: "just some examples that I remember having success with the sig scans anyway"
- r-088: "Unity is another good example."
- r-088: "Though in unity usually you'd be using dnSpy and wouldn't need a sig scan since the symbols almost are already available unless it's an ILP binary."
- r-088: "I think ILP is the wrong term but it's been awhile lol"
- r-088: "il2cpp"
- r-088: "What I'm trying to say is it should be possible to find the exact same function at a different address even if it has only a few changes in instructions based on the previous work I've done"
- r-088: "Well some level of heuristics is required I am not disagreeing there."
- r-088: "But even some rudimentary oversimplistic should work for 60% of the functions. Which is still a large amount of them. But doing some unifying step here would definitely reduce the workload/accessibility for others overall when they're trying to find a function named 'CSWC::LoadModule' in one game and realizing it's 'CSWC::LoadLevel' in another when they're both the same function lol"
- r-088: "Well this isn't constructive though. Are you trying to say I shouldn't bother?"
- r-088: "Or it doesn't interest you?"
- r-088: "Yeah that would probably handle a large amount of functions […]"
- r-089: "[…] Huh?? Do I just ignore your messages completely or something?"
- r-089: "Man I’m so sorry lol"
- r-089: "I don’t remember you sending me this"
- r-089: "The row limits usually are caused by the compiler optimizers right? that’s why I think different platforms would have different integer limits anyway"
- r-089: "Or is that incorrect? You think it’s something BioWare determined during development"
- r-089: "?"
- r-089: "I just imagine Xbox would have smaller ones due to the 64mb of ram they were capped at"
- r-089: "and other hw constraints"
- r-089: "Nobody mods the Xbox version for this reason"
- r-089: "Loops?"
- r-089: "why would a while/for loop affect anything like this"
- r-089: "short or char vs int? Wdym? There is no int in c/c++ they have (u)int<8,16,32,etc>"
- r-089: "right but that doesn’t explain why a short vs a int16 would cause different results when they should be the same thing. I’m just not understanding the point you were making even with the explanation."
- r-089: "i think you’re saying c/c++ has size constraints from the type definition but I thought we were past that page"
- r-089: "yes I doubt they would change a byte to a word or dword in the pc game vs the Xbox but I imagine if they specify a operating system or a platform that the compiler would generate extremely different results resulting in a bunch of different capacities"
- r-089: "Also yes I understand most of the confusions and frustrations in our discussions at this point are caused semantic misunderstandings but I imagine these are temporary problems. we’ll figure out as we interact in these collabs/knowledge sharing discussions"
- r-089: "From now on I’ll post anything resolution related on that issue post"
- r-089: "😂 that makes sense"
- r-089: "I thought I said resolution *order* though"
- r-089: "i don’t think I needed to say that. My bad […]"
- r-090: "can i drop a bunch of random questions here for you to answer with zero urgency haha. Just wondering if you've heard of some of these ideas/stacks i'm looking for"
- r-090: "1. is there a way in programming to convert/write 'code' as natural language while still keeping it fully in tandem with the original code? like if i have a bunch of object oriented classes defined and functions for those classes, is there some implementation out there where I can write all the code as natural english language, something like UML, without losing specificity?"
- r-090: "For example if I want to transpile it to a relevant language but i'm not exactly sure what stack I want. Also just genuinely curious if a structured language exists that i can compile or use with some interpreter"
- r-090: "2. in a codebase, separate from the IDE, is it possible to see a mermaid/figma graph of all of your functions, classes, etc and also drag classes/functions from the graph to actually migrate and organize it, rather than tediously cut/paste between physical files in an ide?"
- r-090: "3. Pick your favorite one and briefly explain why (no debate necessary just curious): /  / > A. Local process with IPC (e.g., Electron main spawns Rust/.NET/Python and exchanges messages) / > B. Local HTTP/WebSocket server started separately (frontend connects to localhost) / > C. Remote server (hosted game logic) over HTTP/WebSocket) / > D. WebAssembly module loaded in browser/Electron (still non-Node runtime)"
- r-090: "4. if you had to pick an engine rewrite to back, and drop the other,  do you think kotor.js has more utility since it can run in a web browser, or is reone the play since a webasm can potentially be written for it later and it's a native app written in the same language using the same (but newer) compiler?"
- r-090: "just honestly curious about your opinions 😛"
- r-090: "5. if you've messed with pyghidra have you figured out how to login/use a shared project within it? i think i've tried everything at this point and no bueno (tried with and without AI 🙁 )"
- r-090: "6. have you noticed any lag on the ghidra server? wondering if i'd be able to reduce these slightly: /  / ```yml /   services: /     ghidra: /       image: blacktop/ghidra /       container_name: ghidra /       environment: /         - MAXMEM=4G /         - DISPLAY=host.docker.internal:0 /       deploy: /         resources: /           limits: /             cpus: 2 /             memory: 4g / ```"
- r-090: "seriously man no pressure i'll come back next month 😄"
- r-090: "> But your qualifier "without losing specificity", leads me to think this may be an impossible ask.  / In my mind it makes sense. I haven't specified a framework, language, or anything so the specificity already is language agnostic"
- r-090: "#1 isn't intended to target LLMs, but i did throw my example into an llm because my original was messy: /  / ```ps1 / # Convert a Unix timestamp (seconds since 1970-01-01 UTC) into a DateTime object. / # NOTE: Unix epoch is 1970, not 1980 — that’s the DOS/FAT epoch. /  / # --- Example usage in a common everyday pattern --- / $ErrorActionPreference = "SilentlyContinue" /  / $rawTimestamp = 1707427200  # Example: some API returned this /  /  / # Call the function and validate the result / $converted = Convert-UnixTimestamp -Timestamp $rawTimestamp /  / if ($null -ne $converted) { /     # Sanity-check the output: ensure it's a DateTime and not default/min value /     if ($converted -is [DateTim […]"
- r-090: "You ever hear the phrase 'a picture represents a thousand words?'"
- r-090: "i think this example already represents a thousand words. But most of those words are implicit to powershell. For example no other language has a $ErrorActionPreference"
- r-090: "If I was writing the code in a natural langauge to start, would it not just be language-agnostic, simplifying the actual contents of that definition?"
- r-090: "The reason I don't use UML in daily programming is because i'm *always* running into obnoxious language specifics that make the implementation i have in my head somewhat impossible"
- r-090: "it is possible i'm not thinking of other examples but tldr: it seems most of this would be a nonfactor due to the natural language definition already being syntax/language/interpreter/compiler agnostic (<----- not sure on the correct terms here lol) /  / > I've seen attempts at something like this before. There are several formal specification languages that came out of Academia in the late 90s, but none of them quite live up to what I would consider "natural language". Natural language processing really only hit its revolution within the past 5 years with LLMs. I have seen demos of people using models such as Claude Opus to analyze code and generate things like UML or mermaid. But your qual […]"
- r-090: "> 2. As mentioned before, I've seen AI implementations of diagram generation. Claude Opus is particularly talented, though I believe this is also a feature of CodeRabbit. For non AI approaches, I've used IntelliJ IDEA's built-in diagram feature to create class diagrams for Java code in the past; of course this is Java specific, but I believe similar tooling has been invented for other languages. As far as drag/dropping for migration goes. I'm not aware of any tooling that would allow for this. Though, if going the AI route, I suppose you might be able to get mileage out of a workflow like: generate a mermaid diagram -> use a mermaid editor to reorganize it -> pass the mermaid code back to th […]"
- r-090: "2. wasn't even intended to be llm specific but you're probably right it has utility there. I just am tired of breaking the heck out of my ctrl+v/ctrl+c/ctrl+x buttons."
- r-090: "1. wasn't either... but i guess that's almost implied with the phrase `natural language` isn't it...?"
- r-090: "is it just a bad idea?"
- r-090: "is that why i'm not finding it anywhere?"
- r-090: "or is it just like extremely non-trivial to do as you said"
- r-090: "### #4: / > My intent was to get your opinion on this debate: / > Hardware is dirt cheap nowadays, do we really need to be micro-optimizing native apps when web apps have so much more visual fidelity, supported on most devices, and easier to deploy/package for an end user (just a website) / > for #4 / > I see so many native apps, still, and i really just.. don't understand it? Why work on a native UI, and maintain a more complicated low level project when there's almost no trade-offs to using... well... anything that can be embedded in a browser, electron..? / > To clarify i'm certain i'm missing something. People wouldn't do it if there's no point. But I can't think of any scenario except: […]"
- r-090: "or if c/c++ projects like reone just are written in c/c++ because of nostalgia […]"
- r-091: "Sorry I’m terrible at these social queues stuff and it’s more so over text IM"
- r-091: "Can you explain why lol? Why is low level and native programming so popular? As someone who started: / Batch -> PowerShell -> Visual Basic -> LUA -> Java -> Python  -> .NET -> node.js I’m absolutely in love with node.js + npm"
- r-091: "mostly because UI development and platform agnostic is OBNOXIOUS in native apps. It never looks as good as react and it is damn near impossible to verify every feature in Mac/Wayland/X11/Windows 7-11"
- r-091: "Which usually are my targets. I dropped 7-10 recently though."
- r-091: "Browser deployment just works.. it’s damn simple…. And less work. /  / So I guess…… how much actual performance improvements are you getting with rust/c++ vs the bloated chromium/electron stuff"
- r-091: "and is it worth it?"
- r-091: "I seriously don’t mean to start a debate I just want an actual good reason to do low level stuff. /  / Wait is it not about pros/cons and more just about it being fun?"
- r-091: "Ohhh you had said this day one! Brilliant."
- r-091: "As an ADHD adult man yeah you probably take this for granted so this is understandable."
- r-091: "I’d like to ask about 5. Again once you make the switch. I could rewrite agentdecompile for v11.2 if you believe you could help me figure out #5 on jython. Seriously. I can’t get the shared projects functionality working regardless of what I attempt on pyghidra. Everything I read tells me this api should work but testing through a stdio server to reproduce is not ideal. The network connection also doesn’t always work so getting a testing environment going to reproduce the issue is non trivial. /  / TLDR: if you have interest a 20 line example in jython that actually connects to our server would be leagues helpful"
- r-091: "For #6 let me know if it becomes a problem in next few days as I publicly give the read only account and the documentation out. I have another VPS I could throw it on I suppose."
- r-091: "Or if you’d like to offer better hosting feel free. I’m just using the free Oracle cloud VPS thing."
- r-091: "While not wanting to dive into this too far I do have ADHD. It can make me seem difficult or obnoxious to communicate with. I simply ask for patience and honesty when relevant. I don’t have an evil bone in my body but sometimes I do joke a bit too much or like to argue about things that don’t matter. But yeah other than that I have a feeling some *really* cool things are about to happen in the community that we are spearheading. As you said we’ll be speedrunning kotor.js in no time 🦵"
- r-092: "So another reason I'm confused. You said this the other day. I thought the whole point was to get some users on it. Otherwise why are we hosting it at all and why are you accessing it so frequently then if it's just you and me using it?"
- r-092: "Well that was the point. It's not like we're risking anything sensitive.;"
- r-092: "I'd rather know about security issues in the first few days during  the surge, than a year from now"
- r-092: "Learning works better that way i think. I patched a few areas where someone could acquire admin the other day based on what you fixed so it's working out so far"
- r-092: "i mean if this was a bank we were protecting ofc i wouldn't be this bold lol"
- r-092: "with someone else's money"
- r-092: "Idk it seems you're very wishy washy about where you're standing on it sometimes it feels like we find mutual understanding and then i go to do something and then it's not aligned with where we are. /  / The only time I've been reluctant is something i got over in pretty much an hour. For some reason I had a thought in my head that you were asking me to host because that way you're not responsible. So I thought it was *possible* I was being too rash. But we did research that day, went over to metaforce found they do basically the same thing we were originally trying to do. So i was just overthinking. my reluctance was simply checking in with reality because i did kind of impulsively throw th […]"
- r-092: "People need to make up their mind I think. Strict guidelines of what we can and can't do, full governed rules, otherwise it's fine we'll make them as we go."
- r-092: "I mean I don't even understand where the misunderstanding is happening. I don't really want to be causing issues with this i just wanted to put this up for everyone to use. It's pretty useful to dump into copilot to find some information on how to do something in e.g. blender for example or some hardcoded row limit of some kind in a 2da function."
- r-092: "Yeah alright I'll just stop dropping things publicly I guess 🤷 idk what's happening at this point lol"
- r-092: "TLDR: this fake-green light actual-yellow light is too confusing to me i'm just going to make this for just you and me i guess"
- r-092: "sry if any of that is non-sequitur i did pull an all nighter 🥶"
- r-092: "mb"
- r-092: "Just an adhd thing. I don't do nuance very well i guess"
- r-092: "The messages I removed were simply because i wasn't happy with how v1 turned out, based on your review. Not because of the liability or anything."
- r-092: "(none of this is your fault & I'm not attacking you btw)"
- r-092: "My bad I probably should have led with that"
- r-092: "Yeah I'd like to adhere to restrictions too I just wish someone would tell me what they are."
- r-092: "Like rather than after the fact. Like 7 of my prs were unusable because they contained too much RE documentation (would have taken longer to go through them than it would to just redo the prs from scratch)"
- r-095: "[…] from what i understood it was never provided by bioware, and only has usage with nwnnsscomp.exe"
- r-095: "*but* in the game itself it's implied that that's the scripting engine"
- r-095: "e.g. id 522 is function xyz in k2, 233 is function abc in k1. and tsl reuses k1's identifiers/definitions"
- r-095: "haven't seen that code in reone but i know where it is in andastra/kotor.js"
- r-095: "i significantly doubt that based on my own understanding. You still have the json dump of the game on your disk from when you ran my json converter tool 😄"
- r-095: "a simple `rg` through it would prove that or not."
- r-095: "now i'm curious whether a quick and lightweight semantic search tool exists"
- r-095: "I *really* need to replace `plocate` lol"
- r-095: "alright i will one sec"
- r-095: "WOW i can't believe i didn't know that"
- r-095: "you're right xD"
- r-095: "wait no..."
- r-095: "oh you don't know this"
- r-095: "OH so darthparametric told me something *interesting*"
- r-095: "the `nwscript.nss` provided in the BIFs is *not* the one used to compile all the `.ncs` scripts"
- r-095: "or something like that."
- r-095: "oh that's probably too nuanced to matter i'm not going to split hairs about that. IIRC they used a different one due specifically to ActionStartConversation not having an overload of an optional argument or something"
- r-095: "ok here's my final argument. You have this: / ```sh / data / - xyz.bif / - abc.bif / - def.bif / ... / Modules / - dan13a.rim / - dan13a_s.rim / - kor48.rim / - kor48_s.rim / ... / Override <empty> / chitin.key / dialog.tlk / swkotor.exe / swkotor.ini / swconfig.exe / strings.dll / ```"
- r-095: "so why is it okay to take apart `chitin.key` and `dan13a.rim` and all the GFFs and other stuffz within the bifs to figure out how they tick, but *not* the exe?"
- r-095: "in my mind they're all files..."
- r-095: "why is the fact that one has *code* important?"
- r-095: "because it sounds like `static data` vs `imperative data` is the discrepancy in your mind (may be using wrong terms)"
- r-095: "Right"
- r-095: "To clarify i'm not an idiot who forgot to mention the context"
- r-095: "my question is"
- r-095: "why can't we look at ghidra decompilations of swkotor.exe, in order to help us figure out how to make swkotor.exe's replacement? […]"
- r-097: "I don’t want a diagram lol I really don’t agree with the way you describe methodology. None of that proves anything"
- r-097: "There’s an infinite amount of people putting together convoluted nonsense but none of that actually implies anyone should be doing that. For example I could jump off"
- r-097: "Ok yeah but where’s the proof. Results. Benchmarks."
- r-097: "all you’re doing is diagramming a bunch of convoluted stuff that sounds good"
- r-097: "none of it proves it’s anything better than what I’m using."
- r-097: "Ok then make your own benchmark"
- r-097: "Literally just something that proves your thing is better than what exists"
- r-097: "Like again, a task that’s sent to ai without your pipeline, and a second identical task sent to ai *with* your pipeljne"
- r-097: "Compare the results"
- r-097: "how?"
- r-097: "I don’t understand why you can’t just do this other than you not wanting to be proven wrong"
- r-097: "ask it to create minesweeper or something"
- r-097: "okay great then make your own benchmark somehow. Just literally anything that proves results"
- r-097: "I’m not saying I don’t believe you I’m saying I’m wired to only care about things that have results lol"
- r-097: "I digest research that I need for sure if you’re saying research exists my guess is the proof/claim/results/benchmarks are included with it […]"
- r-098: "but that is quite the massive document you just sent over"
- r-098: "i like sharing ai stuff not sure if you use/desire what i send you but i just created this [link]"
- r-098: "i got so tired of so many things rate limiting after 2 minutes of light use asking us to pay  lol"
- r-098: "i love unfiltered data."
- r-098: "idk if i'm asperger or what but idk why most people just say 'i dont want to' it's bizarre to me"
- r-098: "i mean i'm not tripping i'm just bewildered"
- r-098: "lol"
- r-098: "well it's not though. It's a single export button. The reason chat logs are preferable is i can see what kinds of phrasing you're using, and what results you're getting, and compare to my methodology. I've been feeling stuck in my own headspace lately when it comes to ai"
- r-098: "but all i ever find when i search around for others chat logs is the stuff that's promoted for some company or something"
- r-098: "its hard to find just random people building stuff with ai, as i don't want to include anyone who's *trying* to get discovered y'know?"
- r-098: "it's like a catch22 with the search engines i use nowadays"
- r-098: "i wish seo wasn't a thing"
- r-098: "yeah if you change your mind though i'd enjoy reading them, building a *brain* 😛"
- r-098: "you can export all your stuff like this btw"
- r-098: "Ah"
- r-098: "there's a latin phrase i can't recall but it means something like 'the thing explains itself'"
- r-098: "hang on lol i'm brainrotted for the night but my point is valid xD"
- r-098: "*Res ipsa loquitur*"
- r-098: "i think that's what you're saying when you're telling me to read this."
- r-098: "Do you want me to be honest though?"
- r-098: "I mean no offense but honestly i really don't know when i should be holding my tongue anymore. I've nothing *mean* to say. Been confusing since i got kicked i'm ngl. […]"
- r-099: "The engine rewrite itself here is an overly ambitious endeavor. Originally it started simply to gauge the current quality and intelligence of ai vibe coding tools. Realizing pretty quickly this was actually writing source code that, to the best of my ability to review, was matching line for line what I was able to decompile using ghidra. The community already provided a lot of reverse engineered components. /  / Being 2026 we’ve all used ai coding agents and ChatGPT to generate at least boilerplate but until that day this was the first time I’d ever given such a task to generate code I didn’t even understand. /  / Game engines are complex beasts, anytime I’ve ever wanted to design a game or […]"
- r-099: "This is the OpenKotOR community, I have and always will continue and intend to fully disclose everything and anything that may be relevant. /  / I do not like to reinvent the wheel but unfortunately none of the other engine rewrites are MIT licensed and all are extremely code-left, meaning they are restrictive in how one can derive from them. /  / Given Apeiron’s C&D this is immediately relevant and important to  scope out and avoid."
- r-099: "Ideally I’d like to migrate away from a full engine rewrite into something that other great developers such as [partner] - KotOR.js have already sacrificed blood, sweat, and tears for 🙂 /  /  / ## Why KotOR.js? /  / There aren’t a lot of other good choices: / - reone is odyssey-targeted and much of it seems to be tightly coupled, which makes things like accessibility and tooling difficult, which is important to me / - xoreos is a grandfathered dinosaur with a similar problem. It’s difficult to extend past its original design. Setting up boost and various libs on windows seemed to be non-trivial, even when trying to offload much of that to ai. / - KotOR Unity (or the northernlights fork) lice […]"
- r-099: "Wdym"
- r-099: "remaking k1 is an engine rewrite by definition, what do you actually mean? Or what is the issue with what I’ve written?"
- r-099: "Huh I’ve heard differently. But what I am saying is it’s important to learn from their mistakes and take reasonable precautions"
- r-099: "What I understand is they reused assets that only users who bought the game are supposed to have"
- r-099: "Simply requiring one file ‘chitin.key’ and providing the entirety of their bits in ‘their’ game isn’t legal lol"
- r-099: "bif*"
- r-099: "I don’t know that’s what they did but I’m even paranoid about including nwscript.nss"
- r-099: "I guess I’ve heard differently."
- r-099: "We do a disservice to my project Andastra by debating semantics of an unrelated project barely important enough to be included in my explanation of my motivations. /  / I don’t know what other assets they were/weren’t reusing. It’s not like their C&D was made fully public nor was the full source code of the game they were building hype for and trying to release. /  / The important thing was this generated not only from me but from other engine rewrites that reasonable extra precautions should be taken and the threat of a future C&D is always possible"
- r-099: "Thank you for polluting my channel with a bizarre fixation on fourteen words out of the several hundred describing motivations for Andastra. I don’t understand why Apeiron’s C&D specifics are relevant at all beyond the following (anything and everything else not mentioned here is completely irrelevant): / - A C&D was submitted. To cease. And desist / - It actually happened / - Targetted a rewrite of KotOR in some way shape or form"
- r-099: "the specifics hardly are relevant. This is an example I pull frequently but basically when a billion dollar company tells you to move you don’t ask yourself if it’s lawful. We get out of the way because we can’t afford to get caught up in the chaos that comes with a lawsuit. /  / > InfernoPlus (also known as InfernoPlus on YouTube and [partner] on X) is the creator. / > Nintendo issued a cease-and-desist (C&D) notice to InfernoPlus on June 21, 2019, just six days after Mario Royale's release, citing copyright infringement. / > InfernoPlus immediately complied by removing all Nintendo assets and relaunching a reskinned version, but Nintendo followed up claiming continued infringement, leading […]"
- r-099: "Not saying they will bribe (I or anyone else doing this isn’t worth the effort)  but even a more charismatic or quick-witted lawyer than I could afford would influence the odds. Also a court case is not only expensive to defend but requiring a large time investment.  /  / Maybe it’s different for you in New Zealand?"
- r-099: "in America all I’m thinking about is the size of their company and the competition that is created from their own rewrite project they’re pursuing which means they would be motivated to shut down others"
- r-099: "That is the reality"
- r-099: "I apologize for my rudeness if it existed. /  / When I got into all this I was just annoyed researching a bunch of scattered integrations: things that provided *pieces* of a solution. Either with problems that I had to discover on my own that are so niche it's ridiculous or problems that are generally gatekept behind the veterens or the archived lucasforums/archived waybackmachine information. /  / What I am creating here is an integration that would have been satisfying and useful to the past version of myself that simply had a goal in mind and little to no place to start beyond a small Python project that you created a long time ago, in a galaxy far far away… 😅"
- r-099: "I carry this torch with honor and dignity within Andastra"
- r-100: "interesting so it still is *loading* the resources *whilst* the main menu is visible"
- r-100: "Excuse my french but... || I'm beyond frustrated with this piss poor resource loading implementation. Frankly pykotor's and andastra's is better... ||"
- r-100: "Gotcha"
- r-100: "can you elevator pitch the current resource loader in reone to me?"
- r-100: "is it just loading everything one by one into memory comprehensivley at init?"
- r-100: "because I might 🤮"
- r-100: "`Loading data/models.bif (891027456+262144)…`"
- r-100: "OH GOD [partner] why have we not fixed this months ago"
- r-100: "ah that's awful"
- r-100: "hopefully i'm misunderstanding xD"
- r-100: "i'm getting timeouts after 10m just because it's taking actual lifetimes to load `data/models.bif`"
- r-100: "hmm"
- r-100: "yeah so that's where this pr probably should end... we need a better resource loader. or the timeout can be set to several hours and pray the user has 32gb of ram for now"
- r-100: "Fair"
- r-100: "100% fair XD"
- r-100: "i really should stop being such a perfectionist 😛"
- r-100: "ok so this needs to be a new pr unfortunately"
- r-100: "Hahahaha"
- r-100: "I'd like you to look at PyKotor's/Andastra's at some point. Wonder what [partner] is doing in kotor.net. Still an installation class? /  / the utility and feasability of the robust implementation makes it extremely intuitive to just grab the resource you need and tracking which resources exist and what offset their data is at at runtime"
- r-100: "it's quite good. Probably it's biggest selling point imo."
- r-100: "[link]"
- r-100: "[link]"
- r-100: "(this code is 1:1 with pykotor's)"
- r-100: "the load magic itself happens in FileResource. I wonder how difficult it'd be to implement this quickly in c++?"
- r-100: "um... whatever save pipeline reone has would be the biggest issue"
- r-100: "(the bioware archives inside of bioware archives can get a bit convoluted within those .sav's) […]"
- r-102: "Okay why are you talking about commission if there’s no buyer?"
- r-102: "am I the buyer in that context?"
- r-102: "Ahhh"
- r-102: "there’s two s’s in that word btw but I’m getting you now"
- r-102: "Staying focused and relevant is important when navigating the landscape"
- r-102: "context is key"
- r-102: "So what’s an example of what isn’t art?"
- r-102: "Just to make sure I’m understanding you correctly"
- r-102: "I’m sorry huh how is that different from this example? The goal was to provide two different scenarios lol. One where the human element is important, and the art is real art, and the other where it ain’t and it’s just rehashed from some other creator/training […]"
- r-106: "[…] if you can type to it that somehow means they're letting random users use pro if a plus member is sending a link"
- r-106: "which is wild"
- r-106: "ya just send this info to perplexity in the chat"
- r-106: "or send it to chatgpt to create a better prompt for your perplexity reply"
- r-106: "go from there"
- r-106: "it should be able to simplify the tools/instructions to your exact scenario and nuance"
- r-106: "i imagine there's a learning curve ya"
- r-106: "ya idk why i said that"
- r-106: "was watching simpsons earlier maybe that's why"
- r-106: "*shrug* i tried lol"
- r-106: "perplexity's answer looked spot on"
- r-106: "ight i'll take your word on it"
- r-106: "good luck tho let me know if any of the plugins are indeed good if you do try em out i'm still trying to find time to learn blender at some point"
- r-106: "bro you do not need to say 'there is no way to speed this up' and be unmovable from it."
- r-106: "you don't even know if perplexity's answer works or not because you haven't tried the plugins."
- r-106: "why not just say 'i dont trust any potential faster way because i want to trust my methods'"
- r-106: "'and introducing unknowns might screw even more things up and i dont feel like trying it'"
- r-106: "which is understandable"
- r-106: "but flat out saying it won't help is nonsense […]"
- r-107: "[…] How is that relevant"
- r-107: "All in all this repo gets into the side of ai that confuses me beyond belief. I see this a lot in various groups where things get a bit chaotically exhaustive. Like I’m jumping into page 100 of a book without any idea what the premise is"
- r-107: "I do see these visions a lot. Like not yours specifically but the ethical and futuristic predictions of ai always confused the hell out of me because they jump into some understanding I haven’t been given"
- r-107: "[link]"
- r-107: "Your repo reminds me a lot of this discord and I don’t understand their stuff either"
- r-107: "I’m not sure these days honestly but it has a lot of info and visions similar to what you talk about in the repo"
- r-107: "Maybe you could explain it to me so I could finally understand lol"
- r-107: "But your repo is alienating to me for the same reason. I don’t have any context on why any of the stuff you’re saying matters"
- r-107: "basically we’re in this arms race with china rn. Reason there’s zero moderation is due to race to asi. If we regulate/moderate ai then china will basically destroy us"
- r-107: "Anyway I don’t know man it’s all a bit much lol. I’m an ADHD adult male who just finds problems in life and finds solutions. Usually with code. Your repo doesn’t give me a problem to solve. So it’s like trying to play a video game with a movie disk of Interstellar. There’s nothing to play"
- r-107: "if that makes sense"
- r-107: "in a PlayStation where the games are digital round disks"
- r-107: "actually that’s a bad example since PlayStations can play movies lol"
- r-107: "Didn’t you write it?"
- r-107: "usually adhd just means I struggle to understand something unless it’s explained interactively. Where I can participate in the learning by asking questions and given some breadcrumbs to follow"
- r-107: "I just don’t understand their problem to solve"
- r-107: "explain that to me and stuff will start to click lol […]"
- r-108: "well I don’t ask myself that every day"
- r-108: "it’d be a waste of time to confirm 0.0001% chance"
- r-108: "Or whatever the decimal"
- r-108: "I’m just saying everything I do and know and understand, I’ve spent my life proving myself."
- r-108: "Some things obviously I’ll pin as ‘learned externally’ and come back to if I ever need to verify/validate it for some argument or some relevant understanding I’m working on"
- r-108: "The whole problem with politics is people don’t know how to critically think or reason"
- r-108: "So I conclude there is no solution despite my childhood self wanting to find one some day. Never made sense how we were able to find some complex science such as prion disease and misfolded protein, but we can’t even decide on immigration policy or anything. My step dad today said ‘if trump cured cancer people probably still would deny him’. Didn’t seem to take when I said ‘ok but what about if Joe Biden did that??’ Would you vote him? /  / The whole notion that if the house and the (forget the word, executive branch group of people) are not the same ‘side’ then nothing gets done is idiocy"
- r-108: "what’s the word for the president’s closet/basement/group lol that’s such a momentum breaker of a tip-of-the-tongue lol"
- r-108: "Well I was talking about whatever group is in the executive branch under the president but your explanation works too."
- r-108: "People are incapable of judging ideas on their own merit"
- r-108: "Adults can’t be retaught and mostly are stuck in their ways. So that’s why I care heavily about education. The only way to actually make any change is education reform"
- r-108: "Thanks"
- r-108: "Anyway I’m saying education systems should teach the value/utility of the knowledge, promoting base human desire to achieve it. For example much of youth wants to be the next Mr.beast lol. They see the utility and value of his content almost immediately: $$$. /  / The labarynth of the reward cycle, to go from obscure boring history, to trigonometry, to eventual college, to money, is not taking advantage of base human anatomy, evolution, and psychological understandings at all."
- r-108: "The tests while in good intent, do not do what they’re designed to do in my lived experience. If you’re saying the research does not confirm my findings I’ll say either the research is skewed (which I will look into if you give me actual sources) or I’ll say it’s changed recently"
- r-108: "Frankly I hope the latter. But probably the former"
- r-108: "I’m sure there’s a world of understanding that you have that I don’t. While I would appreciate the same respect I am aware being me and so different from the avg person I’m not likely to get that. That is probably why I probably seem like an angry dick sometimes. But overall I appreciate you and these conversations. To invalidate mine because it’s not factually based or researched can be obnoxious but I’ve learned to live with it."
- r-108: "Maybe when I was a kid I took ‘be yourself’ too literally. Modern education systems simply want to browbeat people into society it feels like"
- r-108: "I mean it’s not like I hate myself, I’m depressed, or anything. Just I struggled a lot and have always wanted to do better to the next generation"
- r-108: "dunno if it’s an Iowa thing but many people don’t volunteer or really care about the issues."
- r-108: "Got a brother who parties all day and smokes weed going ‘yeah world sucks. More you learn and think about it it sucks’"
- r-108: "Another one works with a cnc machine. Actually my youngest (brother). Absolutely brilliantly he just went to trade school, got certified in something with CNC machines, and makes 40-50k a year"
- r-108: "But many people I've talked to online, in person, everywhere just feel content bringing kids into this, working 9-5, 'relaxing' in front of a tv or with alcohol or something. I really don't get it lol"
- r-108: "Cabinet. 😂 idk why i couldn't rememember. But you're right, I meant Senate/House […]"
- r-109: "[…] I disagree, given you *immediately* mentioned being 'skeptical' about crypto. When there wasn't even something to be skeptical about, in the context i mentioned it in."
- r-109: "So you seem highly opinionated about it lol"
- r-109: "have... have you done this before?"
- r-109: "hahahaha"
- r-109: "look if you want to prove you're looking at it objectively, explain how in any context, that mentioning you're skeptical of crypto is relevant"
- r-109: "Like I would probably believe you if you could rationalize it"
- r-109: "Really"
- r-109: "And there's no shame in being polluted by the garbage crypto junk that's out there either or the hype cycle claims"
- r-109: "I'm gullible af back then anyway, invested a lot"
- r-109: "mostly because my brother was into it and i rarely hang with him so it was something we could do together"
- r-109: "Not that I lost much either."
- r-109: "I wish I could say the same about my brother..."
- r-109: "Exclusively and highly specifically answer how the word 'skeptical' is relevant to the conversation in this image."
- r-109: "Because the conversation was about AI."
- r-109: "You don't see why that seems like you may be opinionated heavily? the sheer mention of crypto having a reaction that got us into the whole debate about whether it's viable crypto? the only point i was making was i remember the fear in the early days of crypto."
- r-109: "ohhhhhhhh"
- r-109: "that was not clear lmao"
- r-109: "no worries i'm sorry too. i made presumptions based on that comment and put more weight in it than the other followup messages you sent"
- r-109: "I mean if you're answering honestly, anyway."
- r-109: "Yeah you did say this."
- r-109: "and this"
- r-109: "and this"
- r-109: "why did i assign a smaller weight to those than the first message? i definitely wasn't objective […]"
- r-110: "it's just so dead simple compared to the nonsense i was trying with qt, maui, and avalonia"
- r-110: "so what people do for especially mobile support is the same thing"
- r-110: "i'm not sure what your launcher does"
- r-110: "but i'm saying the world has kinda leaned towards hosting local webservers with a few lightweight javascript/static files"
- r-110: "this is your gui"
- r-110: "then you deploy with a single command"
- r-110: "e.g. `npx -y [partner]-app`"
- r-110: "it depends what your'e doing though the backend isn't going to be able to move files around on their phone"
- r-110: "but if you want it to launch the game yeah that's doable"
- r-110: "there's no way to mod kotor without a computer"
- r-110: "simple modifications maybe but never full support"
- r-110: "looks good"
- r-110: "why are you asking me if you've already done it"
- r-110: "alright well good luck it doesn't sound like you're interested in listening to me anyway and more that you'd rather complain about your problem to someone. i do the same thing lol"
- r-110: "most likely you didn't consider android and ios apps are sandboxed"
- r-110: "i don't think it can be done but lmk if you prove me wrong lol"
- r-110: "the install method has always been computer -> phone"
- r-110: "i'm not sure why you're doing it like this"
- r-110: "i thought the whole point of maui was to write a singular gui app and have the same gui and app run exactly the same way on all operating systems in an agnostic way so you don't have to learn the specifics of those operating systems"
- r-110: "i feel like you've been talking about the launcher for a year htough"
- r-110: "i remember seeing screenshots in 2023"
- r-110: "it all looks like it took about that long anyhow"
- r-110: "it does look quite good […]"
- r-112: "But 'a lot' is subjective"
- r-112: "A lot is *always* subjective"
- r-112: "Even if you have domain specific knowledge it's *always* subjective"
- r-112: "My problem in the workforce is providing something I inherently need to believe I will never have because that facilitates my abilities"
- r-112: "The workforce prioritizes and promotes heavily the ability to provide overwhelming confidence in those abilities in a way that convinces others"
- r-112: "So basically someone suffering from the extreme form of the Dunning Kruger effect is the most effective at getting the job than me"
- r-112: "confidence seeems to exude from oneself and rub off on others systemically and in a way that overwhelms and distracts from objective reality. most likely a flaw of the human condition"
- r-112: "all of that is nonimportant to what you'll find more important to discuss"
- r-112: "Yeah basically this"
- r-112: "Your ability to say what i just explained in several paragraphs, in just 18 words is the most valuable skillset when working with AI right now"
- r-112: "AI is based on context, semantical understanding, and every token counts"
- r-112: "A token is more or less equivalent in definition to a word"
- r-112: "Using the correct concise words to describe something is more likely to get more qualitative responses from AI"
- r-112: "Since most other people will be describing those things the same way, meaning it's more likely to be in the benchmarks/training data"
- r-112: "If that makes any sense at all."
- r-112: "Figured as much thanks for reiterating I tend to be self-conscious in nature and i don't like that about myself really cus i know objective reality is not my immediate perception but yeah communicating generally is difficult for me for this reason i'm somewhat sensitive. Mostly I ignore it. The reaffirmation helps. Felt I should clarify what my brain is doing, cus while my brain is doing things surface thoughts like that isn't inherently me but the trigger exists and thus the prompt for clarification."
- r-112: "Yeah I imagine AI right now has the wrong people trying to use it. Like some sort of negative progress cycle of some sort"
- r-112: "it's counter-intuitive that the most capable person to be using it is the one that doesn't know that they know they're the best at using it"
- r-112: "Trying to explain that in any context is like pulling teeth"
- r-112: "Probably could say this about a lot of things though. For example I just watched S4 of Attack on Titan and wondered why in the heck the writing became atrocious out of nowhere despite S1-3 being amazing"
- r-112: "Learned the 'time-constraints' and various industry standards that are unlikely to change and not prioritizing 'result-driven science-backed' approaches is to blame"
- r-112: "Pretty much the same reason hollywood is failing right now despite billions and billions being shilled into the industry"
- r-112: "Is this relevant?"
- r-112: "I feel like I'm losing my mind"
- r-112: "Sorry my brain does this sometimes and the ultimate desire to talk through it burns in me 😂 […]"

## full exemplars

Read one before drafting. Notice where the move lands and how the exchange ends.

### r-001: why linux as a daily driver; how linux handles drivers vs windows (mesa/kernel vs userspace) (systems-engineer, redirected, quality 4)

- **self**: Hey I’m just curious what you do for a living I’ve met plenty of devs and compsci majors but literally no one with your domain-specific knowledge. Just been wondering for a fat minute as you have been dropping in over time
- **self**: usually I see a lot of fullstack or devops people or even like kernel developers but your knowledge breadth is just bizarre. Also just wondering: are you allergic to windows or if you have anything against them or anything
- **self**: I tried to swap fully and completely to Linux a few times and even I could never do it and get an objectively better quality pc than I could with win11. So my leading theory is you have a personal vendetta against Microsoft or something, OR you are a SteamDeck guy and learned much of this through fucking around with proton long enough
- **self**: Honestly jw. College didn’t teach me jack about unix/bsd stuff let alone the low level ops you seem to be proficient in
- **self**: Sorry for the pressure my questions/psychoanalysis may have caused
- **systems-engineer**: Yo! /  / At the moment I am just floating around from job to job, did some work for the Canadian government in Ops, but most of the breadth of my knowledge is self learned from just fucking around /  /  / Most people I ran into in College would always focus on a single stack to specialize in (tends to be better for employment) whereas I just kinda tried what was interesting, read a lot
- **systems-engineer**: As for Windows, I have just been around Linux for a long time /  / was stuck on Windows XP as a kid for the longest time (would tear it down almost monthly) and had a pretty decent interest in low level stuff, what makes things tick
- **systems-engineer**: So with Windows my view was always that I was held back by figuring out how it all worked because at the end of the day it is proprietary software
- **self**: Doesn’t windows provide api documentation and comprehensive symbols in visual studio though?
- **systems-engineer**: Well yeah, I guess I subscribed to the whole open source philosophy pretty early on
- **systems-engineer**: Stubbornness was a big driving factor too, Why play quake 3 or Minecraft on a windows pc when I could try and figure out how to do it on Linux which was infinitely cooler (and then learn more about how all the things work)
- **systems-engineer**: Also VS is genuinely one of the worst written pieces of software in the modern day imo (Windows seems to be getting up there now with how shit it has become) /  / On Linux I just enjoy the freedom really, my system's quirks are almost entirely my doing/fault 😛
- **systems-engineer**: Also it is a crime (and by design unfortunately) that More people aren't taught about Unix/BSD/Linux /  / you almost always have to opt in to that kind of course
- **self**: This  is how I did [link] though I admit it was difficult to figure out until I setup c/c++ and visual studio
- **self**: I’ve just never met anyone with this much dedication to continue using Linux this long.
- **self**: But mad respect 🫡
- **self**: I think I’ve tried swapping fully like 5 times in my life and always spending a week researching which distro was right for me. /  / But after few days I kept running into the most ridiculous lack of support in the most common operations
- **self**: I could probably find my notes but my conclusion ended up being ‘Linux was not ready to be used as a daily driver in 2024, there’s too much lackluster’
- **self**: I am envious of the latter part of this 😂 /  / And yeah I’ve hated visual studio from day 1 but frankly apt/dpkg/dnf have no better alternative either…
- **self**: also full honesty I’m too much of a noob to use vim and nano is prolly the first thing I install on a new box
- **systems-engineer**: I find myself that it is easiest to just go in trying not to necessarily wrestle it into being windows but to "port" your workflow into what would work under Linux
- **self**: Well… because if you run into an issue, those games have Internet forums that provide support for the supported os. When you say ‘I’m on Wayland’ people look at you funny 😄
- **systems-engineer**: Yeah that's true / Just need to find the right people 😛 /  / One of those big culture shocks is that on Linux you are essentially on your own (or if you know someone you're pretty well off) /  / if someone fixes something they share it so others can fix it, and so on and so on 😄
- **systems-engineer**: So instead of being on a game forum you might talk to the proton dudes, or the Wine guys that hang around GE's Discord
- **self**: so you use Linux as a daily driver? May I ask for your stack? Like what desktop environment? Plasma? X11?
- **self**: distro?
- **systems-engineer**: I did the distro hopping thing for many years and basically came down to 2 choices /  / For learning for a while: Arch /  / For ease of use and bleeding edge access without pain: Fedora
- **systems-engineer**: So at the moment I am rocking Fedora, Wayland, and Plasma
- **systems-engineer**: (Have been for a decade at least)
- **systems-engineer**: Used to dual boot windows but decided that was just not worth it after certain games became shitty (Destiny 2 in my case) […]

Moves: `probe_expert`, `states_hypothesis`, `apologizes`, `concrete_referent`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-003: cross-platform self-contained packaging; why pyinstaller gets av-flagged and .net does not (systems-engineer, redirected, quality 4)

- **self**: How’s cross-platform compilations work though? .NET for example is the best I’ve seen for specifically packaging/deployment ‘because Microsoft’. Can run one command to create a Mach-o .app, .exe, and an elf unix binary. All three supporting self containment of the various dylib/dll/<insert Linux equivalent in spacing on here> inside the binary itself as one executable file. /  / Is .NET the only SDK that can do this? Always wondered. If rust can do this I might just drop Andastra entirely and rewrite it in rust 😅
- **self**: the only canonical solution I’ve seen is Electron.
- **self**: But that’s mainly GUI problem solving
- **systems-engineer**: The only thing really limiting all of the toolchains out there from doing this is the libraries you use /  / In C: You can easily have a single codebase that compiles into all platforms depending on how you do things /  / if you rely purely on the standard library you are probably safe, but as you get more and more complex you need to abstract stuff (or use libraries that do that for you like SDL, OpenAL, harfbuzz, etc) /  / It seems like it can't since you need to then do the packaging yourself
- **systems-engineer**: With .NET it is abstracting the packaging part, you get your exe, appbundle and linux targz but all it is doing is taking the .netsdk (precompiled for that platform) and then sticking your dlls and assets in the final package
- **self**: harfbuzz i believe is font related if memory serves me well. OpenAL i think is... an open *audio* library? and no idea what SDL would be. /  / Just wanted to state my guesses for the record *before* I pull them up on google 😛
- **systems-engineer**: SDL is the simple directmedia layer, started off small but Valve started developing it so they could drop Win32 windowing and write code that worked everywhere
- **systems-engineer**: [link]
- **systems-engineer**: (also has abstractions for audio, graphics, and other networking stuff too)
- **self**: Also: / > It seems like it can't since you need to then do the packaging yourself / > ... / > sticking your dlls and assets in the final package / None of this is intuitive nor documented in any widely adopted way I can find.
- **self**: But even if it was explained and I implemented it, or a solution exists in the ecosystem for the cross-platform self-containable compile/bundle of the binary, my question would be *how to avoid **this** nonsense? [link]
- **self**: Because as I understand it, only .NET seems to be immune?
- **self**: I'm painfully aware this is a Windows problem 😄
- **systems-engineer**: That's kinda why I like Linux over Windows /  / With Windows: you have an app, dlls it requires and then *sometimes* you bundle some VC++ dlls, and they may be an old version, maybe you need some old windows dxcompiler shaders, etc. /  / With Linux, you have a distro based toolchain /  / you have all these packages for dependencies that you pull on, all standard all the same version everywhere /  / All the software that needs them (harfbuzz font rendering for example) all use the same version
- **systems-engineer**: pyinstaller for example, has to do this: /  / Pretend it's an exe so it looks "normal" to end users
- **systems-engineer**: it then extracts a minimal python install, and runs that to run your python app
- **systems-engineer**: all extracted on the fly and then compressed and upxed so it looks like a trojan 😛 (and the only thing stopping it from being one is the fact that your code is friendly 😄 )
- **self**: Well the issue is so many people used pyinstaller, that a small percentage eventually started using it for quick and easy trojans/rats/virus packaging. /  / Then that screwed everyone over
- **systems-engineer**: Yeah, that is the shit part about ease of use for something as powerful as python
- **self**: But what is bizarre, to me, is it's possible to do the *exact same code* in C#, compile with .NET, and get **zero** flags because Microsoft 🤷 /  / Okay I'm getting why you are a Linux guy after writing that sentence, that indeed is why I wanted to swap as well. But you also must realize when you create tools and apps you probably are alienating all of the people that are using windows no? and isn't that the most common OS in the world right now?
- **self**: I imagine deployment for a specific os like windows isn't a problem your projects deal with a lot
- **self**: For these reasons I wonder if this is why nodejs is becoming so immensely popular, increasingly so since COVID.
- **self**: But then I suppose I'd be asking you why naev's written in rust at all instead of a containerized Docker application using react elements and html5 for the gui
- **systems-engineer**: It all boils down to abstractions
- **self**: But I suppose I'm too obsessed with being canonical
- **systems-engineer**: That's kinda my favourite part /  / since I have started basically just cross compiling everything /  / Example: You can install the mingw package for Fedora /  / it gives you:  / a compiler that makes executable, a sysroot (and lots of other dlls) you can use to link everything /  / all the while all those dlls are versioned and easy to install via the package manager /  / You just need to write a script that searches the sysroot for all the libraries your app needs (mingw includes utilities to help) and then you're set
- **self**: God I wish there was an LLM that responded like this
- **systems-engineer**: One day 😛 maybe discord is selling DMs as training data
- **systems-engineer**: If you tool your windows stuff with mingw, you can essentially build windows apps without windows
- **systems-engineer**: Also: you avoid vcpkg and all the shitty large windows SDKs in the process […]

Moves: `states_stance`, `concrete_referent`, `probe_expert`, `admits_ignorance`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-006: why can't a rust compiler consume c/c++ syntax; ownership, data races, bindgen vs transpiling (systems-engineer, redirected, quality 5)

- **self**: Well I know that just because i've heard that so many times
- **self**: but an example as to what anyone means would be something i'd be interested in
- **self**: what's c/c++'s issue that implies it cannot do what rust is doing?
- **systems-engineer**: It can but it relies on humans to not make mistakes
- **self**: ??
- **self**: you either allow human's to make mistakes, thereby making it a low level language, or you abstract shit away for a high level implementation
- **self**: like an interpreted language like lua/python/go or even higher level of nodejs/electron
- **self**: Wait ignore those last three messages
- **self**: I think the issue is i'm thinking in terms of 'high' and 'low' "levels" when that concept is probably moot
- **self**: when it comes to rust
- **systems-engineer**: Basically it comes down to the compiler being blind if you look at fundamental problems
- **self**: Pinned a message.
- **systems-engineer**: C++: Thread A can hold a pointer to Data X. Thread B can hold a pointer to Data X. Both can try to write to it simultaneously. The compiler permits this. /  / Rust: The compiler sees that two mutable references exist for the same data and refuses to compile the code.
- **systems-engineer**: Rust can be unsafe if you want, you just have to tell it you want to be unsafe
- **self**: > **The compiler permits this.** / What the actual fuck
- **systems-engineer**: Also as well: a C/C++ compiler has no concept of ownership or how long memory should live
- **systems-engineer**: that's what I mean by  / > It can but it relies on humans to not make mistakes /  / You need to track that stuff
- **systems-engineer**: you forget you get a free after use bug, or a race condition
- **self**: Is there any pragmatic reason why we can't have something like tree-sitter be responsible for the lexer/ast/parser of the syntax and the compiler be mutually exclusive to the syntax/ast/language the user chooses to use? because i don't understand why we couldn't just use c/c++ language syntax with a Rust compiler
- **self**: Like i'm guessing something like 1% of the syntax for c/c++ wouldn't be compatible with rust's compiler? and that 1% would indeed make it easier to address as a person trying to migrate away.
- **self**: I'm somewhat aware that this is an ignorant query, with a lack of understanding as to the complexity of what would be involved but i really would like to know the answer to that question somehow haha
- **systems-engineer**: You'd have to change C++ syntax, since there's no words for the concept /  / Because the syntax is ambiguous, the Rust compiler would have to guess /  / If it guesses wrong, the program crashes /  / Rust is designed never to guess, so it would reject the code
- **systems-engineer**: In Rust you specifically have to tell it who owns it, is it mutable, how long should it live
- **self**: So C/C++'s syntax and language, like statements and each line of code, is typically more ambiguous than rust?
- **systems-engineer**: 100%
- **systems-engineer**: There's no intent anywhere
- **systems-engineer**: ⁨```c / void process_data(int* x); / ```⁩ / what does this do?
- **systems-engineer**: That's kind of the problem
- **self**: [link]
- **self**: I see we had the same idea of writing an example. Great minds think alike. Unfortunately I don't speak rust or c/c++ yet so i asked a llm […]

Moves: `probe_expert`, `states_hypothesis`, `admits_ignorance`, `concrete_referent`, `self_corrects`, `pushes_entrenched`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-009: 'fix wine/proton, not kotor': hypothesis that proton is mis-implementing windows; partner reveals he patches wine and that the breakage is modded assets + stricter linux allocation (systems-engineer, escalated, quality 5)

- **self**: Look I’m saying the game expects windows, yet you’re ‘fixing’ things to expect proton. You’re just going to be going through a million more. Why not spend the time improving proton/wine/mesa which you’ve proven with these issues is not targeting windows correctly? /  / Most games and apps implement for the platform they’re targeting and any implicit behavior is implicit behavior that isn’t second-guessed at deploy time. /  / So yeah you could keep targeting every 4 byte sequence or word/byte/float under the sun for any and all games or you could apply global fixes to proton/mesa/wherever the actual issue is /  / TLDR: implicit behavior is to be implemented according to the target.
- **self**: For context explain and list all the small convoluted ‘fixes’ you’ve done recently in last few weeks.
- **self**: the BioWare devs probably have zero idea they existed. Cus they didn’t when they worked on them due to being a windows targetted engine. Shouldn’t proton be adhering to the expected target anyway?
- **self**: Just my two cents.
- **self**: you’d potentially be helping thousands of games and more optimally
- **self**: rather than just this one
- **systems-engineer**: I'm only really fixing things based on how the game is actually programmed /  / All these small fixes are based on disassembly and going through the entire point from where the game crashes /  / vanilla assets aren't the issue we're fixing, this is all modded models and assets
- **systems-engineer**: I actually do work on Wine and Proton too 😛 / KOTOR needed some extra work 🙂
- **systems-engineer**: Star Citizen actually runs due to a couple patches of mine 🙂
- **self**: I’m not convinced these specifics are important. Seems proton/wine are doing a trash job of implementing windows if you’re running into this many issues is what im hypothesizing
- **self**: Nice
- **self**: I mean even windows does a trash job of implementing windows. So the theory is valid windows is covered in backcompat duct tape
- **systems-engineer**: Not only valid but actually the case, you should see the nightmare that goes on behind the scenes 😛
- **systems-engineer**: For KOTOR  in Wine: /  / It works 100% fine in a vanilla game context, it's when the modbuild is applied that these problems started appearing
- **self**: I just don’t think you’re understanding. I’m saying you’re fixing symptoms not the problem. The problem is kotor implemented for a windows target. But you’re trying to fix Kotor rather than proton/wine which clearly aren’t re-implementing windows expected behavior properly?
- **self**: I think you even confirmed this at one point as you were talking about red herrings
- **self**: Without actually describing specifics
- **self**: But also maybe I’m not following because you are a different man to track the regression of all of this with 🤣
- **self**: that SteamDeck thread is like 3 years old. Like that’s some dedication!
- **systems-engineer**: I've been trying longer than that actually, it's a bit of a meme that I will never get it working
- **systems-engineer**: 😛
- **self**: Probably because this is the most popular play tests. The core devs move on after vanilla works.
- **self**: Doesn’t mean everything I said is untrue
- **self**: Nah I’m telling you man you can! Just change your approach!
- **self**: trust
- **systems-engineer**: Not fix kotor, fix kotormax 🙂 /  / KOTOR is fine (the binaries we get are hyper optimized and missing checks for speed on computers of old), it's the assets that are slightly off, and since memory allocation being more strict on Linux is just a fact of life, these small little things just so happen to be a problem 😛
- **self**: KOTORMax needs deprecation so bad
- **self**: omg
- **self**: what a piece of junk
- **systems-engineer**: You could try and make a pykotor backed kotormax […]

Moves: `states_hypothesis`, `pushes_entrenched`, `escalates`, `demands_evidence`, `concedes_point`, `asks_clarifying`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-012: is a from-scratch rust format library a waste of time vs ai-generated kaitai bindings; 'i need to see an actual benchmark' (systems-engineer, redirected, quality 4)

- **self**: […] OH: /  / [link]
- **self**: We already have Rust done 😄
- **self**: I have not verified or tested most of this at all really.
- **self**: But I did do a lot of iterations to ensure some level of accuracy.
- **systems-engineer**: I didn't really plan on it, but in theory with the low level stuff I am writing it is possible. can also use it to help with the C projects or anything since it is guaranteed memory safe
- **self**: is kaitai useless to you?
- **self**: Just wondering, not butthurt. It seemed like a good idea exactly for this scenario.
- **systems-engineer**: I'll have to take a look, depends on how good the generated code is
- **systems-engineer**: It definitely looks cool 🙂 /  / The Rust code is a bit rough to read, but it isn't super easy to automatically write out idiomatic Rust 😅
- **systems-engineer**: In the case of the erf stuff here is how it I have it defined in my implementation so far: /  / ```rust / define_resource_types! { /     /// Unknown or unsupported type. /     Invalid => { ext: "", type_id: 65535 }, /     /// Generic GFF container. /     Gff => { ext: "gff", type_id: 2037 }, /     /// Area (`.are`) GFF generic. /     Are => { ext: "are", type_id: 2012 }, /     /// Dialogue (`.dlg`) GFF generic. /     Dlg => { ext: "dlg", type_id: 2029 }, /     /// Module instance (`.git`) GFF generic. /     Git => { ext: "git", type_id: 2023 }, /     /// Module info (`.ifo`) GFF generic. /     Ifo => { ext: "ifo", type_id: 2014 }, /     /// Journal (`.jrl`) GFF generic. /     Jrl => { ext: " […]
- **systems-engineer**: Which is a bit more easy to parse through compared to: /  / [link]
- **systems-engineer**: that said I am not supporting *all* of those formats
- **self**: ```rs /  / #[derive(Default, Debug, Clone)] / pub struct Gff { /     pub _root: SharedType<Gff>, /     pub _parent: SharedType<Gff>, /     pub _self: SharedType<Self>, /     header: RefCell<OptRc<Gff_GffHeader>>, /     _io: RefCell<BytesReader>, /     f_field_array: Cell<bool>, /     field_array: RefCell<OptRc<Gff_FieldArray>>, /     f_field_data: Cell<bool>, /     field_data: RefCell<OptRc<Gff_FieldData>>, /     f_field_indices_array: Cell<bool>, /     field_indices_array: RefCell<OptRc<Gff_FieldIndicesArray>>, /     f_label_array: Cell<bool>, /     label_array: RefCell<OptRc<Gff_LabelArray>>, /     f_list_indices_array: Cell<bool>, /     list_indices_array: RefCell<OptRc<Gff_ListIndicesArr […]
- **self**: ```rs /  /     /** /      * Array of field index arrays (used when structs have multiple fields) /      */ /     pub fn field_indices_array( /         &self /     ) -> KResult<Ref<'_, OptRc<Gff_FieldIndicesArray>>> { /         let _io = self._io.borrow(); /         let _rrc = self._root.get_value().borrow().upgrade(); /         let _prc = self._parent.get_value().borrow().upgrade(); /         let _r = _rrc.as_ref().unwrap(); /         if self.f_field_indices_array.get() { /             return Ok(self.field_indices_array.borrow()); /         } /         if ((*self.header().field_indices_count() as u32) > (0 as u32)) { /             let _pos = _io.pos(); /             _io.seek(*self.header().f […]
- **self**: [link]
- **self**: This usable for you?
- **self**: to clarify if i see an answer like 'it's functional but not optimal' or 'this is ugly code' or 'this doesnt work and i want to implement it myself' there's probably good reason to remove this pr. Haha
- **self**: I thought it'd allow anyone to bootstrap in whatever language they want
- **self**: Looking at some of the generations, though, at least the python ones are somewhat ugly
- **self**: Then again, i'm looking at MDL the largest format
- **systems-engineer**: I think it is a good reference but I would probably rewrite it myself imo (which I think is the point )
- **self**: is there a build/run/deploy tool like `uv` but for rust itself lol
- **systems-engineer**: Yeah cargo 🙂
- **self**: compiled languages always seem to have some hacky workaround for that. Like `dotnet run`
- **self**: Oh whatt i thought cargo was just how to actually use it the normal way.
- **systems-engineer**: cargo is the one for that, handles dependencies, documentation building linting formatting
- **systems-engineer**: you can define "clippy" definitions to enforce certain concepts
- **systems-engineer**: Like for example I can compile my documentation based on comments:
- **systems-engineer**: I'm also trying to avoid drifting between different similar types, for the most part I am really at a "vertical slice" kind of state
- **self**: I need to see an actual benchmark […]

Moves: `states_stance`, `demands_evidence`, `concrete_referent`, `offers_out`, `probe_expert`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-014: snake.io 'orbs' analogy: individual abstention is negligible, get big first then push ideology; 'i don't debate often — are these points clumsy / on point / dumb?'; 'so you're a coward — me too' (systems-engineer, escalated, quality 5)

- **self**: […] Stoicism talks about cementing for example. I think stoicism is the correct ideology for my point. Been a while
- **self**: Anyway at the stage we are at, there's nothing we can do to become bigger. Except grabbing those orbs.
- **self**: Also I don't debate often. Are these points I'm bringing up: / - Ridiculously clumsy / - On point / - Borderline dumb
- **self**: Somewhat hard for me to tell these days.
- **systems-engineer**: debate doesn't have to be perfect either way 🙂
- **systems-engineer**: some focus on pedantics but I get the concepts you're talking about
- **self**: Well I could be running into a gas station trying to rob them thinking that butter is going to keep me invisible.
- **systems-engineer**: Well for me the system has people focusing on the orbs 😛
- **self**: Does that have the same response from you?
- **self**: So you're a coward
- **self**: is what you're saying
- **self**: ME TOO
- **self**: Mainly I just don't know how not to be a coward
- **systems-engineer**: not really a coward, since I am essentially doing things the hard way
- **self**: Coudl argue that's a lie
- **self**: You're upset with the system.
- **self**: You don't want to chase the orbs. You want free will.
- **self**: Therefore you've chosen your own lttle piece of meaningless subcisting.
- **self**: Which may or may not make you completely happy. To not be chasing all that down
- **self**: You are 27 after all can imagine that and the current tech job market would have you burnt out
- **systems-engineer**: In a way, although in order to get an "enclave" I need to exist in the system first /  / meaningless isn't exactly how I would put it though
- **systems-engineer**: at the end of the day the responsibility of it's existance/survival is on me
- **systems-engineer**: that has meaning
- **self**: This is where I think english language isn't specific enough. Hard can mean a lot of different things. /  / For example if I was making a game, i could make it possible to beat it by solving a math problem or something. /  / I also could put 10 maxed-out stats of enemies in front of you and you could brainlessly click through them all
- **self**: Which is easier
- **self**: Meaningless i'll give you isn't the right word.
- **self**: I was reaching for similar wordsd to the one i wanted out of laziness
- **self**: I gotta stop doing that
- **systems-engineer**: All good 🙂
- **self**: So anyway I think this is where I am and i have no idea what I realistically want.

Moves: `analogy`, `states_stance`, `pushes_entrenched`, `meta_style`, `self_corrects`, `invites_pushback`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-015: how adhd brains learn: q&a with ai vs reading; 'explain why true knowledge is lost with ai'; learned by debating dad with devil's advocate; why docs and youtube fail him (systems-engineer, redirected, quality 5)

- **systems-engineer**: […] The way I have helped others with ADHD learn things is to apply learning is an active way
- **systems-engineer**: reading is not feasible, but what about a quiz, approachable questions
- **self**: For example if i'm not medicated it doesn't matter if i spent hte last 8 months doing LeetCode every morning or going for runs. I go brrrr and the connections don't form, insights don't pop or if they do i can't follow them anywhere
- **self**: Yes.
- **self**: Why can't documentation be written like this?
- **self**: why can't all information be learned like this?
- **self**: this is why i like learning from ai
- **self**: so explain why '
- **self**: 'true knowledge is lost' with ai?
- **self**: Cus i've never understood that
- **systems-engineer**: It can be 🙂 you just aren't looking in the right places
- **systems-engineer**: So with how you are using AI, you are essentially using it as a terminal into the knowledge
- **self**: Whole time we've been talking I've had this going:
- **self**: Loaded up the same prompt 80 times and then jumped here with a burrito
- **self**: Well... yeah. What's wrong with that? If I want a refresher in something like again trigonometry or how a kubernetes cluster works, i'll ask ai.
- **self**: Before that i'd go to stackoverflow, wikipedia, or whatever
- **self**: and then usually get utterly confused and never find what i'm looking for
- **self**: Now I always get direct exact information i'm asking for. So the rate I learn is only limited by teh quality of my questions
- **self**: This is how I learned growing up. My dad and I would stay up late from 9pm to 11pm debating and arguing  about things and one of us would choose devil's advocate. /  / it's probably the only way i learn. /  / Like, literally **EVERYTHING**. EVERYTHING is irrelevant, arbitrary, and unimportant. Unless it has a purpose.
- **self**: For example what was the last large stack you learned, from a walkthrough or a youtube video or something
- **self**: That you actually would recommend
- **systems-engineer**: I normally learn by doing /  / tutorials can be helpful sometimes but for the most part I try and just rawdog things myself
- **self**: Probably shouldn't ask that just to prove a point but if it's good i'll disgress i haven't been giving it a fair shot. But usually it's just like: / - what is this monstrosity / - why is it so large / - what's the point. / - what problem is this solving / - is this *really* the best way to solve it /  / Those questions aren't answered on page one and i zone out
- **self**: There's too much irrelevant info out there isn't ther?
- **self**: > I normally learn by doing / EXACTLY THIS
- **systems-engineer**: not irrelevant, just too large
- **self**: if i see one more bit of info locked behind a youtube vid...
- **self**: i literally will spend that day writing a transcriber myself
- **systems-engineer**: the goal is chunking, reducing your cognitive load
- **self**: Example? […]

Moves: `meta_style`, `states_stance`, `probe_expert`, `demands_evidence`, `concrete_referent`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-016: partner says 'you assume a lot / go in blind'; wizard demands 'describe the problem i'm solving first', then repairs when he realises he brushed off partner's project (naev) (systems-engineer, conceded, quality 5)

- **self**: It's called osmething like the 'Golden Standard' Like we generally like people that are charismatic or attractive, even if they e.g. are on death row for doing some evil sh*t.
- **self**: Huh I can't remember the name of that law
- **systems-engineer**: That seems pretty handy, since you are using existing tools (and I guess my point depends on this) /  / Some people will reimplement certain specific cmdlets for speed, where you call on git, someone may wrap it for some reason so you can call it as a cmdlet. it's the struggle of generalist tools and single task tools /  / both are valid in a way but it becomes painful the deeper you go in either direction (dealing with a bunch of scripts for one off jobs or dealing with the dependency hell of powershell)
- **self**: ### **Halo Effect** / When someone’s charisma, attractiveness, confidence, or communication style makes us assume they’re also smart, trustworthy, competent, or morally good — even when there’s no evidence for that. /  / It’s exactly what your friend was describing:   / liking someone *because* they present well, even if they’re objectively wrong or even harmful.
- **systems-engineer**: blind trust is one thing, but for talks like these you need to go in with no assumptions
- **systems-engineer**: and then at the end, find out if they are full of shit
- **self**: The only way I would do that is if someone I trusted vouched for it.
- **self**: I don't want to be full of shit though
- **self**: Do you?
- **self**: is there some benefit i'm missing out on?
- **self**: How old do you think i am btw? Not sure if i mentioned. Or if that'll change anything.
- **systems-engineer**: Try this instead just to see how it goes: /  / Go in blind with no assumptions and then try to apply it to something, see if it works as it is supposed to /  / if it does, talk about it.. if not, now you know and you can talk about shortfalls of the approach
- **self**: This video specifically?
- **self**: I already know all this
- **systems-engineer**: could be this video or anything else
- **self**: Describe why I need to do this and what problem I'm solving
- **self**: if there's benefit that'd be motivation for me to do it
- **self**: I don't really see any. But is that the point?
- **self**: To get me to blindly jump in and hope it's not a waste of my time?
- **self**: that seems counter-intuitive doesn't it?
- **self**: Sorry if i'm being annoying or rude rn with this.
- **systems-engineer**: I just notice that you assume a lot about things sometimes /  / By assuming you can generalise legitimate things away or miss important parts or even cool things you'd never have noticed
- **systems-engineer**: That is most of life no?
- **systems-engineer**: it's all an experiment at the end of the day
- **self**: From my perspective, 99% of them are useless, something I already know, or something I've forgotten about and is a healthy reminder of that. /  / I don't know about the last point in that sentence though. I wonder if that's the same dopamine hit that people aging hit where they just want nostalgic shit all the time and can't learn anything new. That scares me
- **self**: So yeah everything's an experiment. I might login to my email and see an email from a Nigerian prince and it's somehow *not* a scam.
- **self**: Should I be checking every time though?
- **systems-engineer**: I myself, yeah, to a degree, obviously spam email is a bit of an oversimplification of the concept
- **self**: > I just notice that you assume a lot about things sometimes / > By assuming you can generalise legitimate things away or miss important parts or even cool things you'd never have noticed / Yes I do have this problem. Her's what's actually happening though: / - I have a train of thought. I finish teh train of though because it's leading to something new that i haven't done or thought of before usually. / - **important part**: I go *back* and check if i missed something.
- **self**: Hence all the pins. […]

Moves: `demands_evidence`, `pushes_entrenched`, `apologizes`, `self_corrects`, `meta_style`, `asks_clarifying`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-017: does low-level driver/firmware work help anyone? 'you doing it makes it expected'; 'that is my theory with zero metrics, references and research — which makes it easy to counter'; 'i genuinely like being proven wrong' (systems-engineer, escalated, quality 5)

- **systems-engineer**: […] Doing what you like to do can have the side effect of helping others
- **self**: I'd like to see someone flash a switch 2
- **systems-engineer**: Another thing that should be doable but the corpo firmware says no
- **self**: Well you know what could help others? / Targetting a majority of people rather than your proprietary stuff.
- **systems-engineer**: (and the fuses on board)
- **self**: Because, doesn't that result in this meme:
- **self**: And that increases the learning curve, for everyone.
- **systems-engineer**: Well in the case of the alexa thing, opening up the firmware lets you flash on whatever you'd like
- **self**: So in a way is your stuff beneficial
- **self**: is what i'm asking
- **self**: and i'm not saying that to be rude or prove a point. But just to skip over to the point that i may not understand yet
- **systems-engineer**: Yes I think so /  / device driver stuff is a great example: Why should you be locked down with a device that you own and paid money for
- **self**: When I say i may not understand i do say that genuinely. It probably does sound rude. I genuinely like being proven wrong it just doesn't happen often.
- **systems-engineer**: No I get what you mean
- **self**: Well you could actually sue the bastard
- **self**: rather than try to flash it tediously over years.
- **self**: or you could setup your own business that provides a product that outsells the worse implementation for the rest of the world to enjoy
- **self**: so they don't have to see the pain and torture that you've gone through with all this flashing
- **self**: By doing all this low level stuff you're implying everyone needs to be doing that and that just becomes the status quo
- **self**: Which is *not* a good thing.
- **systems-engineer**: I'm not saying everone should do low level stuff
- **self**: Then companies like Apple corner the market.
- **systems-engineer**: I want to do the low level work so people don't have to
- **self**: You're not.
- **self**: That's what i'm saying. You doing it is making it *expected*.
- **self**: it becomes background noise. People think 'oh yeah someone will do that. I can expect this'.
- **self**: Then one day you're gone. And that amount of work doesn't get contributed 10 years from now for the next Y-phone replacement for the iPhone
- **self**: The same thing you can see happening with jailbreaking the latest iphones
- **self**: it's becoming increasingly harder and harder to do it. The effort level increases. It's becoming *expected* behavior
- **self**: That is my theory, anyway. With zero metrics, referencse, and research. […]

Moves: `probe_expert`, `states_hypothesis`, `pushes_entrenched`, `invites_pushback`, `admits_ignorance`, `concedes_point`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-020: cross-compiling and why pyinstaller trips antivirus: his 'static strings at similar offsets' theory vs partner's 'embedded interpreter masquerading as native'; concedes the earlier native-vs-electron debate after learning rust-wasm; 'wasm is slow' referent (systems-engineer, conceded, quality 4)

- **self**: I don't understand why pyinstaller cannot do this? is it just a lot of work to target another platform/architecture when you're not on that architecture/platform? PyInsatller only builds a binary for the os/arch you're on i mean.
- **self**: Docker images also have the same issue.
- **self**: Why is this only an issue with docker images and pyinstaller (if indeed there's a correlation)?
- **systems-engineer**: Well the issue pyinstaller has is that it is running a tool on top of another tool (python interpreter)
- **self**: In short I don't understand how to package for another os/arch/platform when not running that os/arch/platform 😄
- **self**: is that explained for rust anywhere?
- **self**: Apologies if this is a dumb question
- **self**: What the fuck ***XP***?
- **self**: I'm swapping to rust there's no question
- **systems-engineer**: Yeah, embedded apps are ideal for Rust since you need lightweight programs with memory safety
- **systems-engineer**: I can't remember who maintains the xp target, the windows 7 one needs a bit of building to get working but it does work last I tried it
- **self**: Remember our debate about native code vs stuff in electron?
- **self**: I am on your seide now after learning about rust-wasm stuff
- **systems-engineer**: Ah cool 😅
- **systems-engineer**: wasm is really cool as a concept
- **self**: interesting..
- **systems-engineer**: yeah wasm is extremely quick
- **self**: Huh? the response said the opposite
- **self**: WASM is slow.
- **systems-engineer**: quick compared to other web technologies /  / compared to native, definitely
- **systems-engineer**: compared to javascript *most definitely*
- **systems-engineer**: There will always be overhead with something like wasm, the ideal solution is native but in the cases where you want a browser native app, wasm is the best there is
- **systems-engineer**: I can't remember if there is a specific section but packaging is normally pretty much the same for whatever it is you're building /  / the difference with something like python is the complexity of stripping down the interpreter and bundling it in a way that it looks like a native app
- **systems-engineer**: it's essentially pretending to be something it's not if that makes sense
- **self**: Sort of.....
- **systems-engineer**: Like instead of a native binary you are running python + your python scripts masquerading as a native binary
- **systems-engineer**: so the reason antiviruses see it as problematic or bad is that it looks like it is a compromised binary 😄
- **self**: well my theory has always been that it's the static way they're doing that stuff and the static strings that exist at similar offsets between builds is causing the heuristical detections to operate.
- **self**: like within the pe header or otherwise
- **self**: i don't understand why dotnet/apparently rust don't have the same problem lol […]

Moves: `states_hypothesis`, `probe_expert`, `concrete_referent`, `concedes_point`, `apologizes`, `asks_clarifying`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-023: linux package management vs windows: 'why is numpy an apt package?', 'is it my job as maintainer to know every distro's packages?', 'why isn't this a problem on windows?' — partner: source-built distros vs stable win32 target; 'so obvious when you put it that way' (systems-engineer, conceded, quality 5)

- **self**: […] Hey one more question if you don't mind? Why is there so much crap installable through apt/dpkg/yum/rpm/<other distro package installer here>
- **self**: Like I found a package for numpy in debian/ubuntu and was genuinely confused. Why would i ever want to install the system package instead of through pip normally???
- **self**: As a python dev that severely confused me when i was trying to get the toolset working on linux
- **self**: Why is there so mnay distro specific packages for things that generally do not need specific targetting??
- **self**: And how the fuck do I understand and keep track of how distros are supposed to be doing that crap when I'm developing my python app for windows and all i know is i need numpy 2.0 or greater lol
- **systems-engineer**: It's a different ideology with how software is distributed /  / Basically: / The distro's version of a package is supposed to be the preferred route to installing things /  / remember what I said about dependency management? /  / For deterministic installs you need to make sure everything is pinned/built for the environment
- **self**: are they just optimzied for the distro and generally optional
- **self**: or is it for system level shit only and if i'm making an app that a user doesn't need for their distro for the distro to function, i don't need to worry about `apt` or whatever their packages are?
- **self**: i think i answered my own question haha also means everything i am doing in deps_toolset.ps1 on pykotor is wrong
- **systems-engineer**: Not optional, the main route one should take /  / Windows is very wishy washy, you just transplant the required libraries with the application you install
- **systems-engineer**: basically: You can use pip if you'd like in a venv, but for a system level tool ideally you should use their builds of python dependencies (lets say python 3.15 becomes standard, all of your pip dependencies may break if you lift and shift the distro packages will only be updated if they are guaranteed to work
- **self**: [link]
- **self**: Lmfao
- **self**: This is one of my biggest pet peeves with linux
- **self**: HOW DO I KNOW WHAT I NEED TO INSTALL
- **self**: most of this was 'i get this error what package do i need in ubuntu???'
- **self**: then i ask 'exact 1:1 package in alpine'
- **self**: repeat for other distros
- **self**: literally how does anyone do this? i spent a month on this before ultimately compromising
- **systems-engineer**: yeah, package management is one of those fragmentation problems /  / The easiest thing to do for users is tell them which libraries you need to have installed (not the packages) /  / Then they can find out which packages /  / There's search tools for packages built into the managers
- **self**: But how do I know? all i know is i have a pyqt5 application for example that uses cpython. I had to do an absolute crapton of guesswork to figure out 'okay maybe this package??? it says 'qt' in the name. Ok this one says 'pulseaudio' i guess that 's why the media player doesn't work'
- **self**: Literally how
- **self**: and there's a billion distros all with their own naming and packaging for each of these
- **self**: For example this is **JUST** arch linux: /  / ```ps1 /         "arch": [ /             "mesa", /             "libxcb", /             "qt5-base", /             "qt5-wayland", /             "xcb-util-wm", /             "xcb-util-keysyms", /             "xcb-util-image", /             "xcb-util-renderutil", /             "python-opengl", /             "libxcomposite", /             "gtk3", /             "atk", /             "mpdecimal", /             "python-pyqt5", /             "qt5-multimedia", /             "qt5-svg", /             "pulseaudio", /             "pulseaudio-alsa", /             "gstreamer", /             "libglvnd", /             "ttf-dejavu", /             "fontconfig", / […]
- **self**: debian equivalents? /  / ```ps1 /         "debian": [ /             "libicu-dev", /             "libunwind-dev", /             "libwebp-dev", /             "liblzma-dev", /             "libjpeg-dev", /             "libtiff-dev", /             "libquadmath0", /             "libgfortran5", /             "libopenblas-dev", /             "libxau-dev", /             "libxcb1-dev", /             "python3-opengl", /             "python3-pyqt5", /             "libpulse-mainloop-glib0", /             "libgstreamer-plugins-base1.0-dev", /             "gstreamer1.0-plugins-base", /             "gstreamer1.0-plugins-good", /             "gstreamer1.0-plugins-bad", /             "gstreamer1.0-plugins-ugl […]
- **self**: Slightly different names, for the same crap
- **self**: lol
- **systems-engineer**: So in this case, you've got some transient dependencies that aren't really needed (other packages may pull those in) some are also pre-installed /  / So for example if I install qt5/6, it'll have a massive list of dependencies that the packagers handle for you
- **self**: Why do I not have to do this for windows???
- **self**: Why does my qt5 app just *work* without having to worry about sys level packages on windows like this? […]

Moves: `probe_expert`, `states_stance`, `concrete_referent`, `escalates`, `admits_ignorance`, `concedes_point`, `meta_style`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-026: why a public ai-article argument went badly: bad-faith participants, 'i was trying to frame it as a discussion, in public it looked like an argument i wouldn't drop', 'maybe i just wanted to be heard' (systems-engineer, conceded, quality 4)

- **self**: speaking of you any idea why this guy was such a dick to me? [link] /  / just generally not sure why he was publicly bashing me like that. Accusing me of not putting any effort forth or w/e. The article was obviously ai enhanced but i don't know really why other people are just saying i'm bad at 'conflict resolution'. I tried to frame it within the scope of a discussion on AI but he'd follow up with dumb claims like 'so you didn't write an article, you just had ai generate it'. All I wanted was to help new users get started developing and doing stuff with openkotor even if they didn't have a programming background. I'm at a loss as to why it couldn't simply be that.
- **self**: Just makes me wonder if I can even talk or mention anything AI related anymore
- **systems-engineer**: Well I did have the impression that they are quite particular about things /  / The only interactions I had were them nitpicking things that didn't really need to be nitpicked
- **systems-engineer**: You can talk about it, there is just no pleasing anyone
- **systems-engineer**: that conversation looks like it was a bad faith one anyways, they were never going to read the article even if you wrote it fully or whatever their problem was with it
- **self**: I didn't care if he read it.
- **systems-engineer**: either just don't respond or say thanks for the input and move on /  / Can't agree with everyone or appeal to all
- **self**: Yeah I guess
- **self**: I didn't like that he publicly slandered my article though
- **systems-engineer**: Well it does comes back to the "people can eat shit" point I made 😄
- **systems-engineer**: publicly, don't say that but anyone reading that comment knows
- **systems-engineer**: I tend to just ignore or go "Cool what is the weather like" when it comes to bad faith discussions
- **systems-engineer**: Just have to ignore and move on sometimes, even if that comment was unnecessary on their part
- **self**: So the issue was I was trying to rationalize and explain my position and stance on its usage, and frame it as a discussion, whilst in the public view it'd just be an argument I wouldn't drop
- **self**: I guess it was obvious there was no intent or desire to discuss it openly
- **systems-engineer**: I think that is a good conversation to have but you need to have the right participants if that makes sense /  / The other guy was going into it with bad intentions from the start, no amount of rational or logical positioning / discussion would go anywhere
- **systems-engineer**: It's like explaining to someone your views on things and they just follow up with "you're a stinky head"
- **self**: Definitely sucks not everyone is just inherently willing to do that lol
- **self**: I don't deal with children often I guess lo
- **self**: l
- **systems-engineer**: Yeah, it's like that /  / imo, just ignore people like that if possible
- **systems-engineer**: the older I get the more I learn that "adult" isn't a real thing
- **self**: > The other guy was going into it with bad intentions from the start, no amount of rational or logical positioning / discussion would go anywhere / Yeah this seems obvious idk why i didn't understand that tho
- **self**: Thanks though
- **self**: Maybe i just wanted to be heard
- **systems-engineer**: no worries,  /  / Yeah that is also valid too, just unfortunate that the first comment on that article was the dude being a shithead
- **self**: That's a wild eye opener to many it's something i often forget though
- **systems-engineer**: Yeah, it is sad but also hilarious
- **systems-engineer**: As long as you make sure you are what "adults" are supposed to be you're in a better position than 90% of people
- **self**: Yeah I try. Just have zero idea how to deal with people that aren't I guess. […]

Moves: `probe_expert`, `meta_style`, `self_corrects`, `concedes_point`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-028: how kotor ran in 64mb (xbox/ps2); what vram actually is and why inference needs it ('a question i've asked llms a billion times'); 'you're taking the pov of the gpu but we code from the cpu'; 'is cpu/gpu/ram/vram the best design we could come up with?'; doom ran on the cpu (systems-engineer, redirected, quality 5)

- **systems-engineer**: […] Yeah the tooling also seems to bake in structs directly too, I noticed some of those artifacts when implementing MDL support for rakata
- **self**: I've always wondered why Worrorrnorz's house was a different module.
- **self**: You know, that super small hut in the kashyyyk village.
- **systems-engineer**: Yeah, it most likely made more sense to stick a copy on disk somewhere to avoid having to move the seek head on the DVD
- **self**: It's small enough you'd think it'd just be part of the main village module. I wonder if they had to split it off due to the constraints at the time. It'd be interesting to see why they did that if we ever could get a good estimate of how much memory was being used in that module.
- **self**: Can you elaborate on this? i don't know what you mean by 'bake' and what artifacts are caused from that
- **systems-engineer**: It's a mix of memory at runtime (very limited) and the way data is packed on disk /  / If you don't have to physically move the laser you can actually access stuff pretty quickly on load
- **systems-engineer**: By bake, I mean they were writing a serialized struct in certain parts of the mdl file
- **self**: for clarity can i expect the head of a HDD to operate the same as a laser for these CDs?
- **systems-engineer**: Somewhat, just way slower
- **self**: Gotcha.
- **self**: My college only taught the HDD internals, CDs were already defunct even back then lol
- **systems-engineer**: HDDs also have a different way of storing data compared to CDs which is why you can get away with packaging data in a certain way
- **self**: So here's a question i've asked LLMs a billion times over the past few years. WHat is VRAM and why is it different from RAM, exactly?
- **self**: Like what makes llms so much performant on vram than ram? And why can't it be modular so we can go out and simply buy some? Seems to be this embedded thingamajig on the card that requires buying a new card, unfortunately. Is there a reason we aren't seeing modular systems like this? my theory is because of nvidia being so proprietary and ahead of its time really
- **systems-engineer**: In essence it boils down to two things: proximity to the GPU physically, and a lack of CPU intervention
- **self**: intervention?
- **systems-engineer**: With VRAM, the cpu can load it up like a buffer and then the GPU doesn't need to ask the CPU for anything
- **systems-engineer**: If you need to access say a texture or something in RAM, you need to: ask the cpu where it is, move it (depending on what you need it for) and then the GPU can work
- **systems-engineer**: If you dump a shitload of textures into VRAM the GPU can access everything in parallel, as opposed to waiting on a single CPU thread to do something
- **self**: From this explanation it seems you're taking POV of the gpu.
- **self**: but when we code we're operating from the POV of the cpu
- **self**: so it's weird to read it like that
- **self**: i've always treated the GPU like some remote entity
- **self**: I'd like to understand this better.
- **self**: is it alright if I ping you some of these questions in something like openkotor's #dev-space channel..? it seems we do the community a disservice by talking about this in dms
- **systems-engineer**: Well when you send command via opengl for example, that is actually talking to the GPU directly (or as directly as you can, opengl still translates stuff obviously)  /  / Or when you send a shader to the GPU, it's compiled by the CPU but also is written for the GPU if that makes sense
- **systems-engineer**: Sure 😛 / Can try my best
- **self**: Well what I'd like to understand is why inference is so much faster in GPU and why they always say VRAM is the bottleneck
- **self**: Why can't it use CPU? […]

Moves: `probe_expert`, `states_hypothesis`, `concrete_referent`, `asks_clarifying`, `pushes_entrenched`, `meta_style`, `admits_ignorance`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-031: immutable distros (silverblue) vs traditional: 'provide a worst case scenario', 'example? just one would be fantastic', 'why didn't you just say that — i'm sold'; 'people say opinions don't change, you've convinced me pretty easily, it's all utilitarian' (systems-engineer, conceded, quality 5)

- **systems-engineer**: […] dnf is still the default package manager on Fedora
- **systems-engineer**: basically: I think you should avoid immutables until you feel like you want to try them after getting used to a traditional linux system
- **self**: ahhahh
- **self**: omg i have 32gb of ram and nothing open and for some reason all my apps are out of memory. i hate 11 so much haha
- **self**: i can't even type in discord without it reloading
- **systems-engineer**: That is pretty wild, I forgot how hungry windows is
- **self**: it did not used to be this bad
- **systems-engineer**: Yeah it used to be somewhat okay, I miss those days
- **systems-engineer**: Windows XP was the peak for me 🙂
- **self**: i think what it actually turns out to be is all the various subprocess python.exe/node.exe s that run in the background.
- **self**: 7
- **self**: i literally just watched my message '7' take 20 seconds to send.
- **systems-engineer**: Yeah, the amount of random shit that runs for basically most apps is pretty gross
- **systems-engineer**: So: my suggestion is that you try out normal Fedora as your distro, find out which desktop environment you'd like to run /  / and then from there you can start cooking with gas 🙂
- **systems-engineer**: You can use appimages, rpm packages, or flatpaks /  / The actual backend system stuff really doesn't need to get touched much, most of the stuff you will be configuring will be in your home directory anyways
- **systems-engineer**: Once those first packages and repositories are installed (RPMFusion) you are pretty much good to go with all of your tinkering
- **self**: i'm going to reboot
- **self**: I can't even move y mouse
- **self**: i can't even move my mouse except for 5 secondxs at a time per minute
- **self**: Haha it did not used to be this bad
- **systems-engineer**: that is brutal 😅
- **self**: Ok I’ll cut to the chase and respect your time. How do I turn off core parking on Linux? What should I set my swap to?
- **self**: and what issues will I realistically have in plain language that’ll make me regret using immutable? Is it just more tedious or is there literally things I can’t do?
- **self**: like would suck to setup for a week and then find out I can’t play rocket league or something
- **self**: also… flash player?
- **self**: I know I know but I can’t use ruffle
- **self**: sharex?
- **systems-engineer**: basically: most guides will not be able to be used without you consciously applying the immutable concepts to them /  / basically running before you walk
- **self**: Example?
- **self**: Just one would be fantastic. […]

Moves: `probe_expert`, `demands_evidence`, `pushes_entrenched`, `concedes_point`, `meta_style`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-032: what wine actually is (translation vs emulation, no vm); 'are reone/kotor.js emulators?'; why wine can't mask a crash like windows; reactos; virtualised gpu for ci (systems-engineer, redirected, quality 4)

- **self**: Broadly speaking, how good/bad is wine?
- **self**: is it like i'm going to see a 0.6x multiplier on native performance?
- **self**: or is it just unstable but the same amount of fps in general?
- **systems-engineer**: No it is quite fast, it doesn't emulate (Wine is not an emulator is what WINE stands for 😛 )
- **self**: and uh... memory usage? isn't it spinning up a whole vm 😭
- **systems-engineer**: nope 🙂
- **systems-engineer**: It translates, they are essentially reimplementing the windows api using open source components
- **self**: Damn this was my last request
- **self**: hope i sent off a good last one haha
- **systems-engineer**: ABI is basically the lower level of an API, where an API is the contract between source code, the ABI is the contact between compiled machine code 😄
- **self**: So.....
- **systems-engineer**: Not too bad, that should give you a good dump of info 🙂
- **self**: reone/kotor.js/xoreos are EMULATORS for the KOTOR game?
- **self**: or am i misusing that word?
- **systems-engineer**: misusing, they are reimplementations
- **self**: so what the heck is an emulator again?
- **self**: ok so if i was making wine then it'd be an emulator around kotor.
- **self**: ok i see
- **systems-engineer**: depending on the type you either emulate the machine down to the physical emulator, or emulate how the machine works by emulating how the software works
- **systems-engineer**: so you could have a game run on software that pretends to be the bits that the game expects (the sound is an emulated synth chip or something)
- **systems-engineer**: So with something like WINE..
- **systems-engineer**: Okay: you have KOTOR right, it needs to talk to Windows to build the window and get inputs and handle time
- **systems-engineer**: opengl to send stuff to the GPU, and then talks to windows for sound
- **self**: is it possible to virtualize a GPU for testing opengl stuff in ci/cd?
- **self**: sorry i'll ask that later.
- **systems-engineer**: Yes it is 🙂 Mesa has support for that stuff
- **self**: WOAH
- **self**: no way
- **systems-engineer**: WIne takes a windows API call and then calls on native linux software to do the work, then returns the expected kind of value back to the app
- **systems-engineer**: so you are running a windows game like kotor using xorg or wayland, freetype for text, openal for sound, sdl for input […]

Moves: `probe_expert`, `asks_clarifying`, `concrete_referent`, `self_corrects`, `admits_ignorance`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-034: 'what exactly is a native app vs electron — take chromium to the bare bones'; 'you broke atoms into electrons, i need quarks'; partner answers with a claude-generated breakdown (systems-engineer, redirected, quality 4)

- **self**: what i need is an explanation of what exactly a native app is, vs electron. What specifically is bloat in chromium. Like i want to see a figma that takes it to the bare bones
- **self**: Wtf is in it that's so important.
- **self**: Just give me react and i'm good
- **self**: Literally
- **self**: haha
- **self**: i'm not even posturing man i've tried literally everything to make a native ui look good even sell my soul
- **self**: it just don't
- **self**: [link]
- **systems-engineer**: Yeah, that does tend to be on the operating systems themselves /  / They aren't designed to be super extensible /  / Linux does let you pick and play your frameworks at least but theming is the main drawback in most cases
- **self**: i mean to be fair i haven't tried EVERY high level abstraction library that does ui
- **self**: like i have NOT tried wxWidgets yet
- **self**: I've not tried just using GL to render the window. I imagine that's overkill.
- **self**: like kivy i mean
- **systems-engineer**: Ran this through claude since I was going to type it out but it could do it faster
- **systems-engineer**: this is the bare minimum just to display a window
- **systems-engineer**: vs qt:
- **systems-engineer**: it has a good analogy actually
- **systems-engineer**: The difference is pretty stark. Think of it like this: Electron is shipping an entire web browser just to show your window — it's like delivering a pizza by sending the whole restaurant on a truck. Qt is more like handing the pizza directly to the customer.
- **self**: QUickly explain libuv and skia? only parts of those i'm not getting
- **systems-engineer**: skia is a virtual gpu implementation that abstracts the lower level graphics apis from the browser code
- **systems-engineer**: libuv is for io (typically)
- **self**: I'm still not understanding which part of this is the shitty bloat. Which parts are required for react 😂 i mean i was needing chromium broken down i f i was being completely honest out here i knoew how electron basically worked
- **self**: it's like you broke atoms into electrons. I need quarks bro
- **systems-engineer**: all of it
- **systems-engineer**: no like that whole stack is requried
- **systems-engineer**: that is the bare minimum
- **self**: did they ever figure out what a quark is made of?
- **self**: oops my bad what i'm trying to say is this part makes sense to me.
- **self**: what doesn't make sense is this part:
- **self**: I need that broken into 50 pieces

Moves: `demands_evidence`, `escalates`, `concrete_referent`, `asks_clarifying`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-036: why can't open source build a gpu / reverse-engineer one: 'we cracked denuvo, explain step by step why this is harder'; fabs; 'i fell for the posturing' (systems-engineer, redirected, quality 4)

- **self**: Sure but couldn't we take ghidra to that?
- **self**: And if it's not software, then couldn't we just dismantle the physical parts?
- **systems-engineer**: it's extremely obfuscated and it is all encrypted
- **self**: And more importantly why aren't we using this to figure out how to make our own GPUs outside of nvidia. I really need to watch that video you sent me 'lets make a gpu'. that must be a wild ride
- **self**: Man I went to college three times for a total of 3 years. Total scam i learnt nothing.. i mean my mental health sucked and that's why i don't have the degree but it also was just like 'why am i here if i'm not learning anything...'. the classes were boring, i couldn't remember if i did an assignment or not because it felt exactly the same as another useless assignment.
- **self**: ahh anyway. who cares? we've cracked DENUVO. Why is this any more difficult?
- **self**: Explain that specifically in detail, step by step
- **self**: Haha
- **systems-engineer**: It's just a really complex machine really, everyone with the knowledge to make them aren't doing it for free, they are all under the payroll of those larger companies /  / the architectures are also very expensive to create with all of the fancy work we do for chips as well
- **self**: I got a trash response from an llm on that
- **systems-engineer**: it takes tens of billions of dollars to create a GPU architecture from scratch
- **self**: WHATTTT
- **systems-engineer**: plus you need the knowledge which is only held by a few people on the planet
- **self**: well that sounds like a good script for a movie
- **self**: Only a few people have the information?
- **self**: sounds like the O5 council
- **systems-engineer**: Yeah, they get passed around from company to company
- **self**: 😂
- **self**: wouldn't you expect one dude to pull a snowden though?
- **self**: just one guy gets drunk enough
- **self**: after enough years
- **systems-engineer**: The amount of IP protections in place as well as the money behind it makes it very hard to do so
- **self**: and who's assembling the cards? wouldn't they be able to literally see it be put together enough to know what it's doing
- **self**: Like on the assembly line of course
- **systems-engineer**: Well the cards are designed to only work exclusively with some chip fabs
- **systems-engineer**: we only have 3 on the planet advanced enough to make them
- **self**: What's a fab?
- **self**: like a mount?
- **self**: holster?
- **self**: slot? […]

Moves: `probe_expert`, `demands_evidence`, `escalates`, `analogy`, `concedes_point`, `meta_style`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-037: can a pc boot with no ram? 'why do i need ram, just read/write disk directly', 'what is software, just logic gates no?', 'i'm sure there's a few gaps in my plan'; partner: cache-as-ram, cpu is wired to ram (systems-engineer, escalated, quality 4)

- **self**: Also one more crazy question. If you were stuck in a room with all the tools you need to flash your mobo. You have a FULL pc with everything you could possibly dream in a tech shop. EXCEPT you don't have ram. You need to boot onto the computer and access chrome, because the building is locked by a password. That password only exists on a website which must be accessed with a chromium-based browser. /  / Do you survive and escape? or do you die of starvation/dehydration three days later?
- **self**: ASUS MSI Gigabyte BIOS Flashback requirements no RAM!
- **self**: lol
- **self**: ## There is a proof-of-concept (detailed in a March 31, 2026 Hackaday article) where someone modified coreboot (open-source x86 firmware) to skip DRAM initialization entirely and run code using only the CPU's on-die cache (L2/L3) as temporary "RAM." On older Intel hardware, they got a simple Snake game running and outputting over serial.
- **self**: whatttttt
- **self**: - **How it works technically:** Early in boot, CPUs support "Cache-as-RAM" mode where cache lines act like tiny scratchpad memory before DRAM is brought online. Coreboot historically used this for its own early stages.
- **self**: I don't understand why ram is needed 🤷
- **self**: Why can't it just continually io from the hdd/ssd/nvme
- **self**: [link] my pc can't run this apparently because my gpu is too old.
- **systems-engineer**: in theory this could be used, but yeah without an eeprom programmer with you in that room you are dead. On top of that assuming you could get it to work, you'd need to write a basic bootloader that fits in the cache of a CPU without running out of space (in assembly from scratch) the bios uses ram to function as well
- **self**: Why do I need ram i don't get it at all
- **self**: Just write/read from disk directly?
- **systems-engineer**: RISC-V is a CPU that is being attempted this way, still not as fast as ARM SOCs, so assuming there is a reason the businesses that would use it would want to create it, it's definitely possible
- **systems-engineer**: well you need software to do that
- **systems-engineer**: which needs memory
- **systems-engineer**: and then assuming you can do that, it will take days to boot a modern operating system like that
- **self**: What is software. Just logic gates no?
- **self**: PHYSICALLY and TANGIBLY it is DOING something correct?
- **self**: So.... you could just switchboard the wazoo out of it until you have something that can interface with your disk
- **self**: Random Access Memory shouldn't be required...? unless you're saying in that way i would be using ram.
- **self**: I'm sure there's a few gaps in my plan 😄
- **systems-engineer**: the CPU is directly wired to the RAM so it is required

Moves: `states_hypothesis`, `pushes_entrenched`, `concrete_referent`, `invites_pushback`, `admits_ignorance`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-039: crypto instead of banks; then cgnat-as-control hypothesis: 'feel free to correct me if i'm wrong'; rejects partner's market-square metaphor: 'i'm not understanding where your metaphor does anything' (systems-engineer, stalled, quality 4)

- **systems-engineer**: […] For me: a bank account is mainly a means to an end /  / building credit, etc is almost entirely forced onto us by the systems in place /  / I exist in those systems not because I agree with them but out of necessity /  / I did have some holdings and was into crypto back when dogecoin was under a cent a coin, and I have a dead harddrive out there somewhere with like 400k in litecoin that will never be found unfortunately
- **systems-engineer**: the problem I have with crypto is the original usecase is gone, it's been commodified and the idea that we can use it without the existing systems in place is now dead
- **systems-engineer**: for example: what happens if the US treasury decides to ban it outright? not only is it's value affected since it is pegged to the greenback, you now won't be able to buy things
- **systems-engineer**: crypto is awesome as an idea though, and I do use it for transactions and stuff, but most people use it as a vessel for investment, which just ends up fucking everyone over
- **systems-engineer**: not to mention it is entirely unregulated, the amount of exchanges that have rugpulled their customers is concerning
- **systems-engineer**: billions stolen with zero investigations or repercussions
- **self**: reading this was a weird flash of deja vu for me
- **self**: not because i've read exactly this before either in any other similar contexts either
- **self**: > I exist in those systems not because I agree with them but out of necessity / ...is it actually necessary?
- **systems-engineer**: I think I said something similar when we were talking about my using linux 😛
- **self**: i don't have any credit or a bank account.
- **self**: i'm basically Buddha
- **self**: lol
- **self**: if i could afford a RV and internet i'd live with that
- **systems-engineer**: Pretty much, until we decide that we are done with capitalism, which means (at the moment) we start to head to technofeudalism
- **self**: One moment, while I look this up...
- **self**: > a potential shift where large tech platforms act like digital landlords, controlling access to essential online spaces and extracting value from users ("digital peasants") through data and attention, rather than through traditional market exchanges. While still operating within a capitalist framework, it signifies a move towards a system where power is concentrated in the hands of platform owners who dictate the rules and benefit disproportionately from user activity, creating a hierarchical structure reminiscent of feudalism within the digital economy, a change from the more market-driven model often associated with traditional capitalism.
- **self**: so *that's* why none of em are pushing for ipv6 yet...
- **self**: cgnat controls the masses doesn't it.
- **self**: if nobody can host a listening port...
- **self**: listening server on any port...*
- **systems-engineer**: not quite, since the internet by design cannot be controlled by one entity
- **self**: then everyone's forced to route through inducers or other middlemen that can be a finite amount
- **self**: like a finite amount of non-cgnat internet connections is easier to control than everyone having the freedom to use their internet
- **self**: It's an indirect way to control it
- **self**: If you force everyone on CGNAT then i2p shuts down for example
- **self**: TOR basically works because people have listening ports available in various parts of the world
- **self**: that we can route through
- **self**: i.e. 'relays'
- **self**: feel free to correct if i'm wrong […]

Moves: `states_hypothesis`, `invites_pushback`, `pushes_entrenched`, `escalates`, `concrete_referent`

Why it worked or failed: Neither side produced the referent the other asked for; the exchange stalled on framing.

### r-040: cgnat as freedom loss vs partner's hanlon's-razor/incentives view ('speculating about hidden coordination feels like insight'); 'you focus on the explicit but neglect the potential'; 'can we sidebar, i need you to understand my point'; constitution/5th-amendment analogy; 'lost in text translation, call?' (systems-engineer, escalated, quality 5)

- **self**: > So I do know what you mean by CGNAT causing issues like this, but it's less of a concentrated effort to avoid ipv6 and more of a money reason / You have a tendency that i've noticed to focus on the explicit/obvious parts
- **self**: But you SEVERELY neglect the potential
- **self**: Take the lawsuit with Palworld and Nintendo. It's not just about those two companies, they are about to set a precedent for the whole gaming industry
- **self**: so i understand IPv6 is a migration and will be expensive. But what i've come to understand lately, is that CGNAT is stripping our freedom
- **self**: and i fear it will become the **norm** very soon. A listening server on home internet will be a remnant of the past
- **self**: That scares me. Because that means everything is controlled by the...
- **self**: not the oligarchy. What's the word i'm looking for
- **self**: So yeah there's no incentive to swap to ipv6.... they're already trying to remove section 230 lol
- **self**: as a consumer **we need to make it happen asap**
- **self**: corporatocracy
- **systems-engineer**: I'm not focusing on the obvious because I'm naive or dismissing the other factors.  /  / I'm focusing on incentive structures because that's where the actual leverage is.  /  / Speculating about hidden coordination feels like insight, but it actually makes the problem seem more solvable than it is.
- **systems-engineer**: Money is everything, there is no group of ISPs plotting to kill self-hosting, that is just a side effect of them wanting to go for the cheaper option
- **systems-engineer**: all the ISPs have independently come to the same conclusion that CGNAT is the cheapest option in the near term to avoid IP starvation
- **systems-engineer**: they simply don't care about self hosting, there's no incentive for them to keep things going
- **systems-engineer**: Worth noting too: That section 230 repeal is a platform thing, while that does play into things as they appear right now there isn't a conspiracy here it's just shitty timing /  / if you make things harder to self host you push people to centralized services /  / those centralized services would need to be  run by companies that can survive assuming that repeal goes through
- **systems-engineer**: those laws only apply to american companies though (which are the biggest ones at the moment) but there are still a lot of other options out there.
- **self**: Oh. I guess I'm missing something then
- **self**: Let me reread
- **self**: Apologies if that's what happened
- **self**: i got so confused by this point
- **self**: technofeudalism is a fun word of the day for me
- **self**: > My fibre connection doesn't and still uses ipv4 (not cgnat) which is mainly due to money reasons and engineering costs / > CGNAT is a bandaid, which companies lean on as the costs for moving to ipv6 don't make sense to them.  / Yeah.
- **self**: > there isn't something blocking ipv6 other than the lack of will. / > It's the same reason we still have COBOL in banks, just technical debt compounding with institutional inertia. / > I think this whole thing is a great example of Hanlon's Razor in action 🙂 / > all of these ISPs are also publically traded companies, they are notorious for investing into things with a low ROI as well / Sure?
- **self**: I mean can we sidebar. i kind of need you to understand my point in order to move on. Like i know the challenges of ipv6 migration are as long as our arms but my focus really was on the implicit freedom lost as we slowly roll out cgnat instead of a unique ip to consumers?
- **self**: i just think that's a really important point that people miss and it's honestly the most relevant right now.
- **self**: Otherwise yeah everything you said is a bit more detailed than my understanding of the ipv4/ipv6 problem
- **self**: I feel *lately* that someone is going to capitalize on the cgnat push. Someone like Google or Microsoft. Or LE?
- **self**: LE would probably be *for* cgnat because it deanonymizes the internet and makes tracking a bit easier for em
- **self**: That was kind of my point i guess 😄 i mean maybe they don't have much power in the way of standardizing CGNAT all around.
- **self**: but if they did that would be extremely bad […]

Moves: `states_hypothesis`, `pushes_entrenched`, `apologizes`, `self_corrects`, `escalates`, `analogy`, `concrete_referent`, `meta_style`, `offers_out`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-043: wsl2/hyper-v: is the linux kernel bare metal or virtualised? 'you don't need to dumb things down... i think you lack depth sometimes'; 'prove it'; 'mcp certified means nothing to me, you might as well be posturing'; 'i'd only trust benchmarks or source'; '#removetechnicallanguageeverywhere'; 'sorry for all the questions, i feel dumb' (systems-engineer, conceded, quality 5)

- **self**: You don’t need to dumb things down so heavily. I know a lot just also realize how much I don’t know. I think you lack depth on things sometimes? It’s not like wsl is open source /  / Some people swear by it being a native Linux kernel. Some say it is still bottlenecked by the hyper-v. /  / As for me I don’t understand why they call two different things hyper-v and hypervisor as that adds unnecessary confusion/ambiguity. /  / Hyper-v iirc is the faster one than windows hypervisor
- **self**: Dude kde plasma in wslg looks so nice. I might even block explorer.exe on boot and use that instead
- **self**: Why isn’t everyone doing this? Fuck wine lol this is so much cleaner
- **self**: took me about a day to configure the provisional stuff
- **self**: I was considering aeon for a fat minute
- **self**: Dunno if I’m weird but I’m mixing gnome apps with kde apps 💀
- **systems-engineer**: hyper-v is the windows hypervisior, they name them differently just to make them separate "products" it's all hyper v under the hood /  /  / It will still be bottlenecked under some workloads regardless, the dx12 passthrough stuff they added to mesa sidesteps most of the hardware acceleration problems of the past
- **self**: Using wsl means I get native windows and linux performance. If I install linux, that means I get emulated windows performance. Why would I ever want to do the latter?
- **systems-engineer**: And that is why WSL exists 🙂
- **self**: Prove it
- **self**: nah actually though how do I benchmark that stuff
- **systems-engineer**: [link]
- **systems-engineer**: For benchmarks, pretty much any IO benchmark should show that bottleneck /  / Not fully sure what is slowest off the top of my head but DBs are also affected somewhat
- **systems-engineer**: We had to deploy them via hyper-v vms before we could move to KVMs and bypass a lot of that microsoft licencing junk
- **self**: This might as well be gibberish. What’s the highlights?
- **self**: where’s windows in this diagram lol
- **self**: Root partition?
- **systems-engineer**: the yellow box basically, it shows each of the different examples of virtual machines and how it interracts with each part of the subsystem
- **systems-engineer**: yeah, with hyper-v enabled you are technically running your windows install on the hypervisor and not bare metal (bypassing the hypervisor subsystem)
- **self**: Well I was hoping the diagram would just clearly show me where the bottleneck or resource bloat was.
- **self**: is wsl2 running a native linux kernel or not
- **self**: and how would I test that down to the ms
- **systems-engineer**: in a VM, it is /  / with it's own userspace
- **self**: I don’t even have the hypervisor enabled. Hyper-v is something different
- **self**: I’ll prove it one sec
- **systems-engineer**: I have no idea off the top of my head, you can try IO based tests for throughput (VHDs are quicker than they used to be but still slower than a native drive)
- **systems-engineer**: it's a type 1 hypervisor, instead of booting windows onto your hardware directly you are booting into the hypervisor first /  / Once that is running your root partition (in that diagram) is your windows system, and then any child partitions (other vms) are running alingside them
- **systems-engineer**: the vmbus connects them all so you can talk to and move things between vms in memory
- **self**: I don't even have Windows Hypervisor Platform enabled
- **self**: From stackoverflow I've learned it's slower. […]

Moves: `states_hypothesis`, `escalates`, `demands_evidence`, `pushes_entrenched`, `concrete_referent`, `asks_clarifying`, `apologizes`, `meta_style`, `admits_ignorance`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-044: review of his ai-generated declarative kinoite setup: 'be brutally honest, laugh in my face'; partner: 'insanely over-complicated'; 'why is nix the only one like this?'; 'damnit you're right, thanks for the foresight'; 'i know i'm doing noobie things but i'm not a noob, just adhd and always questioning my information'; exits with 'can i change the subject?' (systems-engineer, escalated, quality 4)

- **self**: […] YES
- **self**: OMFG
- **self**: WHY IS NO OTHER DEV WANTING THIS BESIDES ME LMAO
- **self**: just give me something pre-configured from a seasoned veteren out of the box
- **self**: i'm so tired of these slim distros that have literally nothing
- **self**: why is it like that lmfao.
- **self**: what's the most bloated linux distro in the game right now?
- **self**: give me that
- **systems-engineer**: Well I mean all of them pretty much have: /  / a DE, browser, office suite etc, utilities and then you just install the packages you want
- **systems-engineer**: you setup your de once and then copy the config files it writes and then to restore you just install those packages and restore the config files
- **systems-engineer**: I think what you might be looking for is nix
- **self**: usually i need to `apt install` like a billion things. So many deps. So many upgrades. Just honestly nothing is preconfigured and it's bullshit
- **self**: Yeah i really LOVE nix
- **self**: i just wanted to try something else because maintainability of nix is higher
- **self**: requires more effort/upkeep
- **self**: rpm-ostree was explained to me as the best of both worlds
- **self**: also considering aeon
- **self**: [link] / [link] / [link] / [link]
- **self**: top 4 choices 😛
- **systems-engineer**: Other than the initial setup for any of these options the maintenance burden isn't on you it's on the packagers
- **systems-engineer**: nix, silverblue, etc.
- **systems-engineer**: now if the goal is to prebuild your own image to run on other machines you can use [link]
- **systems-engineer**: I haven't messed with these in a while but you can use their template to preconfigure things: [link]
- **self**: idk what this means
- **self**: look anytime i install an operating system it requires months of painstakingly installing things, going through the settings, configuring everything, personalizing everything. /  / The goal would be to make **any and all of that** provisional/declarative so I can get all of that **out of the box**
- **self**: if immutability isn't the way to do that then i guess i don't want immutability
- **self**: something that won't break and is conventional
- **systems-engineer**: In that case nix is your only option
- **self**: every year or so i reinstall windows and it takes about a month to get it to the point it was before
- **self**: why is nix the only option sorry? […]

Moves: `invites_pushback`, `concrete_referent`, `concedes_point`, `pushes_entrenched`, `meta_style`, `offers_out`, `exit_move`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-045: community response times: 'respectfully, i think that's a brainless answer'; partner: 'sure you don't want to rephrase?', 'it is 8am on a monday'; 'let's just say i'm sorry for being frustrated... does neither of us good to bang heads against walls'; 'people should separate ideas from the person' (systems-engineer, dropped, quality 5)

- **self**: Nevermind lol a lot of dumb shit went down.
- **self**: sorry for bothering you with it
- **self**: I don’t think anybody cared for the idea. I should let people come to me if they want to use my idea instead. Seems to be the strat in OpenKotOR.
- **systems-engineer**: Well it doesn't hurt to leave stuff in a forum post for a while, once you hear some feedback you can start on whatever it was you wanted to do
- **systems-engineer**: Pretty much everything that is an RFC will always take some time to gather feedback
- **self**: ugh yeah you’re probably right
- **self**: wish people could see what I see sometimes though. It’s baffling to watch behavior ensue that I can literally explain because nobody wants to be me the guy that requests things all the time and waits a week or even longer. Lol. Dunno when I became the butt of the joke but that’s bizarre. Doesn’t feel constructive to take it out on anyone but my god I can’t stand most people because of this wishy/washy crap. I am never going to leave but it sounds like I’ll meet less friction if I just stop using openkotor’s name. I’ve no problem using th3w1zard1, OldRepublicDevs, etc if I don’t have autonomy to use the name. But there’s literally things I’ve waited over a week for lol. I’m not the problem wa […]
- **self**: but like I said it’s fine.
- **systems-engineer**: Well keep in mind that everyone works at their own pace, you need to be courteous of that.  /  / I have seen nothing to take away that you are the butt of any joke
- **self**: Respectfully, I think that’s a brainless answer frankly. There’s plenty ample time I give people to respond to the things I don’t know for certain. People take that as me being brainless because I’m asking so much. Leading me to try to take autonomy about the things I don’t see as problematic. Which leads to pushback. /  / so *like I said* the simplest logical solution is to avoid the irrational problem by not using openkotor’s name since I don’t own that and I have no autonomy to act on it
- **self**: lol I must really post too much
- **systems-engineer**: Sure you don't want to rephrase what you just said?
- **self**: respectfully it doesn’t feel like I’m heard ever. It’s hard not to be frustrated by this when it feels so non sequitur with what I’ve written. /  / I am always saying ‘earliest convenience’ I am always saying ‘no worries’
- **self**: And I ask for straightforward details/disclosures about how people want it to be ran. To allow me to align. Literally I get nothing I can use. Like it’s somehow an alien concept for anyone to be coherent. I’m not going to sit around waiting to do things that are fun just to use an OpenKotOR name lol. Basic systems/entropy theory. I might as well just do what everyone else is doing and use the th3w1zard1 name and link externally. /  / But all that does is hide the real problem and show I can’t solve it either despite me having the solution to do so. Because no one wants to give me mind to hear me out ever. /  / Yeah it’s frustrating. Genuinely kills my flow most of the time. Never do mean to […]
- **self**: I don’t like avoiding issues or doing wishy/washy stuff.
- **self**: I don’t understand how people operate under a regime like that frankly. I pride myself on puritan lifestyle of putting effort in, searching for the truths in life, and solving problems.
- **systems-engineer**: People are just busy dude, I have not seen a single issue or reason for there to be any sort of malice behind not answering etc. /  / The last few asks in #admin-only have been responded too, and people mainly lurk around if something has already been answered as there is little reason to #1 short of a reaction /  / The last thing you asked me to look at you deleted before I even got a chance to look at it. /  / My answer isn't brainless it's the truth, people operate on their own pace, if you can't accept that I don't know what to tell you
- **self**: Look in what universe is this a pacing problem respectfully.
- **self**: How many open requests exist in the discord.
- **self**: how many of them are me. And how many have waited multiple weekends?
- **systems-engineer**: Looks like a few, you have to keep in mind that the server isn't super active /  / overwhelming people with a bunch of asks also makes it hard to answer one of them, I see multiple walls of text /  / If you really want to go forward with something just do it and wait till you hear complaints (if any) if none then that is it /  / just a "hey I am doing this" is more than enough
- **self**: Look it’s just clear to me the issue is my utilization and autonomy of the OpenKotOR name. I can just use another name and do my own independent thing separate of the org. Like I was doing. /  / The way this typically works is we get aligned based off of some manifesto. But no one wants to read mine and nobody wants to contribute one. I have nothing to align to, and that gives me nothing to go off of except people’s emotions and fears. Which is frankly just a brainless way to run a community. If there’s a more respectful and true way to say this please let me know. Just I was raised to always be constructive. Fight losing battles. Etc. Be right and be open to being wrong
- **systems-engineer**: You're overthinking things
- **self**: Just how I was raised. None of that means im a dick. Like I said you’ve found a good friend in me I don’t have a mean bone in my body
- **self**: Nah
- **systems-engineer**: Just chill, let things stew for a bit
- **systems-engineer**: discord forums also require you to browse to see any posts, They are hard to discover without looking through them outright
- **self**: This conversation just doesn’t feel real lol. What on earth are you seeing as I type this? Just pure confusion? I guess a real conversation id expect some point I made to be responded to and collaborated with some earlier point or some  mindset. The simplicity and amount of space you’re giving me is what led to me talking about a ‘brainless reply’. Just what else do I even say? What? How can I point out how ridiculous your reply was in a constructive way without you misunderstanding behind the non-immediately-recognizable statement.  /  / I’m basically giving you the alphabet, and wondering how to get to Z, and you chime in to talk about fruit. Why is fruit being mentioned in any context? (T […]
- **self**: I don’t get it at all
- **systems-engineer**: It is 8am on a monday. […]

Moves: `escalates`, `pushes_entrenched`, `demands_evidence`, `apologizes`, `self_corrects`, `exit_move`, `meta_style`

Why it worked or failed: Escalation plus meta-commentary about the debate itself outran the evidence; the partner stopped responding.

### r-049: after partner's apology for shutting the door: linux swap vs windows pagefile — 'why can't swap resize dynamically, should be default', 'linus said don't fuck with userspace — letting ram run amok is fucking with userspace', 'why the fuck are the defaults set up so logs fill the disk'; partner: zram, logrotate has existed for decades (systems-engineer, redirected, quality 4)

- **systems-engineer**: I am sorry if I came off as abrasive, I guess I was just fed up. /  / I am not one to close to door like that often but needed a mental break
- **self**: No worries, i totally get it. I don't think you were out of line or anything
- **self**: Just definitely feel free to let me know if i'm getting that out of line. Scrolling through some of those previous comments that ticked you off was somewhat embarrassing 🥶
- **self**: I'm still struggling to implement fedora if you have a moment? A few various things are just irking me atm
- **systems-engineer**: Proton should work for this 🙂 / Most EAC games have support for Proton unless they have blocked it on purpose (some do)  /  / If you force Proton as a compatibility tool, Steam will download the Windows build and run it via Proton (which works with Rocket League quite well)
- **systems-engineer**: Sure, what are you running into?
- **self**: So when I ran wiindows i was pretty used to running a ton of things, and seeing my ram constantly at 31GB/32GB, with the pagefile being 50 some gigabytes as well over time. /  / However I can't run anywhere near what i used to be able to run on linux. I get crashes every now and then which i can only assume is because i'm running out of memory. /  / The default installation implemented a swap of like 4gb/8gb or something?
- **self**: how do i make it dynamic so it's IMPOSSIBLE to run out of ram and crash out like that?
- **self**: is it possible to use swap on demand like the pagefile i'm used to? lol
- **self**: or how do i manage this?
- **systems-engineer**: Are you specifically getting an OOM message? /  / On Linux swap is used by default once your ram is filled up, Fedora uses something called ZRAM which does on the fly memory compression to get that one step further
- **self**: The other biggest issue i'm having is the fact that i just couldn't bear to use fedora so i swapped back to windows 11
- **self**: see the image
- **self**: i'm totally jk... i'm using a windows 11 theme for kde 💀
- **systems-engineer**: 😛 KDE is awesome for that
- **systems-engineer**: cursed for sure, but that's theming freedom for you 😄
- **self**: Other issues: / - Half of my chipset devices don't work (bluetooth, etc). / - I've no idea how I managed to get the GPU driver installed but for the first two hours i was stuck at 1076x768 and it was awful. I literally gave up an hour in and just prompted ai until i finally had a fix.
- **systems-engineer**: let me see if I can dig up my zram config /  / Should be an easy adjustment if you are really memory starved
- **self**: Well why can't it just dynamically adjust the swap based on how much ram is used? that should be default imo
- **self**: Also I installed homebrew for shits and giggles. I don't plan on installing anything through it though
- **self**: Also how do I test WinUI3 stuff? i think that may have been the whole reason i swapped back to windows. Cus i could always get linux through wsl was how i was thinking
- **self**: How much input lag does proton give?
- **systems-engineer**: If you really are memory starved you can add more swapfiles that way, normally people go the partition route, which only is filled as needed /  / for example, try opening htop: should give you an overview of usage
- **self**: going through wine and all that
- **systems-engineer**: A negligible amount 🙂 / Wine translates and doesn't emulate so there isn't an emulation tax for latency
- **self**: i don't want to add more swapfiles as that slows my pc down. i'd prefer if it'd just automatically handle it at a high level? i don't understand why this isn't widely desired best practices in the kernel already lol who actually is watching their ram usage every 5 seconds?
- **self**: the whole thing Linus said is
- **self**: **don't fuck with userspace**
- **self**: no?
- **self**: Letting ram go amock is fucking with userspace :kappa: […]

Moves: `states_hypothesis`, `pushes_entrenched`, `escalates`, `demands_evidence`, `concrete_referent`, `asks_clarifying`

Why it worked or failed: Kept asking narrower questions until the partner had something concrete to explain.

### r-051: utilitarianism vs egoism and ai use: 'is there a number that nets out the evil of using ai?', bus/detour hypothetical; partner's structured rebuttal ('you built a hypothetical where the utilitarian answer is the opposite'); 'your argument ain't going to convince me until you point out the flaw in mine'; line-by-line rebuttal; 'provide the operating parameters of this discussion so i may align'; partner: 'it rewrites itself around every objection' and leaves for star citizen (systems-engineer, dropped, quality 5)

- **self**: […] Frankly I think you just need to digest what I've said and what I stand for. It may be a hard pill to swallow if you've lived your life a certain way for a long time. Trust me i've tried living every way under the sun in my life i don't waste time if i can help it
- **self**: i've tried everything and i only do what works for me. The only reason I have this conversation with you at all is to potentially prove myself wron g wit hsomething you say, and to potentially inform someone i respect of food for thought
- **self**: it has nothing to do with being right
- **self**: or posturing
- **self**: i just want us both to succeed and make our dreams come true.
- **self**: I've literally partied 8 days of my entire life
- **self**: Even when I play video games like Rocket League i'm reminiscing in the memories.
- **self**: But yes if there was a GLOBAL movement that MATTERED and i thought it was worth pursuing, i'd happily pour my last bitcoin into that shit
- **self**: in my 30s i just found that doing it your way was not getting me the results i wanted
- **self**: if i go viral i can touch more people, influence the masses a bit more, etc
- **self**: i care nothing about being rich other than using it as power to give back
- **self**: I do not know what other way i can state this but do try to keep in mind i'm trying my best to read what you're saying, understand you, and provide an honest answer
- **self**: I just think differently.
- **self**: Life is 90% how one reacts to things, and 10% the stuff that happens
- **self**: TLDR focus on this part: /  / > # it's that the rule is built so the good never actually arrives / It's more, **every day my reach increases**
- **self**: am i expectedx to live the way you're living at age 1 for example? no i need to learn how to walk lol
- **self**: this kind of elitism on morals and the proper way to do things is literally why linux still targets the tech savvy users and less so the dumb guy normal people that just want to see a photo of their cat from their grandma and check their email.
- **self**: nobody thinks in how people think/learn. And the reason elon musk doesn't donate more? Over sense of comfort
- **self**: and crab mentality
- **self**: crab mentality fucking sucks
- **self**: holyyyyyy
- **self**: once the boomers start retiring and passing away maybe we can change that
- **self**: But fr if everyone thought like you and me the world would be a better place
- **self**: I think on that we can agree wholeheartedly
- **self**: If everyone was like the two of us, we wouldn't be disagreeing at all honestly lol
- **self**: because we'd be living probably the same morals
- **self**: I talked to someone the other day about the starvation of africa and the shit going down in the middle east and he was like 'nah they gotta get themselves outta that i'm not going to worry and waste my life worrying about them'. The entitlement to say that is ridiculous lol
- **self**: that's another human being out there
- **self**: 🤷 i hope this reaches you because i'd like you on my side or at least find an argument that'll convince me if i'm wrong. Those are the only two opportunities i can give you
- **self**: Either: / - Help me understand why you're right by telling me what specific part of what i'm saying is wrong / or / - Join my cause and realize i'm pretty much correct, just a bit naive with how i'm preaching this. /  / Offer direction rather than hardwalling my moral compass […]

Moves: `states_stance`, `analogy`, `pushes_entrenched`, `escalates`, `demands_evidence`, `invites_pushback`, `meta_style`, `self_corrects`, `offers_out`

Why it worked or failed: Escalation plus meta-commentary about the debate itself outran the evidence; the partner stopped responding.

### r-052: cors and security hardening: 'why is that default — those aren't my problem', unlocked-house metaphor vs partner's butler-with-keys metaphor; 'agree to disagree'; 'doesn't feel like you ever hear me'; 'just because it's best practice doesn't mean everyone agrees'; 'call me the 10th dentist' (systems-engineer, stalled, quality 5)

- **self**: Why is there so much hardening around security anyway?
- **self**: like... i mean... you ever feel like they take it overboard?
- **self**: it's starting to feel like i can't even sign into things *correctly* as my *own* userver. How on earth is someone smart enough to hack into someone else's account they ain't supposed to get into?
- **self**: i'm somewhat joking but also it's so obnoxious
- **self**: What really bothers me is specifically
- **self**: ...
- **self**: i forgot the name
- **self**: xD
- **systems-engineer**: It's a side effect of Linux being used on most web infra everywhere /  / Fedora is targeted as a "workstation" so they share some of the server side stuff /  / The firewall allows all access on workstations though, that firewall stuff I am mentioning is a bug with wireguard vpns specifically
- **systems-engineer**: But yeah, authentication and stuff has always been this way in the unix / unix-like world since it has it's roots as a mainframe multiuser shared system
- **self**: CORS
- **self**: whyyyy
- **self**: why is that default
- **self**: it only hurts the client that's dumb enough to not use it
- **self**: so why as a *server hoster* do i need to use it???
- **systems-engineer**: Stops mitm attacks
- **self**: yes BUT
- **self**: THOSE ARENT MY PROBLEM
- **self**: lol
- **self**: that's like saying
- **self**: hmm
- **systems-engineer**: Well it is when a site is loading malicious code, you inadvertantly become a launchpad for more stuff
- **self**: ok i have a metaphor
- **self**: hang on this metaphor is hilarious
- **systems-engineer**: Also to finish this thought: Windows had *nothing* until UAC came around, you could pwn a windows system in 10-15 seconds easily since the default root password was normally "password" or "admin" and running stuff *as admin* didn't even need a password
- **systems-engineer**: So where UAC was trying to batten down the hatches, unix's authentication systems were in there from the start out of it's design roots as a mainframe operating system
- **self**: My issue with CORS is that it treats the server owner as morally responsible for what a completely different client decides to do. /  / To me, that logic feels like this: I’m asleep in my own house, I forgot to lock the front door, and some random guy wanders in during the night, ignores multiple obvious signs that he shouldn’t be there, trips over the basement stairs, and somehow I’m the irresponsible one because I didn’t install a childproof gate for trespassers. /  / That’s what CORS feels like. The browser willingly goes to another server, willingly executes code from somewhere else, then acts like the destination server is responsible for protecting the user from the browser’s own decis […]
- **self**: so again, those are *not* my problem lol
- **self**: But yet i feel obligated to enable CORS because so many things will break if i don't have all pieces set the same way. And their defaults are always strict cors
- **self**: I tried standing out and setting it always to * but man that has me exhausted lol i just had another docker image update that broke one of my services due to that env var not being respected in the newer version […]

Moves: `states_stance`, `pushes_entrenched`, `analogy`, `escalates`, `meta_style`, `exit_move`

Why it worked or failed: Neither side produced the referent the other asked for; the exchange stalled on framing.

### r-055: 'why would anybody by choice use linux as a daily driver — until you convince me or i convince you': dxvk 10% speed claim, 'why can't it benchmark itself and pick defaults', 'zero reason multiple wine prefixes need to exist'; 'do you as an expert ever get to a point where there's not simply more to unpack?'; 'what do you think my biggest problem with the linux ecosystem is and why does no one else experience it?' (systems-engineer, redirected, quality 5)

- **self**: Why do so many apps talk about xwayland, x11, Wayland? Which ones do I want to be using given the choice?
- **self**: I know what Wayland/x11 are
- **systems-engineer**: So Wayland is Wayland, XWayland is X11 running using wayland (like a translation layer so xorg apps can talk to the wayland compositor) and then x11 is the standard xorg server /  / Linux is moving towards Wayland as the future, pretty much everything new supports it natively, that said: some stragglers still target xorg for certain compatibility reasons (like running on old LTS distros, etc) /  / So given the choice use Wayland, otherwise xwayland takes over
- **systems-engineer**: you shouldn't need to worry about which is selected, all of it works 🙂 /  / but if for example you want to use HDR, or something else wayland specific (compositor crash survival, etc.) and the app doesn't support it you just need to wait for that app to support it
- **self**: How much stuff still isn’t ported and why are they slower?
- **systems-engineer**: Well things move slowly 🙂  /  / X has been around for 41 years, so sometimes certain apps are slow on the uptake (e.g. they don't want to support and xorg and wayland version). Wayland is quite young in comparison, so not everyone runs it yet. That is unfortunately a Linux fragmentation thing. Pretty much all distros default to Wayland nowadays though. /  / XWayland will continue to be around forever due to that fact and fully supports running xorg apps, including all of the fancy hardware acceleration bits
- **self**: For example sometimes I run (somewhat unrelatedly) d3d11 games through vulkan api using d3vk (or whatever it’s called) and those api calls are like 10% as the speed of turning d3vk off. Noticed this in about THREE standard games during my tests. /  / So I’m just wondering why I ever would want d3vk
- **self**: and more importantly why can’t it just figure out what defaults to use out of the box?
- **self**: it EASILY should be able to run a benchmark itself
- **self**: Based on like… three different app launches and the statistics observed over each of the three times launched
- **self**: And figure out what settings to automatically enable
- **self**: Most of my games I feel like I spend an hour each to get the right settings
- **self**: Who on earth has time for this on a daily driver?
- **systems-engineer**: Which games were you trying to run?  /  / The only times I have problems with games are typically when the anticheat is blocking me, but I haven't had any performance issues that bad, I get probably 95% of native performance
- **self**: also why is there like 7 wrappers around wine and why do none of them use the same prefix? Seriously why do I need containerization with wine at allllllll it’s not like when I run pure windows I need to containerize each app. Bro containerization has been pissing me off lately lol everything has a flatpak/snap and they’re hot garbage with only like 70% of the original functionality
- **self**: for example most apps I can’t run on startup without a manual setup.
- **self**: Or the thing with discord the other day. LITERALLY was just trying to boot into discord and start a voice call. Ended up getting fucked because I needed to restart the app 😂
- **self**: there’s no command to just reset audio devices within an app
- **self**: Yes this is a rant. Lol. Intentionally trying to ask why anybody by choice would use Linux as a daily driver 😂 maybe in doing something wrong
- **self**: But until you convince me or I convince you welcome to another episode of ‘Wizard tries to use Linux, part 1002’ 😂
- **self**: maybe today I fix WARP lol
- **systems-engineer**: Okay so lets try and unpack each one first.. lol
- **self**: Yes we can unpack
- **self**: But FIRST
- **systems-engineer**: `systemctl --user restart pipewire wireplumber` this restarts the audio service 🙂 keep this around just in case you need it
- **self**: explain. Do you, as an expert, EVER GET TO A POINt where there’s NOT SIMPLY MORE TO UNPACK 😂
- **self**: Because hang on
- **self**: Hang on
- **self**: Hang in there
- **self**: It SEEMS to me like it’s retroactively designed to continually be fixed as you go. As in… after you get everything working you have this carefully constructed jenga tower of proprietary nonsense only you understand. / … and if works fine. /  /  / … until you want to run kotor on proton. ‘Let’s boot an old gold of a game and enjoy nostalgia’ /  / Then, you acquire the invalid emitter crash problem. And your day or r&r turns into ‘ima patch this bug for the next joe’  /  / Does that mindset EVER end to the point you can just use ur pc like a normal human being without expecting something to go wrong? /  / Cus as a seasoned user of windows. Linux. And a smidge of mac… it seems literally only wi […] […]

Moves: `states_stance`, `invites_pushback`, `pushes_entrenched`, `concrete_referent`, `escalates`, `probe_expert`, `meta_style`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-056: dynamic swap / oom defaults: 'the more i hear best practices the more they seem like shit practices'; partner: explicit over magical, swap partitions bypass fs layer, systemd-oomd; 'when i insult the people that make this stuff i do so on purpose... i almost always end with ah that makes sense you're right'; 'intuitive design == intuitive defaults'; 'linux has zero try-catches'; 'what's the downside of dynamic swap? why isn't it default?'; 'why are you assuming linux is perfect?' (systems-engineer, escalated, quality 5)

- **systems-engineer**: […] Yeah there are tools to handle that for you (e.g. grow a swapfile dynamically) but normally the best practice is to make a big swap partition if you need it and then forget about it
- **systems-engineer**: [link]
- **systems-engineer**: should be packaged by the distro is you want to install it
- **systems-engineer**: this is the main point against it:  /  / [link]
- **self**: y'know the more i hear the phrase 'best practices' the more they seem like shit practices
- **self**: i'm not even kidding the more i hear that phrase the worst they become
- **self**: there's zero universe that should exist where that fucking swap file doesn't dynamically grow if needed to prevent OOM
- **self**: THat's actually such an oversight
- **self**: btw when I insult the mongoloids that make this stuff i do so on purpose... because they're unlikely to respond directly if i don't attack the decision and come across as a script kiddie from the get go
- **self**: i just enjoy triggering keyboard warriors like that
- **self**: i almost always end with 'ah that makes sense you're right'
- **self**: but until they do i'm 100% just out here thinking they're mongoloids because it's a stupid standard. But yeah it probably has a reason for being that way... i'm sure someone else has considered making it dynamic or having it configurable to that end
- **self**: literally windows ftw for that
- **systems-engineer**: Well there are two different design principles in play /  / Linux was designed around swap partitions not files, so you can't regrow it without unmounting, resizing (if there is space) and then remounting /  / Swapfiles exist too, but they actually don't go through the same IO layer as the rest of the filesystem
- **systems-engineer**: swapon literally says "give me the exact physical disk blocks so I can talk to them directly:
- **systems-engineer**: They could add dynamic resizing and other stuff to the subsystem but they kept it simple on purpose
- **systems-engineer**: Linux almost always is about explicit over magical when it comes to things (as you have noticed) /  / you give the admin the levers and let them decisde the policy. That lets distros set their defaults, etc.
- **systems-engineer**: Windows has all of the fancy resizing stuff since the FS,kernel, and memory management are all handled by the same team and are more able to be intertwined. Linux is modular in comparison, filesystems are abound and not able to be so tightly integrated due to that
- **self**: Look at it this way
- **self**: What happens when Linux runs OOM?
- **self**: hang on
- **self**: does it: / - A: crash/freeze or force terminate some of your programs losing you potentially hours of work / - B: handle it programmatically for the user and warn them that the kernel just prevented a critical issue, thereby saving the user work and time
- **self**: i'm not just talking about this one scenario lol. A seems to be how linux distros want to faciliate most of the stuff for some reason
- **self**: I literally run windows because it does so much in terms of B
- **self**: is anyone in the linux community trying to like... change the mindsets cus currently the overconfiguration potential just leaves a lot of gaps like this
- **self**: they say debian is stable as a rock... but i'm pretty sure this issue would still exist there
- **self**: yes you could say it's a user error
- **self**: but also why is linux advertising to non tech savvy users and acting like the original hurdles of trying to use/run linux are gone
- **self**: the desktop environment looks much nicer but other than that it's still kind of the same design principles. Design principles that require tons of configuring and pentesting everything under the sun to make sure some unexpected issue doesn't happen
- **self**: why is there no attempt to salvage […]

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `meta_style`, `analogy`, `concrete_referent`, `asks_clarifying`, `concedes_point`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-058: apology after the ux fight: 'i seem to become heated in the spirit of discussion and debate and i'm unable to track when you're in it for curiosity or if it's becoming a burden'; offers to drop debate and keep it to 'teach me linux'; returns with a self-found solution 'in the interest of respecting your time' (systems-engineer, stalled, quality 4)

- **self**: The fact someone even needed to ask this is exactly the problem lmao
- **self**: The brainpower that led to the question is exactly a problem. Simply typing ‘paint’ should bring up the alternative. It should have never gotten this far
- **self**: When Discord, Google, Microsoft, GitHub, etc. say "Use a security key", on Windows the OS can respond with Windows Hello (your PIN or biometrics) because Microsoft implemented a full platform authenticator that browsers can talk to. / On Linux (including Fedora 44 KDE), is there a similar way to authenticate?
- **self**: I managed to fix the cloudflare-warp thing. It was not easy and I probably made it worse. Thoughts?
- **self**: I ran: /  / ```bash / sudo dnf install -y [link] [link] [link] [link] [link] / ```
- **self**: *almalinux* lol
- **self**: Yo man what's good i wanted to apologize (again) about the above.... i seem to become heated in the spirit of discussion and debate and i seem to be unable to track when you're in it for the interest and curiosity and passion or if it's just becoming a burden. I'll try to be more mindful moving forward. It really did seem like you weren't interested in an open discussion so that's why I got so heated. /  / If you'd like to cut out debate/discussion and just keep this 'hey can you teach me linux' we can do that too...
- **self**: Hey man! In the interest of respecting your time I found a solution you may be interested in! /  / So kinoite/silverblue doesn't *specifically* need to use flatpaks. I found this solution which works really *really* well. /  / >  / > ## 🧊 Fedora Silverblue / Kinoite Model (immutable OS) / >  / > This workflow is describing Fedora’s **immutable desktop variants**: / >  / > * **Silverblue** (GNOME-based) / > * **Kinoite** (KDE Plasma-based) / >  / > These systems use **`rpm-ostree`** instead of traditional package management. / >  / > ### 🔒 Key idea: the host OS is immutable / >  / > * The base system is **read-only and versioned** / > * You don’t normally install dev tools or packages directl […]
- **self**: full guide: [link]

Moves: `apologizes`, `meta_style`, `offers_out`, `self_corrects`

Why it worked or failed: Neither side produced the referent the other asked for; the exchange stalled on framing.

### r-062: 'the problem with pykotor isn't python but imperative code' hypothesis vs partner's 'dynamically typed languages are ass at large codebases'; 'i'm getting the vibe you're not interested at all'; resref inheriting str — partner: 'why? genuine question. what benefit beyond it makes sense'; overloads 'why is this difficult exactly?' (toolsmith, escalated, quality 4)

- **self**: Hey I'd like to run an idea by you
- **self**: I believe the problem with pykotor isn't python, but the amount of imperitive code being used. Imperitive isn't a word that's typically used in software dev but I've gotten pretty used to using declarative code as I manage my kubernetes cluster. /  / I think the issue is not the weak vs strong types in python vs c#. I believe it's the explicit nature of every function being overly complex, causing to entire program to have a ton of points of failure
- **self**: every skill, task, and concept in life has a balance. Staying within that balance involves knowing what's on both sides. / - **Extreme left**: Terraform, Kubernetes, HCL, and helm use declarative code (almost configuration files).  The downside is it is pretty difficult to configure and customize the exact way you may like. / - **Extreme right**: What we have going on in PyKotor. A bunch of functions with duplicated code basically everywhere. Tons of installation.resource() constructor calls, location calls, each editor almost defines its own implementation of the same thing.
- **self**: this is a good example of what i'm talking about. [link]
- **self**: I am reaching out because I'm aware this is like 20% of a solution for a kotor library, a blunt direction to meander in. Wondering if you have a more canonical way to do something like that?
- **self**: For example you'd think there'd be some GUI library that'd let you create editors for classes, without having to write code-behind. Like define a class, and be able to create, from *just* that class, a functional editor.
- **self**: sorry if this isn't interesting
- **toolsmith**: I don't really know what your going on about
- **self**: The problem with the toolset/pykotor. Your hypothesis is about weak typing
- **toolsmith**: PyKotor's design in some areas is ass, but it doesn't really change the fact that dynamically typed languages are ass at large code bases
- **self**: Yes, that's correct, almost exactly lol
- **self**: But as I'm working with the .net stuff and almost the exact 1:1 code i'm realizing that's not exactly the problem.
- **self**: <[link] this file is a pretty good example of what I mean.
- **self**: Ideally this editor/window shouldn't need code-behind at all.
- **self**: For example some research I've done, I've found projects that'd use wxWidgets (somewhat cool alternative to qt) to dynamically create a gui from cli (code behind): /  / <[link]
- **self**: > Turn (almost) any Python command line program into a full GUI application with one line
- **self**: I am getting the vibe you're not interested at all. Just wondering what you're doing in Kotor.NET?
- **self**: if it's a dumb idea I might drop andastra to start helping with kotor.js 🙂
- **toolsmith**: Seems cool but also seems like you'll be backing yourself into a corner at anything remotely complex?
- **self**: That would be the tradeoff, finding the balance would be the strat
- **toolsmith**: My motivation/interest to work on Kotor.NET has been slowly waning
- **self**: Yeah that's the extreme left i defined here, the same problem with kubernetes/helm/hcl
- **toolsmith**: Especially with all thr progress on k.js and reverse engineering
- **self**: How is that possible
- **self**: it's been totally opposite for me.
- **toolsmith**: I've been half tempted to start helping with k.js
- **toolsmith**: But it's hard to get past that initial hump stopping me
- **self**: Kotor.NET would benefit us all in the long run. Don't doubt yourself man!
- **toolsmith**: Don't really see how?
- **self**: .NET is great for backends, tooling is amazing because dotnet runtime has almost seamless release/publishing […]

Moves: `states_hypothesis`, `concrete_referent`, `invites_pushback`, `pushes_entrenched`, `offers_out`, `probe_expert`, `meta_style`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-064: proposes an lsp so modders can use vs code; partner: 'oh fuck no, i dread vs code', uses visual studio; 'you're just afraid of change'; 'you don't seem to understand anything past vs code no'; partner: 'i don't understand the point you're trying to make, if any?'; ai as his gateway to knowledge ('i was the kid that always asked why') (toolsmith, escalated, quality 4)

- **self**: […] more specifically could be ran on [link]
- **self**: as in, modders will use *that* instead of the shittier frontend we make
- **toolsmith**: Oh fuck no
- **self**: Also that would allow them to use Copilot to mod. which would be disgustingly broken (as in stupidly op)
- **toolsmith**: I mean your welcome to do that if you want
- **toolsmith**: I absolutely dread vs code though
- **self**: What the fuck else is there? you just shit on vim and emacs
- **toolsmith**: You lost me
- **self**: Didn't mean that aggressively just genuinely confused what ide you use for .net if not microsoft's
- **toolsmith**: Visual studio?
- **toolsmith**: Im lost on if your talking about tool development, or end users modding though
- **toolsmith**: This implied that lattter
- **toolsmith**: But this doesn't?
- **self**: - The intent was to let modders use vs code which i thought was a great ide / - You said you hate it / - Given i don't know how else anyone can even code in .net i wondered what you use
- **self**: there's no shot you use visual studio the bulky thing from 2022...
- **self**: wait really?
- **self**: I have 32gb of ram and even that isn't enough to run that on most days lol
- **toolsmith**: Uh yeah. Forgive me for not wanting to install 91747 extensions to get it to work thre way I want to
- **toolsmith**: Lol
- **self**: Brother I have 5
- **self**: wat
- **self**: Nah that's wild haha
- **toolsmith**: I much prefer vs ux over vsc
- **toolsmith**: But that's a me thing
- **self**: But yeah we already have a frontend regardless it's gucci. A language server would allow one to alternatively use it with whatever editor they want however
- **self**: even eMacs
- **self**: brb my cat's going nuts
- **toolsmith**: Are you talking about editing nwscript or the whole toolset
- **toolsmith**: Also vs2022 is taking 500mb memory vs vsc taking 1400mb rn for me lol
- **self**: Ah you're right. But it's larger, and takes ages to open anything […]

Moves: `states_stance`, `escalates`, `pushes_entrenched`, `meta_style`, `self_corrects`, `asks_clarifying`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-065: funding.yml / openkotor org dispute: 'nobody will explain what i did wrong', 'please explain?'; partner: 'no offence, based on what i read you are in the wrong', 'you monetised his work without greenlight', 'it's the principle'; 'i probably am!'; 'how do i align if the guy won't post guidelines' (toolsmith, escalated, quality 4)

- **toolsmith**: […] End up creating too much friction otherwise
- **self**: nobody will explain what I did wrong
- **self**: Why do my posts keep getting deleted
- **self**: I spent so much time writing those up and I wanted input
- **self**: But no I think DESPITE ME LITERALLY CREATING THE FUCKING ORG [partner] thought it was within his right to set me to Member
- **self**: so I’m no longer an admin
- **self**: Actually such brainless thinking to stand in the way of the ONLY GUY MAKING PROGRESS OUT HERE
- **toolsmith**: From what I can see you did link to a patron though? I can 100% see why [partner] got upset
- **self**: Please explain?
- **self**: he has full push access why doesn’t he just remove FUNDING.yml himself?
- **self**: He instead went to [partner]
- **toolsmith**: You monetised his work without greenlight from him
- **self**: And has the gall to say I DONT HAVE CONFLICT RESOLUTION SKILLS. Dude actually pansied out of a conversation that him and I could have easily resolved. One fucking file…
- **self**: I don’t get it
- **toolsmith**: Pretty sure it's the principle of it. Doesn't matter that he could reverse what you did. You still did it.
- **self**: Right but I didn’t get responses last time. He says he responded and he pinged me. But [partner] DELETED THE THREAD
- **self**: so I didn’t even *see* that
- **self**: More or less I’m so tired of asking for permission to do anything around here it feels like I need to ask to upload a fucking sticker or gif
- **self**: Which he made fun of me for doing!
- **toolsmith**: Probably sounds like that conversation should be kept in  / A) dms / B) admin only
- **self**: which it was
- **self**: He escalated to [partner]!
- **self**: I called him out on that too and he won’t apologize.
- **self**: So whole day it felt like everyone is against me
- **self**: We literally could have resolved that so easily
- **self**: He LITERALLY HAS PERMS to fix it himself
- **self**: just delete FUNDING.yml
- **self**: WHICH I TOLD HIM ABOUT
- **toolsmith**: Again that doesn't matter
- **self**: THAT WAS THE FIRST THING I TOLD HIM. ‘My bad the anger feels unwarranted. You can just delete funding.yml there’s no need to escalate. I can do it when I’m on my pc next’ […]

Moves: `demands_evidence`, `escalates`, `pushes_entrenched`, `concedes_point`, `meta_style`, `asks_clarifying`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-067: fork + donations dispute continued: 'explain how i'm the asshole when overall utility is benevolent'; partner: 'copium', 'you have shifted the goal posts', 'a) someone asked you not to b) you did it anyway — it's really not that hard'; 'explain clearly and exhaustively... oh yeah you're not ai, you're lazy'; partner ends with partial apology (toolsmith, escalated, quality 4)

- **self**: […] Cook with another’s food.
- **self**: Why else is it open source?
- **self**: am I not allowed to fork it and do stuff with it? 💀
- **self**: they publicly deleted the fork before I even had a chance to look at [partner]’s issue at my computer. Still haven’t logged in today
- **self**: But he literally complained about one file
- **self**: Three lines in one file
- **self**: Did he really have to delete the whole fork? I spent a bit of time on it and now I don’t even have access anymore
- **toolsmith**: Again you are completely missing the point. You forked it, then started setting up the infrastructure for donations after [partner] explicitly said he did not want that.
- **toolsmith**: You keep minimising the issue by saying all you did was "change a few lines in a file".
- **self**: It’s no worries this is why I am going back to my Puritan roots so I can understand why. Through effort I’ll get there
- **self**: So how did I violate his open source license of <none> and why won’t he answer my question about that?
- **self**: it is hard to align to his wishes when he’s given me nothing to align to
- **toolsmith**: I mean i guess you didn't violate any license, but again that's beside the point
- **self**: My father was a Puritan and I’ve recently started to appreciate the simple mindedness a bit more. It gives me a simple way to finally interface with all of this communication confusion i have in the professional world. So those licenses kinda need to exist, and I take them seriously for sure. Going into this AI world the law is all we have in terms of ethicality otherwise it’d be argued ai steals everything. And they already lost that case afaict.
- **self**: I’m just embracing a new world one that I don’t have a say in 🤷‍♂️ if anything this is a learning opportunity for him to specify a license
- **self**: in that way I did him a favor
- **self**: I’d never say that to him because it’d make him angry
- **self**: but from a utilitarian standpoint, if a gaslighter did what I did to him and had BAD intentions things would have been a lot uglier especially if they DID make money off of it
- **self**: So in that way I just prevented a disaster. 🤷‍♂️. Overall utility is benevolent and positive. Light side points have been earned.
- **self**: TLDR; use AGPL to avoid the SaaS loophole of others selling your work.
- **self**: And if you don’t want AI to steal your work, swap to codeberg
- **self**: explain how I’m the asshole when overall utility is benevolent and good.
- **self**: this is an important lesson for him to learn. Because not all people are kind. I’ve learnt the hard way. But he didn’t have to treat me like a jerk. All I did was point out a problem. I offered to remove it and he went to [partner] over my head to remove my permissions on the org
- **self**: The org I literally created and let him rename
- **self**: the same org I spent 20-30 hours on this week streamlining all the settings on while I multitasked that wasm thing while also multitasking the discord bot stuff.
- **self**: so in all I had a pretty productive weekend and I managed to teach too. Just sucks I have to pay the price
- **self**: no I’m not insane I totally get why he’s virtue signaling. I’m just through pretending like I need to conform and he’s right when I know for a fact I triple checked my math already on everything I just said. Look up the character House M.D. for example he is a benevolent guy that cares about people and helps them grow. Everything a role model should be going into this ai craze. As EVERYONE is scared. I make mistakes so people can protect themselves from true horrors
- **self**: And that will be my contribution I guess
- **toolsmith**: Sounds like a whole load of copium
- **self**: Maybe. But that was my thinking going into it. I have timestamps to prove it 😉 and if [partner] didn’t delete my thread I’d have whole ass facts […]

Moves: `states_stance`, `pushes_entrenched`, `demands_evidence`, `escalates`, `meta_style`, `analogy`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-069: probing a 10-year veteran on how kotor rooms/walkmeshes stitch (his indoor-map builder is '99% there'); why odyssey diverged from aurora — 'you don't reinvent the wheel unless you have to'; 'it sounds like i'm wrong, i'm not denying you that — just your pieces aren't fitting together'; corrected that bioware, not lucasarts, built it (community-member, redirected, quality 5)

- **community-member**: […] The size of the room is part of the mdl file
- **community-member**: The position is in the lyt file
- **self**: What’s the purpose of the door hooks exactly?
- **community-member**: WOK and MDL scales will have to match as well or they won't fit together right
- **community-member**: I think it was for the toolset
- **community-member**: The games doesn't use those as far as I know
- **self**: what exactly are aabb/bwm and what do they relate to walkmeshes (wok/pwk/dwk)? like i understand parts of the answer but not the full ‘eureka’ lol
- **self**: [link]
- **self**: my team has looked through most of the open source projects, taken the whole game apart in ghidra, and you still seem to have more answers than we could realistically figure out
- **community-member**: AABB is axis aligned bounding box. Do you know what a octree is? I believe it's that.  /  / I've always thought that BWM stood for bioware walkmesh
- **self**: No joke one guy reversed the entire thing, naming and documenting each and every function in swkotor, over a two year period.
- **self**: Had zero idea.
- **self**: I would like you to read the conversation. Not that you’ll have the eureka. But to understand the problem. Would you mind? Should only be about 10 messages or so
- **self**: You already a member of the discord?
- **community-member**: I've been working on this for 10 years and have been in the modding scene since it came out lol
- **self**: TEN years?
- **community-member**: Which discord?
- **community-member**: Yeah on KotOR.js
- **self**: [link]
- **self**: Start of the convo is [link]
- **self**: I feel like I’m a novice mage standing in the presence of Gandalf lol
- **self**: bringing him into this I mean
- **self**: Huh some of the convo is in another channel
- **self**: [link]
- **self**: Okay much of your messages somewhat make sense as to why kotormax is suggested
- **self**: While I understand 3ds max is a good way to achieve the desired results what I’d like to have is a full mental understanding of what’s going on on the lowest level. 3dsmax, kaurora, kotormax, all of that is closed source 🙁
- **self**: I have no idea why I said this at the time.
- **self**: Maybe everyone else are the insane ones
- **community-member**: Maybe we can jump on voice coms tomorrow or something it's a lot to type out
- **self**: the warp point seems to be desynced. but it does seem to be a consistent linear offset that each component is skewed by, which implies it should be possible to deterministically do this in pure code, instead of manually editing the boundaries/coordinates/points/etc in the kits. / i seriously respect all the time and effort [partner] put into this especially the kits. Each one created from scratch. / But my theory is the game developers did not manually create kits for each level... they had a level editor, similar to this indoor map builder (like it must have been two dimensional based on puzzle pieces that you can drag in, rather than a 3d implementation). / this by far is the most complica […] […]

Moves: `probe_expert`, `states_hypothesis`, `concrete_referent`, `pushes_entrenched`, `admits_ignorance`, `invites_pushback`, `concedes_point`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-073: github sponsors on the org: partner 'you are trying to make money off it? how do other re projects navigate ip lawyers?'; 'expecting a c&d is paranoid'; partner: 'your donation idea will trigger a c&d long before asset-transfer'; 'sometimes i wonder if i was born with a permanent foot in my mouth'; 'to reciprocate on the push back...' (community-member, escalated, quality 4)

- **self**: […] Bruh
- **self**: Started a call that lasted 0 minutes.
- **self**: you're hiliarious
- **self**: brb
- **community-member**: I'm on another call with some friends rn
- **self**: that question i don't want to point awareness on but lol i think peoplpe are just blatantly ripping and sharing the assets/resources around with each other regardless of if they've bought the game or not. /  /  / We just assume they have bought it and would never have reason to assume otherwise.
- **self**: ah you know my blunt/straightforward communication style did not help me here
- **self**: you think we're coasting on ambiguity rn?
- **community-member**: I don't understand the question
- **self**: Yeah lemme clarify. I'm about to reply to your message with this: /  / > sorry that was a bit ambiguous. You're saying you *don't* want to discuss the topic of allowing the community to donate to our open source projects? Or you *don't* want to **regulate the #🧵asset-transfer channel**. / >  / > Way you wrote it is kinda ambiguous.
- **self**: Conversation kinda got away from me.
- **self**: Expecting a C&D and worrying about it imo is somewhat... paranoid, i think.
- **community-member**: I don't want to regulate
- **self**: i hate politics
- **community-member**: I think your donation idea will trigger a C&D long before the asset transfer stuff will
- **community-member**: that is my opinion
- **self**: no ok you're not following the dots that's my bad though i explained poorly. /  / Worst case scenario (low probability of happening): / - Accepting donations triggers awareness from Disney / - They look for things to 'get' us on. #asset-transfer falls under that category.  / - I immediately jumped to that last point to get ahead of the topic. I raelize now that added more confusion
- **self**: but basically the longer these conversations focus on legality/ethicality/C&D the more paranoid everyone will be about any progress/awareness in general. /  / we should take a stance. That was what the whole re group chat was about. I don't like C&D/legality being brought up every 5 minutes personally. Are you worried about that? and if so why?
- **self**: I don't personally understand why it's a concern. There are **dozens** of other engine rewrites and communities out there that *do* accept donations, and generally garner community involvement in whatever way they intend to contribute. /  / Many people do join with stuff like this: [link] /  / or saying '
- **self**: 'i don't have much dev experience i wish i could contribute some other way'
- **self**: Yeah that's my bad man I wasn't even **THINKING** about the first damn response being the question of ethics/legality
- **self**: because it's not illegal/unethical. Lol. /  / Sometimes I wonder if I was born with a permanent foot in my mouth
- **community-member**: You may not like it, but it's a reality of our chosen passion projects. I don't lose sleep over it, but I don't try to go head first into triggering one if I can help it. But my main question still stands. Why are you looking to accept donations in the first place?
- **community-member**: I think that is a bit harsh on yourself
- **community-member**: you are only trying to help
- **community-member**: But it doesn't mean I won't push back if I see an issue
- **self**: To reciprocate on the push back, I won't fail to point out potential flaws with your strategies if I believe them to be a hinderance overall. I don't push back yet. I wonder if there *is* an issue with jumping straight to a legality/ethicality/C&D topic so often. The users of our discord are currently being given exposure therapy of expecting it at this point, basically Pavlov lol. /  / That is why I did the april fool's joke, to loosen people up a bit and remember to have fun with it. Since nobody intends on doing anything illegal. [link] /  / We've been pretty smart so far.
- **self**: Yeah even during my mania last week on those new meds I looked back and I still remembered to send a 'if theres any issues on my account please remove the admin role from my account as we see fit'. /  / Yeah that could have been worse for sure lol. Basically just adjusting to a new SSRI (anti anxiety). had no idea how my body would react to it 😄 /  / Looks like I simply acted like an overzealous/energetic dumbass for awhile and mostly embarrassed myself more than I did cause any harm to the community. /  / Anyway my point is everyone here is responsible lol. /  / Perhaps the **first** step would be only putting **sponsored** status on **SOME** repositories. And maybe not pointing TOO much at […]
- **self**: it shouldn't be advertised. It should be something that's requested.
- **self**: [link] delete this message if you want 🤣 /  / > why do I send you messages like this? /  / I'm aware i'm up-front no nonsense and loud/overzealous. Removing my messages may make the information and demeanor I bring more tolerable. /  / I'm just not sure how blatant I want to be about the annoyance with legality/ethicality lol. The wishy/washy stuff inhibits progress :/ […]

Moves: `states_stance`, `pushes_entrenched`, `analogy`, `self_corrects`, `meta_style`, `asks_clarifying`, `offers_out`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-074: huggingface mirror of the org: 'why did you clone the site?' → 'does that bother you? just feels like such an attack'; partner: 'you're moving fast and making decisions without checking in'; 'i think you see anything on the surface web as a threat — allow me to guess'; partner's diagnosis: 'you ask why, people answer, you don't like the answer, you rephrase... cycle repeats', 'i have to wait until you stop responding'; 'i like to understand people's positions. maybe they know something i don't. i fail to understand why this is a bad trait' (community-member, dropped, quality 5)

- **community-member**: […] By "this", do you mean the huggingface stuff?
- **self**: Yeah well I guess I want an understanding. / - Why did you reach out? / - What was going through your head? / - Why *this* change instead of another change. Like you didn't mention the discord emoji I added or anything. Or the discord bots I've been putting together.
- **self**: Allow me to guess
- **self**: I think you see anything on the surface web as a threat/liability
- **self**: so what you're wanting is to somewhat centralize and deliberate about our public image
- **self**: but honestly this was so much of an annoyance to me i'll probably just use OldRepublicDevs and if you ever want to merge you can reach out. That'd be more efficient.
- **self**: Thoughts? Does that solve the problems I was creating?
- **self**: Look it's like, I check in, I feel like a dick for posting so much requests.
- **self**: And people tell me 'stop posting so much'
- **self**: So I try to do things. Harmless things. And it's all 'wizard stop doing things without checking in' lol.
- **self**: it's not my fault you guys have full time jobs and/or i like doing this more than y'all. Been like a week since [partner] responded to anything and idk even where [partner]/[partner] went 😂. /  / All this to say sorry 🤷 i'll stop using the openkotor name didn't mean to start an issue. Thought you'd welcome it seeing how much github is turning a large group of repositories for ***'train-your-ai-here-off-our-codebases!'*** lol. I think [partner] is using [link]
- **self**: anyway do you want this huggingface group to be removed/my messages removed or what? you got kinda quiet on me. Lmao
- **self**: I don't know what you want from me sry. reread if you need clarification on where i'm coming from 🤷
- **community-member**: I have to wait until you stop responding, if not we go in circles
- **community-member**: I'm not telling you to leave or start your own thing.
- **community-member**: I didn't know you made this, but I think it's cool and I'm glad you did that
- **self**: good because i wasn't offering to leave either
- **self**: Don't know where that came from
- **community-member**: this, maybe i miss read it
- **community-member**: That is not the issue with the huggingface thing. You cloned the site there and I was trying to find out why. I think it's cool that you want to work with others and use huggingface.
- **self**: Fill this out lol? might be easier than whatever we're doing here.
- **self**: i'm not really expecting you to that would be hilarious. But I definitely have a few projects I want to use something like this for lol.
- **community-member**: i'll take a look at it
- **self**: i use ai because i clearly have a communication issue and nobody reads what I write anyway. I just assumed summarizing my information with ai would be appreciated 🤷
- **community-member**: It is not helping buddy
- **community-member**: I don't think you listen as well as you think you do
- **self**: I feel the same way about literally all of this
- **community-member**: You ask "why", pleople answer, you don't like the asnwer, you rephrase and respond with I must not have been clear... cycle repeats
- **self**: Most is still unresponded to. I mean it's a two way street. This conversation just isn't constructive. I'm not trying to start problems either.
- **self**: Example? […]

Moves: `escalates`, `demands_evidence`, `states_hypothesis`, `pushes_entrenched`, `meta_style`, `apologizes`, `offers_out`, `concrete_referent`

Why it worked or failed: Escalation plus meta-commentary about the debate itself outran the evidence; the partner stopped responding.

### r-076: first contact with the exe-patching re developer: 'why not help with the rewrite engines instead of duct-taping the old buggy engine'; 'exe patches add complexity i'm not convinced is necessary'; 'you have a good reason for being so openly against it?'; 'unless you can prove you can do x, y, z... my stance always involves respecting anyone who can prove me wrong'; 'much of this is contradictory'; 'zero reason to hardcode addresses except laziness'; partner: 'optimality and efficiency aren't important to me, i'm in it for fun' (engine-developer, redirected, quality 5)

- **engine-developer**: […] But yeah, I'll take time to review a lot of the things you've done, and perhaps I can share more specific questions then 😆
- **self**: Why not help with the rewrite engines instead of duct taping the old buggy engine
- **self**: exe level patches introduces a level of complexity I’m not convinced is necessary or viable. I already think even the widescreen + 4gb patches are too much. What you should do is hook in a DLL that lets users create their own code caves
- **self**: back when I was doing client-side modifications we created [link] for that exact reason. Too many game-level memory modifications conflict in convoluted ways
- **self**: Maybe you have addressed these issues already in kotor-patch-manager I’m sorry I still haven’t had a chance to read most of this
- **self**: Especially when a readme isn’t even written
- **engine-developer**: It is a DLL injection scheme! I share some of your thoughts there. Compatibility was a major concern when it came to the design here. Each patch is injected and applied via DLL at run time. While I do allow for simple byte-level patches, most of it does live in allocated executable blocks or code caves. /  / Yeah, been meaning to get around to that readme 😅. Been rather busy lately. Sorry about that
- **engine-developer**: As far as engine rewrites go, I guess that's just not a particularly interesting problem to me.  / I like reverse engineering and working with assembly, and doing clever things with what we've got. / Like I see the arguments for the alternative, but this is just what I think is fun
- **self**: It does seem like a lot of our goals are aligned
- **engine-developer**: I agree
- **self**: Your biggest problem if you want users using it will be intuitive design and reduced friction. I’m not convinced exe level patches won’t steepen accessibility requirements and add unnecessary complication. Many users e.g. proton require much of the engine to remain vanilla. You’d need to look at mesa and its gl library/workarounds for the engine or you’d be alienating 80% of the platforms for example
- **self**: Many users are hardened to how kotor modding has always been and are reluctant to try new things, hence why holopatcher intends to reuse TSLPatcher specifications. If you already have 2da level patches and other stuff done it’d be a large benefit to include tslpatcher’s changes.ini specifications. Using ai I recently ported most of it here last weekend: <[link] one of the largest problems I’ve been working with is the inability to reuse other projects and garner collaboration, mainly do to the programming language used. Something like Kaitai struct would solve that problem. A base library for most things Kotor would be a huge help
- **self**: Kaitai is a way to define binary structures and compile to dozens of language including but not limited to go/python/c/c#/typescript
- **self**: I’m sure there’s a better alternative to Kaitai struct, unfortunately haven’t had much time to look into it. But general accessibility level requirements for developing for kotor at this time is steep and usually involves reinventing the wheel at some level. My goals are to change/improve this somewhat
- **self**: Engine rewrites solve the alienation problem and improve accessibility and they also garner popularity in general. You have a good reason for being so openly against it? At the very least it’d help understand the engine you’re reversing
- **self**: 2.5 years is a long time to devote to reversing a game engine for memory modification at the DLL level is all I’m saying.
- **self**: Optimality and efficiency are important to me. I’m a fullstack developer in my day job and the amount of time I can devote to kotor projects isn’t as much as it was unfortunately [link]
- **self**: Came across this in passing and thought it may interest you: [link]
- **self**: > Lest I create a framework nobody uses /  / Many people do recreate the wheel due to a lack of a base lib which I was addressing earlier.
- **self**: But yeah I just believe the 20 year old engine isn’t worth the manpower required to delay its future funeral. Unless you can prove you can do things such as: / - increase the party cap count and the total amount of characters that can be brought with a companion / - embed the game to be played directly from a website / - introduce many of nvidia’s improvements or a translation lib for directx / - solve the dialog skip bug plagueing users in the second game /  / I currently don’t think (some of) the directions you’re going is optimal. In general, my stance always involves respecting anyone who can prove me wrong in any topic of theory (learning opportunity for me) :).
- **self**: I was pretty vague earlier but what I meant was ideally these should be hand in hand since the same reversing process is required for both
- **engine-developer**: Just catching up on all of this. /  / I don't have a particular aversion to engine re-writes in general. They just don't interest me from a hobby point of view. That may change at some point, but the fact of the mater is "optimality and efficiency" aren't particularly important to me. At least when it comes to this hobby. I'm mostly in it because I think it's fun, and I enjoy tinkering with these sorts of things. Of course if anyone wants to make use of any of the products of my RE work in their projects, whatever they may be, I am of course happen to share and answer questions. /  / I do think there is an audience for exe level patching, even if it may not be the most efficient nor most acc […]
- **self**: Lmao that xkcd is gold
- **self**: Much of this is contradictory. You either can do what you enjoy and like doing, tinkering around, or you can do what the community will be happy to be involved with. And if you feel you could do both maybe create a repo to hold some inner secrets of the engine so rewrites can use as reference. That’d be optimal and get me on board, furthering some of your projects goals too. Guess I’m saying the xkcd isn’t entirely accurate
- **self**: I’ve checked out your RE briefly but not fully for all that stuff you commented for the gog exe
- **self**: Signature based patching at very least would be optimal. Zero reason whatsoever to hardcode addresses except out of laziness. That way k2 developers could contribute, too
- **self**: [link]
- **self**: Kaitai can generate real code for plethora of languages. So I’m not understanding how that xkcd is relevant. It doesn’t create another standard. For example if someone wants Python code they run the Kaitai compiler and they get Python code that they can modify further to their hearts content. /  / Though to be fair i'm not entirely certain Kaitai is the most maintained/best project to use to achieve kaitai's goals. Is that exactly what you meant earlier with the xkcd comic?
- **self**: [link]
- **self**: I wrote you a readme. Let me know if it helps or if I can improve it at all 👍 . […]

Moves: `states_stance`, `pushes_entrenched`, `demands_evidence`, `invites_pushback`, `escalates`, `concrete_referent`, `apologizes`, `meta_style`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-079: tsl dialog-skip bug: his 'tick counter goes negative from a memory leak' theory vs the speedrun community's 'fast text' evidence (missing sound files, predictable timing); 'this has a lot more tangible proof than my theory'; 'damn adhd skimming' (engine-developer, conceded, quality 4)

- **self**: TSL has a dialog skipping bug that happens when the event tick time counter gets set to 0 or a negative number due to a memory leak. It happens randomly after prolonged playtime. /  / Originally I specified something like *if someone hits dialogue skip early they have an unfair advantage*. Basically any unskippable dialogue is immediately skipped regardless when it happens. That'd shave literal minutes
- **self**: Also, finding this and patching it would solve the largest complaints in tsl to date i imagine
- **self**: We're talking hundreds of lines of dialogues skipping through in a blink of an eye lol
- **self**: Only way to resolve it as a normal player is simply restart the game..
- **engine-developer**: We're aware of this, in the community it's called "Fast Text" /  / This is prevented by requiring the user to reset their game between each run. We find that fast text happens after a predictable period of time (in both games in fact)
- **self**: whattt
- **engine-developer**: We've also discovered methods in kotor 1 to intentionally trigger Fast Text wherever we like
- **self**: whattttttt
- **self**: that's crazy man haha
- **self**: is this documented anywhere?
- **engine-developer**: [link]
- **self**: Fast text is an acceptable idiom. whoever coined that is acceptable
- **engine-developer**: Some person on SDA forums back in like 2008 coined the term
- **engine-developer**: That link is for forcing it to occur, I think we have a wwrite up about the general glitch elsewhere
- **self**: > Fast Text is a glitch in KotOR in which the sound files for conversations are not properly loaded, making all dialog in conversations advance instantly with the exception of user-chosen dialog options. While Fast Text happens naturally as memory usage increases, it can also be forced with an application of AMG as follows: / Seems different than what I reverse engineered. My findings says a timer tick rate that's defined as 60000 is incorrectly overflowed and treated as a negative number (effectively zero). Potentially I looked into this incorrectly though, until you've sent this i've had no real way to test it
- **self**: speedrunning community is op.
- **self**: I love this so much
- **engine-developer**: To be fair this was based on our assumptions /  / Because you'll notably get similar behavior if you delete an NPC's dialogue sound file
- **engine-developer**: It's possible we don't have the full picture
- **self**: is it possible it's different in tsl?
- **engine-developer**: Definitely
- **engine-developer**: oops wrong link
- **engine-developer**: [link]
- **self**: Figuring this out would be probably your biggest breakthrough as far as the community is concerned. This has been plaguing people for two decades in TSL.
- **self**: In my case, next would be crash after character creation 😂
- **engine-developer**: We have found that shortly after it occurs, music stops playing, and also textures start to break
- **self**: - <[link] / - <[link] /  / why are there two explanations for the same thing in different pages 🤦
- **self**: Oh I should read. Sorry about that
- **engine-developer**: haha all good, these guides are targetted for different rulesets. Fast Text is legal in glitchless because it's hard to prevent, but *Forced* Fast Text isn't
- **self**: I will say this has a lot more tangible proof than my theory about the tick rate counter does. […]

Moves: `states_hypothesis`, `concrete_referent`, `probe_expert`, `concedes_point`, `apologizes`, `meta_style`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-080: bottom-up learning vs reading docs: 'is this bad practice? how could i find a middle ground'; partner (ex-teacher): 'learning styles are kinda a myth, you have to learn how to learn'; 'what makes you think this? i promise to contemplate objectively'; 'ai is a workload optimizer — for the same reason you use ghidra instead of hex dumps; the only difference is where one draws the line' (engine-developer, redirected, quality 5)

- **self**: Yes. I'm a bottom up learner unfortunately.
- **self**: Like for example, instead of reading cloudflare's api documentation (thousands of pages) I jump in knowing nothing and skim to find what i'm looking for.  /  / is this bad practice generally? if so how could i find some sort of middle ground i wonder
- **self**: also: /  / - Walkmesh Visualizer by glasnonck /  / this small project saved my bacon in multiple scenarios over the last few months 🙂
- **engine-developer**: Yeah that's tough / I've got a CS degree and used to teach, so I'm pretty used to reading some dense documents. But I understand not everyone learns well that way. /  / How are you when it comes to videos? I do have a bunch of stuff on my channel, but it doesn't cover all of this.  /  / We're also happy to answer questions in our Discord if you prefer learning via dialog. We're just trying to provide a few different avenues
- **engine-developer**: Yeah this was a fun one that Glas and I worked on
- **self**: Can't stand videos either, really...
- **self**: I've found the best way to learn/do anything is to just start doing it, and research/learn from hurdles I jump over. /  / I'm painfully aware the world doesn't teach like this generally.
- **self**: Without oversharing, yes I'm diagnosed ADHD. Has caused more problems as I go into adulthood rather than 'sitting still in school' stigmas that are implemented there. /  / I simply struggle to pay attention to things unless it's immediately relevant and important to something i'm *doing*.
- **self**: AABBs cause you any trouble...?
- **self**: Took me three full days to figure out.
- **self**: Well technically I was also doing DWK/PWK/WOK/BWM/AABB and the LYT components.
- **engine-developer**: Yeah I can understand that / I will say that, in my experience from teaching, that "learning styles" are kinda a myth. /  / The truth of the matter is you have to *learn* how to learn, which a lot of schools are not good at doing for students. And the practice required can also be VERY frustrating /  / As far as ADHD goes, I can't quite speak to that msyelf though I've had friends that have managed to be pretty successful with various coping methodologies (Medication, using music, other techniques). I'm no expert there though, so I'd defer to expert opinions
- **engine-developer**: Kinda, we mostly ignored them for the sake of the project
- **self**: > The truth of the matter is you have to learn how to learn, which a lot of schools are not good at doing for students. And the practice required can also be VERY frustrating / God this sounds so painfully obvious when you phrase it like this. Not sure what I was doing but it did sound innate on some level.
- **self**: AABBs are mostly there for optimization purposes anyway.
- **self**: BWM I mean.
- **engine-developer**: Yeah, the visualizer could definitely use some optimization. But for our use case, just exhaustively searching all the triangles did the trick lol
- **engine-developer**: Like if you ever try to load the dune sea in teh visualizer that will be painfully obvious 😛
- **self**: > I will say that, in my experience from teaching, that "learning styles" are kinda a myth. / What makes you think this btw? I promise to contemplate objectively, I've seen this before but I've always dismissed it as neurotypical oversimplification of the brain's active processes.
- **self**: Generally don't like making excuses for myself. To be candid the amount of AI summarization's i've been relying on lately hasn't been something I'm proud of when I hadn't been this dependent previously. So figuring this out would help that problem out significantly, going into 2026 🙂
- **self**: Many articles exist about how ai is apparently ruining our attention spans. Which is somewhat obvious. Large amount of respect for you reverse engineering much of this swkotor.exe without such workflow optimizations
- **engine-developer**: Well I suppose the "kinda" in that phrase is doing some heavy lifting / Like people definitely see differing results with things like doing/listening/reading etc, but It's been my experience that this is more of a "nurture" experience than "nature".  /  / And of course all of this does have the neurotypical assumption as you mentioned. Which is a valid call-out.
- **engine-developer**: Yeah the cognitive off-loading with AI is something I do a TON at work, but hardly at all in my hobbies.
- **engine-developer**: The way I think about it is my hobbies are something that *I* want to do, so I should do them instead of the AI. Whereas work is for putting food on the table, so I focus more on outcomes there
- **engine-developer**: But yeah, as far as getting better at learning, the only real answer I have there is to practice. Try to force yourself to read/watch more, and check your own comprehension after the fact. /  / I'll warn you that this process *sucks*, and can be really painful. But like any other skill you'll get better with time.
- **self**: Okay but there's a balance. AI is just a workload optimizer, allowing one to focus on the stuff they *actually* enjoy.
- **self**: What I don't like doing is browsing 10,000 pages of documentation to find one thing.
- **self**: for example, when setting up my k8s cluster for <[link]
- **self**: For the same reason, you use ghidra. You could just disassemble manually and translate hex dumps yourself otherwise, ghidra is already cognitively off-loading much things.
- **self**: So strictly speaking the only difference is where one chooses to draw the line. […]

Moves: `states_stance`, `invites_pushback`, `probe_expert`, `analogy`, `meta_style`, `concedes_point`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-081: could the ghidra labels become debug symbols / recompile the decomp? 'i can't think of any reason it wouldn't recompile into identical assembly'; why not just move the glxymap struct to bigger memory? partner: hardcoded struct offsets everywhere; wizard restates until 'exactly 💯' (engine-developer, conceded, quality 4)

- **self**: Dumb question but given you have all the functions documented and commented and signatures setup properly, how difficult would it be to get debug symbols out of this?
- **self**: lol
- **engine-developer**: Well I guess that depends what you mean by "debug symbols" / Also I don't have everything commented, just labeled. Rich descriptions would be a great deal more work (not to say I don't plan to at some point when I'm like 50 years old 😆 )
- **engine-developer**: But yeah, I suppose you could rig together a fake PDB for the exe and let existing debuggers mount it. Though I haven't really researched/experimented at all in this regard
- **self**: Something I could load into visual studio, attach to swkotor.exe, and be able to breakpoint at specific functions or code i suppose? or at least have basic c/c++ ide functionality like 'find references'
- **self**: Ah I see.
- **engine-developer**: Hmmm, maybe? / I know that Ghidra has a debugger as well (though I haven't gotten it to work) /  / I do often use Cheat Engine as a debugger, and just have Ghidra on a second monitor to pick out breakpoint spots and such
- **engine-developer**: Though I suppose if we REALLY wanted to go to the next level, we could dump the entire decomp as C-Source, and then just go through the hell that would be getting it to recompile back into an identical EXE. Haha
- **self**: I can't think of any reason it wouldn't recompile into identical assembly though? Compiler optimizations are already implicit in the decompiled code.  I'd assume that the msvc version would be the only variable...?
- **self**: if you're trying to repack and re-encrypt the drm i don't think that would be possible to get a sha256 match to the original though. I briefly played around with that (wrote an unpacker and a decrypter that'll turn a steam swkotor.exe into a gog swkotor.exe, but it never would idempotently match 1:1 in roundtrip  fashion)
- **self**: i imagine a bunch of issues would pop up as you said. I'm not familiar with c/c++'s compiler that well, but the 'thunk' functions would be a potential pain
- **self**: Not sure why the c/c++ compiler seemingly arbitrarily just creates functions that do nothing except jump to another function. I believe that's what a thunk is anyway
- **engine-developer**: So in-theory, yeah it would just work.  / In practice, the code that ghidra generates can be quite messy, and often has issues compiling at all. I was listening to some dev logs from teh fellas that fully decompiled Lego Island with Ghidra (a much smaller game than kotor), and they went through hell to get to 99% accuracy.
- **engine-developer**: Yeah that's pretty much what a thunk is. They're often used for stack space managements and other black-magic optimizations these compilers rely on.
- **self**: I did want to talk about <[link] though. /  / Would it not be simpler to just migrate the `GlxyMap` struct somewhere where larger amounts of unallocated/unreferenced memory exists, so you could size it however large you'd like to? /  / What wasn't making sense to me is, if the struct is sized 0x10, and a bunch of code in various functions in the EXE utilizing the galaxy map struct are using a array.Length() call on that struct or something, couldn't you just update all references somewhat easily? or is that code not unified into a single function/potentially 0x10 is hardcoded in multiple places? That part wasn't clear, really, but in my experience when trying to resize structs like this I ne […]
- **self**: huh i don't know why that was such a mouthful. Basically: /  / ```c /  / struct GlxyMap { /   // ... / } /  / void fun_00342457 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / int fun_00324357 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / void fun_0039787 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / void fun_00323427 { /     GlxyMap* x = load(); /     int total_rows = x.Length(); / } /  / ```
- **self**: or is it actually more like dozens of functions under the sun are hardcoding the size 0x10
- **engine-developer**: So you kinda summarize the problem. When a property of an object is access in C++, let's say property at `0x1c`, the compiler will interpret that as referencing the object's pointer + `0x1c`. And this will appear hardcoded all over. /  / Arbitrarily resizing a structure like this requires a good deal of care not to trample over other offsets.
- **engine-developer**: Kinda, it's probably be easier to explain verbally than typing if you just want to call
- **self**: Actually this directly clarifies it
- **self**: But we could, i'd need to find a mic
- **engine-developer**: But yeah, so my solution for these kinda cases is usually to change the access pattern instead of the object allocation. /  / So for `available_planets`, what I've done (in my work-in-progress galaxy map patch), is everywhere this offset gets referenced as an inline `int[16]`, and instead have it referenced like an `int*` to an array I allocate elsewhere. That way I don't have to effect the offsets of the other fields in the same struct. /  / There's lot of different, well established, strategies for over coming this sort of thing though.
- **self**: Okay if I'm understanding correctly, the core issue seems to be that expanding a fixd-size array inside the struct (e.g. from 16 to a larger number) shifts all subsequent member offsets. Since compiled C++ code uses hardcoded offsets like `struct_ptr + 0x1C` for member access, this breaks every reference to later fields. So treating the `available_planets` field as an `int*` pointing to a separately allocated array, which would presumably be dynamically sized?
- **engine-developer**: Exactly 💯
- **self**: Probably worth mentioning the galaxy map itself is small, 16 would already be polluting the space
- **self**: The camera area in the room directly behind the galaxy map would be a good place to put extra planets/warps. Since this is a DLG.

Moves: `probe_expert`, `states_hypothesis`, `concrete_referent`, `asks_clarifying`, `concedes_point`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-082: how the devs built levels; 'why is documentation such wip despite you saying you like to write? expecting involvement? lacking motivation? not sure how to plan it?'; 'how is this not tslpatcher? or why can't it be?'; partner: 'not to directly refute you, but some people cared'; 'maybe i don't get out enough or i'm in my own world' (engine-developer, redirected, quality 4)

- **self**: Hey man how does all the game’s AABB/BWM/walkmeshes work, exactly? Why’s it so different from other games? And more importantly, how EXACTLY do you think the devs created all the levels in both games? Do you think they had a level editor or that they hand wrote all the models/walkmeshes? what do you think their tools looked like for level editing? You think they were manually aligning coordinates/planes/boundaries? just wondering why I can’t programmatically make them fit together in a way that makes sense, which implies they *were* manually packaged/bundled. like a human guessing and checking measurements in the game to avoid seams/alignment problems between doors and the walls for example, […]
- **self**: But thank you for this.. honestly good advice. Definitely feels like I should be able to figure it out
- **self**: Also the other day this clicked, as a great idea. Don’t remember why 🙂. validation/verification reasons I imagine?
- **self**: Could ask in a forum and ping you if you prefer
- **engine-developer**: They likley had a level editor. In fact I think it may have been an earlier version of the editor that get's distributed with 'The Witcher: Enhanced Edition', another Aurora based game. /  / As far as "how does it all work?" great question. I wish I knew. But I'm confident we'll get there. /  / I can't imagine that they manually aligned the coordinates. And didn't this get accomplished to some degree by the old-guard with gmax or something. TBH, I've never dug into modeling stuff too deeply with this game. So I don't have a  great sense of what is/isn't possible.
- **engine-developer**: I'm confused, what are you asking exactly?
- **self**: It’s my understanding the reason level editors exist in dragon age, the Witcher, jade empire, nwn etc is due to their tileset approach. Odyssey does something bizarrely different
- **engine-developer**: hmm, perhaps so. LIke I said, that area isn't really my forte
- **self**: Well I was asking if you had any plans to release this
- **self**: Apologies for the confusion
- **self**: Happy holidays, btw!
- **engine-developer**: So when you say "this", do you mean: / - The patching capabilities to call upon internal GFF functions? In which case, this has been released as a part of the patching framework, and patches can leverage these functions / - A tool for verifying GFF implementations using internal game functions? I have not put anything together for this, and don't currently have plans to. If you'd think it's be really useful, and can try to make some time for it. / - Wrapping BWM functionality in the patching framework and exposing capabiltiies there. I have not done this yet, but I absolutely plan to. As I think it would be useful, both for research purposes, but also in some patching.
- **engine-developer**: Though if you meant like a stand-alone GFF library using internal game functions. I don't currently have plans for that. But one could theorhetically create one quite easily using what I've done so far
- **self**: I think I’ve learned something new every single interaction I’ve had with you. This one being about how important exact specifics, and details, are in writing
- **self**: but the second point is what I’ve been asking about 🙂
- **engine-developer**: Gotcha, yeah it could be neat I suppose. I don't know how particularly useful it's be these days. Seeing as the GFF format is a pretty solved problem at this point. But I'd be happy to hear other opinions
- **self**: Verifying gff implementations with what the game does in its own loader would save me hours ~~penetrating~~ pentesting each toolset version in the game for various combinations of various values in various fields between gff  formats
- **engine-developer**: That is a fair argument haha
- **self**: Eh everytime I look at the functions ` readare` or `readutc` in pykotor I still think I’m missing a field, or something is incorrectly assumed to be default, or I have the wrong field type for a certain field.
- **self**: Basically the same problem KOTOR tool suffers from, which is why that tool isn’t safe to be used for editing, only extraction.
- **engine-developer**: Ah I see, so to be clear I've so far just wrapped the functionality for directly editing GFF files. I don't have any libraries regarding the validity of different labels/types for specific GFF derived formats (IFO, RES, ARE, UT*, etc). /  / Though I do know how to get those...
- **engine-developer**: The game hard codes basically all the valid labels for any given GFF typed file. So it's just a matter of digging through that object types respective "load" functionality to determine what is valid
- **self**: Why the f*ck did my iPhone think it was acceptable to replace the word *pen-testing* with *penetrating*
- **engine-developer**: The GFF implementation I've done so far for patching framework lives [here]([link] if you're curious
- **self**: Would implicit defaults (when a field isn’t specified) be all together in a single function or spaced out depending on context? For example the field ‘OldHitTest’ in DLG. Still don’t know what that one does haha
- **self**: A lot of the toolset just assumes a default is zero or -1 without any verification whatsoever
- **self**: You seem to be missing a gff field type (or two)
- **engine-developer**: Right so defaults are a part of the `Read` functions in the GFF api. For example, this is a snippet from function `CSWSCreature::LoadCreature`, which loads UTCs: / ``` /     iVar7 = CResGFF::ReadFieldINT(this_01,struct,"CreatureSize",(int *)&param_2,3); /     this->creature_size = iVar7; /     bVar4 = CResGFF::ReadFieldBYTE(this_01,struct,"IsDestroyable",(int *)&param_2,1); /     (this->object).is_destroyable = (uint)bVar4; /     bVar4 = CResGFF::ReadFieldBYTE(this_01,struct,"IsRaiseable",(int *)&param_2,1); /     (this->object).is_raiseable = (uint)bVar4; /     bVar4 = CResGFF::ReadFieldBYTE(this_01,struct,"DeadSelectable",(int *)&param_2,1); /     (this->object).dead_selectable = (uint)bVa […]
- **engine-developer**: I can check on that DLG field no problem
- **engine-developer**: Which ones? […]

Moves: `probe_expert`, `states_stance`, `pushes_entrenched`, `concrete_referent`, `self_corrects`, `offers_out`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-084: '700,000 lines of code says i've already done all this' (ai-decompiled engine); nodejs vs .net vs c/c++: 'what's wrong with nodejs/npm??', 'do we really care about micro optimizations c/c++ can do?', 'sorry for ranting, so damn tired of people posturing'; partner: ambivalent, 'sometimes people just feel they're supposed to have an opinion'; 'i'm not understanding whether you're saying people are posturing or complaining about real issues' (engine-developer, redirected, quality 4)

- **self**: […] But yes it does not currently run and I have zero clue why 😂
- **engine-developer**: I mean if it's proving useful, then I'm glad haha
- **self**: What I’m saying is I need a more exhaustive broken down  roadmap
- **self**: I think.
- **self**: as even my own isn’t working right now
- **self**: Just too much code lol
- **self**: I think testing various parts of the engine in modular parts would be useful, such as save serialization
- **self**: Not sure how to do as such with the engine loop.
- **engine-developer**: I did mess with Ghidra MCP a bit a few weeks ago, and honestly I found it to be a bit lack luster in feature quality. Definitely needs some iteration from teh developers side (whcih is a bit concerning as the original dev abandoned the project and the new dev hasn't been as active) /  / buyt I digress
- **self**: But yes awhile back you mentioned you don’t have interest in the engine rewrites. I still argue both should be worked on in tandem since it’s helpful collab for everyone as shown 😄
- **engine-developer**: So you've been saying this a lot, and I thought I understood what you meant, but now I'm wondering if I should just ask, what precisely do you mean by roadmap?
- **self**: Here is an existing project for another game that somewhat backs my point: [link]
- **self**: I must have read your mind
- **self**: lol
- **engine-developer**: Like my main goal with the reverse engineering work was first and foremost to provide a resource to other clever people in the kotor development scene. And I feel I have accomplished that. /  / Though there's still plenty more to be done, and new goals to come about
- **engine-developer**: But yeah, when you say "I want a roadmap". Are you just asking for an itemized chronological list of milestones for the patch manager project?
- **engine-developer**: Or somethign else
- **self**: Well i was vague because i am not sure what my next step is for Andastra specifically and was looking for some steps that’d benefit both of us
- **engine-developer**: I see
- **engine-developer**: My understadning is that Andastra is basically your Xoreos?
- **self**: I believe the correct term is spitballing. I apologize for being terrible at it.
- **self**: Yes!
- **engine-developer**: (insert snide comment about reinventing the wheel)
- **self**: There were a few reasons it was overall necessary
- **self**: Much of the community is working with .NET and I’m hoping that and its toolset will garner some more open collaboration
- **engine-developer**: .Net is pretty great for this kind of work
- **self**: Many people get turned off to JavaScript, c/c++, Python, it’s somewhat obnoxious how relevant that xkcd has been becoming
- **engine-developer**: I can understand being turned off by JS, though I personally don't mind C/C++ or python for that matter (privded the python makes liberal use of type-hinting and other best pratices)
- **engine-developer**: But yeah, that all makes sense
- **self**: explain the first part lol […]

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `apologizes`, `asks_clarifying`, `concrete_referent`, `meta_style`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-085: roadmap document review: 'i value utmost brutal honesty, be as mean as you want... don't feel obligated'; partner: 'scattered and unfocused, tries to be three documents at once'; 'ohh duh you're absolutely right'; 'do you ever hit diminishing returns in writing? how do you gauge good enough?' (80% rule); ai offloading in a hobby — 'i do like debating, i want to confirm i'm doing things healthily'; 'thanks gpt' / 'damn i've been called out' (engine-developer, conceded, quality 5)

- **self**: Could I possibly get you to proofread some writing I'm doing for the game?
- **self**: I'm about to drop a large, large roadmap for the future of the toolset and i want to verify my motivation is being understood and explained properly
- **self**: goal would be to revolutionize and reform the modding ecosystem but that may be a bit ambitious. Though given the amount of stuff I'm about to release I do think that's an accurate statement 🙂
- **engine-developer**: yeah I can give it a read
- **engine-developer**: How nit-picky do you want me to be?
- **self**: Bro i value utmost brutal honesty. You can be as mean as you want.
- **self**: But as much time/effort as you're willing to put in I guess?
- **self**: Also you're not going to believe this...
- **self**: but here's another developer's reaction
- **engine-developer**: Randall Munroe really is a modern philosopher
- **engine-developer**: I'll give it a read and list out some thoughts as I go
- **self**: Thanks man. I mean don't feel obligated if at all possible. Would prefer you to determine that yourself, based on your own interest levels
- **engine-developer**: [I ended up just dropping it in google docs and using the suggest feature to lay out my thoughts.]([link] /  / Take or leave any of my edits, and consider the comments as well
- **self**: Wow
- **engine-developer**: I hope I wasn't too harsh 😅
- **self**: well is it honest?
- **engine-developer**: I'll admit I gave the start more scrutiny than the end haha, I was getting a bit tired
- **self**: When I got into all this I was just annoyed researching a bunch of scattered integrations: things that provided pieces of a solution. Either with problems that I had to discover on my own that are so niche it's ridiculous or problems that are generally gatekept behind the veterens / so i'd like it to be more accessible to the next person that comes along like myself /  / I know 99% of the people I meet will not be that person. But that one person that comes along like myself will. And that's why I do it 🙂 /  / To that end i'd like pykotor (and potentially andastra in the coming future) be basically on the production level of comprehension for a  development SDK as if Bioware themselves were […]
- **self**: ^ that is my overall goal 😂 i don't know if the document is facilitating that or not
- **self**: How do I see your comments/reviews? So far I just see my writing.
- **engine-developer**: really? one sec
- **self**: I don't use 'bloodbath' or google docs so it's probably a button i'm not seeing
- **engine-developer**: I updated to just make the link an editor, refresh and check again
- **engine-developer**: it should just appear
- **engine-developer**: "bloodbath" is just a term for when a paper has a lot of errors or corrections, a reference to red pens typically used in academia
- **engine-developer**: Did that work?
- **self**: Oh you went full proofread/revision/editor on this
- **self**: Yeah my writing is terrible. I did not really need that focused on.
- **engine-developer**: haha, yeah it just kinda happened as I started workign through it
- **self**: Just the ideas and concepts as a whole I wanted advice on. […]

Moves: `invites_pushback`, `offers_out`, `concedes_point`, `probe_expert`, `states_stance`, `meta_style`, `self_corrects`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-087: usb-c ('you take that back!', 'sounds like a skill issue', 'tldr straight nonsense until i hear otherwise', hunts down the taken-down talk); ghidra checkout persistence — 'the intent is dumb' vs partner 'i disagree, a restart could scuttle tons of work'; 'i'm realizing i'm the devil's advocate here but the debate is solid'; 'i'll argue just about anything with anyone' / 'i've noticed'; 'tell me what's frustrating about myself and i'll work on it'; partner: 'equally fun and frustrating... i'm afraid of conflict' (engine-developer, redirected, quality 5)

- **self**: This sounds like postgresql. Looks like an annoying attempt to get new people vendor locked into amazon's stuff
- **engine-developer**: Yeah postgres is one of the offerings within RDS
- **self**: I miss the days when were unifying things under conventions/standards. Like usb-c might be the biggest example of that that'll happen in our lifetime i'm afraid
- **engine-developer**: And unfortunately USB-C kinda sucks
- **self**: One sec
- **self**: You take that back!
- **engine-developer**: at least from an electrical engineering stand-point
- **engine-developer**: thanks!
- **self**: What's wrong with usb-c? i'm not an engineer but seems great.. i mean i'm not picky I thought lightning was already good. /  / the whole 'right side up -> doesn't work, flip it to wrong side -> doesn't work, flip it back to right side -> *finally works*' was an annoying problem to deal with previously.
- **self**: just happy they unified and it's reversible lol
- **engine-developer**: if you[ve refresehd I've renamed and reorganized a bit
- **engine-developer**: I'm trying to hunt down the talk I watched on this, it's fascinating stuff. But essentially it boils down to be VERY over engineered, and causing a bunch of problems for hardware manufactures
- **self**: Sounds like a skill issue on those manufacturers
- **self**: They're getting paid to weld copper and silver... how hard could that possibly be. Sorry they're having *so much issue* changing over from micro/macro usb or whatever they previously were making
- **self**: I'm kidding but i'd like to know why it's an issue
- **engine-developer**: Ah I found the video 😭
- **self**: tldr: straight Nonsense (until I hear otherwise)
- **self**: um?
- **engine-developer**: Yeah, it appears to have been taken down
- **self**: I wonder why
- **self**: jk
- **engine-developer**: I'm not too upset about it, it was just a really good talk and I wish I could find a recording of it
- **engine-developer**: oh well
- **self**: what do you remember about it?
- **self**: maybe I could search it semantically from that description
- **self**: youtube's search has been horrible lately
- **self**: In ghidra I notice you have kotor_MAC and kotor2_MAC. Which mac version is this? the macstore version?
- **self**: from what I recall there's two versions. Well actually three, one of them is just a .appimage pack of wine wrapper around the windows version 😂
- **engine-developer**: Due to the variety of different ways hardware manufactures stretched and abused the earlier iterations of the USB standard, USB-C ended up being designed to cater to all of these different desires leading to it being an extremely complex connector standard with many pitfalls, integration issues, and diffiulty replicating the *true* version of it. Which is why often bootleg cables don't quite work correctly with all devices.  /  / The name of the talk was "Usb-C and its overengineered history By Tempo on Vrchat", and it has definitely been taken down, there might be a mirror somewhere
- **engine-developer**: I'm not sure. I got them second hand from a friend, but they are both compiled to run natively on MAC (no wine wrapper). They also have some debug symbols for functions IDs and parameters, which is very useful […]

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `demands_evidence`, `concrete_referent`, `meta_style`, `invites_pushback`, `concedes_point`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-088: porting k1 labels to k2 by signature scanning: '70% of functions should be 1:1'; partner: 'byte-precise comparison is naïve, compilers propagate small changes'; 'this isn't constructive though — are you saying i shouldn't bother, or it doesn't interest you?'; partner: 'not at all... i'm a perfectionist'; 'they target an ocean, we're targeting a small pond' → 'this is a fair point' (engine-developer, escalated, quality 5)

- **self**: Anyway, I think the next step into ghidra RE outside of kotor.js/openkotor would be to develop an algorithm that can sig scan for the matching similar function in the other programs.
- **engine-developer**: Perhaps... counter-point: I go purchase some illegal aderal, crsuh it up, take a few days off work, and go ham reverseing kotor 2 by hand.
- **engine-developer**: Your idea is probably better, just wanted to lay out our options
- **self**: Something like 70% of the programs should be exactly 1:1 matches, while the others may simply have simple small changes of some sort. You don't re-invent a game engine overnight, which would otherwise be required for k1 -> tsl in the timespan they've had, so most of the engine will more-or-less be the same. The problem seems to be I can't *prove* it with any iterative method I've concocted so far
- **self**: Yeah I could just take random 8-byte sequences of bytecode from each ghidra function and try to find the same byte sequence in the other programs but that isn't a satisfying solution. I'd like something that will actually use more ghidra functionality so I can get more involved with working with their extension API
- **self**: Because redoing all the work you've previously done, with the other games/platforms, does not sound like a good use of time
- **engine-developer**: The thing is, while I'm sure this is accurate for the actual source. Compiliers can be finicky. Even the smallest changes to a data type, can have propagating effects to hundreds of functions. /  / This usually looks like different registers being used, the stack frame getting organized differently, pointer offsets changing by small differences
- **self**: But failing that it seems ghidra supports another sort of external server, mainly: / - PostgreSQL / - Elastic / - Some other form I can't recall
- **self**: This would only happen if things changed at compile time.
- **self**: You any reason to suspect something like that happened?
- **engine-developer**: Definitely! Compiliers are complex beast and will often give out very different results for even small changes, espeically when optimizers are being run
- **self**: e.g. different flags being used, optimizer strategies differed between msvc compilers but this was back in 2001/2003 so i'd have to look into what all was available. I don't know when visual studio came out lol
- **self**: I just haven't seen it in my experience is all
- **self**: Usually I can copy like e.g. 12 or so byte sequences and find them in the other disassembly. Halo 1 pc -> Halo 1 CE, Battlefront 1 -> 2, battlefield hardline -> bf4
- **self**: just some examples that I remember having success with the sig scans anyway
- **self**: Unity is another good example.
- **self**: Though in unity usually you'd be using dnSpy and wouldn't need a sig scan since the symbols almost are already available unless it's an ILP binary.
- **self**: I think ILP is the wrong term but it's been awhile lol
- **self**: il2cpp
- **engine-developer**: For example: / Say in kotor 2, they added one new field to the creature object (I actually happen to know they added a lot of fields), but for the sake of example, let's say it's just one. Every single field that is further in the object structure than it would have it's offset adjusted by 4. Now lets say that pushes one of the offsets past the the 1  byte barrier (0xFF). Now the instructions referencing this pointer need to use a larger instruction size to fit the full reference in. This then shifts the surrounding instructions. Which can change the way the branching algorithm settles which will change your jumps, and then these new jumps get optimized down differently, and now the register […]
- **self**: What I'm trying to say is it should be possible to find the exact same function at a different address even if it has only a few changes in instructions based on the previous work I've done
- **engine-developer**: I do agree some fundamentals will be very similar, but assuming byte precise comparison is naïve
- **engine-developer**: Sure, I'm just pointing out that this is a rather hard problem.
- **self**: Well some level of heuristics is required I am not disagreeing there.
- **self**: But even some rudimentary oversimplistic should work for 60% of the functions. Which is still a large amount of them. But doing some unifying step here would definitely reduce the workload/accessibility for others overall when they're trying to find a function named 'CSWC::LoadModule' in one game and realizing it's 'CSWC::LoadLevel' in another when they're both the same function lol
- **self**: Well this isn't constructive though. Are you trying to say I shouldn't bother?
- **self**: Or it doesn't interest you?
- **engine-developer**: Not at all, I think this is worth a shot, and I'd be thrilled to see it work. /  / I just also know that the guys at ghidra have been working on this same problem for a while now with the various algorithms they offer in the version manager tool, and it still isn't very up to the task. /  / I guess I'm trying to temper your expectations
- **engine-developer**: Furthermore, there may be some easier wins to get a lot of functions to work with. /  / For example, all of the NW script commands are numbered, and those numbers appear in the decomp. I've written a script in the past to autopopulate thosse for kotor 1. Would just need to adjust it a bit for kotor 2, and doctor up the NWScript.nss file.
- **self**: Yeah that would probably handle a large amount of functions […]

Moves: `states_hypothesis`, `concrete_referent`, `pushes_entrenched`, `asks_clarifying`, `escalates`, `analogy`, `concedes_point`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-089: 2da row limits across platforms: 'the row limits are caused by compiler optimizers right? xbox would have smaller ones due to 64mb'; partner: hardcoded loops and 8-bit casts; 'there is no int in c/c++'; 'i'm just not understanding the point'; 'most of our confusions are semantic misunderstandings, temporary problems' (engine-developer, conceded, quality 4)

- **self**: […] Huh?? Do I just ignore your messages completely or something?
- **self**: Man I’m so sorry lol
- **engine-developer**: This is a good question. I'm not actually sure if any of the row limits are platform dependent... In theory, most should be the same, but intger sizing can get funky between platforms/compilrs, so don't quote me on that
- **self**: I don’t remember you sending me this
- **engine-developer**: Haha, don't worry about it
- **self**: The row limits usually are caused by the compiler optimizers right? that’s why I think different platforms would have different integer limits anyway
- **self**: Or is that incorrect? You think it’s something BioWare determined during development
- **self**: ?
- **self**: I just imagine Xbox would have smaller ones due to the 64mb of ram they were capped at
- **self**: and other hw constraints
- **self**: Nobody mods the Xbox version for this reason
- **engine-developer**: So it varies, many are caused because the devsjust decided to use a `short` or `char` instead of an `int`, choices that *should* be preserved between versions. Others are caused because explicit limits for things like loops, and buffer allocation. So it's hard to say
- **self**: Loops?
- **self**: why would a while/for loop affect anything like this
- **engine-developer**: So for example, when looping through all the rows on planetary.2da they just hard code `while(i < 16)` instead of using the `row_count` property on the 2DA
- **self**: short or char vs int? Wdym? There is no int in c/c++ they have (u)int<8,16,32,etc>
- **engine-developer**: I was using some shorthand here, I mean 8-bit, 16-bit, or 32-bit values for row indexing.
- **engine-developer**: Which is why so many of the limits are either 2^8, 2^16, or 2^32
- **self**: right but that doesn’t explain why a short vs a int16 would cause different results when they should be the same thing. I’m just not understanding the point you were making even with the explanation.
- **self**: i think you’re saying c/c++ has size constraints from the type definition but I thought we were past that page
- **self**: yes I doubt they would change a byte to a word or dword in the pc game vs the Xbox but I imagine if they specify a operating system or a platform that the compiler would generate extremely different results resulting in a bunch of different capacities
- **engine-developer**: So for example, whenever the game is trying to access a row of placeables.2da (in kotor 1), this row index gets cast to 8-bits. This means any rows beyoung row 256 will overflow, and circle back. Which is why it is limited to only 256 rows. /  / Presumably, the developers typed these fields as some 8-bit integer, in which case one would think that other versions compiling from teh same source, would perform the same cast.
- **engine-developer**: Correct, and that's why I said "don't quote me on this" above. I'm unsure at what degree of type strength many of these row limitations were introduced.
- **engine-developer**: If they were explicitly typed or casted this way, then these limitations would be preserved into other compilations. IF they were platform specified, then it's less clear. /  / i.e. the 64-bit android version may have some tabels that can have 2^64 rows
- **self**: Also yes I understand most of the confusions and frustrations in our discussions at this point are caused semantic misunderstandings but I imagine these are temporary problems. we’ll figure out as we interact in these collabs/knowledge sharing discussions
- **self**: From now on I’ll post anything resolution related on that issue post
- **engine-developer**: see the term "resolution" confused me initially, because my mind jumped to "display/graphics resolution". But yeah I get ya
- **self**: 😂 that makes sense
- **self**: I thought I said resolution *order* though
- **self**: i don’t think I needed to say that. My bad […]

Moves: `states_hypothesis`, `probe_expert`, `pushes_entrenched`, `asks_clarifying`, `concedes_point`, `meta_style`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-090: question dump (natural-language code, graph-based refactoring, ipc architectures, which engine rewrite to back) ending in the recurring 'hardware is dirt cheap, do we really need to micro-optimize native apps?' debate; partner: offline gaming, and 'it's just way more fun — i do node/ts all day at work'; 'ohhh i never thought about that' (engine-developer, conceded, quality 4)

- **self**: can i drop a bunch of random questions here for you to answer with zero urgency haha. Just wondering if you've heard of some of these ideas/stacks i'm looking for
- **engine-developer**: please
- **self**: 1. is there a way in programming to convert/write 'code' as natural language while still keeping it fully in tandem with the original code? like if i have a bunch of object oriented classes defined and functions for those classes, is there some implementation out there where I can write all the code as natural english language, something like UML, without losing specificity?
- **self**: For example if I want to transpile it to a relevant language but i'm not exactly sure what stack I want. Also just genuinely curious if a structured language exists that i can compile or use with some interpreter
- **self**: 2. in a codebase, separate from the IDE, is it possible to see a mermaid/figma graph of all of your functions, classes, etc and also drag classes/functions from the graph to actually migrate and organize it, rather than tediously cut/paste between physical files in an ide?
- **self**: 3. Pick your favorite one and briefly explain why (no debate necessary just curious): /  / > A. Local process with IPC (e.g., Electron main spawns Rust/.NET/Python and exchanges messages) / > B. Local HTTP/WebSocket server started separately (frontend connects to localhost) / > C. Remote server (hosted game logic) over HTTP/WebSocket) / > D. WebAssembly module loaded in browser/Electron (still non-Node runtime)
- **self**: 4. if you had to pick an engine rewrite to back, and drop the other,  do you think kotor.js has more utility since it can run in a web browser, or is reone the play since a webasm can potentially be written for it later and it's a native app written in the same language using the same (but newer) compiler?
- **self**: just honestly curious about your opinions 😛
- **self**: 5. if you've messed with pyghidra have you figured out how to login/use a shared project within it? i think i've tried everything at this point and no bueno (tried with and without AI 🙁 )
- **self**: 6. have you noticed any lag on the ghidra server? wondering if i'd be able to reduce these slightly: /  / ```yml /   services: /     ghidra: /       image: blacktop/ghidra /       container_name: ghidra /       environment: /         - MAXMEM=4G /         - DISPLAY=host.docker.internal:0 /       deploy: /         resources: /           limits: /             cpus: 2 /             memory: 4g / ```
- **self**: seriously man no pressure i'll come back next month 😄
- **engine-developer**: 1. I've seen attempts at something like this before. There are several formal specification languages that came out of Academia in the late 90s, but none of them quite live up to what I would consider "natural language". Natural language processing really only hit its revolution within the past 5 years with LLMs. I have seen demos of people using models such as Claude Opus to analyze code and generate things like UML or mermaid. But your qualifier "without losing specificity", leads me to think this may be an impossible ask. As axiomatically speaking, specificity requires some type of formal language, which at the end of the day will always be some sort of programming language. There may be […]
- **self**: > But your qualifier "without losing specificity", leads me to think this may be an impossible ask.  / In my mind it makes sense. I haven't specified a framework, language, or anything so the specificity already is language agnostic
- **self**: #1 isn't intended to target LLMs, but i did throw my example into an llm because my original was messy: /  / ```ps1 / # Convert a Unix timestamp (seconds since 1970-01-01 UTC) into a DateTime object. / # NOTE: Unix epoch is 1970, not 1980 — that’s the DOS/FAT epoch. /  / # --- Example usage in a common everyday pattern --- / $ErrorActionPreference = "SilentlyContinue" /  / $rawTimestamp = 1707427200  # Example: some API returned this /  /  / # Call the function and validate the result / $converted = Convert-UnixTimestamp -Timestamp $rawTimestamp /  / if ($null -ne $converted) { /     # Sanity-check the output: ensure it's a DateTime and not default/min value /     if ($converted -is [DateTim […]
- **self**: You ever hear the phrase 'a picture represents a thousand words?'
- **self**: i think this example already represents a thousand words. But most of those words are implicit to powershell. For example no other language has a $ErrorActionPreference
- **self**: If I was writing the code in a natural langauge to start, would it not just be language-agnostic, simplifying the actual contents of that definition?
- **self**: The reason I don't use UML in daily programming is because i'm *always* running into obnoxious language specifics that make the implementation i have in my head somewhat impossible
- **self**: it is possible i'm not thinking of other examples but tldr: it seems most of this would be a nonfactor due to the natural language definition already being syntax/language/interpreter/compiler agnostic (<----- not sure on the correct terms here lol) /  / > I've seen attempts at something like this before. There are several formal specification languages that came out of Academia in the late 90s, but none of them quite live up to what I would consider "natural language". Natural language processing really only hit its revolution within the past 5 years with LLMs. I have seen demos of people using models such as Claude Opus to analyze code and generate things like UML or mermaid. But your qual […]
- **self**: > 2. As mentioned before, I've seen AI implementations of diagram generation. Claude Opus is particularly talented, though I believe this is also a feature of CodeRabbit. For non AI approaches, I've used IntelliJ IDEA's built-in diagram feature to create class diagrams for Java code in the past; of course this is Java specific, but I believe similar tooling has been invented for other languages. As far as drag/dropping for migration goes. I'm not aware of any tooling that would allow for this. Though, if going the AI route, I suppose you might be able to get mileage out of a workflow like: generate a mermaid diagram -> use a mermaid editor to reorganize it -> pass the mermaid code back to th […]
- **engine-developer**: The "before" here refers to the previous paragraph (#1), where I mention LLM based UML generation.
- **self**: 2. wasn't even intended to be llm specific but you're probably right it has utility there. I just am tired of breaking the heck out of my ctrl+v/ctrl+c/ctrl+x buttons.
- **self**: 1. wasn't either... but i guess that's almost implied with the phrase `natural language` isn't it...?
- **engine-developer**: Yeah I'm aware, and in that case teh asnwer is "no", I'm not aware of any tooling for this
- **self**: is it just a bad idea?
- **self**: is that why i'm not finding it anywhere?
- **self**: or is it just like extremely non-trivial to do as you said
- **engine-developer**: I wouldn't say it's a bad idea, I'm just not particularly aware of any well trodden implementations of anything like this.
- **self**: ### #4: / > My intent was to get your opinion on this debate: / > Hardware is dirt cheap nowadays, do we really need to be micro-optimizing native apps when web apps have so much more visual fidelity, supported on most devices, and easier to deploy/package for an end user (just a website) / > for #4 / > I see so many native apps, still, and i really just.. don't understand it? Why work on a native UI, and maintain a more complicated low level project when there's almost no trade-offs to using... well... anything that can be embedded in a browser, electron..? / > To clarify i'm certain i'm missing something. People wouldn't do it if there's no point. But I can't think of any scenario except: […]
- **self**: or if c/c++ projects like reone just are written in c/c++ because of nostalgia […]

Moves: `probe_expert`, `states_stance`, `invites_pushback`, `offers_out`, `concedes_point`, `self_corrects`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-091: 'why is low level and native programming so popular? i seriously don't mean to start a debate i just want an actual good reason... wait, is it not about pros/cons and more about it being fun? ohhh you had said this day one! brilliant'; discloses adhd: 'i simply ask for patience and honesty' (engine-developer, conceded, quality 4)

- **self**: Sorry I’m terrible at these social queues stuff and it’s more so over text IM
- **self**: Can you explain why lol? Why is low level and native programming so popular? As someone who started: / Batch -> PowerShell -> Visual Basic -> LUA -> Java -> Python  -> .NET -> node.js I’m absolutely in love with node.js + npm
- **self**: mostly because UI development and platform agnostic is OBNOXIOUS in native apps. It never looks as good as react and it is damn near impossible to verify every feature in Mac/Wayland/X11/Windows 7-11
- **self**: Which usually are my targets. I dropped 7-10 recently though.
- **self**: Browser deployment just works.. it’s damn simple…. And less work. /  / So I guess…… how much actual performance improvements are you getting with rust/c++ vs the bloated chromium/electron stuff
- **self**: and is it worth it?
- **self**: I seriously don’t mean to start a debate I just want an actual good reason to do low level stuff. /  / Wait is it not about pros/cons and more just about it being fun?
- **self**: Ohhh you had said this day one! Brilliant.
- **self**: As an ADHD adult man yeah you probably take this for granted so this is understandable.
- **self**: I’d like to ask about 5. Again once you make the switch. I could rewrite agentdecompile for v11.2 if you believe you could help me figure out #5 on jython. Seriously. I can’t get the shared projects functionality working regardless of what I attempt on pyghidra. Everything I read tells me this api should work but testing through a stdio server to reproduce is not ideal. The network connection also doesn’t always work so getting a testing environment going to reproduce the issue is non trivial. /  / TLDR: if you have interest a 20 line example in jython that actually connects to our server would be leagues helpful
- **self**: For #6 let me know if it becomes a problem in next few days as I publicly give the read only account and the documentation out. I have another VPS I could throw it on I suppose.
- **self**: Or if you’d like to offer better hosting feel free. I’m just using the free Oracle cloud VPS thing.
- **self**: While not wanting to dive into this too far I do have ADHD. It can make me seem difficult or obnoxious to communicate with. I simply ask for patience and honesty when relevant. I don’t have an evil bone in my body but sometimes I do joke a bit too much or like to argue about things that don’t matter. But yeah other than that I have a feeling some *really* cool things are about to happen in the community that we are spearheading. As you said we’ll be speedrunning kotor.js in no time 🦵
- **engine-developer**: Yup, the developers are delightfully inconsistent with this. Sometimes, GUI colors get derived from the relevant `.gui` GFF file as you described, other things it comes from one of several Global color constants within the EXE. I have all of these global colors identified within the Ghidra project already, and they would be trivial to patch to different values.  /  / As for the Alt+F4 pop-up, this shares a class with the other message boxes (Save confirmation, return to ebon hawk, etc), and would also be easily adjustable via patching.
- **engine-developer**: Don't worry about it, you're fine

Moves: `states_stance`, `probe_expert`, `invites_pushback`, `self_corrects`, `concedes_point`, `meta_style`, `apologizes`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-092: publishing ghidra-server credentials: 'i thought the whole point was to get users on it'; 'i'd rather know about security issues in the first few days than a year from now'; partner: piracy concerns, screenshots the earlier dms; 'you're very wishy washy... fake-green light actual-yellow light'; partner: 'do you have memory issues?'; 'i'd like to adhere to restrictions, i just wish someone would tell me what they are' (engine-developer, escalated, quality 4)

- **self**: So another reason I'm confused. You said this the other day. I thought the whole point was to get some users on it. Otherwise why are we hosting it at all and why are you accessing it so frequently then if it's just you and me using it?
- **engine-developer**: I do want other people on it, we just also need to be careful about how we spread the credentials around. /  / For example a publicly facing GitHub wiki doc will invite randos with malicious intent to load up the server and try things. /  / I'm, by-all-means, on board with getting other open kotor folk, or developers accessing the server though
- **self**: Well that was the point. It's not like we're risking anything sensitive.;
- **self**: I'd rather know about security issues in the first few days during  the surge, than a year from now
- **self**: Learning works better that way i think. I patched a few areas where someone could acquire admin the other day based on what you fixed so it's working out so far
- **self**: i mean if this was a bank we were protecting ofc i wouldn't be this bold lol
- **self**: with someone else's money
- **engine-developer**: What about the whole big discussion we had regarding concerns about abetting piracy?  /  / Like someone could get the exe by just doing Export Program > Original File
- **engine-developer**: (Yes I'm screenshotting DMs, but you were in this DM group so it's fine lol)
- **self**: Idk it seems you're very wishy washy about where you're standing on it sometimes it feels like we find mutual understanding and then i go to do something and then it's not aligned with where we are. /  / The only time I've been reluctant is something i got over in pretty much an hour. For some reason I had a thought in my head that you were asking me to host because that way you're not responsible. So I thought it was *possible* I was being too rash. But we did research that day, went over to metaforce found they do basically the same thing we were originally trying to do. So i was just overthinking. my reluctance was simply checking in with reality because i did kind of impulsively throw th […]
- **self**: People need to make up their mind I think. Strict guidelines of what we can and can't do, full governed rules, otherwise it's fine we'll make them as we go.
- **self**: I mean I don't even understand where the misunderstanding is happening. I don't really want to be causing issues with this i just wanted to put this up for everyone to use. It's pretty useful to dump into copilot to find some information on how to do something in e.g. blender for example or some hardcoded row limit of some kind in a 2da function.
- **self**: Yeah alright I'll just stop dropping things publicly I guess 🤷 idk what's happening at this point lol
- **self**: TLDR: this fake-green light actual-yellow light is too confusing to me i'm just going to make this for just you and me i guess
- **self**: sry if any of that is non-sequitur i did pull an all nighter 🥶
- **self**: mb
- **self**: Just an adhd thing. I don't do nuance very well i guess
- **self**: The messages I removed were simply because i wasn't happy with how v1 turned out, based on your review. Not because of the liability or anything.
- **engine-developer**: Okay... So it seems like there's just been a big misunderstanding here. So allow me to clarify a few things: / - I didn't *ask* you to host the Ghidra server, you just did one day. And I was thankful for it, as it saves me time, and it's a good thing to have. I don't think it was rash or irresponsible. Just a nice thing to do. / - We gave the green light to do what metaforce does. That is, distribute and collaborate on Ghidra things within our community, but not outwardly. This means, sharing and setting people up with the Ghidra server/agentdecompile in the Discord is just fine. But posting credentials on the open internet is less fine. / - You're right, I am wishy-washy. I personally don't […]
- **engine-developer**: And, if you'll excuse the personal question, do you have memory issues? / This isn't the first time it's felt like you've forgotten something we spoke about previously. I know that can be an ADHD symptom, but I didn't want to be presumptuous...
- **self**: (none of this is your fault & I'm not attacking you btw)
- **self**: My bad I probably should have led with that
- **self**: Yeah I'd like to adhere to restrictions too I just wish someone would tell me what they are.
- **self**: Like rather than after the fact. Like 7 of my prs were unusable because they contained too much RE documentation (would have taken longer to go through them than it would to just redo the prs from scratch)

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `exit_move`, `meta_style`, `apologizes`

Why it worked or failed: Pushed an entrenched position past the point where new evidence was arriving; escalation without a new referent.

### r-095: clean-room reverse engineering with the reone maintainer: 'how is reverse engineering the gffs/bifs different from the exe? that technicality is stupid, sorry for being rudely blunt'; 'is it really cut and dry where the line is? maybe i'm insane'; 'i significantly doubt that — a simple rg would prove it' → 'wow you're right'; 'i'm debating the semantics of your position — are you not a debate type of person like i am?'; partner: 'my position is to not think about this too much' (modder-b, dropped, quality 5)

- **self**: […] from what i understood it was never provided by bioware, and only has usage with nwnnsscomp.exe
- **self**: *but* in the game itself it's implied that that's the scripting engine
- **self**: e.g. id 522 is function xyz in k2, 233 is function abc in k1. and tsl reuses k1's identifiers/definitions
- **self**: haven't seen that code in reone but i know where it is in andastra/kotor.js
- **modder-b**: Yes, I think it is in one of the BIFs that contains nss sources as well as ncs bytecode.
- **self**: i significantly doubt that based on my own understanding. You still have the json dump of the game on your disk from when you ran my json converter tool 😄
- **self**: a simple `rg` through it would prove that or not.
- **self**: now i'm curious whether a quick and lightweight semantic search tool exists
- **self**: I *really* need to replace `plocate` lol
- **modder-b**: check out `data/scripts.bif`
- **self**: alright i will one sec
- **self**: WOW i can't believe i didn't know that
- **self**: you're right xD
- **self**: wait no...
- **self**: oh you don't know this
- **self**: OH so darthparametric told me something *interesting*
- **self**: the `nwscript.nss` provided in the BIFs is *not* the one used to compile all the `.ncs` scripts
- **self**: or something like that.
- **self**: oh that's probably too nuanced to matter i'm not going to split hairs about that. IIRC they used a different one due specifically to ActionStartConversation not having an overload of an optional argument or something
- **modder-b**: Yeah, there are some discrepancies like this that.
- **self**: ok here's my final argument. You have this: / ```sh / data / - xyz.bif / - abc.bif / - def.bif / ... / Modules / - dan13a.rim / - dan13a_s.rim / - kor48.rim / - kor48_s.rim / ... / Override <empty> / chitin.key / dialog.tlk / swkotor.exe / swkotor.ini / swconfig.exe / strings.dll / ```
- **self**: so why is it okay to take apart `chitin.key` and `dan13a.rim` and all the GFFs and other stuffz within the bifs to figure out how they tick, but *not* the exe?
- **self**: in my mind they're all files...
- **self**: why is the fact that one has *code* important?
- **self**: because it sounds like `static data` vs `imperative data` is the discrepancy in your mind (may be using wrong terms)
- **modder-b**: Because that is the only thing we make. The whole reone project produces just one executable that replaces swkotor.exe.
- **self**: Right
- **self**: To clarify i'm not an idiot who forgot to mention the context
- **self**: my question is
- **self**: why can't we look at ghidra decompilations of swkotor.exe, in order to help us figure out how to make swkotor.exe's replacement? […]

Moves: `states_stance`, `probe_expert`, `pushes_entrenched`, `demands_evidence`, `concedes_point`, `apologizes`, `meta_style`, `self_corrects`, `asks_clarifying`

Why it worked or failed: Escalation plus meta-commentary about the debate itself outran the evidence; the partner stopped responding.

### r-097: skeptic role: partner's 'geometric reasoning layer' claims for ai agents — 'i'd like to see it compared to a simple haiku conversation with context7 tools, otherwise i'm not convinced'; 'that doesn't sound right — if they were flawed they'd never corner the market'; 'ok pause, i think we're having two different conversations, provide an example'; 'stop explaining that and focus on the results'; 'where's the proof. results. benchmarks'; 'i don't understand why you can't just do this other than not wanting to be proven wrong'; 'i'm wired to only care about things that have results' (peer-developer, stalled, quality 5)

- **peer-developer**: […] Here is a diagram to help sum it up
- **peer-developer**: YOU /  │ /  ▼ / CLOUD CODEX / general-purpose frontier intelligence / planning / coding / architecture / tool use / orchestration /  │ /  │ calls MCPStudio /  ▼ / MCPSTUDIO /  │ /  ├── Canonical game-dev library /  ├── Project knowledge /  ├── Experience memory /  ├── MCP tools /  │ /  └── LOCAL GPU GEOMETRIC REASONING LAYER /           │ /           ├── geometric specialists /           ├── perturbation testing /           ├── counterfactual testing /           ├── reasoning-rail detection /           └── confidence / evidence /                  │ /                  ▼ /           structured decision analysis /                  │ /                  ▼ /                CODEX /           makes […]
- **self**: I don’t want a diagram lol I really don’t agree with the way you describe methodology. None of that proves anything
- **self**: There’s an infinite amount of people putting together convoluted nonsense but none of that actually implies anyone should be doing that. For example I could jump off
- **peer-developer**: Imagine making your usage 60x smarter
- **peer-developer**: Without it costing you any money
- **self**: Ok yeah but where’s the proof. Results. Benchmarks.
- **self**: all you’re doing is diagramming a bunch of convoluted stuff that sounds good
- **peer-developer**: The whole reason I explained all of that
- **self**: none of it proves it’s anything better than what I’m using.
- **peer-developer**: Was because the benchmarks do not capture this
- **peer-developer**: It does
- **self**: Ok then make your own benchmark
- **peer-developer**: Scientifically
- **self**: Literally just something that proves your thing is better than what exists
- **self**: Like again, a task that’s sent to ai without your pipeline, and a second identical task sent to ai *with* your pipeljne
- **self**: Compare the results
- **peer-developer**: My work is proof, for one
- **self**: how?
- **peer-developer**: Because I can do more, more accurately and better quality while doing less
- **peer-developer**: With less mistakes
- **self**: I don’t understand why you can’t just do this other than you not wanting to be proven wrong
- **peer-developer**: The central problem is that most conventional AI benchmarks primarily measure whether a model arrived at the correct output
- **self**: ask it to create minesweeper or something
- **peer-developer**: The benchmarks are NOT understanding or measuring whether the internal process producing that output is robust to changes in the underlying problem.
- **self**: okay great then make your own benchmark somehow. Just literally anything that proves results
- **peer-developer**: Dude I don’t need to make my own benchmark
- **peer-developer**: This research already exists
- **self**: I’m not saying I don’t believe you I’m saying I’m wired to only care about things that have results lol
- **self**: I digest research that I need for sure if you’re saying research exists my guess is the proof/claim/results/benchmarks are included with it […]

Moves: `demands_evidence`, `states_stance`, `pushes_entrenched`, `escalates`, `asks_clarifying`, `meta_style`, `concedes_point`

Why it worked or failed: Neither side produced the referent the other asked for; the exchange stalled on framing.

### r-098: wants the partner's raw ai chat logs, not his curated presentation: 'idk why most people just say i don't want to, it's bizarre to me'; 'anyone can write a presentation... i go straight to the citations'; partner: 'you lose out on perspective, slow down and let it invoke thought'; 'this wasn't supposed to be a debate — usually i'm a debate person'; 'we're going in circles, i wonder why that happens with me so often lately' (peer-developer, escalated, quality 4)

- **self**: but that is quite the massive document you just sent over
- **self**: i like sharing ai stuff not sure if you use/desire what i send you but i just created this [link]
- **peer-developer**: Too much work, just read the presentation I thoughtfully put together to describe how the method works
- **peer-developer**: It's worth more than a shit ton of unfiltered data
- **self**: i got so tired of so many things rate limiting after 2 minutes of light use asking us to pay  lol
- **self**: i love unfiltered data.
- **peer-developer**: it won't really serve you that well, and you'll just spend more time and energy going through all of that rather than seeing it presented with care
- **self**: idk if i'm asperger or what but idk why most people just say 'i dont want to' it's bizarre to me
- **self**: i mean i'm not tripping i'm just bewildered
- **self**: lol
- **peer-developer**: well the reason I don't want to is it's time consuming for no reason when I've already put together a peer reviewed presentation...
- **self**: well it's not though. It's a single export button. The reason chat logs are preferable is i can see what kinds of phrasing you're using, and what results you're getting, and compare to my methodology. I've been feeling stuck in my own headspace lately when it comes to ai
- **self**: but all i ever find when i search around for others chat logs is the stuff that's promoted for some company or something
- **self**: its hard to find just random people building stuff with ai, as i don't want to include anyone who's *trying* to get discovered y'know?
- **self**: it's like a catch22 with the search engines i use nowadays
- **self**: i wish seo wasn't a thing
- **self**: yeah if you change your mind though i'd enjoy reading them, building a *brain* 😛
- **self**: you can export all your stuff like this btw
- **peer-developer**: i say in my presentation that "The visible advantage is not prompt fluency. It is the ability to carry one player facing intention through mechanics, levels, art, tools, testing and team delivery"
- **peer-developer**: The secret is not the prompt
- **self**: Ah
- **peer-developer**: That being said, lazy prompting does lead to lazy output
- **peer-developer**: It's a factor, but if you focus only on that part of the method you'll lose out
- **self**: there's a latin phrase i can't recall but it means something like 'the thing explains itself'
- **self**: hang on lol i'm brainrotted for the night but my point is valid xD
- **self**: *Res ipsa loquitur*
- **self**: i think that's what you're saying when you're telling me to read this.
- **peer-developer**: Well, a presentation does speak for itself in a way. It's meant to be paired with speech from the presenter, but it makes ideas easy to latch onto. In a format that can be downloaded into your brain easier
- **self**: Do you want me to be honest though?
- **self**: I mean no offense but honestly i really don't know when i should be holding my tongue anymore. I've nothing *mean* to say. Been confusing since i got kicked i'm ngl. […]

Moves: `states_stance`, `pushes_entrenched`, `meta_style`, `self_corrects`, `offers_out`, `concedes_point`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-099: public c&d-risk debate in his own engine channel: 'remaking k1 is an engine rewrite by definition, what do you actually mean?'; 'we do a disservice to my project by debating semantics'; 'thank you for polluting my channel with a bizarre fixation on fourteen words'; 'i apologize for my rudeness if it existed'; partner: 'that's the last i'll say on the matter'; others add precedent and he adjusts ('i should at least delicense the project') (channel-member, dropped, quality 5)

- **self**: The engine rewrite itself here is an overly ambitious endeavor. Originally it started simply to gauge the current quality and intelligence of ai vibe coding tools. Realizing pretty quickly this was actually writing source code that, to the best of my ability to review, was matching line for line what I was able to decompile using ghidra. The community already provided a lot of reverse engineered components. /  / Being 2026 we’ve all used ai coding agents and ChatGPT to generate at least boilerplate but until that day this was the first time I’d ever given such a task to generate code I didn’t even understand. /  / Game engines are complex beasts, anytime I’ve ever wanted to design a game or […]
- **self**: This is the OpenKotOR community, I have and always will continue and intend to fully disclose everything and anything that may be relevant. /  / I do not like to reinvent the wheel but unfortunately none of the other engine rewrites are MIT licensed and all are extremely code-left, meaning they are restrictive in how one can derive from them. /  / Given Apeiron’s C&D this is immediately relevant and important to  scope out and avoid.
- **self**: Ideally I’d like to migrate away from a full engine rewrite into something that other great developers such as [partner] - KotOR.js have already sacrificed blood, sweat, and tears for 🙂 /  /  / ## Why KotOR.js? /  / There aren’t a lot of other good choices: / - reone is odyssey-targeted and much of it seems to be tightly coupled, which makes things like accessibility and tooling difficult, which is important to me / - xoreos is a grandfathered dinosaur with a similar problem. It’s difficult to extend past its original design. Setting up boost and various libs on windows seemed to be non-trivial, even when trying to offload much of that to ai. / - KotOR Unity (or the northernlights fork) lice […]
- **channel-member**: Not sure if an engine rewrite is comparable to the C&D Apeiron got
- **self**: Wdym
- **channel-member**: Apeiron were remaking K1. I don't think an engine rewrite has anywhere near the same danger for a c&d
- **self**: remaking k1 is an engine rewrite by definition, what do you actually mean? Or what is the issue with what I’ve written?
- **channel-member**: It was a whole new game with its own assets
- **self**: Huh I’ve heard differently. But what I am saying is it’s important to learn from their mistakes and take reasonable precautions
- **channel-member**: Yeah they were morons trying to pass it off as a "mod" when that very clearly was not the case
- **self**: What I understand is they reused assets that only users who bought the game are supposed to have
- **channel-member**: Voice overs
- **self**: Simply requiring one file ‘chitin.key’ and providing the entirety of their bits in ‘their’ game isn’t legal lol
- **self**: bif*
- **channel-member**: All other assets were their own (or bought from a asset store more likely)
- **self**: I don’t know that’s what they did but I’m even paranoid about including nwscript.nss
- **self**: I guess I’ve heard differently.
- **channel-member**: What other assets could they have reused that would make sense
- **self**: We do a disservice to my project Andastra by debating semantics of an unrelated project barely important enough to be included in my explanation of my motivations. /  / I don’t know what other assets they were/weren’t reusing. It’s not like their C&D was made fully public nor was the full source code of the game they were building hype for and trying to release. /  / The important thing was this generated not only from me but from other engine rewrites that reasonable extra precautions should be taken and the threat of a future C&D is always possible
- **channel-member**: They got a C&D for encroaching on Disney's IP by advertising and creating a whole new game
- **channel-member**: And they did post the C&D letter
- **channel-member**: Do what you got to do to feel safe, but you're not at risk like Apeiron was
- **self**: Thank you for polluting my channel with a bizarre fixation on fourteen words out of the several hundred describing motivations for Andastra. I don’t understand why Apeiron’s C&D specifics are relevant at all beyond the following (anything and everything else not mentioned here is completely irrelevant): / - A C&D was submitted. To cease. And desist / - It actually happened / - Targetted a rewrite of KotOR in some way shape or form
- **self**: the specifics hardly are relevant. This is an example I pull frequently but basically when a billion dollar company tells you to move you don’t ask yourself if it’s lawful. We get out of the way because we can’t afford to get caught up in the chaos that comes with a lawsuit. /  / > InfernoPlus (also known as InfernoPlus on YouTube and [partner] on X) is the creator. / > Nintendo issued a cease-and-desist (C&D) notice to InfernoPlus on June 21, 2019, just six days after Mario Royale's release, citing copyright infringement. / > InfernoPlus immediately complied by removing all Nintendo assets and relaunching a reskinned version, but Nintendo followed up claiming continued infringement, leading […]
- **self**: Not saying they will bribe (I or anyone else doing this isn’t worth the effort)  but even a more charismatic or quick-witted lawyer than I could afford would influence the odds. Also a court case is not only expensive to defend but requiring a large time investment.  /  / Maybe it’s different for you in New Zealand?
- **self**: in America all I’m thinking about is the size of their company and the competition that is created from their own rewrite project they’re pursuing which means they would be motivated to shut down others
- **self**: That is the reality
- **self**: I apologize for my rudeness if it existed. /  / When I got into all this I was just annoyed researching a bunch of scattered integrations: things that provided *pieces* of a solution. Either with problems that I had to discover on my own that are so niche it's ridiculous or problems that are generally gatekept behind the veterens or the archived lucasforums/archived waybackmachine information. /  / What I am creating here is an integration that would have been satisfying and useful to the past version of myself that simply had a goal in mind and little to no place to start beyond a small Python project that you created a long time ago, in a galaxy far far away… 😅
- **self**: I carry this torch with honor and dignity within Andastra
- **channel-member**: All I was _trying_ to say is you really don't need to be concerned about a copyright strike. Apeirons situation was completely different. Something like SW Genesis is far more likely to get shot down then this. Take that what you will, that's the last I'll say on the matter. I look forward to seeing progress on this […]

Moves: `states_stance`, `escalates`, `pushes_entrenched`, `asks_clarifying`, `apologizes`, `concedes_point`, `self_corrects`

Why it worked or failed: Escalation plus meta-commentary about the debate itself outran the evidence; the partner stopped responding.

### r-100: reone's resource loader (public wasm thread): 'elevator pitch the current resource loader to me... because i might 🤮', 'oh god why have we not fixed this months ago'; maintainer: 'a matter of priorities, it works, endar spire and taris play'; 'fair, 100% fair, i should stop being such a perfectionist'; 'why implement binary readers from scratch, surely there's a vcpkg lib?'; tries to read reinterpret_cast/boost endian: 'haha i tried'; 'the cursors are in the exe??' (channel-member, redirected, quality 4)

- **self**: interesting so it still is *loading* the resources *whilst* the main menu is visible
- **self**: Excuse my french but... || I'm beyond frustrated with this piss poor resource loading implementation. Frankly pykotor's and andastra's is better... ||
- **channel-member**: WASM is likely going to land first, at least the resources part. So nothing changes for now, I think. / Rakata integration will probably mean the resource subsystem is going to be redesigned, but I'd prefer to have WASM already enabled at this point, so we can test it.
- **self**: Gotcha
- **self**: can you elevator pitch the current resource loader in reone to me?
- **self**: is it just loading everything one by one into memory comprehensivley at init?
- **self**: because I might 🤮
- **self**: `Loading data/models.bif (891027456+262144)…`
- **channel-member**: Global resources - yes, then module resources when at loadModule.
- **self**: OH GOD [partner] why have we not fixed this months ago
- **self**: ah that's awful
- **self**: hopefully i'm misunderstanding xD
- **self**: i'm getting timeouts after 10m just because it's taking actual lifetimes to load `data/models.bif`
- **self**: hmm
- **self**: yeah so that's where this pr probably should end... we need a better resource loader. or the timeout can be set to several hours and pray the user has 32gb of ram for now
- **channel-member**: It is a matter of priorities. Current resource loader is simplistic, but it works - we can play through Endar Spire and almost through Taris at this point. / Startup time on a native build is barely noticeable.
- **self**: Fair
- **self**: 100% fair XD
- **self**: i really should stop being such a perfectionist 😛
- **self**: ok so this needs to be a new pr unfortunately
- **channel-member**: It wasn't until save/load feature when I had to actually look at resources, though I agree it is not good at all. Hence why I'm happy that [partner] is working on Rakata.
- **self**: Hahahaha
- **self**: I'd like you to look at PyKotor's/Andastra's at some point. Wonder what [partner] is doing in kotor.net. Still an installation class? /  / the utility and feasability of the robust implementation makes it extremely intuitive to just grab the resource you need and tracking which resources exist and what offset their data is at at runtime
- **self**: it's quite good. Probably it's biggest selling point imo.
- **self**: [link]
- **self**: [link]
- **self**: (this code is 1:1 with pykotor's)
- **self**: the load magic itself happens in FileResource. I wonder how difficult it'd be to implement this quickly in c++?
- **self**: um... whatever save pipeline reone has would be the biggest issue
- **self**: (the bioware archives inside of bioware archives can get a bit convoluted within those .sav's) […]

Moves: `states_stance`, `escalates`, `probe_expert`, `concrete_referent`, `concedes_point`, `self_corrects`, `apologizes`, `admits_ignorance`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-102: public group debate on ai art: 'you all are having different conversations — i need some context'; 'so what's an example of what isn't art? just to make sure i'm understanding you'; 'human in the loop won't be forever' vs 'it will as long as we live' → 'uhhh doubtful, what do you think an autonomous cloud agent is'; 'sentience is extremely different from genai... the foundation of what genai is makes it fundamentally impossible' (channel-member, stalled, quality 4)

- **channel-member**: […] What’s your thoughts on this?
- **channel-member**: its not loaded yet but looks pretty nice
- **self**: Okay why are you talking about commission if there’s no buyer?
- **self**: am I the buyer in that context?
- **channel-member**: i consider a person who is prompting AI to do art
- **channel-member**: to be sort of a commisioner
- **channel-member**: you "Commision" AI to draw something for you
- **channel-member**: but without the money
- **self**: Ahhh
- **channel-member**: (usually)
- **self**: there’s two s’s in that word btw but I’m getting you now
- **channel-member**: I’ve got to admit I used AI to help me with texturing and I do so on a lot of 3d models in order to save me time. But I still stay in the creative director seat, it becomes more to a just a one click texture. I paint it, change it how I want it, clean the UVs if I need to
- **channel-member**: oh thanks
- **channel-member**: That’s an example of the human component, but still using ai as a tool
- **channel-member**: that's what im talking about
- **channel-member**: you're simply using AI as a tool
- **channel-member**: but a good chunk of work is done by you
- **channel-member**: So the problem comes down to people in the end doesn’t it
- **channel-member**: and you're the one fixing shit
- **channel-member**: and directing it
- **channel-member**: It’s just that the mass percentage of people seek the easy path, which makes the public opinion of ai low
- **self**: Staying focused and relevant is important when navigating the landscape
- **self**: context is key
- **self**: So what’s an example of what isn’t art?
- **self**: Just to make sure I’m understanding you correctly
- **channel-member**: hm
- **channel-member**: i think its something where you just prompt AI to do something
- **channel-member**: straight up
- **channel-member**: nothing else done
- **self**: I’m sorry huh how is that different from this example? The goal was to provide two different scenarios lol. One where the human element is important, and the art is real art, and the other where it ain’t and it’s just rehashed from some other creator/training […]

Moves: `asks_clarifying`, `states_stance`, `pushes_entrenched`, `escalates`, `demands_evidence`, `concrete_referent`, `exit_move`

Why it worked or failed: Neither side produced the referent the other asked for; the exchange stalled on framing.

### r-106: blender vertex cleanup 'can't be automated' vs ai-research tooling: partner 'find a way to automate it and i'll eat my shorts'; 'you do not need to say there's no way and be unmovable — you haven't even tried the plugins'; 'you say a lot of absolutes on topics both of us don't know anything about'; 'probably a personality defect on my part for challenging your absolute statements, or maybe i care about your projects'; 'as a favor to me try 1–2 plugins and report back, you can prove your point'; partner tries the plugin: 'great tool, doesn't help this situation' (veteran-modder, conceded, quality 5)

- **self**: […] if you can type to it that somehow means they're letting random users use pro if a plus member is sending a link
- **self**: which is wild
- **veteran-modder**: and there are a lot of situations where I need only the X or the Y or the Z
- **self**: ya just send this info to perplexity in the chat
- **self**: or send it to chatgpt to create a better prompt for your perplexity reply
- **self**: go from there
- **veteran-modder**: I don't see the point, there's no magical solution to this problem. /  / Like I said, even being able to copy the coordinates of a vertice, wouldn't always be helpful.
- **self**: it should be able to simplify the tools/instructions to your exact scenario and nuance
- **veteran-modder**: sometimes it would be detrimental
- **self**: i imagine there's a learning curve ya
- **veteran-modder**: do yourself a favour, drop all the games models, lyt, vis and textures into a folder, then import m26ac or m26ae by lyt and look around the level in game
- **veteran-modder**: find a way to automate it and ill eat my shorts
- **veteran-modder**: not that I have any shorts
- **veteran-modder**: but yeah
- **self**: ya idk why i said that
- **self**: was watching simpsons earlier maybe that's why
- **self**: *shrug* i tried lol
- **veteran-modder**: when modelling something from scratch, there's 100% a way to skip all this bullshit and line things up cleaner as you go
- **self**: perplexity's answer looked spot on
- **veteran-modder**: but with something already modelled, it's just not that simple
- **self**: ight i'll take your word on it
- **self**: good luck tho let me know if any of the plugins are indeed good if you do try em out i'm still trying to find time to learn blender at some point
- **veteran-modder**: believe me, I wish there was a way to speed this up or automate it. But there just isn't
- **veteran-modder**: I doubt I will try em, I don't do much modelling
- **self**: bro you do not need to say 'there is no way to speed this up' and be unmovable from it.
- **self**: you don't even know if perplexity's answer works or not because you haven't tried the plugins.
- **self**: why not just say 'i dont trust any potential faster way because i want to trust my methods'
- **self**: 'and introducing unknowns might screw even more things up and i dont feel like trying it'
- **self**: which is understandable
- **self**: but flat out saying it won't help is nonsense […]

Moves: `states_stance`, `concrete_referent`, `pushes_entrenched`, `escalates`, `meta_style`, `demands_evidence`, `offers_out`, `concedes_point`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-107: partner's ai-archive concept and 'alignment': 'is any of this accurate?' (ai summary of his repo); 'your repo doesn't give me a problem to solve — like playing a video game with a movie disk of interstellar'; 'adhd means i need it explained interactively with breadcrumbs'; 'let's get agreement on the fundamental problem, then whether alignment is the best solution'; partner: 'that is completely wrong', 'gpt5 thinks you do not understand anything at all'; 'that is an assumption you have that i do not — likely the disconnect, let me research'; 'i'll meet you halfway'; 'you've cemented a lot of things as fact'; 'show the entire conversation as a link so i can further my research'; 'the desire t […] (veteran-modder, escalated, quality 5)

- **self**: […] How is that relevant
- **veteran-modder**: Yeah probably, it still needs a lot of work, the idea is fully formed in my head and I have multiple documents for it, but that is just a readme I heavily revised multiple times today.
- **veteran-modder**: You would have to familiarise yourself with the concept of the Library of Babel from Jorge Luis Borges book "The Library of Babel"
- **self**: All in all this repo gets into the side of ai that confuses me beyond belief. I see this a lot in various groups where things get a bit chaotically exhaustive. Like I’m jumping into page 100 of a book without any idea what the premise is
- **veteran-modder**: Here is a single line summary from my conversation with GPT5 /  / "A navigable world-scale digital environment for AI behaviour, preservation, provenance-anchored training, and loss-recovery using deterministic seed-space topology." /  / But even then that doesn't do the idea justice either. /  / Just understanding the idea of the Library of Babel should be enough to help you.
- **self**: I do see these visions a lot. Like not yours specifically but the ethical and futuristic predictions of ai always confused the hell out of me because they jump into some understanding I haven’t been given
- **veteran-modder**: Essentially I think it is just that most people think current AI models are sentient, I however do not. I actually wrote a one page proposal for rephrasing terminology we use around AI because of that, I believe we should refer to current models as IA for Interpretive Algorithm, but thats another thing entirely.
- **self**: [link]
- **self**: Your repo reminds me a lot of this discord and I don’t understand their stuff either
- **veteran-modder**: I might take a look, not many people there, whats it like? I do actually have a few servers space for once I think, I was in 100 up until the other day.
- **self**: I’m not sure these days honestly but it has a lot of info and visions similar to what you talk about in the repo
- **self**: Maybe you could explain it to me so I could finally understand lol
- **self**: But your repo is alienating to me for the same reason. I don’t have any context on why any of the stuff you’re saying matters
- **veteran-modder**: I would be happy to, ask some questions, lets start with what you don't understand which I believe is the Library of Babel concept?
- **self**: basically we’re in this arms race with china rn. Reason there’s zero moderation is due to race to asi. If we regulate/moderate ai then china will basically destroy us
- **veteran-modder**: "The Library of Babel" is a short story by Argentine author and librarian Jorge Luis Borges, conceiving of a universe in the form of a vast library containing all possible 410-page books of a certain format and character set. - Wikipedia
- **self**: Anyway I don’t know man it’s all a bit much lol. I’m an ADHD adult male who just finds problems in life and finds solutions. Usually with code. Your repo doesn’t give me a problem to solve. So it’s like trying to play a video game with a movie disk of Interstellar. There’s nothing to play
- **self**: if that makes sense
- **veteran-modder**: I comprehend it but I don't understand it on a personal level
- **self**: in a PlayStation where the games are digital round disks
- **self**: actually that’s a bad example since PlayStations can play movies lol
- **self**: Didn’t you write it?
- **veteran-modder**: write what? I was referring to your explanation about ADHD etc
- **veteran-modder**: the repo, yes
- **veteran-modder**: AI helped me revise it a lot though
- **self**: usually adhd just means I struggle to understand something unless it’s explained interactively. Where I can participate in the learning by asking questions and given some breadcrumbs to follow
- **veteran-modder**: did you never end up checking out my Gallery of Babel application? Which is capable of generating 80 million random characters from the entire unicode range or any individual preset, or combination of presets in around ~2.6 seconds?
- **veteran-modder**: Well I am happy to explain it, have had to for everyone else I have tried to explain the idea to, even AI models. /  / You understand alignment issues and drift in AI models right?
- **self**: I just don’t understand their problem to solve
- **self**: explain that to me and stuff will start to click lol […]

Moves: `probe_expert`, `states_stance`, `asks_clarifying`, `demands_evidence`, `meta_style`, `pushes_entrenched`, `self_corrects`, `concedes_point`, `invites_pushback`, `analogy`

Why it worked or failed: Stance held without a new referent, so the partner argued the framing rather than the fact.

### r-108: education and standardized testing: 'i sometimes wonder if adhd is real or if kids are bored'; 'none of that is relevant to anything i said' → 'oh ok, let me reread with that context'; 'the way things have always been done is a shitty reason to keep doing them and i stand by that'; 'i don't like being a vessel for information i haven't vetted myself — i'm 99.9999% sure i'm human'; 'if the research doesn't confirm my findings, give me actual sources'; where to use an llm in a creative mod: 'the boring parts' (modder, redirected, quality 5)

- **modder**: […] Tbh that’s an interesting point of view
- **modder**: I have my own similar opinions like that but none quite as grandiose as “Am I human?”
- **self**: well I don’t ask myself that every day
- **self**: it’d be a waste of time to confirm 0.0001% chance
- **self**: Or whatever the decimal
- **self**: I’m just saying everything I do and know and understand, I’ve spent my life proving myself.
- **self**: Some things obviously I’ll pin as ‘learned externally’ and come back to if I ever need to verify/validate it for some argument or some relevant understanding I’m working on
- **self**: The whole problem with politics is people don’t know how to critically think or reason
- **modder**: I don’t know if I could call that the WHOLE problem.
- **self**: So I conclude there is no solution despite my childhood self wanting to find one some day. Never made sense how we were able to find some complex science such as prion disease and misfolded protein, but we can’t even decide on immigration policy or anything. My step dad today said ‘if trump cured cancer people probably still would deny him’. Didn’t seem to take when I said ‘ok but what about if Joe Biden did that??’ Would you vote him? /  / The whole notion that if the house and the (forget the word, executive branch group of people) are not the same ‘side’ then nothing gets done is idiocy
- **modder**: Congress and the White House btw
- **self**: what’s the word for the president’s closet/basement/group lol that’s such a momentum breaker of a tip-of-the-tongue lol
- **modder**: House + Senate = Congress
- **modder**: “President’s Cabinet.” Although sometimes just called the White House.
- **self**: Well I was talking about whatever group is in the executive branch under the president but your explanation works too.
- **self**: People are incapable of judging ideas on their own merit
- **self**: Adults can’t be retaught and mostly are stuck in their ways. So that’s why I care heavily about education. The only way to actually make any change is education reform
- **self**: Thanks
- **self**: Anyway I’m saying education systems should teach the value/utility of the knowledge, promoting base human desire to achieve it. For example much of youth wants to be the next Mr.beast lol. They see the utility and value of his content almost immediately: $$$. /  / The labarynth of the reward cycle, to go from obscure boring history, to trigonometry, to eventual college, to money, is not taking advantage of base human anatomy, evolution, and psychological understandings at all.
- **self**: The tests while in good intent, do not do what they’re designed to do in my lived experience. If you’re saying the research does not confirm my findings I’ll say either the research is skewed (which I will look into if you give me actual sources) or I’ll say it’s changed recently
- **self**: Frankly I hope the latter. But probably the former
- **modder**: Brb gotta drive home
- **self**: I’m sure there’s a world of understanding that you have that I don’t. While I would appreciate the same respect I am aware being me and so different from the avg person I’m not likely to get that. That is probably why I probably seem like an angry dick sometimes. But overall I appreciate you and these conversations. To invalidate mine because it’s not factually based or researched can be obnoxious but I’ve learned to live with it.
- **self**: Maybe when I was a kid I took ‘be yourself’ too literally. Modern education systems simply want to browbeat people into society it feels like
- **self**: I mean it’s not like I hate myself, I’m depressed, or anything. Just I struggled a lot and have always wanted to do better to the next generation
- **self**: dunno if it’s an Iowa thing but many people don’t volunteer or really care about the issues.
- **self**: Got a brother who parties all day and smokes weed going ‘yeah world sucks. More you learn and think about it it sucks’
- **self**: Another one works with a cnc machine. Actually my youngest (brother). Absolutely brilliantly he just went to trade school, got certified in something with CNC machines, and makes 40-50k a year
- **self**: But many people I've talked to online, in person, everywhere just feel content bringing kids into this, working 9-5, 'relaxing' in front of a tv or with alcohol or something. I really don't get it lol
- **self**: Cabinet. 😂 idk why i couldn't rememember. But you're right, I meant Senate/House […]

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `self_corrects`, `demands_evidence`, `meta_style`, `invites_pushback`, `concrete_referent`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-109: crypto vs banks: 'fear of it means it's good to invest in'; 'look what you're not understanding is the negligibility of mining on value — look exclusively at price graphs'; 'your main issue is you've been corrupted by the hype'; 'if you want to prove you're looking at it objectively, explain how the word skeptical is even relevant' (screenshot as referent); partner: 'i was just curious, i pivoted the topic' → 'ohhh that was not clear... why did i assign a smaller weight to those messages? i definitely wasn't objective. fuck lol' (modder, conceded, quality 5)

- **self**: […] I disagree, given you *immediately* mentioned being 'skeptical' about crypto. When there wasn't even something to be skeptical about, in the context i mentioned it in.
- **modder**: smh spoken like a man who hasn't carried a mattress out of a burning building
- **self**: So you seem highly opinionated about it lol
- **self**: have... have you done this before?
- **modder**: Don't get too excited, it was just a joke lol
- **self**: hahahaha
- **self**: look if you want to prove you're looking at it objectively, explain how in any context, that mentioning you're skeptical of crypto is relevant
- **modder**: But look, I think I mostly agree with you on this. Don't think of me as moronic on the matter. I see a lot of potential in the TECHNOLOGY. Perhaps the better way of summarizing it is "The tech is cool, but the consumers are so stupid they're ruining it for me."
- **self**: Like I would probably believe you if you could rationalize it
- **self**: Really
- **self**: And there's no shame in being polluted by the garbage crypto junk that's out there either or the hype cycle claims
- **self**: I'm gullible af back then anyway, invested a lot
- **self**: mostly because my brother was into it and i rarely hang with him so it was something we could do together
- **self**: Not that I lost much either.
- **self**: I wish I could say the same about my brother...
- **modder**: Well look. I don't know if I can say I'm objective, but I think I am. I am using my education on economics and monetary policy and applying it to the trends I see in the crypto market. My opinions are not driven by anyone who has interacted with the crypto market. I can't decide for myself if that's objectivity, but my gut says it is.
- **self**: Exclusively and highly specifically answer how the word 'skeptical' is relevant to the conversation in this image.
- **self**: Because the conversation was about AI.
- **self**: You don't see why that seems like you may be opinionated heavily? the sheer mention of crypto having a reaction that got us into the whole debate about whether it's viable crypto? the only point i was making was i remember the fear in the early days of crypto.
- **modder**: Well, can't skepticism be based in objectivity?
- **modder**: tbh I was just curious what your opinion on it was. So I pivoted the topic.
- **self**: ohhhhhhhh
- **self**: that was not clear lmao
- **modder**: My apologies, then.
- **self**: no worries i'm sorry too. i made presumptions based on that comment and put more weight in it than the other followup messages you sent
- **self**: I mean if you're answering honestly, anyway.
- **self**: Yeah you did say this.
- **self**: and this
- **self**: and this
- **self**: why did i assign a smaller weight to those than the first message? i definitely wasn't objective […]

Moves: `states_stance`, `pushes_entrenched`, `escalates`, `demands_evidence`, `concrete_referent`, `analogy`, `self_corrects`, `apologizes`, `meta_style`

Why it worked or failed: Held to one concrete referent until the partner produced it, then conceded the part that was answered.

### r-110: android sandboxing and a maui launcher: 'it doesn't sound like you're interested in listening... i don't think it can be done but lmk if you prove me wrong'; escalates into 'there's no way you wrote this entire thing from scratch yourself'; 'i haven't slept in 3 days maybe i'm paranoid'; partner calmly: ai wrote parts, 'i'm not doing mind games, i promise'; 'fuck dude i don't like accusing people of shit... i mean i was right'; partner: 'if you want my thoughts on a tool, state that explicitly, otherwise i'll be like cool and pessimistic' (veteran-modder, redirected, quality 4)

- **self**: it's just so dead simple compared to the nonsense i was trying with qt, maui, and avalonia
- **veteran-modder**: yeah I figured I probably should have gone about a different approach, I am trying to make a mobile version of the launcher, got everything built for it but I am struggling to get access to the "/Android/data/com.aspyr.swkotor2/files" directory in order to swap the files for playing K1/K2
- **self**: so what people do for especially mobile support is the same thing
- **self**: i'm not sure what your launcher does
- **self**: but i'm saying the world has kinda leaned towards hosting local webservers with a few lightweight javascript/static files
- **self**: this is your gui
- **self**: then you deploy with a single command
- **self**: e.g. `npx -y [partner]-app`
- **self**: it depends what your'e doing though the backend isn't going to be able to move files around on their phone
- **self**: but if you want it to launch the game yeah that's doable
- **self**: there's no way to mod kotor without a computer
- **self**: simple modifications maybe but never full support
- **veteran-modder**: pretty much it just renames a bunch of files, that's the old .bat version of the launcher. /  / I recently finished building the C# WinFormsApp version for Windows which is a little more fancy, looks like this.
- **self**: looks good
- **self**: why are you asking me if you've already done it
- **veteran-modder**: yeah, no worries, thanks for getting back to me about it though. /  / I just need to figure out a way to access the directory, then I can get it working. /  / That's the windows version, not the MAUI Android version.
- **veteran-modder**: That's the mobile version currently, I probably need to do it all in java to bypass the restrictions on the Android/data directory tbh but I figure there must be a way to do it.
- **self**: alright well good luck it doesn't sound like you're interested in listening to me anyway and more that you'd rather complain about your problem to someone. i do the same thing lol
- **self**: most likely you didn't consider android and ios apps are sandboxed
- **self**: i don't think it can be done but lmk if you prove me wrong lol
- **veteran-modder**: I am listening and I am aware they are sandboxed, but apps can access that directory, that is there are apps that can.
- **self**: the install method has always been computer -> phone
- **veteran-modder**: yeah, it still is, this is just meant to launch it and to swap the files that have to alternate for launching k2 or k1
- **self**: i'm not sure why you're doing it like this
- **self**: i thought the whole point of maui was to write a singular gui app and have the same gui and app run exactly the same way on all operating systems in an agnostic way so you don't have to learn the specifics of those operating systems
- **veteran-modder**: laziness I guess, I hoped it would be quick lol
- **self**: i feel like you've been talking about the launcher for a year htough
- **self**: i remember seeing screenshots in 2023
- **self**: it all looks like it took about that long anyhow
- **self**: it does look quite good […]

Moves: `states_stance`, `invites_pushback`, `escalates`, `pushes_entrenched`, `meta_style`, `apologizes`, `self_corrects`, `demands_evidence`

Why it worked or failed: Stance stated first, pushback invited; the partner answered the question instead of the tone.

### r-112: why isn't everyone treating ai as revolutionary: 'so i just assume i'm wrong about ai being anything more than a gag — it's obnoxious to feel like i'm living in delusion and have nobody able or willing to tell me otherwise'; 'is this relevant? i feel like i'm losing my mind'; claims group reasoning beats individual → partner: 'we call that groupthink' → 'i guess i answered my own question — well, the conversation allowed me to'; 'i wouldn't have reached that conclusion until i explained the thought process to you' (modder, conceded, quality 5)

- **self**: But 'a lot' is subjective
- **self**: A lot is *always* subjective
- **modder**: Pick away but if you mean right now I am multi-tasking atm
- **self**: Even if you have domain specific knowledge it's *always* subjective
- **self**: My problem in the workforce is providing something I inherently need to believe I will never have because that facilitates my abilities
- **self**: The workforce prioritizes and promotes heavily the ability to provide overwhelming confidence in those abilities in a way that convinces others
- **self**: So basically someone suffering from the extreme form of the Dunning Kruger effect is the most effective at getting the job than me
- **self**: confidence seeems to exude from oneself and rub off on others systemically and in a way that overwhelms and distracts from objective reality. most likely a flaw of the human condition
- **self**: all of that is nonimportant to what you'll find more important to discuss
- **self**: Yeah basically this
- **self**: Your ability to say what i just explained in several paragraphs, in just 18 words is the most valuable skillset when working with AI right now
- **self**: AI is based on context, semantical understanding, and every token counts
- **self**: A token is more or less equivalent in definition to a word
- **self**: Using the correct concise words to describe something is more likely to get more qualitative responses from AI
- **self**: Since most other people will be describing those things the same way, meaning it's more likely to be in the benchmarks/training data
- **self**: If that makes any sense at all.
- **modder**: actually it does
- **modder**: I didn't actually consider that's what makes conciseness in prompting so useful before now though
- **modder**: My wife should use more Copilot, then. Her business writing professor in college said that her "writing style was concise to the point of cold."
- **modder**: Which holds the record of the second-best feedback either of us ever got from a professor. #1 was being when my professor wrote in her response to a paper of mine that I have "An obvious enthusiasm for the explosives industry."
- **self**: Figured as much thanks for reiterating I tend to be self-conscious in nature and i don't like that about myself really cus i know objective reality is not my immediate perception but yeah communicating generally is difficult for me for this reason i'm somewhat sensitive. Mostly I ignore it. The reaffirmation helps. Felt I should clarify what my brain is doing, cus while my brain is doing things surface thoughts like that isn't inherently me but the trigger exists and thus the prompt for clarification.
- **self**: Yeah I imagine AI right now has the wrong people trying to use it. Like some sort of negative progress cycle of some sort
- **self**: it's counter-intuitive that the most capable person to be using it is the one that doesn't know that they know they're the best at using it
- **self**: Trying to explain that in any context is like pulling teeth
- **self**: Probably could say this about a lot of things though. For example I just watched S4 of Attack on Titan and wondered why in the heck the writing became atrocious out of nowhere despite S1-3 being amazing
- **self**: Learned the 'time-constraints' and various industry standards that are unlikely to change and not prioritizing 'result-driven science-backed' approaches is to blame
- **self**: Pretty much the same reason hollywood is failing right now despite billions and billions being shilled into the industry
- **self**: Is this relevant?
- **self**: I feel like I'm losing my mind
- **self**: Sorry my brain does this sometimes and the ultimate desire to talk through it burns in me 😂 […]

Moves: `states_hypothesis`, `invites_pushback`, `meta_style`, `self_corrects`, `concedes_point`, `apologizes`

Why it worked or failed: Repair moves (apology, self-correction) reopened the exchange after it had tipped.

## sources

- `discord`: /home/brunner56/boden_wizard_chat_context/archive/originals/discord/discord_exports/discord_dms/: Eight DM exports with technical peers, 2025-02 to 2026-08. Alpha records were cut by cut_alpha.py from the aggregator's in-flight window notes (112 windows, lo/hi message indexes) and re-sliced from the originals; each record keeps the 30-turn stretch densest in engine moves. Handles and links replaced. The canonical aggregate (docs/essays/_sources/debate-dataset/discord_debates.jsonl, 109 stretches, 7,754 turns) supersedes this cut through /evolve.
- `discord`: /home/brunner56/boden_wizard_chat_context/archive/originals/discord/discord_exports/openkotor_discord_msgs/: Seven public-channel threads (engine rewrites, tools, off-topic) where the subject argues in a group.
