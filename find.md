---
title: Find
---

Ever needed to list the number of files or folders?

You can do so by using:

### <strong>Example #1</strong>
Problem: Find number of files named findme in current directory

Input: `find . -name "findme" -type f | wc -l`

Output:

```
1
```

Description:

- `find` to find file named findme
- `wc -l` to count

### <strong>Example #2</strong>
Problem: Find number of folders named node_modules in current directory

Input: `find . -name "node_modules" -type d | wc -l`

Output:

```
11
```

Description:

- `find` to find folder named node_modules
- `wc -l` to count