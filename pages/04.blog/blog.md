---
title: Blog
metadata:
  description: A tale of **awesomazing** adventures

slug: my-gravtastic-blog

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true

feed:
    description: Sample Blog Description
    limit: 10

pagination: true
---

# My Gravtastic Blog
A tale of **awesomazing** adventures
