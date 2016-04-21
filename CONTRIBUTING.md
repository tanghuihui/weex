# Weex Contributing Guide

Welcome to create pull requests or open issues for bugfix, doc, example, suggestion and anything.

* [Open Issues](https://github.com/alibaba/weex/issues/new)
* [Create Pull Requests](https://github.com/alibaba/weex/compare)

## Commit Log

FORMAT

```
{action} [{module}] {description}
```

* `{action}`
    * `+` add
    * `*` update or bugfix
    * `-` remove
* `{module}`
    * Including: android, ios, jsfm, html5, doc, website, example, test, all 

for example:

* `+ [android] add refreshing for WebView`
* `* [doc] update video auto-play property`
* `- [example] remove abc`

## Branch Name 

Format: 

```
{module}-{action}-{shortName}
```

* `{module}`, see [commit log module](#commit-log)
* `{action}`
    * Including: feature, bugfix

for example:

* `android-bugfix-memoryLeak`
* `jsfm-feature-communication`

## Pull Request

[Create Pull Requests](https://github.com/alibaba/weex/compare).