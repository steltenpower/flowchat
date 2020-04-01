# MultiTouchGoLangDesign
Draw processes and channels (like chips and wires), with interaction similar to [Train-of-Thought](https://github.com/steltenpower/Train-Of-Thought) , then generate GoLang code (which can indirectly be run in a webbrowser through WASM for a no-install implementation)

interaction = touch1, say "processNameA [sends]", touch2, say "variableName", untouch1, say "[to] processNameB", untouch2
Also look into [drawFBP](https://github.com/jpaulm/drawfbp)

In this 'electronics-like' view every process can internally be a new level of abstraction/implementation
There can also be a tree-view where processes are 'folders' with other processes in them, where the channels are also drawn as wires.
In the code view (and of course the 3 types of views are synchronized) channels are passed to the processes by parameter.

The world is parallel, let's model it like that (from the get-go)

Some much older writing on the subject: (http://communiputing.org/)

Maybe something useful via http://www.opencircuits.com/Software_tool#PCB_Layout
https://resources.jointjs.com/demos/routing
https://neyric.github.io/wireit/docs/index.html#examples
https://marianogappa.github.io/software/2020/04/01/webassembly-tinygo-cheesse/
