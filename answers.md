Answer 1:  git version 2.30.0.windows.2
Answer 2:diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager-core
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.email=zt727820@ohio.edu
user.name=Zachary Thomas Takacs
Answer 3: file:///C:/Program%20Files/Git/mingw64/share/doc/git-doc/git-add.html
Answer 4: The most similar command is
        status
PS C:\Users\12162\Documents\ztakacs-cs2400\git-lab> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answer.md
        answers.md
Answer 5 : On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answer.md
        answers.md
Answer 7:On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answer.md
        answers.md

nothing added to commit but untracked files present (use "git add" to track)
Answer 8: commit 0bc5f2ac8a477b04eb03024d2e7021a92b4cb9a5 (HEAD -> master)
Author: Zachary Thomas Takacs <zt727820@ohio.edu>
Date:   Tue Jan 26 18:52:27 2021 -0500

    Initial commit
Answer 9:Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answer.md
        answers.md

no changes added to commit (use "git add" and/or "git commit -a")
Answer 10: no
Answer 11: I was Rejected
Answer 12: remote: Enumerating objects: 8, done.
remote: Counting objects: 100% (8/8), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (6/6), 1.33 KiB | 71.00 KiB/s, done.
From https://github.com/Tarkis-Togulhorn/git-lab
   0bc5f2a..ad2d650  main       -> origin/main
error: Your local changes to the following files would be overwritten by merge:
        README.md
Please commit your changes or stash them before you merge.
Aborting
Answer 13: Get-ChildItem : Parameter cannot be processed because the parameter name 'a' is ambiguous. Possible matches include:
-Attributes -Directory -File -Hidden -ReadOnly -System.
At line:1 char:4
+ ls -a
+    ~~
    + CategoryInfo          : InvalidArgument: (:) [Get-ChildItem], ParameterBindingException
    + FullyQualifiedErrorId : AmbiguousParameter,Microsoft.PowerShell.Commands.GetChildItemCommand
Done