```python
class AboutMe:
    def __init__(self):
        self.contact = {
            "mail": "leticiatsm@icloud.com"
        }
        
        self.personal_information = {
            "country": "São Paulo, Brazil",
            "college": "Presbyterian Mackenzie University"
        }
        
        self.knowledge = {
            "programming_languages": ["Python", "JavaScript", "Swift", "HTML"],
            "databases": ["SQLite"]
        }
    
    def get_contact(self):
        return self.contact
    
    def get_personal_information(self):
        return self.personal_information
    
    def get_knowledge(self):
        return self.knowledge
    
    def __str__(self):
        return (f"Contact: {self.contact}\n"
                f"Personal Information: {self.personal_information}\n"
                f"Knowledge: {self.knowledge}")

if __name__ == "__main__":
    me = AboutMe()
    print(me)
```
