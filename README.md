My dotfiles.

alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'
echo ".cfg" >> .gitignore
git clone --bare <git-repo-url> $HOME/.cfg
alias config='/usr/bin/git --git-dir=$HOME/.cfg/ --work-tree=$HOME'

GIST: <script src="https://gist.github.com/ErikLillehagen/a47d7c5cc8785164f20a660dea2df4a2.js"></script>
