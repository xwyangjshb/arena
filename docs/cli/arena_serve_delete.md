## arena serve delete

delete a serving job and its associated pods

### Synopsis

delete a serving job and its associated pods

```
arena serve delete a serving job [flags]
```

### Options

```
  -h, --help   help for delete
```

### Options inherited from parent commands

```
      --arenaNamespace string   The namespace of arena system service, like TFJob (default "arena-system")
      --config string           Path to a kube config. Only required if out-of-cluster
      --loglevel string         Set the logging level. One of: debug|info|warn|error (default "info")
      --namespace string        the namespace of the job (default "default")
      --pprof                   enable cpu profile
```

### SEE ALSO

* [arena serve](arena_serve.md)	 - Serve a job.

###### Auto generated by spf13/cobra on 7-Sep-2018