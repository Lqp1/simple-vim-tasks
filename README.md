# Simple VimTasks
A very simple plugin to manage everyday tasks.
License is `MIT`.

## Shortcuts in 'Tasks' buffer
The following keys are defined in normal mode, on each of the tasks:
* v : Change state to "Done"
* x : Change state to "Cancel"
* c : Remove the state from this entry
* w : Change state to "Work in progress"
* p : Change state to "Pending"
* W : Save to buffer
* q : Exit this buffer, without saving
* n : add entry
* e : edit entry

## EX Commands
Use the following to choose a file to open:
> :VimTasksOpen *file*

Use the following to load `~/.local.vt`:
> :VimTasks

## File format
Tasks are stored in plaintext, following this format:
> State Description
Where:
* **State** : an optional integer describing the state of the entry
* **Description** : is the text of the entry.
