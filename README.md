# Automatic installation of apps, tools and libraries for frontend devs

## Usage

1. Edit the `Brewfile.example` and edit, add or remove casks as you like.
2. If you want to put your apps anywhere else than `~/Applications`, edit the `cask_args appdir` line accordingly.
3. Rename `Brewfile.example` to `Brewfile` and move it to your home directory along with `install_packages.sh`.
4. Ensure that you have admin privileges then run `chmod +x install_packages.sh && ./install_packages.sh`.
5. Make sure that the installed Python version is available in your path as `python` and pip is available as `pip`. It is probably necessary to add an alias like `alias python=python3.10` and `alias pip=pip3.10`.

## What the script does

1. Install xcode utilities
2. Install homebrew
3. Add `homebrew/bundle` tap
4. Install all software listed in the local `Brewfile`

## Further reading

- [Homebrew](https://brew.sh/)
- [Homebrew Bundler](https://github.com/Homebrew/homebrew-bundle)
- [Homebrew Cask](https://github.com/caskroom/homebrew-cask)
- [Mac Appstore Command Line Interface](https://github.com/mas-cli/mas)
- 
