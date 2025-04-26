# second
second repository

test my connection

ssh-keygen -t ed25519 -C "email"

eval "$(ssh-agent -s)"
ssh-add ~/.ssh/id_ed25519

xclip < ~/.ssh/id_ed25519.pub
insert this on github as New SSH key

-------------------------------

# zsh
install zsh and zsh-completions

-------------------------------

~/.zshrc
autoload -Uz compinit promptinit
compinit
promptinit

# This will set the default prompt to the walters theme
prompt adam2

----------------------------

# autocomplit

~/.zshrc
autoload -Uz compinit
compinit

----------------------------
