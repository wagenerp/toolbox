# Toolbox

This is a collection of random tools I happened to write for augmenting my own workflows.

## macro processor
Reads python code embedded in another file as comments and puts its output into the file itself, giving macros to any language that supports comments.

## q-run
To be used in conjunction with your window manager, reacting to hotkeys and running commands configured on a per-project basis. Fill out an executable `.qrun` file and invoke `q-run host` in its parent directory, then invoke e.g. `q-run execute 1` via hotkey to execute `.qrun 1`.

## µconf
Manages configurations by replacing symlinks grouped together via names. Regards configuration (containing actual files, grouped and identified via common names) and target directories (containing symlinks to files of common group name).
