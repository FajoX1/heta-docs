# **Function `decode_hash()`**

This function is decoding heta module hash.

## **Arguments**
- `mhash` (*string*): The hash to decode.
- `app_name` (*string, optional*): The application name used in the request header. Defaults to "Heta lib"

### **Return Value**
*Dictionary*: The result of hash decoding in JSON format.

## **Usage Example**
```python
import heta

result = heta.decode_hash("207db6467c7ddd9b")
print(result)

# Output:

# {'link': 'https://heta.hikariatama.ru/Codwizer/ReModules/VirusTotal.py', 'name': 'VirusTotal'}
```