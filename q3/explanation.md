# Q3 Explanation

- A hard link points to the same inode as the original file, so both names remain valid after the original name is removed.
- A symbolic link stores the target path rather than sharing inode data, so it breaks when the target is deleted.
- `ls -li` and `stat` were used to compare inode numbers and metadata for the hard link, symbolic link, and original file.
- The experiment confirmed that hard links preserve file access after deletion of the original path, while symbolic links do not.
