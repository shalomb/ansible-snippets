# ansible-snippets

Ansible Vim snippets for
  [UtilSnips](https://github.com/SirVer/ultisnips) and
  [SnipMate](https://github.com/garbas/vim-snipmate)

This is a fork of
[phenomenes/ansible-snippets.git](https://github.com/phenomenes/ansible-snippets.git)
which will eventually diverge and become a project of its own.

_NOTE_: If you wish to have ansible snippets that match the latest
version of ansible, you should use phenomenes fork instead as it
appears to be auto-generated from the documentation.

This fork is a work-in-progress to

* Create meaningful/practical ansible snippets that would be used in
  day-to-day scenarios working with ansible.

* Rearrange and [Huffman encode](https://en.wikipedia.org/wiki/Huffman_coding)
  the snippets to provide concise and logically organised completions.

* Reduce the time taken to fill in a workable completion down to an
  absolute minimum - while still allowing completions for unusual cases.

* Provide snippets that complete common use-cases that are not purely
  derived from the ansible module documentation.

* Auto-generate snippets from the latest version of the documentation
  under the
  [Ansible Module Index](http://docs.ansible.com/ansible/latest/modules_by_category.html).

* Eventually re-organize snippets into multiple smaller projects to
  match the logical structure laid out by ansible in the
  [Ansible Module Index](http://docs.ansible.com/ansible/latest/modules_by_category.html).

## Requirements

* [UtilSnips](https://github.com/SirVer/ultisnips) or
  [SnipMate](https://github.com/garbas/vim-snipmate)

## Installation

Recommended: Use your preferred vim plugin/add-on manager.

To manually install, clone this repo to your vim directory

```
cd ~/.vim/
git clone https://github.com/phenomenes/ansible-snippets.git
```

and then restart vim.

## Usage

Open a `.yml` or `.yaml` file that represents your ansible playbook
or role task file and in insert mode type one of the
available snippet completions (e.g. `play`, `apt`, etc) and then

* Press `ctrl-r tab` to view possible snippet completions.
* Press `tab` to expand the desired snippet, then complete each field
  pressing `tab` again to move to the next field, etc.

## Hacking

* Edit the `ansible-snippets/snippets/yaml.snippets` file to
  add/extend your snippets.

* In your vim session, test out the snippet expansion
  (vim does not need to be restarted).

* Contribute back

## License

BSD 2-clause "Simplified" License

