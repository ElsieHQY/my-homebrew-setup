# my-homebrew-setup
This repository contains the CLI settings I use to initialize Homebrew on my MacBook.

First, install Homebrew.
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
Add the Homebrew execution path to your PATH environment variable.
```
// Step 1
(echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/use_your_name_in_place_of_it/.zprofile

// Step 2
eval "$(/opt/homebrew/bin/brew shellenv)"
```
Below is the list I installed, recorded for future use.
```
brew install --cask google-chrome
brew install --cask slack
brew install --cask skype
brew install --cask messenger
brew install --cask visual-studio-code
brew install git
brew install bash-git-prompt
```
