---
layout: default
title: Credits
number: 1
---

# Credits

MinDoc Manual: A Minimal Computing Template for Publishing Digital Documentary Editions of Primary Sources

By: Liza Senatorova, Chris Goodwin, John Randolph, Caroline Kness

{{ site.mindoc_media | sort: "order" | where_exp: "item", "item.page == 'source'" | where_exp: "item", "item.media_type == 'image'" | where_exp: "item", "item.order == '01'" }} {% include media.html pages=intro_images %}

{% include media.html pages=intro_images %} 
