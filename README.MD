# git bigfile detection

The tool allows to check for large files in a git repo
with the intent to put it under git-lfs control.

Specifically it will check for parts being changed often.

The tool requires "git" to be installed using "git rev-list" 
and "git cat-file" to inspect the object store. Read more about 
git-plumbing at [git-scm:Git-Internals-Git-Objects](https://git-scm.com/book/en/v2/Git-Internals-Git-Objects)


