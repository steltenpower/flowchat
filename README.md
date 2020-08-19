# MultiTouchGoLangDesign
Draw processes and channels (like chips and wires), with 3 finger moves combined with speaking 'process A, datachannel D, process B'.
(This is similar to the interaction explained in [Train-of-Thought](https://github.com/steltenpower/Train-Of-Thought).

Then generate GoLang code (which can indirectly be run in a webbrowser through WASM for a no-install implementation).

Also look into [drawFBP](https://github.com/jpaulm/drawfbp)

In this 'electronics-like' view every process can internally be a new level of abstraction/implementation
There can also be a tree-view where processes are 'folders' with other processes in them, where the channels are also drawn as wires.
(Many years ago I actually coded a demo of this folder thingy to later see it mentioned in a promotion report without my name being mentioned ...)
In the code view (and of course the 3 types of views are synchronized) channels are passed to the processes by parameter.

The world is parallel, let's model it like that (from the get-go)

Some much older writing on the subject: (http://communiputing.org/)

Maybe something useful via http://www.opencircuits.com/Software_tool#PCB_Layout
https://resources.jointjs.com/demos/routing
https://neyric.github.io/wireit/docs/index.html#examples
https://marianogappa.github.io/software/2020/04/01/webassembly-tinygo-cheesse/

sidenote: met symbooltjes aangeven hoe onderzoeksdata tussen HPC, publiceren, archief, etc. beweegt
