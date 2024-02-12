# MLOPs-Task-1

## Git Commands

- To clone the repository:
  ```bash
  git clone https://github.com/RumaisaIlyas/MLOPs-Task-1.git

- To Create Branches 
  git branch dev
  git branch test
  git branch master

-Switch to git dev
  git checkout dev

-Create separate branches for each team member
  git branch member1-feature 
  git branch member2-feature

-Switch to the branch of a team member:
  git checkout member1-feature




fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git init
Reinitialized existing Git repository in C:/Users/fahad/Downloads/MLops_Task_1/MLOPs-Task-1/.git/

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git branch dev
fatal: a branch named 'dev' already exists

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git branch test
fatal: a branch named 'test' already exists

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git branch main
fatal: a branch named 'main' already exists

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git checkout dev
Switched to branch 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch fahad_branch

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch Rumaisa_branch

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout fahad_branch
Switched to branch 'fahad_branch'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ mkdir src tests

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ touch src/main.py tests/test_main.py README.md requirements.txt               
fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ notepad README.md


fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ ^[[200~git checkout dev
bash: $'\E[200~git': command not found

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ git checkout dev
Switched to branch 'dev'
M       README.md

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git add .

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m
error: switch `m' requires a value

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m "This is my first commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'fahad@FahadRamzan.(none)')

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git config --global user.email "i200443@nu.edu.pk"

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git config --global user.name "Fahad Ramzan"

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m "This is my first commit"
[dev 15f7f84] This is my first commit
 4 files changed, 25 insertions(+), 1 deletion(-)
 create mode 100644 requirements.txt
 create mode 100644 src/main.py
 create mode 100644 tests/test_main.py

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout dev
Already on 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge dev
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout fahad_branch
Switched to branch 'fahad_branch'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (fahad_branch)
$ git checkout dev
Switched to branch 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge fahad_branch
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout Rumaisa_branch
Switched to branch 'Rumaisa_branch'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (Rumaisa_branch)
$ git checkout dev
Switched to branch 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge Rumaisa_branch
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git add .

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m "Merged into dev"
On branch dev
nothing to commit, working tree clean

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git push origin dev
info: please complete authentication in your browser...
remote: Permission to RumaisaIlyas/MLOPs-Task-1.git denied to FahadRamzan.
fatal: unable to access 'https://github.com/RumaisaIlyas/MLOPs-Task-1.git/': The requested URL returned error: 403

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git push origin dev
info: please complete authentication in your browser...
Enumerating objects: 9, done.
Counting objects: 100% (9/9), done.
Delta compression using up to 20 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (9/9), 1.50 KiB | 1.50 MiB/s, done.
Total 9 (delta 0), reused 3 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/RumaisaIlyas/MLOPs-Task-1/pull/new/dev
remote:
To https://github.com/RumaisaIlyas/MLOPs-Task-1.git
 * [new branch]      dev -> dev

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch
  Rumaisa_branch
* dev
  fahad_branch
  main
  test

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout Rumaisa_branch
Switched to branch 'Rumaisa_branch'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (Rumaisa_branch)
$ git checkout Rumaisa_branch
Already on 'Rumaisa_branch'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (Rumaisa_branch)
$ git checkout dev
Switched to branch 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge Rumaisa_branch
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git add .

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m
error: switch `m' requires a value

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git commit -m "Added Rumaisa_branch"
On branch dev
nothing to commit, working tree clean

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git push origin dev
Everything up-to-date

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch
  Rumaisa_branch
* dev
  fahad_branch
  main
  test

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ ^C

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout dev
Already on 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge Rumaisa_branch
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git log Rumaisa_branch
commit 805e4273d6f25503562438e8adc2044cb4bc7480 (origin/main, origin/HEAD, test, main, fahad_branch, Rumaisa_branch)
Author: Rumaisa Ilyas <119864397+RumaisaIlyas@users.noreply.github.com>
Date:   Mon Feb 12 10:10:32 2024 +0500

    Initial commit

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git log dev
commit 15f7f841d095e66e17cf2ff180807068afcbfa9e (HEAD -> dev, origin/dev)
Author: Fahad Ramzan <i200443@nu.edu.pk>
Date:   Mon Feb 12 10:59:51 2024 +0500

    This is my first commit

commit 805e4273d6f25503562438e8adc2044cb4bc7480 (origin/main, origin/HEAD, test, main, fahad_branch, Rumaisa_branch)
Author: Rumaisa Ilyas <119864397+RumaisaIlyas@users.noreply.github.com>
Date:   Mon Feb 12 10:10:32 2024 +0500

    Initial commit

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git diff dev..Rumaisa_branch
diff --git a/README.md b/README.md
index 8a93cde..423718c 100644
--- a/README.md
+++ b/README.md
@@ -1,25 +1 @@
-# MLOPs-Task-1
-
-## Git Commands
-
-- To clone the repository:
-  ```bash
-  git clone https://github.com/RumaisaIlyas/MLOPs-Task-1.git
-
-- To Create Branches
-  git branch dev
-  git branch test
-  git branch master
-
--Switch to git dev
-  git checkout dev
-
--Create separate branches for each team member
-  git branch member1-feature
-  git branch member2-feature
-
--Switch to the branch of a team member:
-  git checkout member1-feature
-
-
-
+# MLOPs-Task-1
\ No newline at end of file
diff --git a/requirements.txt b/requirements.txt
deleted file mode 100644
index e69de29..0000000
diff --git a/src/main.py b/src/main.py
deleted file mode 100644
index e69de29..0000000
diff --git a/tests/test_main.py b/tests/test_main.py
deleted file mode 100644
index e69de29..0000000

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch
  Rumaisa_branch
* dev
  fahad_branch
  main
  test

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git main
git: 'main' is not a git command. See 'git --help'.

The most similar command is
        mailinfo

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git branch test
fatal: a branch named 'test' already exists

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git branch
  Rumaisa_branch
  dev
  fahad_branch
* main
  test

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (main)
$ git checkout dev
Switched to branch 'dev'

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git merge Rumaisa_branch
Already up to date.

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch
  Rumaisa_branch
* dev
  fahad_branch
  main
  test

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git branch -a
  Rumaisa_branch
* dev
  fahad_branch
  main
  test
  remotes/origin/HEAD -> origin/main
  remotes/origin/dev
  remotes/origin/main

fahad@FahadRamzan MINGW64 ~/Downloads/MLops_Task_1/MLOPs-Task-1 (dev)
$ git status
On branch dev
nothing to commit, working tree clean
