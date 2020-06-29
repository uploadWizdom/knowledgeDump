# knowledgeDump

## Configurating terminal

### Aliases
The alias command makes it possible to launch any command or group of commands (with arguments, options or redirections) by entering a pre-set string.

Open the settings file
```bash
vim ~/.bashrc
```
Add aliases
```bash
alias ll='ls -ltrha --color=auto' # add arguments to a command that exists
alias ls='ls -ltrha --color=auto' # add arguments to a command that exists

alias vi='vim' # redirect the old application to the new one
alias exot='exit' # correct typing errors
alias clera='clear' # correct typing errors

alias qpositive='history -c && history -w && exit' # link more commands under one
```
