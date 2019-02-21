# Customization Options

Configuring Geometry is just a matter of setting some variables. Below, you'll find a 
list of all possible options that you can set that will override Geometry appearance 
and functionality.



## `geometry_docker_machine.zsh`

Show the docker machine name. 

#### Options

| Variable | Description | Defaults |
| - | - | - |
| `GEOMETRY_DOCKER_MACHINE_SYMBOL` | Indicator. | `⚓` |
| `GEOMETRY_DOCKER_MACHINE_COLOR` | Text color of the machine name. | `blue` |

## `geometry_exec_time.zsh`

Show the elapsed time for long running commands.

#### Options:

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_EXEC_TIME_FILE` | Path to temp direcotry, where file is stored. |  |
|`GEOMETRY_EXEC_TIME_PATIENCE`| Seconds before the time is shown. | |

## `geometry_git.zsh`

Show git related information, such as branch name, status and time since last commit.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_GREP` | Used to override our searching. | `rg` > `ag` > `grep` |

#### `geometry_git_stashes()`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_SYMBOL_STASHES`| Indicator. | `●` |
|`GEOMETRY_GIT_COLOR_STASHES`| Color.| `144` |

#### `geometry_git_time()`
| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_COLOR_NO_TIME`| Text color. | `white` |
|`GEOMETRY_GIT_NO_COMMITS_MESSAGE`| Text message shown when there's no commits.| `no-commits` |
|`GEOMETRY_GIT_TIME_DETAILED`| Detailed timestamp instead of simple. | `false` |

#### `geometry_git_branch()`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_COLOR_BRANCH`| Text color. | `242` |

#### `geometry_git_status()`
| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_COLOR_DIRTY`| Color for the indicator. | `red` |
|`GEOMETRY_GIT_COLOR_CLEAN`| Color for the indicator. | `green` |
|`GEOMETRY_GIT_SYMBOL_DIRTY`| Indicator when dirty. | `⬡` |
|`GEOMETRY_GIT_SYMBOL_CLEAN`| Indicator when clean. | `⬢` |

#### `geometry_git_rebase()`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_SYMBOL_REBASE`| Indicator. | `®` |

#### `geometry_git_remote() `

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_SYMBOL_UNPUSHED`| Unpushed indicator. | `⇡` |
|`GEOMETRY_GIT_SYMBOL_UNPULLED`| Unpulled indicator. | `⇣` |

#### `geometry_git_conflicts()`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_COLOR_CONFLICTS_UNSOLVED`| Unsolved conflicts color. | `red` |
`GEOMETRY_GIT_COLOR_CONFLICTS_SOLVED`| Solved conflicts color. | `green` |
|`GEOMETRY_GIT_SYMBOL_CONFLICTS_SOLVED`| Solved conflicts indicator | `◆` |
`GEOMETRY_GIT_SYMBOL_CONFLICTS_UNSOLVED`| Unsolved conflicts indicator | `◈` |

#### `geometry_git()`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_COLOR_BARE`| Color. | `blue` |
|`GEOMETRY_GIT_SYMBOL_BARE`| Indicator. | `⬢` |

#### `geometry::git_wrapper`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_GIT_SEPARATOR`| Separator for the indicators. | `::` |

## `geometry_hg.zsh`

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_HG_COLOR_BRANCH`| - | `242` |
|`GEOMETRY_HG_COLOR_DIRTY`| - | `red` |
|`GEOMETRY_HG_SYMBOL_DIRTY`| - | `⬡` |
|`GEOMETRY_HG_COLOR_CLEAN`| - | `green` |
|`GEOMETRY_HG_SYMBOL_CLEAN`| - | `⬢` |
|`GEOMETRY_HG_SYMBOL_SEPARATOR`| - | `::` |

## `geometry_hostname.zsh`

shows user and hostname information, by default in the `enter` prompt.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_HOSTNAME_HIDE_ON`| Don't show the username and hostname indicator when the hostname matches.| `localhost` |
|`GEOMETRY_HOSTNAME_SEPARATOR`| Separator between user and hostname. | `@` |

## `geometry_jobs.zsh`

shows background jobs, by default in the `enter` prompt.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_JOBS_SYMBOL`| Indicator. | `⚙` |
|`GEOMETRY_JOBS_COLOR`| Color for the indicator. | `blue` |

## `geometry_kube.zsh`

Show kubectl (Kubernetes) client version and current context/namespace.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_KUBE_COLOR`| Color for the indicator. | `blue` |
|`GEOMETRY_KUBE_SYMBOL`| Indicator. | `⎈` |
|`GEOMETRY_KUBE_PIN`| Can be set to always show `geometry_kube`. | |

## `geometry_node.zsh`

Show node and npm/yarn version when in a node project context.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_NODE_COLOR`| - | `green` |
|`GEOMETRY_NODE_SYMBOL`| - | `⬡` |
|`GEOMETRY_NODE_PIN`| Can be setup to always show `geometry_node` outside of the context of a node project folder. | |

## `geometry_npm_package_version.zsh`

Display the current folder's npm package version from package.json (by @drager)

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_NPM_PACKAGE_VERSION_SYMBOL`| - | `📦` |
|`GEOMETRY_NPM_PACKAGE_VERSION_SYMBOL_COLOR`| - | `red` |
|`GEOMETRY_NPM_PACKAGE_VERSION_COLOR`| - | `red` |

## `geometry_path.zsh`

Show the current path.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_PATH_SYMBOL_HOME`| Symbol representing the home directory. | `%3~` |
|`GEOMETRY_PATH_SHOW_BASENAME`| - | `false` |
|`GEOMETRY_PATH_COLOR`| - | `blue` |

## `geometry_ruby.zsh`

Display the current ruby version, rvm version, and gemset.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_RUBY_COLOR`| - | `white` |
|`GEOMETRY_RUBY_SYMBOL`| - | `◆` |
|`GEOMETRY_RUBY_RVM_SHOW_GEMSET`| - | `true` |

## `geometry_rust_version.zsh`

Display the current version of rust (by @drager).

| Variable | Description | Defaults |
| - | - | - |
`GEOMETRY_RUST_VERSION_COLOR`| - | `red` |

## `geometry_rustup.zsh`

Display a symbol colored with the currently selected rustup toolchain.

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_RUSTUP_STABLE_COLOR`| - | `green` |
|`GEOMETRY_RUSTUP_BETA_COLOR`| - | `yellow` |
|`GEOMETRY_RUSTUP_NIGHTLY_COLOR`| - | `red` |
|`GEOMETRY_RUSTUP_PIN`| Can be setup to keep rustup rendering even out of context. | |
|`GEOMETRY_RUSTUP_SYMBOL`| - | `⚙` |

## `geometry_status.zsh`

Show a symbol with error/success and root/non-root information

| Variable | Description | Defaults |
| - | - | - |
|`GEOMETRY_STATUS_COLOR`| - | `white` |
|`GEOMETRY_STATUS_COLOR_ERROR`| - | `red` |
|`GEOMETRY_STATUS_SYMBOL`| - | `▲` |
|`GEOMETRY_STATUS_SYMBOL_ERROR`| - | `△` |
|`GEOMETRY_STATUS_SYMBOL_ROOT`| - | `▼` |
|`GEOMETRY_STATUS_SYMBOL_ROOT_ERROR`| - | `▽` |
|`GEOMETRY_STATUS_SYMBOL_COLOR_HASH`| - | `false` |

## `geometry_virtualenv.zsh`

Show the current `virtualenv` or `conda` environment.

|`GEOMETRY_VIRTUALENV_CONDA_SEPARATOR`| - | `:` |
|`GEOMETRY_VIRTUALENV_COLOR`| - | `green` |
|`GEOMETRY_VIRUALENV_CONDA_COLOR`| - | `green` |
