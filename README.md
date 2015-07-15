Gloner
=======
Clone repositories from GitHub. This is my first script with Shell.

## Usage
repos.txt
```txt
gabrieljmj/render:master;gabrieljmj/power2:master;gabrieljmj/shouldphp:dev
```
```cmd
$ gloner -f repos.txt
Cloning into 'render'...
remote: Counting objects: 93, done.
remote: Total 93 (delta 0), reused 0 (delta 0), pack-reused 93
Unpacking objects: 100% (93/93), done.
Checking connectivity... done.
Cloning into 'power2'...
remote: Counting objects: 22, done.
remote: Total 22 (delta 0), reused 0 (delta 0), pack-reused 22
Unpacking objects: 100% (22/22), done.
Checking connectivity... done.
Cloning into 'shouldphp'...
remote: Counting objects: 1426, done.
rRemote: Total 1426 (delta 0), reused 0 (delta 0), pack-reused 1426eceiving obje
Receiving objects:  97% (1384/1426), 292.01 KiB | 275.00 KiB/s
Receiving objects: 100% (1426/1426), 316.22 KiB | 275.00 KiB/s, done.
Resolving deltas: 100% (788/788), done.
Checking connectivity... done.
DONE!
```