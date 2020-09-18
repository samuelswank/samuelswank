### Hi, I'm Samuel. 👋

```python
class Samuel:
    def __init__(self, username="shengjiyang", year=2020):
        self.username = username
        self.name = 'Samuel Adam Swank'
        
        self.skills = [
            "Python",
            "NumPy + SciPy",
            "Pandas",
            "scikit-learn",
            "xgboost",
            "TensorFlow",
            "Flask",
            "FastAPI"
            "Heroku",
            "AWS",
            "Elastic Beanstalk",
            "Git + GitHub",
            "Mandarin"
      ]
        
        self.education = {
            'programming': ('Data Science', 'Lambda School'),
        }
        
        self.employment = {
            'desired' : {
                'company' : 'Your Company',
                'role' : 'Data Scientist'
            },
            'current': {
            'company' : 'FedEx Ground',
            'role' : 'Operations Administrator'
            }
        }
        
    def __str__(self):
        description = """
        Aspiring Data Scientist and ameteur philologist with a background in econometrics.
        Absolutely loves Star Trek and the Greek philosophy which inspired it.
        Runs every morning and needs to start hiking and swimming again.
        """
        return description
        
    def learn(self, new_skill):
        self.skills.append(new_skill)

Samuel = Samuel(2020)
```
