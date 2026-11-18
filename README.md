# Memriser
![GitHub License](https://img.shields.io/github/license/ellisf09/memriser)
An intelligent browser automation tool built in Python and Selenium that automatically completes Memrise speed reviews and learning tasks using translation APIs, DOM analysis, and local answer caching.

## ✨ Features
- **Automated Browser Interaction:** Uses Selenium and JavaScript injection to read prompts and submit answers seamlessly.
- **Self-Learning Knowledgebase:** Caches verified translations locally to speed up future reviews without redundant API calls.
- **Translation & Override Support:** Integrates with Google Translate and supports custom synonym mappings via `syn_overrides.json`.
- **Configurable Behaviour:** Easily tweak automation delays and bot settings in `bot_config.json`.

## 🛠️ Prerequisites
- Python 3.8+
- Google Chrome installed
- Matching [ChromeDriver](https://chrome.com) added to your system `PATH`

## 🚀 Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd Memriser
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Configure credentials:**
   Create a `.env` file in the root directory and add your Memrise login details:
   ```env
   MEMRISE_EMAIL=your_email@example.com
   MEMRISE_PASSWORD=your_password
   ```

4. **Run the bot:**
   ```bash
   python Memriser.py
   ```

## 🤝 Contributing
Contributions, bug reports, and feature requests are welcome! Feel free to fork the repository and submit a pull request.
