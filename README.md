# find-command

When you know the exact file name:
```bash
sudo find / -name CMakeLists.txt 2>/dev/null
```

When you do not know the exact file name:

```bash
sudo find / -name "ubuntu*" 2>/dev/null
```

Search multiple files:
```bash
sudo find / -name ge25519.c -o -name ed25519.c 2>/dev/null
```
