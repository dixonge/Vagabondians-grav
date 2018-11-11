---
#cover: header.jpg  this is optional...
sitemap:
    changefreq: weekly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 8
    pagination: true
feed:
    description: 'Vagabondians - Escape Normal, Explore Your World'
    limit: 3
pagination: true
---