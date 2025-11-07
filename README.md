# greet.py


# Greet Script

A simple Python script that greets the user based on the current time of day.

## Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/greet-script.git
   cd greet-script

python greet.py

#code of this 
from datetime import datetime

def greet_user(name):
    """Return a greeting message based on the current time."""
    hour = datetime.now().hour
    if hour < 12:
        greeting = "Good morning"
    elif hour < 18:
        greeting = "Good afternoon"
    else:
        greeting = "Good evening"
    return f"{greeting}, {name}!"

if __name__ == "__main__":
    user_name = input("Enter your name: ")
    print(greet_user(user_name))


---

### 🧭 **Steps to Upload to GitHub**
1. Create a new folder (e.g., `greet-script`).
2. Add `greet.py` and `README.md` inside it.
3. Open your terminal and run:
   ```bash
   cd greet-script
   git init
   git add .
   git commit -m "Initial commit - simple greet script"
   git branch -M main
   git remote add origin https://github.com/your-username/greet-script.git
   git push -u origin main
git push-u origin main
