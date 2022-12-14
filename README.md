# Sky Vault
[![Test Coverage](https://img.shields.io/badge/Test%20Coverage-100%25-success)](https://github.com/jacob-h-barrow/Penguin-Services)
[![Security](https://img.shields.io/badge/Secure-True-informational)](https://github.com/jacob-h-barrow/Penguin-Services)
[![Platform](https://img.shields.io/badge/Platform-Ubuntu%2020%2B-critical)](https://github.com/jacob-h-barrow/Penguin-Services)
[![Python Version](https://img.shields.io/badge/Python-3.8%2B-critical)](https://github.com/jacob-h-barrow/Penguin-Services)
[![MIT License](https://img.shields.io/badge/License-MIT-lightgrey)](https://github.com/jacob-h-barrow/Penguin-Services/blob/main/Penguin-Services.png)

![skyvault](https://user-images.githubusercontent.com/117854828/205438474-5aaf5b90-034b-421a-801e-8c1e12a387bd.png)

- Created By Jacob H Barrow

## Why Was It Created
- Got tired of managing my passwords on sticky notes1

## IMPORTANT
- Still work in progress

## Todos
- Tkinter manager
- Automatic installation
- Cloud integration

## Critical Installation
``` console
penguin@services:~$ sudo mkdir -p /usr/code/config
penguin@services:~$ sudo chown $USER /usr/code/config
penguin@services:~$ sudo chmod 710 /usr/code/config
```

## Short Tutorial
``` python
>>> from skyvault import LinuxConfigParser
>>>
>>> user_config = LinuxConfigParser()
>>> user_config.read()
>>> 
>>> information = {"postgresql": [{"key": "host", "value": "localhost"}, {"key": "port", "value": "1337"}]}
>>>
>>> user_config.add_information(information)
>>>  
>>> user_config.parse_printer() 
>>> print(user_config.to_json())
>>> user_config.new_file_write('/tmp/file.ini')
```
## Frequency Of Development
- Whenever the baby and wife are sleeping!

## Remember
- If you find this package helpful, follow mascots and join Dumbledore's Army!
