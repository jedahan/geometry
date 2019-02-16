### `geometry_docker_machine.zsh`

Show the docker machine name.

Options: none.

### `geometry_exec_time.zsh`

Show the elapsed time for long running commands.

Options:
`GEOMETRY_EXEC_TIME_FILE` - Path to temp directory.
`GEOMETRY_EXEC_TIME_PATIENCE` - Seconds before the time is shown.

### `geometry_git.zsh`

#### `geometry_git_stashes()`
`GEOMETRY_GIT_COLOR_STASHES` - 144
`GEOMETRY_GIT_SYMBOL_STASHES` - ●

#### `geometry_git_time()`
`GEOMETRY_COLOR_NO_TIME` - white 
`GEOMETRY_GIT_NO_COMMITS_MESSAGE` - no-commits
`GEOMETRY_GIT_TIME_DETAILED` - false

#### `geometry_git_branch()`
`GEOMETRY_GIT_COLOR_BRANCH` - 242

#### `geometry_git_status()`
`GEOMETRY_GIT_COLOR_DIRTY`- red
`GEOMETRY_GIT_COLOR_CLEAN`- green
`GEOMETRY_GIT_SYMBOL_DIRTY` - ⬡
`GEOMETRY_GIT_SYMBOL_CLEAN` - ⬢

#### `geometry_git_rebase()`
`GEOMETRY_GIT_SYMBOL_REBASE` - ®

#### `geometry_git_remote() `
`GEOMETRY_GIT_SYMBOL_UNPUSHED` - ⇡
`GEOMETRY_GIT_SYMBOL_UNPULLED` - ⇣
`GEOMETRY_GIT_SYMBOL_CONFLICTS_SOLVED` - ◆
`GEOMETRY_GIT_SYMBOL_CONFLICTS_UNSOLVED` - ◈

#### `geometry_git_conflicts()`
`GEOMETRY_GIT_COLOR_CONFLICTS_UNSOLVED` - red
`GEOMETRY_GIT_COLOR_CONFLICTS_SOLVED` - green
`GEOMETRY_GIT_SYMBOL_CONFLICTS_SOLVED` - ◆
`GEOMETRY_GIT_SYMBOL_CONFLICTS_UNSOLVED` - ◈

#### `geometry_git()`
`GEOMETRY_GIT_COLOR_BARE` - blue
`GEOMETRY_GIT_SYMBOL_BARE` - ⬢

#### `geometry::git_wrapper`
`GEOMETRY_GIT_SEPARATOR` - ::

### `geometry_hg.zsh`

`GEOMETRY_HG_COLOR_BRANCH` - 242
`GEOMETRY_HG_COLOR_DIRTY` - red
`GEOMETRY_HG_SYMBOL_DIRTY` - ⬡
`GEOMETRY_HG_COLOR_CLEAN` - green
`GEOMETRY_HG_SYMBOL_CLEAN` - ⬢
`GEOMETRY_HG_SYMBOL_SEPARATOR` - ::

### `geometry_hostname.zsh`

Shows user and hostname information.

`GEOMETRY_HOSTNAME_HIDE_ON` - localhost
`GEOMETRY_HOSTNAME_SEPARATOR` - @

### `geometry_jobs.zsh`

Shows background jobs.

`GEOMETRY_JOBS_COLOR` - blue
`GEOMETRY_JOBS_SYMBOL` - ⚙

### `geometry_kube.zsh`

Show kubectl (Kubernetes) client version and current context/namespace.

`GEOMETRY_KUBE_COLOR` - blue
`GEOMETRY_KUBE_SYMBOL` - ⎈

### `geometry_node.zsh`

Show node and npm/yarn version when in a node project context.

`GEOMETRY_NODE_COLOR` - green 
`GEOMETRY_NODE_SYMBOL` - ⬡

### `geometry_npm_package_version.zsh`

Display the current folder's npm package version from package.json (by @drager)

`GEOMETRY_NPM_PACKAGE_VERSION_SYMBOL` - 📦
`GEOMETRY_NPM_PACKAGE_VERSION_SYMBOL_COLOR` - red
`GEOMETRY_NPM_PACKAGE_VERSION_COLOR` - red

### `geometry_path.zsh`

Show the current path.

`GEOMETRY_PATH_SYMBOL_HOME` - "%3~"   # symbol representing the home directory
`GEOMETRY_PATH_SHOW_BASENAME` - false
`GEOMETRY_PATH_COLOR` - blue

### `geometry_ruby.zsh`

Display the current ruby version, rvm version, and gemset.

`GEOMETRY_RUBY_COLOR` - white
`GEOMETRY_RUBY_SYMBOL` - ◆
`GEOMETRY_RUBY_RVM_SHOW_GEMSET` - true

### `geometry_rust_version.zsh`

Display the current version of rust (by @drager).

`GEOMETRY_RUST_VERSION_COLOR` - red

### `geometry_rustup.zsh`

Display a symbol colored with the currently selected rustup toolchain.

`GEOMETRY_RUSTUP_STABLE_COLOR` - green
`GEOMETRY_RUSTUP_BETA_COLOR` - yellow
`GEOMETRY_RUSTUP_NIGHTLY_COLOR` - red

### `geometry_status.zsh`

Show a symbol with error/success and root/non-root information

`GEOMETRY_STATUS_COLOR` - white
`GEOMETRY_STATUS_COLOR_ERROR` - red
`GEOMETRY_STATUS_SYMBOL` - ▲
`GEOMETRY_STATUS_SYMBOL_ERROR` - △
`GEOMETRY_STATUS_SYMBOL_ROOT` - ▼
`GEOMETRY_STATUS_SYMBOL_ROOT_ERROR` - ▽
`GEOMETRY_STATUS_SYMBOL_COLOR_HASH` - false

### `geometry_virtualenv.zsh`

Show the current `virtualenv` or `conda` environment.

`GEOMETRY_VIRTUALENV_CONDA_SEPARATOR` - :
`GEOMETRY_VIRTUALENV_COLOR` - `DEFAULT_COLOR`
`GEOMETRY_VIRUALENV_CONDA_COLOR` - `DEFAULT_COLOR`
