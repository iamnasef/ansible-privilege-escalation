# ansible-privilege-escalation

## Description
---

shell.yml is an ansible playbook you can use to make linux privilege escalation attack from user A to user B.\
**User A** must have sudo permessions to run ansible-playbook as **User B**

## How It Works 
---

1. Uses sudo to make a copy of /bin/bash as **User B**
2. Adds SUID Permessions to it, so we can execute it as **User B**

## How To Use
---

1. Run ``` sudo /usr/bin/ansible-playbook shell.yml```\
2. Run ```./bash -p```


## Contact
---
- [Email](mailto:hello@iamnasef.com)
- [Github](https://github.com/iamnasef)
- [Twitter](https://twitter.com/iamnasef)
- [Linkedin](https://www.linkedin.com/in/iamnasef/)
