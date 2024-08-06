---
title: Rich Content
date: 2022-07-18 20:29:08
tags: ["Hugo", "Ladder", "shortcode"]
featured: false
---
<!--more-->
## figure

## ref in posts
[Neat]({{< ref "blog/videos.md" >}})
[Who]({{< relref "blog/videos.md#who" >}})

## hide toggle
{{< toggle summary="summary" >}}
```shell
hide value
```
{{< /toggle>}}

### without summary
{{< toggle >}}
```shell
hide value
```
{{< /toggle>}}


## tab group code

{{< tab name="Hello" >}}
```shell
Hello World!
```


{{< tab name="Goodbye" >}}
```shell
Goodbye Everybody!
```



## tab group

{{< tab name="MacOS" >}}
brew install hugo


{{< tab name="Linux" >}}
apt install hugo


{{< tab name="Window" >}}
window install hugo

