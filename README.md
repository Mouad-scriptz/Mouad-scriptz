```py
class Me:
    def __init__(self):
        self.name = "Mouad"
        self.discord = "mouad.0"
        self.telegram = "@mouadscriptz"
        self.projects_in_bound = ["HCaptcha Solver (UD)"]

    def present(self):
        print("🌟🚀 Welcome to my Profile! 🚀🌟")
        print("\n - Information - ")
        print(f"Name: {self.name}")
        print(f"Discord: {self.discord}")
        print(f"Telegram: {self.telegram}")
        print("Projects:")
        for idx, project in enumerate(self.projects_in_bound, start=1):
            print(f"  {idx}. {project}")

me = Me()
me.present()
```
