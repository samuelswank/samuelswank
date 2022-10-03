### Hi, I'm Samuel! 👋

```python
class Samuel:
    def __init__(self, username="samuelswank", year=2022):
        self.username = username
        self.name = 'Samuel Adam Swank'
        
        self.skills = {
            'Python' : { 
                'Pandas',
                'Matplotlib',
                'scikit-learn',
                'Flask'
            },
            'R': {
                'tidyverse',
                'Shiny'
            },
            'C#' : {
                'Entity Framework Core',
                'xUnit'
            },
            'SQL' : { 'PostgreSQL' }
            'Devops' : { 
                'Amazon Web Services' : { 'AWS Relational Database Management System' } 
            },
            'Devops' : { 'Amazon Web Services' : { 'AWS Relational Database Management System' } },
            'Mandarin' : { '我住台灣兩年' }
        }
        
        self.education = {
            'certifications': ( 'Data Science', 'Bloom Institute of Technology' ),
            'degrees' : { 'Associates' : ( 'General Studies', 'Salt Lake Community College' ) }
        }
        
        self.employment = {
            'desired' : {
                'company' : 'Your Company',
                'role' : 'Software Engineer'
            },
            'current': {
            'company' : 'FedEx Ground',
            'role' : 'Operations Administrator'
            }
        }
        
    def __str__(self):
        description = """
        Software Engineer and Researcher.
        Absolutely loves Star Trek and the Greek philosophy which inspired it.
        Runs every morning and needs to start hiking and swimming again.
        """
        return description
        
    def learn(self, new_skill):
        self.skills.append(new_skill)

Samuel = Samuel(year=2022)
```

Portfolio : [Samuel Swank](https://samuelswank.github.io/)

Medium : [Samuel Swank](https://medium.com/@samswank)

LinkedIn : [Samuel Swank](https://www.linkedin.com/in/samuel-swank/)
