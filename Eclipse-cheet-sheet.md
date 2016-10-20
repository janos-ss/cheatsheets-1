Initial setup
-------------

- Download RCP version
- Edit `eclipse.ini`

        -showLocation
        -Xms512m
        -Xmx966m

Workspace setup
---------------

- Add **Package Explorer** view
    - Window | Show View | Other... | type "Package"
    - Drag it to the left panel, drop the useless Project Explorer view
- Setup **Package Explorer** view to use **Working Sets**
    - Click on the small triangle near the top-right corner
    - Select Top Level Elements | Working Sets
- Add **Problems** view
    - Window | Show View | Other... | type "Problems"
    - Drag it to the leftmost tab in the bottom panel
- Turn on line numbers
    - Preferences | search: line
    - General | Editors | Text Editors | Show line numbers
- Make Maven show XML tab in POM editor by default
    - Maven | User Interface

Keyboard shortcuts
------------------

    control 1           quick fix
    F12                 focus to editor
    alt /               complete text
    control k           find next match of last search or highlighted text
    F3                  open implementation / jump to declaration
    control alt h       open call hierarchy
    F11                 debug last configuration
    control F11         run last configuration
    control shift i     inspect value
    control t           quick type hierarchy
    F4                  open type hierarchy view
