<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&duration=2500&pause=1000&color=39FF14&center=true&vCenter=true&width=435&lines=Hi+there!+I%27m+Aryan;Love+to+Code+and+Teach" alt="Typing SVG" />
</p>


#!/usr/bin/env python3
# -*- coding: utf-8 -*-

class AryanPuranSanaye:
    """
    Hello! I'm Aryan, a passionate software developer from Iran.

    This entire profile is written in Python to showcase my love for clean,
    structured code. I'm a Master's student in Software Engineering with a 
    strong focus on Python development. I thrive on learning new technologies,
    collaborating on exciting projects, and sharing my knowledge.
    """

    def __init__(self):
        """Initializes the profile data."""
        self.name = "Aryan Puran Sanaye"
        self.title = "Junior Python Developer | MSc Software Engineering Student"
        
        self.skills = {
            "Languages": ["Python"],
            "Frameworks": ["Django", "Django REST Framework"],
            "Libraries": ["Telegram Bot", "Tkinter"],
            "Paradigms": ["Object-Oriented Programming (OOP)", "Clean Code"]
        }

        self.current_projects = {
            "NetStore": "A full-featured e-commerce web application built with Django.",
            # "Future Project": "Always learning and building something new..."
        }

        self.education_history = {
            "MSc in Software Engineering": {
                "university": "Islamic Azad University, Tehran Shomal",
                "status": "Currently enrolled",
            },
            "BSc in Computer Engineering": {
                "university": "Islamic Azad University, Gorgan",
                "status": "Graduated 2024",
            },
        }

        self.contact_info = {
            "LinkedIn": "https://www.linkedin.com/in/aryan-puransanaye/",
            "Instagram": "https://www.instagram.com/arypnsy",
            "Discord": "https://discord.com/users/801045534483546133",
            # "GitHub": "Your GitHub Profile URL here"  # <-- Don't forget to add this!
        }

    def run(self):
        """Executes the profile display."""
        
        print(">>> import profile from aryan_puran_sanaye")
        print(">>> profile.run()\n")
        
        # --- Bio ---
        print(f"--- About Me ---\n{self.__doc__}")
        
        # --- Skills ---
        print("\n--- Technical Skills ---")
        for category, skills_list in self.skills.items():
            print(f"{category}: {', '.join(skills_list)}")
            
        # --- Education ---
        print("\n--- Education ---")
        for degree, details in self.education_history.items():
            print(f"- {degree} at {details['university']} ({details['status']})")

        # --- Projects ---
        print("\n--- Projects ---")
        for name, desc in self.current_projects.items():
            print(f"- {name}: {desc}")

        # --- Contacts ---
        print("\n--- Connect With Me ---")
        for platform, url in self.contact_info.items():
            print(f"- {platform}: {url}")
            
        print("\n# --- Process finished with exit code 0 ---")
        print("# Thanks for visiting!")


# To see the profile, instantiate the class and run it.
if __name__ == "__main__":
    my_profile = AryanPuranSanaye()
    my_profile.run()
