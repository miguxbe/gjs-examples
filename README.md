# gjs-examples
GJS examples showing how to build Gtk javascript applications (Gnome).

### Run

Download this project with:

git clone https://github.com/optimisme/gjs-examples.git

cd gjs-examples

Then run the examples with:

gjs egAsset.js

gjs egHeader.js

gjs egList.js

gjs egSearch.js

...

### egAsset.js

GJS example showing how to build Gtk javascript applications
using Gtk.Image

![egAsset0](https://raw.github.com/optimisme/gjs-examples/master/captures/egAsset0.png)

### egIcon.js

GJS example showing how to build Gtk javascript applications
setting the application icon from the 'assets' folder and if
not available from the 'stock icons'

![egIcon0](https://raw.github.com/optimisme/gjs-examples/master/captures/egIcon0.png)
![egIcon1](https://raw.github.com/optimisme/gjs-examples/master/captures/egIcon1.png)

### egCss.js

GJS example showing how to build Gtk javascript applications
using Gtk.CssProvider from source code or from loaded .css files

![egCss0](https://raw.github.com/optimisme/gjs-examples/master/captures/egCss0.png)

### egJustify.js

GJS example showing how to build Gtk javascript applications
using Gtk.Label and its justification options

![egJustify0](https://raw.github.com/optimisme/gjs-examples/master/captures/egJustify0.png)

### egTimers.js

GJS example showing how to build Gtk javascript applications
emulating setTimeout, clearTimeout, setInterval and clearInterval
functions with Mainloop timeout_add. It also shows how to import
and use an application library

![egTimers0](https://raw.github.com/optimisme/gjs-examples/master/captures/egTimers0.png)

### egEvent.js

GJS example showing how to build Gtk javascript applications
using Gtk.EventBox to catch events for widgets which do not 
have their own window

![egEvent0](https://raw.github.com/optimisme/gjs-examples/master/captures/egEvent0.png)

### egSpawn.js

GJS example showing how to build Gtk javascript applications
executing a non blocking command line call, it uses
TextBuffer, TextView, GLib.spawn_async_with_pipes,
Gio.UnixInputStream, Gio.DataInputStream and read_line_async

![egSpawn0](https://raw.github.com/optimisme/gjs-examples/master/captures/egSpawn0.png)

### egInfo.js

GJS example showing how to build Gtk javascript applications
getting information from GLib and command line

![egInfo0](https://raw.github.com/optimisme/gjs-examples/master/captures/egInfo0.png)

### egDialog.js

GJS example showing how to build Gtk javascript applications
adding an option to the application's Gio.Menu and opening 
dialog and modal windows using Gtk.Dialog

![egDialog0](https://raw.github.com/optimisme/gjs-examples/master/captures/egDialog0.png)
![egDialog1](https://raw.github.com/optimisme/gjs-examples/master/captures/egDialog1.png)
![egDialog2](https://raw.github.com/optimisme/gjs-examples/master/captures/egDialog2.png)

### egList.js

GJS example showing how to build Gtk javascript applications
using Gtk TreeView and ListStore

![egList0](https://raw.github.com/optimisme/gjs-examples/master/captures/egList0.png)

### egJSON.js

GJS example showing how to build Gtk javascript applications
reading and writting JSON files, the example makes use of
Gio.File.new_for_path, replace_async, load_contents_async

![egJSON0](https://raw.github.com/optimisme/gjs-examples/master/captures/egJSON0.png)

### egOpen.js

GJS example showing how to build Gtk javascript applications
with FileChooserDialog with FileFilter, set_extra_widget (ComboBox),
Gio File new_for_path, load_contents_async, query_info_async

![egOpen0](https://raw.github.com/optimisme/gjs-examples/master/captures/egOpen0.png)
![egOpen1](https://raw.github.com/optimisme/gjs-examples/master/captures/egOpen1.png)

### egHeader.js

GJS example showing how to build Gtk javascript applications
using Gtk HeaderBar, and Popover buttons with Gtk Widget or Gio GMenu.

![egHeader0](https://raw.github.com/optimisme/gjs-examples/master/captures/egHeader0.png)
![egHeader1](https://raw.github.com/optimisme/gjs-examples/master/captures/egHeader1.png)

### egSearch.js

GJS example showing how to build Gtk javascript applications
using Gtk HeaderBar, SearchBar and a filtered FlowBox

![egSearch0](https://raw.github.com/optimisme/gjs-examples/master/captures/egSearch0.png)

### egSelect.js

GJS example showing how to build Gtk javascript applications
using Gtk HeaderBar, SearchBar, ActionBar, a filtered FlowBox,
an application library and custom widgets to create a selection
mode

![egSelect0](https://raw.github.com/optimisme/gjs-examples/master/captures/egSelect0.png)
![egSelect1](https://raw.github.com/optimisme/gjs-examples/master/captures/egSelect1.png)

### egClutter.js

GJS example showing how to build Gtk javascript applications
using Gtk and Clutter, showing how to drag actors with
Clutter.DragAction, perform animations with PropertyTransition,
TransitionGroup and control the actor from Gtk.Scale

![egClutter0](https://raw.github.com/optimisme/gjs-examples/master/captures/egClutter0.png)

### egCairo.js

GJS example showing how to build Gtk javascript applications
using Gtk and Cairo, the left example adds one Cairo actor to
Clutter, the example on the right adds one Cairo widget to GTK
using GtkClutter.Embed, Gtk.DrawingArea, Cairo.Context,
Clutter.Canvas

![egCario0](https://raw.github.com/optimisme/gjs-examples/master/captures/egCairo0.png)

### egWebmsg.js

GJS example showing how to build Gtk javascript applications
using Webkit.WebView, also showing how to send messages from GTK
to Webkit and vice versa

![egWebmsg0](https://raw.github.com/optimisme/gjs-examples/master/captures/egWebmsg0.png)
