# Create and Delete Files/Folders

**Date:** Jun 22, 2026

## What I Learned

- `touch`
- `rm`
- `mkdir`
- `rmdir`

---

## Files

**With `touch`, I can create a file.**

### Example

```bash
touch notes.txt
ls
```

Output:

```text
Desktop  Documents  Downloads  Music  notes.txt  Pictures
```

**With `rm`, I can delete a file permanently.**

### Example

```bash
rm notes.txt
ls
```

Output:

```text
Desktop  Documents  Downloads  Music  Pictures
```

---

## Folders

**With `mkdir`, I can create a new folder.**

### Example

```bash
mkdir notes
ls
```

Output:

```text
Desktop  Documents  Downloads  Music  notes
```

**With `rmdir`, I can delete an empty folder. (`rm -r` deletes a folder and everything inside it.)**

### Example

```bash
rmdir notes
ls
```

Output:

```text
Desktop  Documents  Downloads  Music
```
