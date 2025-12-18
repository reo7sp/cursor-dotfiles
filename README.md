# cursor-dotfiles

## How to install

```sh
git clone https://github.com/reo7sp/cursor-dotfiles

mkdir -p "$HOME/Library/Application Support/Cursor/"
mv cursor-dotfiles "$HOME/Library/Application Support/Cursor/User"
cat extensions.txt | xargs -n1 cursor --install-extension
```
