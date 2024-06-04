# tasks
Tasks for personal productivity built using https://taskfile.dev

## Setup
- Install go-task `brew install go-task'
- Clone this Repo to `<dir>`
- Edit `<dir>/Taskfile.yaml` to set REPO_DIR to `<dir>`
- Symlink global tasks file `ln -s <dir>/Taskfile.yaml ~`

Optional
- Create a zsh alias for 't' to run global tasks
`alias t='task -g'`

## Usage
List Tasks
t --list

Run a task
t <taskName>
