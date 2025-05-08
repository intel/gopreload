## PROJECT NOT UNDER ACTIVE MANAGEMENT

This project will no longer be maintained by Intel.

Intel has ceased development and contributions including, but not limited to, maintenance, bug fixes, new releases, or updates, to this project.  

Intel no longer accepts patches to this project.

If you have an ongoing need to use this project, are interested in independently developing it, or would like to maintain patches for the open source software community, please create your own fork of this project.  

Contact: webadmin@linux.intel.com
# gopreload

This repo adds functionality that is similar to `LD_PRELOAD` to Golang.
If you import this package and then run your program with the `GO_PRELOAD` environment variable set to a path to plugin, it will be loaded.
To add this to your program all you have to do is add the following into your main file:

```go
import _ "github.com/Granulate/gopreload"
```
