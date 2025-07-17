# Dotfiles

Designed to be used with GNU _stow_.

```bash
sudo pacman -S stow
```

Get the repository:
```bash
cd ~
git clone git@github.com:jeraldlt/dotfiles.git
```
Each program has it's own directory, create the symlinks as such:
```bash
cd ~/dotfiles
stow helix # will create symlinks for helix
```
