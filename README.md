vim and zsh
===========

My vim and zsh config files.

To Use: 
First make sure zsh, vim, tmux, and git are installed then from /home/[user] run:

    # Or use ssh instead of https
    git clone https://github.com/mlundyCO/vim_zsh_config
    ln -s /home/[user]/vim_zsh_config/vimrc /home/[user]/.vimrc
    ln -s /home/[user]/vim_zsh_config/zshrc /home/[user]/.zshrc
    ln -s /home/[user]/vim_zsh_config/tmux.conf /home/[user]/.tmux.conf

Then run "chsh" and point to /bin/zsh, then logout and log back in.
If the files already exist and you don't want to save any configuration, you can just delete them.
