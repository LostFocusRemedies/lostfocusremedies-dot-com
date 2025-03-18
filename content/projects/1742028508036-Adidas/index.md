---
title: "Adidas"
date: 2025-03-15
draft: false
description: "a description"
tags: ["yolo", "tag"]
---
 an example to get you started
# This is a heading
## This is a subheading
### This is a subsubheading
#### This is a subsubsubheading
This is a paragraph with **bold** and *italic* text.
Check more at [Blowfish documentation](https://blowfish.page/)
undefined

# Blowfish Shortcodes Demo

Below you’ll find examples for each shortcode [documented here](https://blowfish.page/docs/shortcodes).

{{< youtubeLite id="SgXhGb-7QbU" label="Blowfish-tools demo" >}}

{{< alert >}}
**Warning!** This action is destructive!
{{< /alert >}}

{{< mermaid >}}
graph LR;
A[Lemons]-->B[Lemonade];
B-->C[Profit]
{{< /mermaid >}}


{{< instagram DHLydRLMZzV >}}


<!-- minimal use -->
{{ partial "video.html" (dict "Src" "https://www.w3schools.com/html/mov_bbb.mp4") }}

<!-- extended use -->
{{ partial "video.html" (dict "Src" "videos/demo.mp4" "Width" "500" "Height" "auto" "Autoplay" "false" "Loop" "false" "Muted" "false" "Controls" "true" "Class" "ght-video") }}