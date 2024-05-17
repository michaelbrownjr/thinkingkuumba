---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
summary: "Summary goes here"
alias: ["alias goes here"]
draft: false
cover:
    image: "cover image goes here"
    alt: "alt text goes here"
    hiddenInSingle: true
ShareButtons: ["threads", "reddit", "whatsapp", "facebook"]
---