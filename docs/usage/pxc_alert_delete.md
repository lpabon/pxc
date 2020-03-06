## pxc alert delete

Delete Portworx alerts

### Synopsis

Delete Portworx alerts

```
pxc alert delete [flags]
```

### Examples

```

  # Delete portworx related alerts
  pxc alert delete

  # Delete alerts based on particular alert type. Delete all alerts related to "volume"
  pxc alert delete -t "volume"
```

### Options

```
  -h, --help          help for delete
  -t, --type string   alert type (Valid Values: [volume node cluster drive all]) (default "all")
```

### Options inherited from parent commands

```
      --pxc.config string       Config file (default is $HOME/.pxc/config.yml)
      --pxc.config-dir string   Config directory (default "/home/lpabon/.pxc")
      --pxc.context string      Force context name for the command
      --pxc.token string        Portworx authentication token
      --pxc.v int32             [0-3] Log level verbosity
```

### SEE ALSO

* [pxc alert](pxc_alert.md)	 - Manage alerts on a Portworx cluster

###### Auto generated by spf13/cobra on 5-Mar-2020