# gnome-workspace-list-name

I've started using PopOS / Ubunto, so now I too want to make an extension! ^_^

gnome extention to display the names of the Workspaces in the list when switching


---
---

### Some notes to myself while developing

Folder location of the extension: ~/.local/share/gnome-shell/extensions/workspacelistnames@kaffekod.nu

---

[Testing extension](https://gjs.guide/extensions/development/creating.html#x11-sessions)

X11 does not support running nested sessions, so we will enable the extension and then restart GNOME Shell to reload extensions.

1. Enable the extension
    `$ gnome-extensions enable example@gjs.guide`

2. Monitor the output of GNOME Shell
    `$ journalctl -f -o cat /usr/bin/gnome-shell`

3. Press Alt+F2 and run the built-in `restart` command

---

[Looking glass](https://gjs.guide/extensions/development/debugging.html#looking-glass)

Looking Glass is a debugger and inspector, built into GNOME Shell. 

Alt+F2 → lg

*I have a gut-feeling that I'm going to use this a lot because it's fun to connect all the dots*

---

