---
title: "Module Details: hideoper (v3)"
---

## The "hideoper" Module

### Description

This module adds user mode `H` (hideoper) which hides the server operator status of a user from unprivileged users.

### Configuration

To load this module use the following `<module>` tag:

```xml
<module name="hideoper">
```

This module requires no other configuration.

### User Modes

Name     | Character | Type   | Parameter Syntax | Usable By        | Description
-------- | --------- | ------ | ---------------- | ---------------- | -----------
hideoper | H         | Switch | *None*           | Server operators | Hides the user's server operator status from unprivileged users.
