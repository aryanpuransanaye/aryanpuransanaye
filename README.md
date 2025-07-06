```python
# 👋 Hi there! I'm Aryan

# Master's Student in Software Engineering
# Junior Python Developer
# Passionate about teaching, clean coding, and learning
# Always open to collaboration and sharing knowledge


skills = [
    "Python",
    "Django",
    "Django REST Framework",
    "Telegram Bot",
    "Tkinter",
]

projects = {
    "NetStore": "A full-featured e-commerce web app with Django, "
                "including user authentication, product management, "
                "shopping cart, and order system."
}

education = {
    "BSc": {
        "field": "Computer Engineering",
        "university": "Islamic Azad University, Gorgan",
        "year": 2024,
    },
    "MSc": {
        "field": "Software Engineering",
        "university": "Islamic Azad University, Tehran Shomal",
        "status": "Currently enrolled",
    }
}

contacts = {
    "Instagram": "https://www.instagram.com/arypnsy",
    "LinkedIn": "https://www.linkedin.com/in/aryan-puransanaye/",
    "Discord": "https://discord.com/users/801045534483546133",
}

def main():
    print("Skills:")
    for skill in skills:
        print(f" - {skill}")

    print("\nProjects:")
    for name, desc in projects.items():
        print(f" - {name}: {desc}")

    print("\nEducation:")
    for degree, info in education.items():
        print(f" - {degree} in {info['field']} from {info['university']} ({info.get('year', info.get('status'))})")

    print("\nContact me:")
    for platform, url in contacts.items():
        print(f" - {platform}: {url}")

    print("\nThanks for visiting my profile!")

if __name__ == "__main__":
    main()
