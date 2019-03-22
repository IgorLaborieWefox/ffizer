# Changelog

<a name="x.y.z-dev" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version x.y.z-dev

### Changed
- ⬆️  Bump reqwest from 0.9.11 to 0.9.12

### Fixed
- 🐛  (git) fix authentication via ssh, https

### Miscellaneous
- ⚗  (ci) update github-upload task to not failed on error during release creation
- 🚧  (cargo-release) start next development iteration 0.11.4-dev

<a name="0.11.3" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.11.3

### Fixed
- 🐛  (git) remove folder if error during git retieve

### Miscellaneous
- 🚀  (cargo-release) version 0.11.3
- ⚗  (ci) try fix for github-upload
- 📝  update changelog
- 🚧  (cargo-release) start next development iteration 0.11.3-dev

<a name="0.11.2" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.11.2

### Fixed
- 🐛  (ci) try to fix github-upload-flow

### Miscellaneous
- 🚀  (cargo-release) version 0.11.2
- 🚧  (cargo-release) start next development iteration 0.11.2-dev

<a name="0.11.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.11.1

### Added
- ✨  (hbs) add helper env_var
- ✨  default_value can be composed of previously defined value

### Changed
- ⬆️  (build) update cargo.lock
- 🔧  (ci) try to fix upload of asset on github (for windows, mac, linux)
- ⬆️  Bump handlebars from 1.1.0 to 2.0.0-beta.1
- ♻️  (git) try to git pull instead of rm + clone on already cached (cloned) template
- 🔧  (cargo) tried to decrease size of executable
- ⬆️  Bump structopt from 0.2.14 to 0.2.15

### Fixed
- 🐛  (test) fix test about env_var
- 🐛  path_helpers canonicalize existing path
- 🐛  (test) fix warning
- 🐛  try to static link openssl
- 🐛  fix the download of git repository

### Miscellaneous
- 🚀  (cargo-release) version 0.11.1
- 🚀  (cargo-release) version 0.11.0
- 📝  (ci) add info
- ⚗  (build) fix syntax error in Makefile.toml
- ⚗  (build) try to use github-release to upload dist
- 🚧  (cargo-release) start next development iteration 0.10.3-dev

<a name="0.10.2" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.10.2

### Changed
- ⬆️  Bump reqwest from 0.9.10 to 0.9.11

### Removed
- 🔥  (cirrus) remove upload script

### Miscellaneous
- 🚀  (cargo-release) version 0.10.2
- ⚗  (travis) try named cache to optimize
- 🚧  (cargo-release) start next development iteration 0.10.2-dev

<a name="0.10.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.10.1

### Added
- 👷  (azure) set up CI with Azure Pipelines

### Changed
- 🔧  (make) use profile and platform
- 🔧  (make) move upload to github as part of make
- 🔧  (azure) add deploy to github + fix variables
- 🔧  (cirrus) fix osx script
- 🔧  (cirrus) fix syntax
- 🔧  (publish) diseable changelog update during publication
- 🔧  (travis) try to workaround the timeout (on windows)
- 🔧  (cirrus) try a windows &amp; osx setup

### Removed
- 🔥  (cirrus) remove cirrus-ci configuration

### Fixed
- 🐛  (azure) profile injection cross platform
- 🐛  (azure) fix typo in profile injection
- 🐛  (azure) try to fix syntax
- 🐛  (make) fix typo in tasks.zip-release-binary-for-target
- 🐛  (make) fix syntax error into windows path
- 🐛  (windows) try to fix the packaging
- ✏️  (README) syntax error
- 🐛  (travis) always build the zip to not fail during release

### Miscellaneous
- 🚀  (cargo-release) version 0.10.1
- 🚧  (cirrus) disable codecov on cirrus
- 📦  (make) use &quot;cargo release&quot; for publish-flow
- 📝  add a CHANGELOG.md
- 📦  (cargo) update lock
- 🚧  (cargo-release) start next development iteration 0.10.1-dev

<a name="0.10.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.10.0

### Added
- 👷  (travis) increase cache timeout (try to fix for windows)
- 👷  (cirrus) try to setup codecov
- 👷  (cirrus) add missing install of cargo-make (2)
- 👷  (cirrus) add missing install of cargo-make
- 👷  (travis, cirrus, make) setup cargo-make
- 👷  (cirrus) trigger and enable release mode
- 👷  start experiment with cirrus-ci
- ✅  (e2e) add a basic test about import
- ✨  (imports) allow to use ffizer_src_uri and ffizer_src_rev into imports
- ✨  (fileext) remove extention .ffizer.raw (and keep it)
- 👷  (travis) try to re-enable the cache
- 👷  (travis) disable cargo install-update -a
- ✨  (imports) allow template to be composed by other template
- 👷  increase timeout when builing on travis

### Changed
- 🎨  use Upper Case for lazy static ref
- ⬆️  Bump serde from 1.0.88 to 1.0.89
- ⬆️  Bump regex from 1.1.0 to 1.1.2
- ⬆️  Bump lazy_static from 1.2.0 to 1.3.0
- 🎨  (tests) automate test from local directories
- ⬆️  Bump reqwest from 0.9.9 to 0.9.10
- ⬆️  Bump serde from 1.0.87 to 1.0.88
- ⬆️  Bump tempfile from 3.0.6 to 3.0.7
- 🎨  (render) introduce a TransformValues trait - use it to delegate its impl to each type
- ⬆️  Bump assert_cmd from 0.10.2 to 0.11.0
- ⬆️  Bump tempfile from 3.0.5 to 3.0.6
- ⬆️  Bump serde from 1.0.86 to 1.0.87
- 🎨  change the way to import serde &amp; serde_derive
- 📌  update locked dependencies
- 🎨  apply clippy suggestions
- 🎨  reformat
- 🎨  refactor source definition into SourceLoc (SourceLoc can be used from cli or cfg)
- 🎨  (cfg) remove crappy ignores_str, by using a PathPattern
- ⬆️  Bump reqwest from 0.9.8 to 0.9.9
- ⬆️  Bump serde_derive from 1.0.84 to 1.0.85
- ⬆️  Bump serde from 1.0.84 to 1.0.85
- ⬆️  Bump Inflector from 0.11.3 to 0.11.4
- ⬆️  Bump console from 0.7.3 to 0.7.5
- ⬆️  Bump console from 0.7.2 to 0.7.3
- ⬆️  Bump reqwest from 0.9.5 to 0.9.8
- ⬆️  Bump self_update from 0.5.0 to 0.5.1
- ⬆️  Bump failure from 0.1.4 to 0.1.5
- ⬆️  Bump serde_derive from 1.0.83 to 1.0.84
- ⬆️  Bump serde from 1.0.83 to 1.0.84
- 🎨  remove useless 'extern crate' with rust edition 2018
- 🎨  refactor cli opts and sub command
- ⬆️  Bump failure from 0.1.3 to 0.1.4
- ⬆️  Bump serde from 1.0.82 to 1.0.83
- ⬆️  Bump serde_derive from 1.0.82 to 1.0.83
- ⬆️  Bump indicatif from 0.10.3 to 0.11.0
- ⬆️  Bump console from 0.7.1 to 0.7.2

### Removed
- 🔇  (scripts) remove trace when run getLatest.sh

### Fixed
- 🐛  fix getLatest.sh for linux
- 🐛  remove .unwrap() inside main code
- 🐛  (e2e) ignore diff between \r\n and \n
- ✏️  (README) fix typo
- 🐛  (travis) fix syntax error

### Miscellaneous
- 🚀  (cargo-release) version 0.10.0
- 📦  set the right version (0.10.0 not yet release)
- 📝  (README) add codecov badge
- 📦  try cargo-release
- 📝  (README) update features checkbox
- 📦  prepare release
- 📦  (scripts) to download the latest binary
- 📦  repo for sample renamed
- 📝  (README) complete homebrew instruction
- 📦  (brew) move homebrew stuff to homebrew-ffizer repo
- 📦  transfert repo ownership from davidB to ffizer
- 📦  (homebrew) experiment to deploy a formulae
- 📝  (README) update link to book
- 🚀  deploying docs manually (no ci)
- 📝  (book) move part of content of README into book

<a name="0.9.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.9.0

### Changed
- 🎨  apply clippy suggestion
- ⬆️  Bump git2 from 0.7.5 to 0.8.0
- ⬆️  Bump serde_derive from 1.0.81 to 1.0.82
- ⬆️  Bump serde from 1.0.81 to 1.0.82
- ⬆️  Bump structopt from 0.2.13 to 0.2.14
- ⬆️  Bump serde_derive from 1.0.80 to 1.0.81
- ⬆️  Bump serde from 1.0.80 to 1.0.81

### Breaking changes
- 💥  cli change to support subcommand (apply &amp; upgrade)

<a name="0.8.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.8.0

### Changed
- ⬆️  move to rust edition 2018
- 🚸  (cli) use human_panic...

### Miscellaneous
- 📦  prepare release

<a name="0.7.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.7.1

### Changed
- ⬆️  Bump regex from 1.0.6 to 1.1.0
- ⬆️  Bump indicatif from 0.10.2 to 0.10.3
- ⬆️  Bump indicatif from 0.10.1 to 0.10.2
- ⬆️  Bump console from 0.7.0 to 0.7.1
- ⬆️  upgrade dependencies

### Miscellaneous
- 📦  prepare release
- 📝  (README) add a template to the list

<a name="0.7.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.7.0

### Added
- ✨  (cfg) can use handlebars into ignores'entry and default_value in ffizer.yaml
- 👷  (travis) try to fix random timeout on windows (6)
- 👷  (travis) try to fix random timeout on windows (5)
- 👷  (travis) try to fix random timeout on windows (4)
- 👷  (travis) try to fix random timeout on windows (3)
- 👷  (travis) try to fix random timeout on windows (2)
- 👷  (travis) try to fix random timeout on windows
- ✨  (render) add helper to transform path

### Changed
- 🎨  (e2e) compare content of file as string (vs vec[u8]) to ease debug
- 🎨  (e2e) capture stderr &amp; stdout
- ⬆️  Bump tempfile from 3.0.4 to 3.0.5
- ⬆️  Bump indicatif from 0.9.0 to 0.10.1

### Fixed
- ✏️  (README) fixing typo

### Miscellaneous
- 📦  prepare release
- 🚧  (cfg) allow to use handlebars and cli info into part of ffizer.yml
- 📝  (README) how to chain helpers
- 📝  (README) fix syntax
- 📦  (cargo) try to exclude tests

<a name="0.6.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.6.0

### Added
- ✨  (render) add helper to do http request and a preconfigured to request gitignore.io
- ✨  #6 (render) add helper to transform string

### Changed
- 🔧  (e2e) disable remote test by default

### Miscellaneous
- 📦  prepare release

<a name="0.5.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.5.0

### Changed
- 🚸  (cli) clean display to user (happy path only)
- ⬆️  Bump dialoguer from 0.2.0 to 0.3.0

### Miscellaneous
- 📝  (README) update doc (help, usage,...)

<a name="0.4.2" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.4.2

### Added
- ✨  (cli) add support of source subfolder

### Changed
- ⬆️  Bump assert_cmd from 0.10.1 to 0.10.2

### Miscellaneous
- 📦  (release) customize release profile
- 📝  (README) update features list (states &amp; planned)

<a name="0.4.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.4.1

### Added
- ✨  (cli) add --rev to specify the git revision

### Fixed
- 🐛  (git) do not remove existing cache before success clone

<a name="0.4.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.4.0

### Added
- 👷  (travis) remove build for i686
- 👷  (travis) try to fix compilation on i686
- ✨  (cli) add offline mode
- ✨  (source) accept remote git repository as source for template

### Changed
- 🎨  (git) comment unused code
- ♻️  move Uri into SourceUri
- 🎨  prepare for rust edition 2018
- 🎨  (e2e) test the executable via cli
- ⬆️  Bump dialoguer from 0.1.0 to 0.2.0

### Fixed
- 🐛  (windows) try to fix bug when git clone
- 🐛  detection of file to &quot;Ignores&quot; is done during the scan
- 🐛  fix a bug when compare 2 files (one with .ffizer.hbs and one without)
- 🐛  fix due to change in api of dialoguer
- 🐛  fix file order priority

### Miscellaneous
- 📦  prepare release
- 📦  (cargo) clean travis info
- 📄  (LICENSE) list dependencies and licenses in CREDITS
- 📦  (travis) store note for future check
- 📝  (README) remade the TOC
- 🚧  prepare to support several form of template uri

<a name="0.3.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.3.0

### Added
- ✨  (cli) add experimental flags to always accept default value for variables
- ✨  (cli) add flags to control confirmation (always, never, auto)
- ✨  (cfg) allow to ignore (glob) file and directy
- ✅  (e2e) add 2 tests to show every features (need some improvement)

### Changed
- ⬆️  Bump walkdir from 2.2.6 to 2.2.7
- ♻️  (cli) move Cmd into Ctx.cmd_opt: CmdOpt

### Fixed
- 🐛  fixe processing order of files
- 🐛  (render) use the rendered path for *.ffizer.hbs
- 🐛  (render) enable strict mode and log variables to help debug template
- ✏️  (README) fix title level
- 🐛  (travis) ‘cargo publish’ doesn’t work on windows

### Miscellaneous
- 📦  prepare release
- 📝  (README) add TOC

<a name="0.2.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.2.1

### Fixed
- 🐛  (cargo) expected at most 5 keywords per crate

### Miscellaneous
- 📦  prepare release
- 📝  (README) update badges
- 📝  (README) update install instruction
- 📦  (travis) generate archive without target path

<a name="0.2.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.2.0

### Added
- ✨  (render) file name and folder name could be rendered
- 👷  (appveyor) remove appveyor as CI
- 👷  (travis) try a workaround to deploy windows (2)

### Changed
- ♻️  (error) use failure to manage the error

### Fixed
- ✏️  (README) wrong project name, reformulate

### Miscellaneous
- 📦  prepare release
- 🚧  (render) basic implementation to support *.ffizer.hbs
- 🚧  read a configuration file (.ffizer.yaml) from the template folder

<a name="0.1.2" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.1.2

### Added
- 👷  (travis) try a workaround to deploy windows (3)
- 👷  (travis) try a workaround to deploy windows (2)

<a name="0.1.1" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.1.1

### Added
- 👷  (travis) try a workaround to deploy windows
- 👷  (travis) fix the api_key

<a name="0.1.0" data-comment="this line is used by gitmoji-changelog, don't remove it!"></a>
## Version 0.1.0

### Added
- 👷  (travis) try to add windows support
- ✨  (cli) ask confirmation before apply plan
- ✨  copy dir and files from template and base for next step (cause it’s not KISS).
- 👷  fix os specific setup
- ✅  initialize testing
- 👷  bootstrap conf for travis and appveyor
- ✨  (main) setup of log + cli arguments read
- 🎉  init

### Changed
- 💄  (cli) add a progress bar for the execution (experimental)
- 🚸  (cli) complete description
- 🎨  (main) main is a wrapper for the lib
- 🚚  rename project from fgen to ffizer fgen already exists

### Fixed
- 🐛  (README) fix appveyor badge
- 🐛  (cli) use flags instead of args, correct description

### Miscellaneous
- 📦  (cargo) prepare info for publishing
- 📝  (README) udapte
- 🚧  (cli) confirm plan before execute
- 🚧  ordering action by path
- 📝  (README) add badges for travis, status, license
- 📄  add license CC0-1.0
- 🚧  (copy mode) bootstrap the code for plan &amp; execute + scan src
- 📝  (README) add help of the cli, and sub-features
- 📝  (README) update alternatives list
- 📝  (README) fix format
- 📝  (README) ideas &quot;en vrac&quot;
- 📝  (README) add ideas, motivations, alternatives,...

_Generated by [gitmoji-changelog (rust version)](https://github.com/fabienjuif/gitmoji-changelog-rust)_