# **Function `search()`**

This function is searching module in heta

## **Arguments**
- `query` (*string*): The search query.
- `limit` (*int, optional*): The number of search results. Defaults to 1.
- `app_name` (*string, optional*): The application name used in the request header. Defaults to "Heta lib"

## **Return Value**
*Dictionary*: The search result in JSON format.

## **Usage Example**

```python
import heta

for mod in heta.search("carbon", limit=10):
  print(mod['module']['name'])

# Output:

# carbon
# Carbon
# catboy
# Iris
# corona
# RndNsfw
# cartoonimg
# craiyon
# cdeanon
# Craiyon
```