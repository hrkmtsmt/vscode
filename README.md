# Setup VSCode `settings.json`

## Step 1. Remove settings.json from VSCode app dir

Remove user settings.json  
Make sure you back up your settigs.json before you delete it

```
rm ~/Library/"Application Support"/Code/User/settings.json
```

## Step 2. Clone settings.json from Git repository to VScode app dir

Clone settings.json

```
git clone git@github.com:hrkmtsmt/vscode.git
```

## Step 3. Create symbolic settings.json

```
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
