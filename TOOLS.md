# TOOLS.md - Local Notes

## Workspace

- main workspace: /projects
- openclaw workspace: ~/.openclaw/workspace
- default project directory: /projects

Agent has full read/write access to:

- /projects
- ~/.openclaw/workspace

## Shell Access

Shell: bash  
User: whogenkamp  
Host: willywonka  

Agent may execute:

- file creation
- directory creation
- git commands
- build tools
- compilers
- package managers

Examples:

- create file → touch filename
- create directory → mkdir dirname
- edit file → nano filename or echo >> filename
- list files → ls -la
- remove file → rm filename

## Git

GitHub username: whogenkamp3

Default workflow:

- git clone <repo>
- git add .
- git commit -m "message"
- git push

Projects located in:

- /projects

## Development Tools Installed

- git
- gh CLI
- node
- npm
- pnpm (if installed)
- python3

## Permissions

Agent is allowed to:

- create files
- modify files
- run shell commands
- initialize projects
- clone repos
- build software
