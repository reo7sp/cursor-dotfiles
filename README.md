# cursor-dotfiles

## How to install

```sh
git clone https://github.com/reo7sp/cursor-dotfiles

mkdir -p "$HOME/Library/Application Support/Cursor/"
rm -rf "$HOME/Library/Application Support/Cursor/User"
mv cursor-dotfiles "$HOME/Library/Application Support/Cursor/User"
ln -sf "$HOME/Library/Application Support/Cursor/User" .cursor-dotfiles
cat extensions.txt | xargs -n1 cursor --install-extension
```
