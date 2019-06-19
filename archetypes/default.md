---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
weight: {{ strings.TrimLeft "posts/" .File.Path | strings.TrimRight .File.LogicalName | strings.TrimRight "/" }}
tags: []
---

