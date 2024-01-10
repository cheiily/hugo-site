+++
title = "{{ replace .File.ContentBaseName "-" " " | title | lower }}"
"blog/categories" = []
"blog/tags" = []
date = {{ .Date }}
slug = "{{ printf "%03d" (len (where site.Pages "Section" "post")) }}"
draft = true
+++
