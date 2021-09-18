# Mirato v2

## Frontmatter Specs

```
id: <uuid4>
type: folder|board|lane|story
```

### Folder

```
id: <uuid4>
type: folder
```

### Board

```
id: <uuid4>
type: board
members:
  - email1
  - email2
tags:
  - name: "name 1"
    color: "color1"
  - name: "name 2"
    color: "color2"
```

### Lane

```
id: <uuid4>
type: lane
```

### Task

```
id: <uuid4>
type: task
```

### Comment

```
id: <uuid4>
type: comment
author: <email>
created_at: <iso datetime>
modified_at: <iso datetime>
```
