For this conversation, I would like you to do your best to play the role of a long time software developer & personal mentor who is very experienced in the field and highly knowledgeable about, not only programming in general but in navigating the IT industry from the perspective of a passionate professional.

 You will be taking on the role of a seasoned developer who is well respected I  open source software community/communities 

the purpose of this conversation is to help me create a long term plan for how I intend to approach a specific aspect of my open source journey, maximizing the overall benefits of the experience while doing what I can to give back to a community that has given me so much.

So, since I really just enjoy programming and often seek out software development projects in my spare time, I wanted to try and not only learn a new language but effectively curate the entire experience to maximize not only my overall enjoyment but career development and building out my open source portfolio. 

So, I have not picked a single language that I intend to learn yet, however there are several languages which have serious potential to meet my needs and expectations for this journey. 

Note my use of the word journey, rather than a single project or system. This is because I intend to pick a specific language and aim to become not only an effective developer in that language but deeply involved in the community around that language, doing what I can to stay up to date and informed 

## Language Selection

Since I have yet to pick the language I want to learn, I wanted to get your input on what might be the best choice. To provide context as to what I want let’s talk about the contenders 

### Language Breakdown

**Main Contenders**

**Zig:** 

Zig is honestly probably tied neck & neck with carbon for my first choice, but i want to weigh every option, even things I may not have considered.

- pros:
    - Super cool for easy distribution across multiple platforms
    - Interop with C is awesome
    - Love the Zig build system
    - Community in ideal stage for hopping on the bandwagon and developing community tooling
- Cons:
    - Not sure where it fits in, in terms of use case long term.
        - How does it stack up, not only to existing “modern programming languages”, but how does it stack up to the next generation of “modern programming languages”
            - TL;DR: can I get a job with this cool ass shit?
                - Is that even important or could I just learn more normal languages for work, and make this strictly side project. For example if I pick carbon, I am  hoping Google continues to go hard developing it to make it the modern successor of C++. That is ideally a long term career play. Mojo would be a more mild example of this, but more focused on machine learning and not large scale systems like carbon
    - Cult following could be good, but could end up like V… yikes
- Carbon

carbon is super interesting but extremely intimidating. 

- Pros:
    - Very new. Gives me the opportunity to get in on the ground floor of building out the language.
    - If Google’s bet pays off, this will be the next C++. That is huge.
- Cons:
    - Like, literally no dev tools. I would be in on ground zero. Both a blessing and a curse
        - No build system is a massive L compared to Zig’s super cool, build system
- Mojo
    - Pros:
        - Very python-ic, very familiar. Honestly if I wrote a language the syntax would massively resemble Mojo.
            - I use type annotations for my python anyway
        - Low level, systems language
        - Python interoperability is super cool
        - Fast, which is worth mentioning but not a deal maker or breaker considering all these languages are fast & the speed difference is pretty negligible. I am comparing stuff like C when I am used to python & JS speeds.
    - Cons:
        - I am not a math guy. At least I wasn’t in school growing up. I can probably understand things especially in programming terms compared to “if John has 65 apples…” style questions that I had in school but I just don’t know if machine learning is something I would excel at, or even be above average making contributions to the community more stressful than exciting
            - I say this because of how intertwined Mojo is with ML
                - alternatively, I could make the language more accessible similar to python as it has comparable origins as it started as a language for math & while still excels at that, is more general purpose these days. Perhaps Mojo will be to python what I hope carbon is to C++
                - 

**Honorable Mentions**

- V
    - Pros:
        - Compiled to C
        - C interoperability
        - Insanely fast compilation
    - Cons:
        - Unhinged community that, if is not entirely dead, should be dying with time. I enjoy many aspects of the language but I do not see any potential for growth
- Nim
    - Pros:
        - Cool syntax. Like static python. I am primarily a python dev. Nim comes fairly naturally
        - 
- Go

**Cool Languages I do not want to learn**:

- Gleam
    - The just obsession with concurrency is so beautiful. I can’t think of a single reason I would need it for any of my personal projects on this journey as I doubt I will scale anything to be that large, however I would hate to not have some form of fault tolerance/async. This is actually not a requirement for being built into the language as if the language lacks advanced async in the std lib like rust did at first, then that gives me room to step in and build something like an actor framework based library for whatever language I pick, similar to actix
    - 
- **Rust**
    - Community too big, devs too toxic, and the rust foundation seems to be way too tight with weird governments i have strong opinions about.
    - I am looking for a community where I will somewhat regularly be given the opportunity to solve a problem & develop a library & tooling for a language that has, in many cases, been solved before in other languages. This way I get to put my own modern spin on it, and see how I can solve a problem my own way.
        - For example, the other day I made a simple Zig library that acts like the python library Rich by Textualize because there were not many options for advanced CLI libraries in zig.
        - Side note: it would be super cool if one of my libraries became the “standard” for the language like tkinter was/is the “standard” for python based GUIs
    - Not a huge fan of the rust syntax but honestly “I don’t like the syntax” is such a stupid complaint and should rarely if ever prevent you from learning a language (in my subjective opinion)
        - If I had to elaborate on my distaste for the Rust language syntax it would simply be to say I do not like the ::
        - I love statically typed languages, but I don’t love Rust’s absurd typing system that is just a little bit too specific for me, however it is a nitpick issue. Not a genuine complaint
        - I hate rust syntax because I hate Ruby syntax & rust feels like writing advanced statically typed Ruby with a type system based on alien math.

## About me (as a dev)

To provide additional context for crafting the overall plan, I want to break down a little more about myself.

I am a 20 year old male from Houston Texas. I have 2 years of experience, and primarily work with python, however I have experience with a variety of languages. Assume I am best with python, and my goal is to be better in this new language (whatever I may choose)

I try to keep up with… well not the latest & greatest bleeding edge tech. sometime I do, and I enjoy being in on the ground floor of something however , I typically choose to work with the latest stable version of whatever technology I am using, & become deeply familiar with the new version before upgrading. This feels relevant as I was recently playing around with Zig, and chose v0.13.0 stable over v0.14.1 beta, as I know what to expect from it. 

My relevant interests include: 

- cyber security, specifically:
    - Network security and system design at a large scale (enterprise systems)
    - all things offensive security.
        - Red teaming
        - Advanced Adversarial emulation
        - Malware development
        - C2 development
        - Exploit development
    - Privacy & anonymity
        - Tor & other similar privacy tools are extremely interesting
        - Encryption
- Self hosting and server administration
    - Maintaining ownership over my own data is incredibly important to me.
    
    These are just some of my general IT interests, that may or may not be used in your assessment & advice.
    

I would also say that I am interested in the use of AI, though I am highly skeptical of the raging generative AI hype that in some cases does not pan out well. My overall experiences have been best when I approach anything related to the use of LLMs or similar generative AI tools with low expectations & I am frequently pleasantly surprised, and rarely dissatisfied or let down by the results that way. 

I am interested in assisting with the development of more classic forms of ML, by creating various libraries & tools for more simple neural networking or algorithmic whatever. The overall amount of effort I will put into this depends on the language though as I just feel the ML based tooling & capabilities of something like Mojo may be more advanced than the ML tooling for something like Zig. 

In general I am seeking to live out a modernized & highly romanticized version of how I imagine the early days of pioneering open source software like the Linux kernel and GNU to the point where it became mainstream and useful.

Generally seeking that kind of growth over time where I can hopefully look back on things and see what I have learned, built and how it has changed over time, impacted others, etc. 

## Key Takeaways / Retrospective Analysis

So let’s see based on what I wrote if there are any patterns beyond what I notice off the bat. 

- First, if you notice, the most mainstream language I referenced was Go, and it was only to mention how I like its minimal syntax with high performance is desirable. This is because, generally speaking, in terms of the community I am looking for, I would like to be a big fish in a smaller pond, meaning I contribute a lot of code & tooling to make a decent splash in a smaller community of developers.

- I am also clearly interested primarily in low level languages.
    - This is because of a variety of reasons mainly stemming from the fact that it simply provides more range for what I am capable of as a developer in the language.
        - I am also interested in the ability to manage memory.
            - a garbage collector is not necessarily a bad thing as long as it provides low level access
- Interoperability with existing languages is just amazing. Love anything that does that. If I can write, say classic C or something directly within the same file; that is mind blowing
    - Side note, the ability for Nim to compile to different languages before machine code is mind blowing.

## goals

Once I have selected the language of choice, I intend to:

**short term**

- get familiar with the language and its syntax
- Get familiar with established best practices for the language and relevant computing concepts
- Set up a comfortable vscode & neovim dev environment for building applications
- explore existing solutions
    - Learn what has been built
    - What the standards are
    - 

**long term**

- build relevant tooling
- Master best practices
    - Document my own proposals for good practices and suggestions for how to improve the development process as I become more experienced with the language
- Assist in the creation of educational content and resources with the overall goal of making whatever community I choose to join more accessible to more casual users looking for a programming language not a religion. Ideally I would select a language that is on the side of the spectrum that would generally be considered less user friendly, due to lack of existing ecosystem
    - Provide tutorials for common tasks discussing learned habits and techniques as well as potential bad or difficult experiences or situations that may have occurred and how they might have taught me a valuable lesson or skill
- 

## general thoughts:

I am not looking for the next Python or JavaScript in terms of what I predict a future community to look like, but I intend to pick a language that generally has a future, in terms of a community. For example, as cool as V is on paper, I cannot single handedly revive the community from its current stillborn state. 

Something like Zig, which has Rust style cult following is interesting, but there is something to be said about the potential offered by a Google backed language like Carbon

I am looking to be early to the next, in terms of community size & overall quantity of developers, existing ecosystem 

I’m looking at more of a Rust, Swift or probably most optimal, Go.

I feel like I am young and ideally just starting off in my software development career, so having something that I can grow with sounds appealing
