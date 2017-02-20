# gerrit-events-log-plugin
prebuilt gerrit events-log plugin

Usage:
------------


you should enable your gerrit plugin remote install feature firstly:

> [plugins.allowRemoteAdmin](https://gerrit-review.googlesource.com/Documentation/config-gerrit.html#plugins.allowRemoteAdmin)

> Enable remote installation, enable and disable of plugins over HTTP and SSH.
> If set to true Administrators can install new plugins remotely, or disable existing plugins.
> Defaults to *false*.


```
sh -p 29418 admin@gerrit-server gerrit plugin install https://raw.githubusercontent.com/xusiwei/gerrit-events-log-plugin/master/events-log-v2.13.jar
```
