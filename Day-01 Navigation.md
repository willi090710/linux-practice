# Linux Navigation

**Date:** June 10, 2026

## What I Learned

- `pwd`
- `ls`
- `cd`

---

## `pwd`

**With `pwd`, I can see my current location in the file system.**

### Example

```bash
pwd
```

Output:

```text
/home/willi
```

---

## `ls`

**With `ls`, I can see the contents of the current directory.**

### Example

```bash
pwd
```

Output:

```text
/home/willi
```

```bash
ls
```

Output:

```text
Desktop  Documents  Downloads  Music  Pictures  Videos
```

### Additional Information

Using the `-a` option displays hidden files and directories, which usually start with a dot (`.`).

```bash
ls -a
```

---

## `cd`

**With `cd`, I can navigate through directories.**

### Example

```bash
ls
```

Output:

```text
Desktop  Documents  Downloads  Music  Pictures  Videos
```

```bash
cd Downloads
pwd
```

Output:

```text
/home/willi/Downloads
```
