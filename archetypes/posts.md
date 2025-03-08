---
date: {{ .Date }}
lastmod: {{ now.Format "2006-01-02" }}
showTableOfContents: false
type: "post"
draft: true
image: ""
title: "{{ replace .File.ContentBaseName `-` ` ` | title }}"
description: ""
tags: ["",]
---
