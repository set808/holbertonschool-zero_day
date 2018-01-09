# Emacs

At the end of this project you are expected to be able to explain to anyone, *without the help of Google*:

* What is Emacs
  * Emacs is a modal command line text editor
* Who is Richard Stallman
  * Richard Stallman is a software freedom activist who launched the GNU Project
* The basic Emacs commands
  * opening and saving files
    * opening C-x C-f
    * saving C-x C-s
  * What is a buffer and how to switch from one to the other
    * A buffer is the object where the text you are editing resides. To switch from one to the other C-x b [name of buffer] <RET>
  * Using the mark and the point to set the region
    * C-SPC sets the mark and the are between the mark and the point is the region.
  * Cutting and pasting lines and regions
    * killing current line C-k
    * killing region C-w
    * yanking C-y
    * replace yanked text with previously killed text M-y
  * Searching forward and backward
    * Searching forward C-s
    * Searching backward C-r
  * Invoking commands by name
    * M-x [command]
  * Undo
    * C-/
    * C-_
    * C-x u
  * Cancelling half-entered commands
    * C-g
  * Quitting
    * C-x C-c