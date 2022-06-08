# Setup VSCode `settings.json`

```
# Remove user settings.json
# Make sure you back up your settigs.json before you delete it
rm ~/Library/"Application Support"/Code/User/settings.json

# Clone settings.json
git clone git@github.com:hrkmtsmt/vscode.git

# Create symbolic settigs.json
cd <clone-dir>
ln -s ~/<clone-dir>/settings.json ~/Library/"Application Support"/Code/User/settings.json
```

## Font Family

```
font-family: "'JetBrains Mono', 'GenJyuuGothic-Monospace-Regular', monospace";
```

- JetBrains Mono

https://www.jetbrains.com/ja-jp/lp/mono/

- GenJyuu Gothic

http://jikasei.me/font/genjyuu/
