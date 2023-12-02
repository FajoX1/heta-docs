# **Class `Repo`**

This class provides methods for working with a hikka mods repository.

## **Method `get_modules()`**
The method is receives all modules from repository.

#### **Arguments**
- `repo` (*string*): URL of the repository.

#### **Return Value**
*List of dictionaries*: List of modules in the format [{"name": "name_mod"}, {"name": "name_mod2"}]

## **Usage Example**
```python
import heta

modules_list = heta.repo.get_modules("https://github.com/FajoX1/FAmods")
print(modules_list)

# Output:

# [{'name': 'wakatime'}, {'name': 'CodeBase64'}, {'name': 'stats'}, {'name': 'faker'}, {'name': 'edmes'}, {'name': 'fun'}, {'name': 'fabrika'}, {'name': 'tonscan'}, {'name': 'telegrapher'}, {'name': 'timer'}, {'name': 'tondns'}, {'name': 'gsearch'}, {'name': 'infoip'}, {'name': 'removebg'}]
```