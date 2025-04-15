# git-port
MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git status
On branch main
nothing to commit, working tree clean

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git --help
usage: git [-v | --version] [-h | --help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--no-lazy-fetch]
           [--no-optional-locks] [--no-advice] [--bare] [--git-dir=<path>]
           [--work-tree=<path>] [--namespace=<name>] [--config-env=<name>=<envvar>]    
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone      Clone a repository into a new directory
   init       Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add        Add file contents to the index
   mv         Move or rename a file, a directory, or a symlink
   restore    Restore working tree files
   rm         Remove files from the working tree and from the index

examine the history and state (see also: git help revisions)
   bisect     Use binary search to find the commit that introduced a bug
   diff       Show changes between commits, commit and working tree, etc
   grep       Print lines matching a pattern
   log        Show commit logs
   show       Show various types of objects
   status     Show the working tree status

grow, mark and tweak your common history
   backfill   Download missing objects in a partial clone
   branch     List, create, or delete branches
   commit     Record changes to the repository
   merge      Join two or more development histories together
   rebase     Reapply commits on top of another base tip
   reset      Reset current HEAD to the specified state
   switch     Switch branches
   tag        Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch      Download objects and refs from another repository
   pull       Fetch from and integrate with another repository or a local branch
   push       Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git restore
fatal: you must specify path(s) to restore

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git push -u origin main
To https://github.com/wizzyonu/git-port.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/wizzyonu/git-port.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git pull origin main
From https://github.com/wizzyonu/git-port
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git add .

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git commit -m "Merge remote changes"
On branch main
nothing to commit, working tree clean

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git push origin main
To https://github.com/wizzyonu/git-port.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/wizzyonu/git-port.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git pull --rebase origin main
From https://github.com/wizzyonu/git-port
 * branch            main       -> FETCH_HEAD
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/wizzyonu/git-port.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. If you want to integrate the remote changes,
hint: use 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git pull --rebase origin main
From https://github.com/wizzyonu/git-port
 * branch            main       -> FETCH_HEAD

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git pull --rebase origin main
From https://github.com/wizzyonu/git-port
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.
From https://github.com/wizzyonu/git-port
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.
 * branch            main       -> FETCH_HEAD
Successfully rebased and updated refs/heads/main.
Successfully rebased and updated refs/heads/main.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git push origin main
MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git push origin main
Enumerating objects: 12, done.
$ git push origin main
Enumerating objects: 12, done.
Enumerating objects: 12, done.
Counting objects: 100% (12/12), done.
Delta compression using up to 4 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (11/11), 4.66 KiB | 434.00 KiB/s, done.
Total 11 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), done.
To https://github.com/wizzyonu/git-port.git
   2f3be76..a6ac848  main -> main

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ git clone https://github.com/saadpasta/developerFolio
Cloning into 'developerFolio'...
remote: Enumerating objects: 6319, done.
remote: Total 6319 (delta 0), reused 0 (delta 0), pack-reused 6319 (from 1)
Receiving objects: 100% (6319/6319), 27.63 MiB | 492.00 KiB/s, done.
Resolving deltas: 100% (2672/2672), done.

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$ code index.txt

MICHAEL@DESKTOP-J1J4JC5 MINGW64 ~/Desktop/NIIT PROJECT FILE (main)
$