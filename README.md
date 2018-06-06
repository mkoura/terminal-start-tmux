# Moved to https://gitlab.com/mkourim/terminal-start-tmux

Script I use to start tmux or attach existing tmux session automatically with roxterm (can be used with any terminal emulator).

Usage:
- create new profile - it's not suitable for default profile as it will not work with '-e' (execute).
- set this script as *custom command* in the settings of the new profile
- start `roxterm -p <new profile>` (ideally via shortcut)


Use case:

I want to be able to launch terminal and have my current tmux session attached automatically.
When there is no tmux session running, new session should be started.
When I open new window or tab, I just want to start new shell (there's no point in attaching the same tmux session again).
