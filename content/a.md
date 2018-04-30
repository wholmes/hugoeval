---
title: "This is A's Title"
date: 2018-4-26T11:41:24-05:00
draft: true
author: "Whittfield"
language: "English"
tags: ["tag1", "tag2", "tag3"]
categories: ["cat1"]
moods: ["Happy", "Upbeat"]
color: blue
---

YAML, TOML, JSON
This is A markdow file, it's in the root directory


{{< figure src="https://placeimg.com/640/480/people" title="Steve Francia" >}}


{{< highlight html >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< /highlight >}}


{{< instagram BiD2TAmHpBJ >}}

[Neat]({{< ref "dir1/b.md" >}})

[Who]({{< relref "dir1/dir2/c.md#who" >}})

{{< vimeo 146022717 >}}