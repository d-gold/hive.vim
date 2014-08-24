hive.vim
========

Simple hive syntax file for vim.

This is based off the existing vim syntax highlighting for Oracle with various oraclisms removed and hiveisms added. It makes working in hive a little bit friendlier.

You will want to add a

    au BufRead,BufWrite *.hql set filetype=hive

to your .vimrc (of course, using whatever extensions you use for your hive files instead of .hql).
