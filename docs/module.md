# **Class `module`**

This class provides methods for working with modules.

## **Method `get_link()`**

The method receives a link to the specified module.

### **Arguments**
- `author` (*string*): The author's name of the module.
- `project_name` (*string*): The name of the repository containing the module.
- `module_name` (*string*): The name of the module.

### **Return Value**
*String*: Link to the module.

## **Usage Example**
```python
import heta

print(heta.get_link("Codwizer", "remodules", "virustotal"))

# Output:

# https://heta.hikariatama.ru/Codwizer/remodules/virustotal.py
```

<hr>

## **Method `get_code()`**

The method receives code of the module from module link.

### **Arguments**
- `mlink` (*string*): Link to the module.

### **Return Value**
*String*: Code of the module.

## **Usage Example**
```python
import heta

print(heta.module.get_code("https://raw.githubusercontent.com/FajoX1/FAmods/main/wakatime.py"))
```