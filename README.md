# Mnemonic Keymap

A keymap for all IntelliJ-based IDEs where most shortcuts have two keystrokes:
the first one defines a group and the second one defines an action in this group
(e.g. `Ctrl/Cmd+D, A` for **Debug > Attach to Process** or
`Ctrl/Cmd+N, U` for **Navigate > Find Usages**).

You may want to try out this keymap if some of the following features are important to you:

- Easy-to-remember mnemonic mappings
- Same shortcuts across different operating systems
- Fewer modifier keys
- No conflicts with system shortcuts
- No conflicts on non-English Latin keyboards

Specific key bindings are listed below by category.

Single-chord shortcuts:

- [Standard editor shortcuts](#standard-editor-shortcuts)
- [Standard macOS application shortcuts](#standard-macos-application-shortcuts)
- [Shortcuts for sequential actions](#shortcuts-for-sequential-actions)

Double-chord shortcuts:
- [Ctrl/Cmd+B (block) - manipulate code blocks](#b)
- [Ctrl/Cmd+D (debug) - running and debugging](#d)
- [Ctrl/Cmd+E (editor) - editor actions](#e)
- [Ctrl/Cmd+G (gather) - code folding actions](#g)
- [Ctrl/Cmd+I (inspect) - code analysis actions](#i)
- [Ctrl/Cmd+J (jump) - single-destination navigation](#i)
- [Ctrl/Cmd+K (kommit) - VCS actions](#k)
- [Ctrl/Cmd+L (line) - manipulate code lines](#l)
- [Ctrl/Cmd+N (navigate) - multiple-destination navigation](#n)
- [Ctrl/Cmd+P (project) - global project actions](#p)
- [Ctrl/Cmd+O (other) - IDE-specific and plugin-specific actions](#o)
- [Ctrl/Cmd+R (refactor) - bulk transformations](#r)
- [Ctrl/Cmd+T (test) - testing actions](#t)
- [Ctrl/Cmd+U (utilities) - global helper actions](#u)
- [Ctrl/Cmd+W (window) - manipulate tool windows](#w)

> **NOTE:**  Availability of the actions listed below depends on your IDE and installed plugins

## Single-chord shortcuts

### Standard editor shortcuts
| Windows/Linux    | macOS   | Action         |
|------------------|---------|----------------|
| `Ctrl+A`         | `Cmd+A` | **Select All** |
| `Ctrl+C`         | `Cmd+C` | **Copy**  |
| `Ctrl+F`         | `Cmd+F` | **Find**  |
| `Ctrl+S`| `Cmd+S` | **Save** |
| `Ctrl+V`         | `Cmd+V` | **Paste** |
| `Ctrl+X`         | `Cmd+X` | **Cut**  |
| `Ctrl+Y`         | `Cmd+Y` | **Redo** |
| `Ctrl+Z`| `Cmd+Z` | **Undo** |

### Standard macOS application shortcuts 
|      |                                   |
|--------------|-----------------------------------------|
|`Cmd+H`| **Hide Front Application** | 
|`Cmd+M`| **Minimize**| 
|`Cmd+Q`| **Quit** |
|`Cmd+,`| **Preferences** |

### Shortcuts for sequential actions
| Windows/Linux        | macOS                | Action                                                       |
|----------------------|----------------------|--------------------------------------------------------------|
| `F1`                 | `F1`                 | **Back**                                                     |
| `Shift+F1`           | `Shift+F1`           | **Forward**                                                  |
||||
| `F2`                 | `F2`                 | **Last Edit Location**                                       |
| `Shift+F2`           | `Shift+F2`           | **Next Edit Location**                                       |
||||
| `Ctrl+F2`            | `Cmd+F2`             | **Next Method**                                              |
| `Ctrl+F1`            | `Cmd+F1`             | **Previous Method**                                          |
||||
| `F3`                 | `F3`                 | **Find Next**                                                |
| `Shift+F3`           | `Shift+F3`           | **Find Previous**                                            |
||||
| `F4`                 | `F4`                 | **Next Occurrence of the Word at Caret**                     |
| `Shift+F4`           | `Shift+F4`           | **Previous Occurrence of the Word at Caret**                 |
||||
| `Ctrl+F4`            | `Cmd+F4`             | **Next Highlighted Error**                                   |
| `Ctrl+F3`            | `Cmnd+F3`            | **Previous Highlighted Error**                               |
||||
| `F5`                 | `F5`                 | **Next Change** / **Next Difference in Diff viewer**         |
| `Shift+F5`           | `Shift+F5`           | **Previous Change** / **Previous Difference in Diff viewer** |
|||
| `F6`                 | `F6`                 | **Next Emmet Edit Point**                                    |
| `Shift+F6`           | `Shift+F6`           | **Previous Emmet Edit Point**                                |
|||
| `F7`                 | `F7`                 | **Move Caret to Code Block Start**                           |
| `F8`                 | `F8`                 | **Move Caret to Code Block End**                             |
| `Shift+F7`           | `Shift+F7`           | **Move Caret to Code Block Start with Selection**            |
| `Shift+F8`           | `Shift+F8`           | **Move Caret to Code Block End with Selection**              |
||||
| `Ctrl+Shift+F7`      | `Cmd+Shift+F7`       | **Go to Containing Declaration**                             |
| `Ctrl+Shift+F8`      | `Cmd+Shift+F8`       | **Select Containing Declaration**                            |
||||
| `Ctrl+F6`            | `Cmd+F6`             | **Unselect Occurrence**                                      |
| `Ctrl+F7`            | `Cmd+F7`             | **Add selection for Next Occurrence**                        |
||||
| `F10`                | `F10`                | **Extend Selection**                                         |
| `F9`                 | `F9`                 | **Shrink Selection**                                         |
||||
| `Ctrl+F8`            | `Cmd+F8`             | **Step Into**                                                |
| `Ctrl+F9`            | `Cmd+F9`             | **Step Over**                                                |
| `Ctrl+F10`           | `Cmd+F10`            | **Force Step Over**                                          |
| `Ctrl+F11`           | `Cmd+F11`            | **Force Step Into**                                          |
| `Shift+F11`          | `Shift+F11`          | **Smart Step Into**                                          |
| `Ctrl+F12`           | `Cmd+F12`            | **Step Out**                                                 |
||||
| `Alt+Shift+Down`     | `Ctrl+Shift+Down`    | **Move Statement Down**                                      |
| `Alt+Shift+Up`       | `Ctrl+Shift+Up`       | **Move Statement Up**                                        |
| `Alt+Shift+Left`     | `Ctrl+Shift+Left`     | **Move Element Left**                                        |
| `Alt+Shift+Right`    | `Ctrl+Shift+Right`    | **Move Statement Right**                                     |
||||
| `Alt+Down`           | `Alt+Down`           | **Move Line Down**                                           |
| `Alt+Up`             | `Alt+Up`             | **Move Line Up**                                             |
||||
| `Alt+Left`           | `Cmd+Alt+Left`       | **Select Previous Tab**                                      |
| `Alt+Right`          | `Cmd+Alt+Right`      | **Select Next Tab**                                          |
||||
| `Ctrl+[digit]`       | `Ctrl+[digit]`       | **Go to bookmark X**                                         |
| `Ctrl+Shift+[digit]` | `Ctrl+Shift+[digit]` | **Toggle bookmark X**                                        |
||||
| `Ctrl+Space`         | `Ctrl+Space`         | **Basic Completion**                                         |
| `Ctrl+Alt+Space`     | `Ctrl+Alt+Space`     | **Second Basic Completion**                                  |
| `Ctrl+Shift+Space`   | `Ctrl+Shift+Space`   | **Type-Matching Completion**                                 |
||||
| `Ctrl+Tab`           | `Ctrl+Tab`           | **Basic Completion**                                         |

## Double-chord shortcuts

<a id="b"></a>
### First chord: Ctrl/Cmd+B (block) - manipulate code blocks

| Second Chord | Mnemonic    | Action                                   |
|--------------|-------------|------------------------------------------|
| `A`          | as          | **Save as Template**                     |
| `B`          | buffer      | **Paste from History**                   |
| `C`          | comment     | **Comment/Uncomment with Block Comment** |
| `D`          | definitions | **Generate Definitions**                 |
| `G`          | generate    | **Generate**                             |
| `I`          | implement   | **Implement Methods**                    |
| `O`          | override    | **Override Methods**                     |
| `P`          | paste       | **Paste as Plain Text**                  |
| `R`          | rearrange   | **Rearrange**                            |
| `S`          | surround    | **Surround With...**                     |
| `T`          | template    | **Insert Live Template**                 |
| `U`          | unwrap      | **Unwrap / Remove**                      |


<a id="d"></a>
### First chord: Ctrl/Cmd+D (debug) - running and debugging

| Second Chord | Mnemonic    | Action                               |
|--------------|-------------|--------------------------------------|
| `A`          | attach      | **Attach to Process**                |
| `B`          | breakpoints | **View Breakpoints**                 |
| `C`          | cursor      | **Run to Cursor**                    |
| `D`          | debug       | **Debug Selected Configuration**     |
| `E`          | evaluate    | **Evaluate Expression**              |
| `F`          | find        | **Show Execution Point**             |
| `G`          | go on       | **Resume Program**                   |
| `I`          | immediate   | **Navigate to Immediate Window**     |
| `J`          | jump        | **Jump to Statement**                |
| `K`          | konfig      | **Edit Configurations**              |
| `L`          | line        | **Toggle Line Breakpoint**           |
| `N`          | new run     | **Rerun**                            |
| `O`          | over        | **Stop**                             |
| `P`          | pause       | **Pause Program**                    |
| `R`          | run         | **Run Selected Configuration**       |
| `S`          | skip        | **Force Run to Cursor**              |
| `T`          | temporary   | **Toggle Temporary Line Breakpoint** |
| `U`          | update      | **Update Running Application**       |
| `V`          | value       | **Set Value**                        |
| `W`          | watch       | **Add to Watches**                   |
| `X`          |             | **Toggle Breakpoint Enabled**        |
| `Y`          |        | **Quick Evaluate Expression**        |
| `1`          |             | **Run... (select configuration)**    |
| `2`          |             | **Debug... (select configuration)**  |
| `3`          |             | **Run Context Configuration**        |

<a id="e"></a>
### First chord: Ctrl/Cmd+E (editor) - editor actions

| Second Chord | Mnemonic       | Action                                   |
|--------------|----------------|------------------------------------------|
| `A`          | all            | **Select All Occurrences**               |
| `B`          | bold           | **Markdown: Bold**                       |
| `C`          | case           | **Toggle Case**                          |
| `D`          | documentation  | **Quick Documentation**                  |
| `E`          | ends           | **Add Carets to Ends of Selected Lines** |
| `F`          | format         | **Reformat Code**                        |
| `I`          | implementation | **Quick Definition**                     |
| `I`          | italic         | **Markdown: Italic**                     |
| `J`          | juxtapose      | **Compare with Clipboard**               |
| `K`          | kode           | **Markdown: Code**                       |
| `L`          | link           | **Markdown: Link**                       |
| `O`          | oppose         | **Compare With**                         |
| `P`          | parameter      | **Parameter Information**                |
| `P`          | picture        | **Markdown: Insert Image**               |
| `R`          | replace        | **Replace**                              |
| `S`          | scratch        | **New Scratch File**                     |
| `T`          | through        | **Markdown: Strikethrough**              |
| `U`          | usages         | **Highlight Usages in File**             |
| `W`          |                | **Copy Path/Reference**                  |
| `X`          |                | **Close Tab**                            |

<a id="g"></a>
### First chord: Ctrl/Cmd+G (gather) - code folding actions

| Second Chord | Mnemonic    | Action                      |
|--------------|-------------|-----------------------------|
| `A`          | all         | **Expand All**              |
| `B`          | block       | **Fold Code Block**          |
| `C`          | collapse    | **Collapse**             |
| `D`          | definitions | **Collapse to Definitions**     |
| `E`          | expand      | **Expand**               |
| `O`          | open        | **Expand Recursively**            |
| `S`          | selection   | **Fold Selection/Remove Region**        |
| `T`          | toggle      | **Toggle Folding** |
| `X`          |             | **Collapse All**               |

<a id="i"></a>
### First chord: Ctrl/Cmd+I (inspect) - code analysis actions

| Second Chord | Mnemonic   | Action                     |
|--------------|------------|----------------------------|
| `A`          | analyze    | **Inspect Code**           |
| `C`          | calls      | **Call Hierarchy**         |
| `E`          | error      | **Error Description**      |
| `F`          | functions  | **Method Hierarchy**       |
| `I`          | imports    | **Imports Hierarchy**           |
| `N`          | name       | **Run Inspection by Name** |
| `S`          | stacktrace | **Analyze Stack Trace**    |
| `T`          | types      | **Type Hierarchy**         |
| `0`          |            | **Inspect This**           |

<a id="j"></a>
### First chord: Ctrl/Cmd+J (jump) - single-destination navigation

| Second Chord | Mnemonic    | Action                           |
|--------------|-------------|----------------------------------|
| `A`          | another     | **Move Caret to Matching Brace** |
| `B`          | breadcrumbs | **Jump to Navigation Bar**       |
| `C`          | class       | **Type Declaration**             |
| `D`          | declaration | **Go to Declaration**            |
| `E`          | editor      | **Jump to Source**               |
| `F`          | files       | **File Path**                    |
| `P`          | project     | **Locate in Solution View**      |
| `R`          | related     | **Switch Header/Source**         |
| `S`          | switcher    | **Switcher**                     |
| `T`          | terminal    | **Open in Terminal**             |
| `0`          |             | **Select In**                    |

<a id="k"></a>
### First chord: Ctrl/Cmd+K (kommit) - VCS actions

| Second Chord | Mnemonic | Action              |
|--------------|----------|---------------------|
| `A`          | add      | **Add to VCS**      |
| `B`          | branches | **Branches**        |
| `C`          | commit   | **Commit**          |
| `D`          | diff     | **Show Diff**       |
| `F`          | fetch    | **Fetch**           |
| `K`          | kommit   | **Commit and Push** |
| `L`          |          | **Pull**            |
| `P`          | push     | **Push**            |
| `R`          | requests | **Pull Requests**   |
| `U`          | update   | **Update**          |
| `0`          |          | **VCS Operations**  |

<a id="l"></a>
### First chord: Ctrl/Cmd+L (line) - manipulate code lines

| Second Chord | Mnemonic  | Action                            |
|--------------|-----------|-----------------------------------|
| `B`          | bookmark  | **Toggle Bookmark**               |
| `C`          | comment   | **Comment with Line Comment**     |
| `D`          | duplicate | **Duplicate Line or Selection**   |
| `F`          | flag      | **Toggle Bookmark with Mnemonic** |
| `G`          | go        | **Go to Line**                    |
| `I`          | indent    | **Auto-Indent Lines**             |
| `J`          | join      | **Join Lines**                    |
| `N`          | numbers   | **Show Line Numbers**             |
| `R`          | reverse   | **Reverse Lines**                 |
| `S`          | sort      | **Sort Lines**                    |
| `W`          | wrap      | **Soft-Wrap**                     |
| `X`          |           | **Delete Line**                   |

<a id="n"></a>
### First chord: Ctrl/Cmd+N (navigate) - multiple-destination navigation

| Second Chord | Mnemonic       | Action                                      |
|--------------|----------------|---------------------------------------------|
| `A`          | all            | **Go to Symbol**                            |
| `B`          | bookmarks      | **Show Bookmarks**                          |
| `C`          | class          | **Go to Class**                             |
| `E`          | edits          | **Recently Changed Files**                  |
| `F`          | find           | **Find in Files**                           |
| `I`          | implementation | **Go to Implementations / Derived Symbols** |
| `J`          |         | **Structure / Go to File Member**           |
| `K`          | kode           | **Go to Implementation**                    |
| `L`          | list           | **Show Usages**                             |
| `N`          | navigate       | **Navigate To**                             |
| `O`          | open           | **Go to File**                              |
| `P`          | peers          | **Go to Related Symbol**                    |
| `R`          | recent         | **Recent Files**                            |
| `S`          | super          | **Go to Super Method / Base Symbols**       |
| `T`          | text           | **Search Text**                             |
| `U`          | usages         | **Find Usages**                             |
| `V`          | visited        | **Recent Locations**                        |
| `W`          | watch          | **Add to Watches**                          |
| `X`          | xtended        | **Find Usages Settings**                    |
| `Z`          |                | **Recent Changes**                          |
| `0`          |                | **Search Everywhere**                       |

<a id="o"></a>
### First chord: Ctrl/Cmd+O (other) - IDE-specific and plugin-specific actions

| Second Chord | Mnemonic | Action                                                      |
|--------------|----------|-------------------------------------------------------------|
| `A`          | apply    | **Apply Code Changes / Hot Reload** (Android Studio, Rider) |
| `D`          | device   | **Select Device** (Android Studio)                   |
| `E`          | edit     | **Edit Property Value** (Android Studio, i18n)              |
| `R`          | restart  | **Apply Changes and Restart** (Android Studio)              |

<a id="p"></a>
### First chord: Ctrl/Cmd+P (project) - global project actions

| Second Chord | Mnemonic  | Action                                      |
|--------------|-----------|---------------------------------------------|
| `A`          | ant       | **Run Ant Target**                          |
| `B`          | build     | **Build Project/Solution**                  |
| `C`          | clean     | **Clean Project/Solution**                  |
| `N`          | nuget     | **NuGet Quick List**  (Rider)               |
| `O`          | open      | **Open File or Project**                    |
| `R`          | rebuild   | **Rebuild Project/Solution**                |
| `S`          | structure | **Project Structure**                       |
| `T`          | test      | **C# Interactive** (Rider)                  |
| `U`          | update    | **Reload All from Disk**                    |
| `W`          | with me   | **Code With Me**                            |
| `X`          |           | **Cancel Build**                            |

<a id="r"></a>
### First chord: Ctrl/Cmd+R (refactor) - bulk transformations

| Second Chord | Mnemonic  | Action                              |
|--------------|-----------|-------------------------------------|
| `A`          | all       | **Replace in Files**                |
| `B`          |           | **Reformat File**                   |
| `C`          | cleanup   | **Reformat and Cleanup**            |
| `D`          | duplicate | **Copy**                            |
| `E`          | extract   | **Extract Method**                  |
| `F`          | field     | **Introduce Field**                 |
| `G`          |           | **Silent Reformat and Cleanup**     |
| `I`          | interface | **Extract Interface**               |
| `J`          | jump      | **Jump to Statement**               |
| `K`          | konstant  | **Introduce Constant**             |
| `L`          | line      | **Inline**                          |
| `N`          | new run   | **Rerun**                           |
| `O`          | optimize  | **Optimize Imports**                |
| `P`          | parameter | **Introduce Parameter**             |
| `R`          | rename    | **Rename**                          |
| `S`          | signature | **Change Signature**                |
| `T`          | type      | **Extract Class**                   |
| `U`          | uber      | **Extract Superclass**              |
| `V`          | variable  | **Introduce Variable**              |
| `W`          |           | **Move**                            |
| `X`          |           | **Safe Delete**       |
| `Y`          |           | **Pull Members Up**             |
| `Z`          |           | **Push Members Down**       |
| `0`          |           | **Refactor This**                     |

<a id="t"></a>
### First chord: Ctrl/Cmd+T (test) - testing actions

| Second Chord | Mnemonic | Action                           |
|--------------|----------|----------------------------------|
| `A`          | all      | **Run All Tests from Solution** (Rider) |
| `C`          | cover    | **Run with Coverage / Cover Unit Tests** |
| `D`          | debug    | **Debug Unit Tests** (Rider)     |
| `F`          | failed   | **Rerun Failed Tests** (Rider)   |
| `G`          | go       | **Go to Test**                   |
| `L`          | last     | **Repeat Previous Run** (Rider)  |
| `N`          | new      | **Create New Session** (Rider)   |
| `P`          | profile  | **Profile / Profile Unit Tests** |
| `R`          | run      | **Run Unit Tests** (Rider)       |
| `S`          | session  | **Run Current Session** (Rider)  |
| `S`          | show     | **Show Coverage Data**           |
| `U`          | unit     | **Run under dotMemory Unit** (Rider) |
| `X`          |          | **Stop Execution** (Rider)       |
| `0`          |          | **Unit Testing Quick List** (Rider) |

<a id="u"></a>
### First chord: Ctrl/Cmd+U (utilities) - global helper actions

| Second Chord | Mnemonic      | Action                          |
|--------------|---------------|---------------------------------|
| `A`          | action        | **Find Action**                 |
| `B`          | browser       | **Open in Browser** (Tasks)     |
| `C`          | changes       | **Local History**                        |
| `D`          | documentation | **Context Help**                |
| `G`          | guide         | **Help Topics**                 |
| `K`          | keep          | **Save Context**  (Tasks)        |
| `L`          | load          | **Load Context**  (Tasks)                    |
| `N`          | new start     | **Restart IDE**                       |
| `O`          | open          | **Open Task**  (Tasks)                 |
| `R`          | refresh       | **Refresh**                      |
| `S`          | settings      | **Settings**                    |
| `T`          | tasks         | **Switch Task**   (Tasks)              |
| `U`          | ui            | **Quick Switch Scheme**          |
| `X`          |               | **Clear Context**     (Tasks)          |
| `Z`          |               | **Close Active Task** (Tasks)          |

<a id="w"></a>
### First chord: Ctrl/Cmd+W (window) - manipulate tool windows

| Second Chord | Mnemonic      | Action                           |
|--------------|---------------|----------------------------------|
| `A`          | ant           | **Ant Window**                   |
| `A`          |               | **Build Window** (Rider)         |
| `B`          | bookmarks     | **Bookmarks Window**             |
| `C`          | commit        | **Commit Window**                |
| `D`          | debug         | **Debug Window**                 |
| `E`          | endpoints     | **Endpoints Window**             |
| `F`          | find          | **Find Window**                  |
| `G`          | gradle        | **Gradle Window**                |
| `I`          | il            | **IL Viewer Window** (Rider)     |
| `J`          |               | **Problems Window**              |
| `K`          |               | **Services Window**              |
| `L`          | learn         | **Learn Window**                 |
| `N`          | notifications | **Notifications Window**         |
| `O`          |        | **Profiler Window**              |
| `P`          | project       | **Project/Explorer Window**      |
| `R`          | run           | **Run Window**                   |
| `S`          | structure     | **Structure Window**             |
| `T`          | terminal      | **Terminal Window**              |
| `U`          | unit          | **Unit Tests Window** (Rider)    |
| `V`          | vcs           | **Version Control Window**       |
| `X`          |            | **Database Window**              |
| `Y`          |               | **TODO Window**                  |
| `Z`          |      | **Hierarchy Window**             |
| `1`          |               | **Toggle Presentation Mode**     |
| `2`          |               | **Toggle Distraction Free Mode** |
| `3`          |               | **Toggle Full Screen Mode**      |
| `4`          |               | **Toggle Zen Mode**              |
| `5`          |               | **Hide Active Tool Window**      |
| `6`          |        | **Hide All Tool Windows**        |
| `9`          |           | **Maximize Tool Window**         |
| `0`          |               | **Jump to Last Tool Window**     |
