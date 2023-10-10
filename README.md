# flowchat
![](https://repository-images.githubusercontent.com/150806953/3b199200-bc4c-11eb-91a4-f3674a3e1509)
Draw processes and channels (like chips and wires), with 2-finger moves combined with speaking 'A sends X to B'
(This is similar to the interaction explained in [Train-of-Thought](https://github.com/steltenpower/Train-Of-Thought).

Then possibly generate GoLang code (which can indirectly be run in a webbrowser through WASM for a no-install implementation).

Also look into [drawFBP](https://github.com/jpaulm/drawfbp), specifically https://github.com/jpaulm/drawfbp/blob/master/lib/drawfbp_file.xsd

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
