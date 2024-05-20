# Neovim + NvChad setup
This config is primarily for Node.js and Golang, but I might add other LSPs as well.

## How to run?
1. Install Neovim on your system: `brew install nvim` or `pacman -Sy nvim`
2. Install NvChad `git clone -b v2.0 https://github.com/NvChad/NvChad ~/.config/nvim --depth 1`
3. Install GO `brew install go` or `pacman -Sy go`
4. Install Node.js `brew install node` or `pacman -Sy node`
5. Install goimports, gofumpt and golines: `go install github.com/incu6us/goimports-reviser/v3@latest` `go install mvdan.cc/gofumpt@latest` `go install github.com/segmentio/golines@latest`
6. Go to your custom Neovim config directory and clone my repository `git clone https://github.com/TheBunnies/nvim-config --depth 1`

## Terminal setup
I use tmux + ITerm2 + oh-my-zsh on my Mac and tmux + oh-my-zsh on my Arch Linux.
You might also want to install the Nerd font. Personally I use `JetBrainsMono Nerd Font`
`pacman -Sy ttf-jetbrains-mono-nerd` or `brew install font-jetbrains-mono-nerd-font`
