# Automatic installation of programs and libraries for frontend devs
## Usage
Check out code and copy the `Brewfile.example` file into you home directory as `Brewfile` and if needed add more programs or edit the file as you like. For instance, chose the shell you like. If you want to put your compiled programs anywhere else than `/Applications`, edit the `cask_args appdir: '/Applications'` line accordingly.

Run `install_packages.sh` from your home directory to install all progs from the Brewfile.

After installing your shell environment, add `/usr/local/opt/python@3.7/libexec/bin` to your path [permanently](https://unix.stackexchange.com/questions/26047/how-to-correctly-add-a-path-to-path).

You are done then and have more time to configure your freshly installed mac.

## What the script does
- Install xcode utilities
- Install homebrew
- Install homebrew bundle
- Install all software listed in the local `Brewfile`

## Further reading
- [Homebrew](https://brew.sh/)
- [Homebrew Bundler](https://github.com/Homebrew/homebrew-bundle)
- [Homebrew Cask](https://github.com/caskroom/homebrew-cask)
- [Mac Appstore Command Line Interface](https://github.com/mas-cli/mas)
