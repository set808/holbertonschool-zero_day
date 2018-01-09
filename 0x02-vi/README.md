# VI

At the end of this project you are expected to be able to explain to anyone *without the help of Google*:

* What is vi
  * vi is a text editor originally created for Unix
* Who is Bill Joy
  * Co-founder of Sun Microsystems, original author of the vi text editor
* The basic vi commands
  * How to start and exit vi
    * Start vi: vi filename
    * Exit vi: :x<Return>
  * What are the command and insert modes, and how to switch from one to the other
    * insert mode: i while in command mode
    * command mode: ESC while in insert mode
  * Edit text
    * There are multiple commands to edit text such as r, cw, etc.
  * Cutting and pasting lines
    * Cutting current line: yy
    * Cutting multiple lines: Nyy
    * Paste: p
  * Searching forward and backward
    * Searching forward: /string
    * Searching backward: ?string
  * Undo
    * u
  * Quitting
    * Quit and save: :x<Return>
    * Quit: :q<Return>
    * Quit even though latest changes have not been saved: :q!<Return>