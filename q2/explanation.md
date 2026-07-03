# Q2 Explanation

- `mkdir -p ...` created the project directories for documentation, source code, and logs.
- `chmod 750` restricted directory traversal so only the owner and group could access the workspace directories.
- `chmod 640` limited file readability so only the owner and group could view the project files.
- The `umask` value determined the default permissions for newly created files in this workspace.
