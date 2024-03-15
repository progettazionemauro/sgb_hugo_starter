<p>Site Description: {{ .Site.Params.siteDescription }}</p>

+++
title = '{{ replace .File.ContentBaseName "-" " " | title }}'
date = {{ .Date }}
draft = true
+++
