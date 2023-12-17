# **Class `Repo`**

This class provides methods for working with a hikka mods repository.

## **Method `get_modules()`**
The method is receives all modules from repository.

#### **Arguments**
- `repo` (*string*): URL of the repository.

#### **Return Value**
*List of dictionaries*: List of modules in the format `[{"link": "link_to_mod", "name": "name_mod"}, {"link": "link_to_mod2", "name": "name_mod2"}]`

## **Usage Example**
```python
import heta

modules_list = heta.repo.get_modules("https://github.com/FajoX1/FAmods")
print(modules_list)

# Output:

# [{'link': 'https://github.com/FajoX1/FAmods/raw/main/wakatime.py', 'name': 'wakatime'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/CodeBase64.py', 'name': 'CodeBase64'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/stats.py', 'name': 'stats'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/faker.py', 'name': 'faker'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/edmes.py', 'name': 'edmes'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/fun.py', 'name': 'fun'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/fabrika.py', 'name': 'fabrika'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/tonscan.py', 'name': 'tonscan'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/telegrapher.py', 'name': 'telegrapher'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/timer.py', 'name': 'timer'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/tondns.py', 'name': 'tondns'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/gsearch.py', 'name': 'gsearch'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/infoip.py', 'name': 'infoip'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/removebg.py', 'name': 'removebg'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/hetalib.py', 'name': 'hetalib'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/phoneinfo.py', 'name': 'phoneinfo'}, {'link': 'https://github.com/FajoX1/FAmods/raw/main/checkhost.py', 'name': 'checkhost'}]
```