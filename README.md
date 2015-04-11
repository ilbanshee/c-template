# C-Template

This repository contains a bare minimum C project with autotools setup script.

## How to use

In order to create a new project;

1. *clone* this repo;
2. *rename* _c-template_ directory accordingly to your project;
3. enter project directory and *remove* the _.git_ dir;
4. handle _configure.ac_:
   1. *change* AC_INIT macro value;
   2. *edit* the file as you like/need;
6. *edit/change* _LICENSE_ file (change name or license if you don't like MIT);
7. *edit* _README.md_ with some bare info on your project;
8. _optionally_ *edit* the _Makefile.am_ and .gitignore files (see notes below);
9. init a new repo with git (remember to setup user.email/user.name and stuff like that);
10. start coding.

## Notes

There are some assumptions in this template layout:

1. there is only a Makefile.am in the project dir, I found it clearer for simple tests/ideas;
2. the makefile will generate a _main_ executable from a main.c source file;
3. a default .gitignore is present for many C artifacts, including an entry for _main_, if you
   want a different name for you executable change the .gitignore also.