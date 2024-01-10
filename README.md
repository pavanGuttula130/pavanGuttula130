### Hi there 👋

<!--
**pavanGuttula130/pavanGuttula130** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
```python
from typing import List

__author__ = "Pavan Guttula"
__email__ = "pavanguttula123@gmail.com"
__description__ = (
    " 🤖 Artificial Intelligence Enthusiastic | 🐬 Deep Learning | 🐍 Python "
)
__location__ = "🌎 Anytown, SomeWhere"
__github__ = "https://github.com/pavanGuttula130"


class Who:
    def __init__(self):
        self.author = __author__
        self.email = __email__
        self.description = __description__
        self.location = __location__
        self.github = __github__
        self.interests = [
            "📈 Data science",
            "🤖 Machine learning",
            "🎨 Creative coding"
        ]
        self.skills = [
            "🐍 Python",
            "🐘 PostgreSQL",
            "🍃 MongoDB"
        ]
    def get_interests(self) -> str:
        return " | ".join(self.interests)
    def get_skills(self) -> str:
        return " | ".join(self.skills)
    def __repr__(self):
        return f"<h1>{self.author}</h1><p>{self.description}</p><p>{self.location}</p><p>Interests: {self.get_interests()}</p><p>Skills: {self.get_skills()}</p><a href='{self.github}' target='_blank'>Check out my code on GitHub</a>"

Who()
```
