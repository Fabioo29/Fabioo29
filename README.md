```python
#!/usr/bin/python
# -*- coding: utf-8 -*-


class Engineer:
    def __init__(self):
        self.name = "Fábio Oliveira"
        self.tech_stack = {
            'main': ['Python', 'Django', 'Docker', 'Git'],
            'web': ['Bootstrap', 'JQuery', 'CSS', 'HTML'],
            'xtra': ['C', 'C++', 'VHDL', 'Assembly', 'MATLAB']
            }
    
    def GetInTouch(self, *args):
        print('Reach me on linkedin.com/in/{}/ or with {}.'.format(args[0], args[1]))


me = Engineer()
me.GetInTouch('fabioo29', 'fabiodiogo29@gmail.com')
```
