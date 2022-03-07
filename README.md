# Hi there, welcome!

[![Open Source Love svg3](https://badges.frapsoft.com/os/v3/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)


```python
#!/usr/bin/python
# -*- coding: utf-8 -*-
from dataclasses import dataclass


@dataclass
class DataEngineer:
    """Makes data pipelines and do magic"

    name: str = "Jonas Ferreira"
    role: str = "Data Engineer"
    location: str = "Brazil"
    knowledge_base: list = [
        "Data Engineering",
        "Machine Learning",
        "Cloud Platforms"
    ]
    
    def __post_init__(self):
        self.knowledge_base.insert(0, "Clean Code")

    def say_hello(self):
        print(f"""Hey, whats up? My name is {self.name} and i live in {self.location}. 
                 Nowadays i am working as a {role} and recently I am focusing on {self.knowledge_base[0]} 
                 and {self.knowledge_base[2]} for my personal and professional growth.""")
       
me = DataEngineer()
me.say_hello()

```

## 🔧 Technologies & Tools

![](https://img.shields.io/badge/OS-Linux-informational?style=flat&logo=linux&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Editor-VS_Code-informational?style=flat&logo=visual-studio-code&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Code-Python-informational?style=flat&logo=python&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Shell-Bash-informational?style=flat&logo=gnu-bash&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-PostgreSQL-informational?style=flat&logo=postgresql&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-MySQL-informational?style=flat&logo=mysql&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-Docker-informational?style=flat&logo=docker&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-GCP-informational?style=flat&logo=google&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-AWS-informational?style=flat&logo=amazon&logoColor=white&color=blueviolet)
![](https://img.shields.io/badge/Tools-Azure-informational?style=flat&logo=microsoft&logoColor=white&color=blueviolet)

