# Safe_rm Unix Recycling Bin Project

**Problem**: UNIX has no recycle bin.  When you remove a file or directory, it is gone and cannot be restored. This project is to write a safe_rm and safe_rm_restore to provide users with a recycle bin which can be used to safely delete and restore files.

## Running the safe_rm
```bash
safe_rm file_to_delete
```

## --interactive --verbose --recursive Options for safe_rm
```bash
safe_rm -ivr directory/directory2/file_to_delete
```

## To Restore the Deleted File or Directory
```bash
safe_rm_restore deleted_file_inode
```
