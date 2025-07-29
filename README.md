# Application-Mod-0
Phase pratique

C:\Users\GOD BLESS>git --version
git version 2.50.1.windows.1

C:\Users\GOD BLESS>git config --global user.name "IrvinRolcens"

C:\Users\GOD BLESS>git config --global user.email "irvinadandozan@gmail.com"

C:\Users\GOD BLESS>mkdir MonDossier

C:\Users\GOD BLESS>cd MonDossier

C:\Users\GOD BLESS\MonDossier>git init
Initialized empty Git repository in C:/Users/GOD BLESS/MonDossier/.git/

C:\Users\GOD BLESS\MonDossier>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\GOD BLESS\MonDossier>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\GOD BLESS\MonDossier>git add index.html
fatal: pathspec 'index.html' did not match any files

C:\Users\GOD BLESS\MonDossier>git add index.html

C:\Users\GOD BLESS\MonDossier>git commit -m "project init"
[master (root-commit) 33ba9b9] project init
 1 file changed, 9 insertions(+)
 create mode 100644 index.html

C:\Users\GOD BLESS\MonDossier>git log
commit 33ba9b9e316de7894ec2e27f99d88437d2bf16d4 (HEAD -> master)
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 15:48:35 2025 +0100

    project init

C:\Users\GOD BLESS\MonDossier>git branch backgroundColor

C:\Users\GOD BLESS\MonDossier>git branch
  backgroundColor
* master

C:\Users\GOD BLESS\MonDossier>git chechout backgroundColor
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

C:\Users\GOD BLESS\MonDossier>git checkout backgroundColor
Switched to branch 'backgroundColor'

C:\Users\GOD BLESS\MonDossier>git add index.html

C:\Users\GOD BLESS\MonDossier>git commit -m "Modification du texte"
[backgroundColor 2c2cc2b] Modification du texte
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\GOD BLESS\MonDossier>git log
commit 2c2cc2b509eebaa3c092a7b1bb67e054b38b87a0 (HEAD -> backgroundColor)
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 16:05:02 2025 +0100

    Modification du texte

commit 33ba9b9e316de7894ec2e27f99d88437d2bf16d4 (master)
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 15:48:35 2025 +0100

    project init

C:\Users\GOD BLESS\MonDossier>git checkout master
Switched to branch 'master'

C:\Users\GOD BLESS\MonDossier>git merge backgroundColor
Updating 33ba9b9..2c2cc2b
Fast-forward
 index.html | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\GOD BLESS\MonDossier>git branch -d backgroundColor
Deleted branch backgroundColor (was 2c2cc2b).

C:\Users\GOD BLESS\MonDossier>git log
commit 2c2cc2b509eebaa3c092a7b1bb67e054b38b87a0 (HEAD -> master)
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 16:05:02 2025 +0100

    Modification du texte

commit 33ba9b9e316de7894ec2e27f99d88437d2bf16d4
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 15:48:35 2025 +0100

    project init

C:\Users\GOD BLESS\MonDossier>git branch
* master

C:\Users\GOD BLESS\MonDossier>git log
commit 2c2cc2b509eebaa3c092a7b1bb67e054b38b87a0 (HEAD -> master)
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 16:05:02 2025 +0100

    Modification du texte

commit 33ba9b9e316de7894ec2e27f99d88437d2bf16d4
Author: IrvinRolcens <irvinadandozan@gmail.com>
Date:   Tue Jul 29 15:48:35 2025 +0100

    project init

C:\Users\GOD BLESS\MonDossier>
