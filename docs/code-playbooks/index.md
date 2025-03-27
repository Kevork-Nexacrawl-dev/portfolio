````markdown
---
title: Code Playbooks
description: Production-ready code patterns and solutions I've implemented
---

# Code Playbooks

This section contains reusable code patterns and solutions from my professional work.

## Python Async Patterns

```python
async def fetch_data(url):
    async with aiohttp.ClientSession() as session:
        async with session.get(url) as response:
            return await response.json()
        
````
