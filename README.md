# delete-duplicate-downloads-alfred3
An Alfred3 workflow for deleting duplicate download files and directories from your /Downloads directory that are taking up extra space for no reason.

### WARNING
This Alfred3 uses a simple bash cmd with this structure:
```
~/Downloads/*\(*\).*
~/Downloads/*\(*\)
```
This means any files that uses `()` right before the file extension `file(1).zip` or any folder that has `()` at the end of the folder name `folder(1)` will be deleted.
