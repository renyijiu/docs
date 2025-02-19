---
id: keto-namespace-validate
title: keto namespace validate
description: keto namespace validate Validate namespace definitions
---

<!--
This file is auto-generated.

To improve this file please make your change against the appropriate "./cmd/*.go" file.
-->

## keto namespace validate

Validate namespace definitions

### Synopsis

validate Validates namespace definitions. Parses namespace yaml files or configuration files passed via the configuration flag.
Returns human readable errors. Useful for debugging.

```
keto namespace validate <namespace.yml> [<namespace2.yml> ...] | validate -c <config.yaml> [flags]
```

### Options

```
  -h, --help   help for validate
```

### Options inherited from parent commands

```
  -c, --config strings   Config files to load, overwriting in the order specified. (default [/home/runner/keto.yml])
```

### SEE ALSO

- [keto namespace](keto-namespace) - Read and manipulate namespaces
