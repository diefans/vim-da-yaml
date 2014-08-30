# vim-da-yaml


## Thanks

Basically this project is a rip-off from [vim-ansible-yaml](https://github.com/chase/vim-ansible-yaml).
This indentation just works - so many thanks!


## Install

### Using [Vundle](https://github.com/gmarik/vundle)

1. Add the following to your `.vimrc` where other bundles are located:

		Bundle 'diefans/vim-da-yaml'

2. Run from command line:

		$ vim +BundleInstall

### Using [pathogen](https://github.com/tpope/vim-pathogen)

1. Check out the repository into your bundle path:

        $ cd ~/.vim/bundle
        $ git clone git://github.com/diefans/vim-da-yaml.git

### Normal

1. Check out the repository and copy the following to `.vim/` directory or any
   other run time path, keeping their directory structure intact:

		syntax/yaml.vim
		indent/yaml.vim
