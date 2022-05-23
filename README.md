# Setup VSCode `settings.json`

```
# Remove user settings.json
# Make sure you back up your settigs.json before you delete it
rm ~/Library/"Application Support"/Code/User/settings.json

# Clone settings.json
git clone

# Create symbolic settigs.json
cd <clone-dir>
ln -s ~/<clone-dir>/settings.json ~/Library/"Application Support"/Code/User/settings.json
```
