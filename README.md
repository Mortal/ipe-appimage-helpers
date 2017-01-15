When you run [Ipe](http://ipe.otfried.org/)
from an AppImage, you normally have to specify
absolute paths to the files you want to edit,
and you have to specify the program name (`ipe`, `iperender`, ...)
as the first argument.

With these scripts, you can run `ipe`, `iperender`, ...
with relative paths as arguments, and a small Bash helper
will convert arguments to full paths before running the AppImage.
