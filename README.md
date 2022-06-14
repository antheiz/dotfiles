## Getting Started with NVIM (Neo VIM)

#### Settings Save

To keep these settings saved, just write these commands in a file in your user folder. The name and location will vary depending on whether you use Neovim:

    Neovim: <username>/.config/nvim/init.vim  
    
#### Plugin manager setup 

    $ sh -c 'curl -fLo "${XDG_DATA_HOME:-$HOME/.local/share}"/nvim/site/autoload/plug.vim --create-dirs \
       https://raw.githubusercontent.com/junegunn/vim-plug/master/plug

