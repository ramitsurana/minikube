## minikube start

Starts a local kubernetes cluster.

### Synopsis


Starts a local kubernetes cluster using Virtualbox. This command
assumes you already have Virtualbox installed.

```
minikube start
```

### Options

```
      --iso-url string   Location of the minikube iso (default "https://storage.googleapis.com/minikube/minikube-0.3.iso")
```

### Options inherited from parent commands

```
      --alsologtostderr value          log to standard error as well as files
      --log-flush-frequency duration   Maximum number of seconds between log flushes (default 5s)
      --log_backtrace_at value         when logging hits line file:N, emit a stack trace (default :0)
      --log_dir value                  If non-empty, write log files in this directory
      --logtostderr value              log to standard error instead of files
      --show-libmachine-logs           Whether or not to show logs from libmachine.
      --stderrthreshold value          logs at or above this threshold go to stderr (default 2)
  -v, --v value                        log level for V logs
      --vmodule value                  comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [minikube](minikube.md)	 - Minikube is a tool for managing local Kubernetes clusters.

