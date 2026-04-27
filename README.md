def generate_readme():
    content = f"""
# 🧠 About Me

**Name:** Thato M  
**Role:** Software Engineer 💻  

**Background:**  
👨‍⚕️ Healthcare Professional (Dietitian 🍏)  
♟️ Chess | 📷 Photographer  

📚 **Status:** Building skills every day  
🐍 **Primary Languages:** HTML, Python, Java  

🌱 Once focused on healing patients through nutrition,  
now building systems and solving problems through code 💻  

---

## ⚡ Current Focus
- 🌱 Improving programming skills
- 🧠 Strengthening problem solving

---

## 🧬 Health Tech Interests
- 📂 Nutrition tracking systems
- 📊 Health data analysis
- 📝 Diet planning applications
- 💡 Digital healthcare solutions

---

## 📋 Connect & Collaborate
- Email: your@email.com
- LinkedIn: your-linkedin
- GitHub: your-github
- X: your-twitter

---

## 📈 Profile Views
(You can add a badge here later)

---

## 🔳 QR Code
(Add QR code image here)
"""

    with open("README.md", "w", encoding="utf-8") as file:
        file.write(content.strip())

    print("README.md generated successfully!")


generate_readme()
