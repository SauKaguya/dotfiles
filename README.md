# dotfiles

On the new system you want to recreate the dot files:
```bash
git init .
git remote add origin https://github.com/SauKaguya/dotfiles.git
git fetch
# rm .bashrc ... # any files that are present by OS default
git checkout dotfiles
```
