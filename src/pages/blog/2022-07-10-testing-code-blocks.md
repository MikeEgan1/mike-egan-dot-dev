---
templateKey: blog-post
title: Testing Code Blocks
date: 2022-07-10T22:27:52.429Z
description: Testing code blocks
featuredpost: false
tags:
  - code
  - blocks
  - python
  - requests
---
```python
import requests

response = requests.get('https://www.mikeegan.dev')
if response.status_code == 200:
  print('we did it!')
```

```python
import requests

response = requests.get('https://www.mikeegan.dev')
if response.status_code == 200:
  print('No language')
```

```javascript
// In your gatsby-config.js
plugins: [
  {
    resolve: `gatsby-transformer-remark`,
    options: {
      plugins: [
        `gatsby-remark-prismjs`,
      ]
    }
  }
]
```