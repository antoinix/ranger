## ranger

#### I. How to <u>use</u>?
##### 1. Clone this repo to local ( $HOME/.config is recommended )
```
cd ~/.config && git clone --depth=1 https://github.com/antoinix/ranger
```
##### 2. Install [nerd-fonts](https://github.com/ryanoasis/nerd-fonts) form github
---
#### II. What is <u>new</u>?
##### 1. The new function: see, a shell script which can help us view detailed info about specific variable in rc.conf

##### 2. Configuration of see:
##### In .bashrc, add this block:
```
source $HOME/.config/ranger/see/complete
alias see="bash $HOME/.config/ranger/see/see"
```
##### 3. Usage of see:
##### In the shell:
```
see [variable]
# Note: support tab completion
```
