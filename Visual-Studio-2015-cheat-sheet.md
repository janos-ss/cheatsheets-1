Debugger key bindings
---------------------

    F10    step over
    F11    step into
    S-F11  step out
    F5     resume

Key bindings
------------

http://visualstudioshortcuts.com/2015/

    control ,               open class (symbol too?)
    control ;               open file
    control m control x     expand region
    control k t             open call hierarchy
    control alt pgdown      next tab
    control shift b         build
    shift F12               find all references
    control r t             run test method in current enclosing block
    control r control t     debug test method in current enclosing block
    F12                     follow reference / go to definition 
    control x               delete current line (puts on clipboard)
    control F5              run selected start project
    control tab             switch between window tabs
    alt f c                 close window tab
    contorl .               quick fix (convenient for using {} blocks, implement interface, etc)
    contorl k s             opens the code snippet window (surround with if, for, do, class, etc)
    control k f             format (indent) selected text
    control k d             format (indent) entire document
    control k c             comment selected text block with //
    control k u             uncomment selected text block
    control k k             toggle bookmark
    contorl k n             jump to next bookmark
    control -               go back

WANTED! key bindings
--------------------

    ?      jump to next error

Typed shortcuts, other tips
---------------------------

That is, short key sequences that when typed, trigger the insertion of some text block.

- `///` - Generates a *summary* block (documentation).
- `override` - Triggers a selector window of base class or interface methods that can be overridden, and upon selection generates a proper function signature with dummy body.
- `}` - Formats the block it closes. This is useful. If you need to enclose existing code in a `{}` block, you don't need to worry about re-indenting, simply type the opening line of the block with the `{`, and then close the block with `}` and press enter. The moment you press enter the block will be re-indented properly.
- To implement interface methods, move the cursor on the interface name and press the context menu key. A menu will pop up that will give the option to implement the interface or to implement it explicitly. This will create regions too.
