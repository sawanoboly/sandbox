test repository
====

create remote branch
--

    $ git branch dev0.1 master
    $ git checkout dev0.1

edit some file.

    $ git commit -ma 'edit README.md'
    $ git push origin dev0.1


marge branch to master
--

    $ git checkout master
    $ git merge  dev0.1 master
    $ git push origin master

add tag release master
--
    $ git tag 0.1
    $ git push origin 0.1


remove local and remote branch
--

    $ git branch -d dev0.1
    $ git push origin :dev0.1
