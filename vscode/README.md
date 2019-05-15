# VSCode

## Extensions

### Export

```bash
code --list-extensions > extensions
```

### Import

```bash
cat extensions | xargs -L 1 echo code --install-extension
```
