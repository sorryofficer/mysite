---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
categories: ["Project"]
tags: ["electronics", "DIY"]
summary: "One-line summary of this project."
image: "/images/projects/{{ .Name }}.jpg"
---
