# ReadMe File for \GitHub\uslci_aip\01_data_received

## Git Commands
| Command | Action | Notes |
|:-------:|:------:|:------|
| git ls-files -v | List affected files | "S" = `skip-worktree` set.<br>"s" = `assume-unchanged` set.
| git update-index --skip-worktree <file> | Set the bit and ignore an already tracked file | [How to ignore changes in tracked files with Git][update-index]
| git update-index --no-skip-worktree <file> | Unset the bit and reenable tracking | [How to ignore changes in tracked files with Git][update-index]

## References
[update-index]: http://blog.stephan-partzsch.de/how-to-ignore-changes-in-tracked-files-with-git/
