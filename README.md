<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2500&pause=1000&color=39FF14&center=true&vCenter=true&width=435&lines=Hi+there!+I%27m+Aryan;Love+to+Code+and+Teach" alt="Typing SVG" />
</p>

```python
class AryanPuranSanaye:
    """
    • From Iran.
    • Junior Python Developer  
    • Passionate about teaching, clean coding, and learning
    • A fan of clean, well-structured code, passionate about teaching, and committed to lifelong learning.
    • Master's Student in Software Engineering

    """

    # ──────────────────────────────────────────────────────────────────────
    # INITIALISATION
    # ──────────────────────────────────────────────────────────────────────

    def __init__(self) -> None:
        self.full_name = "Aryan PuranSanaye"
        self.title = (
            "Junior Python Developer  |  Python Instructor"
        )

        #My Skills 🤹
        self.skills = {
            "Languages":  ["Python"],
            "Frameworks": ["Django", "Django REST Framework"],
            "Libraries":  ["python-telegram-bot", "Tkinter"],
            "Paradigms":  ["OOP", "Clean Code"],
        }

        #My Projects 💻
        self.projects = {
            "NetStore":
                "Full‑featured e‑commerce web app built with Django.",
            "Future Project":
                "Always learning and building something new…",
        }

        #My Goals 🎯
        self.goals = {
        "Django": "Improve my expertise in Django and build more scalable web applications.",
        "Python": "Deepen my understanding of Python, including advanced concepts.",
        "Teaching": "Enhance my teaching skills to better support and inspire students."
        }

        #My Educational Wxperience 🎓
        self.education = {
            "MSc in Software Engineering": {
                "university": "Islamic Azad University, Tehran Shomal",
                "status": "Currently enrolled",
            },
            "BSc in Computer Engineering": {
                "university": "Islamic Azad University, Gorgan",
                "status": "Graduated 2024",
            },
        }

        #Let's Connect 🛜
        self.contacts = {
            "LinkedIn":  "https://www.linkedin.com/in/aryan-puransanaye/",
            "Instagram": "https://www.instagram.com/arypnsy",
            "Discord":   "https://discord.com/users/801045534483546133",
            "GitHub":  "https://github.com/aryanpuransanaye"
        }

    # ──────────────────────────────────────────────────────────────────────
    # PUBLIC METHODS
    # ──────────────────────────────────────────────────────────────────────

    def run(self) -> None:
        """Pretty‑prints profile info to the console."""

        print(">>> import profile from aryan_puran_sanaye")
        print(">>> profile.run()\n")

        # About
        print("--- About Me ---")
        print(self.__doc__.strip())

        # Skills
        print("\n--- Technical Skills ---")
        for cat, items in self.skills.items():
            print(f"{cat:<10}: {', '.join(items)}")

        # Education
        print("\n--- Education ---")
        for degree, info in self.education.items():
            uni = info["university"]
            stat = info["status"]
            print(f"- {degree}  —  {uni}  ({stat})")

        # Projects
        print("\n--- Projects ---")
        for name, desc in self.projects.items():
            print(f"- {name}: {desc}")

        # Contacts
        print("\n--- Connect With Me ---")
        for platform, url in self.contacts.items():
            print(f"- {platform}: {url}")

        print("\n# Process finished with exit code 0")
        print("# Thanks for visiting!\n")


# ──────────────────────────────────────────────────────────────────────
# SCRIPT ENTRY‑POINT
# ──────────────────────────────────────────────────────────────────────

if __name__ == "__main__":
    AryanPuranSanaye().run()
