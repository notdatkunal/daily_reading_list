
for linux
```
code --list-extensions | while read extension;
do
 code --uninstall-extension $extension --force
done
```

**For Mac/Linux**

```
rm -rf ~/.vscode/extensions
```

**For Windows**

```
rmdir %USERPROFILE%\.vscode\extensions /s
```

