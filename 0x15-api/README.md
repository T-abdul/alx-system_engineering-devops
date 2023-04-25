0x15. API

Background Context

Old-school system administrators usually only know Bash and that is what they use to build their scripts. While Bash is perfectly fine for a lot of things, it can quickly get messy and not efficient compared to other programming languages. The new generation of system administrators, usually called SREs, are pretty much regular software engineers but instead of building products, they are managing systems. And one of the big differences with their predecessors is that they know more than just Bash scripting.
root@7465a50bd0bd:/alx-system_engineering-devops/0x15-api# vi README.md
root@7465a50bd0bd:/alx-system_engineering-devops/0x15-api# ls
REAADME.md
root@7465a50bd0bd:/alx-system_engineering-devops/0x15-api# cat REAADME.md
0x15. API

Background Context

Old-school system administrators usually only know Bash and that is what they use to build their scripts. While Bash is perfectly fine for a lot of things, it can quickly get messy and not efficient compared to other programming languages. The new generation of system administrators, usually called SREs, are pretty much regular software engineers but instead of building products, they are managing systems. And one of the big differences with their predecessors is that they know more than just Bash scripting.

One popular way to expose an application and dataset is to use an API. Often, they are the public facing part of websites and micro-services so that allow outsiders to interact with them – access and modify their data. In this project, you will access employee data via an API to organize and export them to different data structures.

This is a perfect example of a task that is not suited for Bash scripting, so let’s build Python scripts.
Resources

Read or watch:

    Friends don’t let friends program in shell script
    What is an API
    What is an API? In English, please
    What is a REST API
    What are microservices
    PEP8 Python style - having a clean code respecting style guide is really appreciated in the industry

Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:
General

    What Bash scripting should not be used for
    What is an API
    What is a REST API
    What are microservices
    What is the CSV format
    What is the JSON format
    Pythonic Package and module name style
    Pythonic Class name style
    Pythonic Variable name style
    Pythonic Function name style
    Pythonic Constant name style
    Significance of CapWords or CamelCase in Python
https://www.turnkeylinux.org/blog/friends-dont-let-friends-program-shell-script
https://www.webopedia.com/definitions/api/
https://www.freecodecamp.org/news/what-is-an-api-in-english-please-b880a3214a82/
https://www.sitepoint.com/rest-api/
https://smartbear.com/learn/api-design/microservices/
https://peps.python.org/pep-0008/
