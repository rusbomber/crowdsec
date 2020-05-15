## cscli update

Fetch available configs from hub

### Synopsis


Fetches the [.index.json](https://github.com/crowdsecurity/hub/blob/master/.index.json) file from hub, containing the list of available configs.


```
cscli update [flags]
```

### Options

```
  -h, --help   help for update
```

### Options inherited from parent commands

```
  -c, --config-dir string   Configuration directory to use. (default "/etc/crowdsec/cscli/")
      --debug               Set logging to debug.
      --error               Set logging to error.
      --info                Set logging to info.
  -o, --output string       Output format : human, json, raw. (default "human")
      --warning             Set logging to warning.
```

### SEE ALSO

* [cscli](cscli.md)	 - cscli allows you to manage crowdsec

###### Auto generated by spf13/cobra on 14-May-2020