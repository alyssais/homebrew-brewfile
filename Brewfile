platform = { "Darwin" => "macOS" }[`uname -s`.chomp]
dir = Pathname.new("#{ENV["HOME"]}/.Brewfile").readlink.dirname
instance_eval (dir/"#{platform}.Brewfile").read if platform

tap  'homebrew/command-not-found'
tap  'vitorgalvao/tiny-scripts'
tap  'neovim/neovim'

brew 'vitorgalvao/tiny-scripts/cask-repair'
brew 'diff-so-fancy'
brew 'direnv'
brew 'extract_url'
brew 'fzf'
brew 'gpg'
brew 'git', args: ["with-pcre2"]
brew 'hub' # maybe dotfiles
brew 'jq'
brew 'less'
brew 'openssh'
brew 'ncdu'
brew 'neovim/neovim/neovim'
brew 'postgresql'
brew 'pv'
brew 'ruby-install'
brew 'ssh-copy-id'
brew 'the_silver_searcher'
brew 'tmux'
brew 'wget'
brew 'weechat', args: ["with-python", "with-perl"]
brew 'yarn'
brew 'youtube-dl'
brew 'z'
brew 'zsh'
