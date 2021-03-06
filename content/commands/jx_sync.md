---
date: 2018-05-21T13:42:49Z
title: "jx sync"
slug: jx_sync
url: /commands/jx_sync/
---
## jx sync

Synchronises your local files to a devpod

### Synopsis

Synchronises your local files to a DevPod so you an build and test your code easily on the cloud 

For more documentation see: http://jenkins-x.io/developing/devpods/

```
jx sync [flags]
```

### Examples

```
  # Starts synchonizing the current directory files to the users DevPod
  jx sync
```

### Options

```
  -c, --container string         The name of the container to log
      --daemon                   Runs ksync in a background daemon
  -d, --dir string               The directory to watch. Defaults to the current directory
  -h, --help                     help for sync
  -n, --namespace string         the namespace to look for the Deployment. Defaults to the current namespace
      --no-init                  Disables the use of 'ksync init' to ensure we have initialised ksync
  -p, --pod string               the pod name to use
      --reload                   Should we reload the remote container on file changes?
  -r, --remote-dir string        The remote directory in the DevPod to sync
      --watch-only ksync watch   Should we just run the ksync watch command only
```

### SEE ALSO

* [jx](/commands/jx/)	 - jx is a command line tool for working with Jenkins X

###### Auto generated by spf13/cobra on 21-May-2018
