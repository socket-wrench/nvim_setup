### Neovim Setup

This is an Ansible playbook to setup an environment for Neovim (nvim).  For CentOS/RHEL/Fedora.

## Prerequisites

Prerequisite here in ansible.  Tested on version 2.9.9.

## Includes

Installs python36 and python-pip

Includes the following plugins
  * jedi-vim
  * deoplete.nvim
  * deoplete-jedi
  * vim-airline
  * vim-airline-themes
  * auto-pairs
  * nerdcommenter
  * neoformat
  * nerdtree
  * neomake

## Usage
Unpack to a directory and run the playbook.
	# cd nvim_setup
	# ./nvim_setup.yml
