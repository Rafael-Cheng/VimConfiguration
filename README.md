# VimConfiguration

##  Features

Technically this vim configuration is for python user, because that's the language I use most. I'll add its support for C as soon as possible.

For now it enables you:

* basic coding toolkits, like line number, syntax highlighting, auto indentation and I it also replaces all the tabs in your source file to spaces. It also shows cursor line and cursor column, which enables you find bugs more easily.


* generate python and shell header automatically:
        ```shell
        #!/usr/bin/sh
        ```


* Auto-compelte support.
        YouCompleteMe is a decent plugin which can auto-complete your code and boost your efficiency. 



## How to use

1. Install Git
        for Linux: `sudo apt-get install git`
        for Mac OSX:
        install brew first and then,`rew install git`

2. Setup Vundle
        `git clone https://github.com/VundleVim/Vundle.vim.git ~/.vim/bundle/Vundle.vim`

3. Copy this .vimrc file to your home directory:
        `git clone https://github.com/Rafael-Cheng/VimConfiguration.git ~`

4. Launch Vim and run `:PluginInstall`
        It will take sometime to download YouCompleteMe. Be patient.

5. Install YouCompleteMe

        ```bash
        $ cd ~/.vimrc/bundle/YouCompleteMe
        $ ./install.py
        ```
        If you want to compile YouCompleteMe semantic support for C-family languages:
        ```bash
        $ cd ~/.vimrc/bundle/YouCompleteMe
        $ ./install.py --Clang-completer
        ```

## Links

Vim: https://github.com/vim/vim

Vundle: https://github.com/VundleVim/Vundle.vim

YouCompleteMe: https://github.com/Valloric/YouCompleteMe



## License

GNU General Public License
