# ⚔️ Deutsch Ritter Quest  
**A gamified RPG adventure for mastering the German language.**  

Deutsch Ritter Quest isn't just another vocabulary tool—it's your companion on a journey from a German novice to a linguistic knight. Built with **Flask** and **SQLAlchemy**, this web app transforms the challenge of learning into an engaging quest where every word learned boosts your status and every challenge keeps you on your toes.

### ✨ What’s Inside
- **The Quest Log**: A dynamic vocabulary system powered by a custom scraper that pulls real-world data directly from GermanPod101.
- **Hero Stats**: Track your progress with a personalized health and score system—celebrate your wins and learn from your mistakes.
- **Safe Passage**: Secure user authentication so your learning stats and "hero" progress are always saved.
- **Simple & Swift**: A clean, Bootstrap-powered interface designed to keep you focused on the adventure ahead.

### 🛠️ The Gear Under the Hood
- **Back-end**: Python / Flask
- **Data Mastery**: SQLAlchemy (SQLite)
- **Quest Provisioner**: BeautifulSoup (for automated vocabulary scraping)
- **Front-end UI**: Bootstrap 5

### 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/AnishWerkstatt/Learn-German.git
   cd Learn-German
   ```

2. **Set up a virtual environment**:
   ```bash
   # Windows (PowerShell)
   python -m venv venv
   .\venv\Scripts\Activate.ps1
   
   # Linux/macOS
   python -m venv venv
   source venv/bin/activate
   ```

3. **Install dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Initialize the data (Scrape words)**:
   ```bash
   python main.py -s
   ```

5. **Run the adventure**:
   ```bash
   python main.py
   ```

**Ready to start your journey? Strap on your armor and start your quest!** 🏰✨
