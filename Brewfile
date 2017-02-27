platform = { "Darwin" => "macOS" }[`uname -s`.chomp]
dir = Pathname.new("#{ENV["HOME"]}/.Brewfile").readlink.dirname
instance_eval (dir/"#{platform}.Brewfile").read if platform

tap  'homebrew/command-not-found'
tap  'vitorgalvao/tiny-scripts'
tap  'homebrew/dupes'
tap  'neovim/neovim'

brew 'vitorgalvao/tiny-scripts/cask-repair'
brew 'diff-so-fancy'
brew 'direnv'
brew 'gpg'
brew 'gpg-agent'
brew 'git'
brew 'hub' # maybe dotfiles
brew 'homebrew/dupes/less'
brew 'homebrew/dupes/openssh'
brew 'neovim/neovim/neovim'
brew 'postgresql'
brew 'ruby-install'
brew 'ssh-copy-id'
brew 'the_silver_searcher'
brew 'yarn'
brew 'youtube-dl'
brew 'zsh'
