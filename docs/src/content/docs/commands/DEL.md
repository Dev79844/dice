---
title: DEL
description: DEL deletes all the specified keys
---

<!-- This file is automatically generated. Any modifications made directly to this file
  may be overwritten. For more details on how this file is generated and how to use
  the related commands, refer to the documentation available in the `internal/cmd/cmd_*.go` files.
-->

#### Syntax

```
DEL key [key ...]
```

DEL command deletes all the specified keys and returns the number of keys deleted on success.

#### Examples

```

	localhost:7379> SET k1 v1
OK OK
localhost:7379> SET k2 v2
OK OK
localhost:7379> DEL k1 k2 k3
OK 2
```
