Express app for visualizethesource.com

# Importing data

Any directory will work, but to work specifically with git repositories:

- Clone the repo to a local directory
- change directory so the directory you want to import (and all its descendants) is in the current directory.

```bash
python import_data.py dir_to_import
```

`dir_to_import` must be in the current directory, so if it is not in the same directory as `import_data.py`
then you'll need to reference the python script appropriately, for example:

```bash
python ../import_data.py repos/dir_to_import
```

If you are importing a git repo you should remove the `.git` folder as it takes up a lot of space.
