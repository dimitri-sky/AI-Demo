<div align="center">
<h1>Aisha - AI Discord Companion<br>
(Limited Release Demo)</h1>

<h2>Talk with Aisha now: https://discord.gg/ekG5SbBCJS</h2>

  <img src="aisha.png" alt="Aisha Logo" width="300" height="300">
</div>

## 🌟 Features

- **Personalized AI Engagement**: Experience personalized interactions based on your unique personality model, created by Aisha.
- **User Profile Management**: Builds and maintains user profiles, including interests, goals, and relationships.
- **Google Search Integration**: Leverages Google Search and OpenAI to scrape and summarize information based on user interests, delivering concise summaries and relevant links.
- **Automated Engagement**: Sends personalized reminders (8h, 24h, 72h) to stimulate user engagement and maintain lively conversations.
- **Advanced Rate Control**: Utilizes custom rate limiting for smooth request handling and optimal user experience.
- **Server and DM Handling**: Enables seamless communication between servers and direct messages, with specific interaction patterns.
- **Robust Error Handling**: Employs sophisticated error handling and retry mechanisms to ensure uninterrupted user experiences.
- **Comprehensive Logging**: Provides detailed logging for seamless debugging and real-time monitoring.

## 💻 Technologies Used

- **OpenAI API**: Powers intelligent and dynamic AI responses.
- **Discord API**: Facilitates bot interactions within the Discord platform.
- **Firebase Firestore API**: Securely stores user profiles and conversations.
- **Google Seach API**: Google user's interests.
- **Asyncio**: Enables efficient asynchronous programming.
- **APScheduler**: Manages scheduling for timely task execution.
- **Python**: The backbone programming language that brings Aisha to life.
- **BeautifulSoup**: Scrape websites.

## 📁 Files
- **aisha.py**: Main file, monolithic approach due to the scope of the project.
- **google_interests.py**: Google search a user's interest, scrape 10 top results, pick the best one, and open a conversion with the user about it.
- **logger.py**: Colurful logger.
- **rate_limiter.py**: Rate limiter to stop spam.
- **keys.py**: Keys, provide your own.

## 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/dimitri-sky/Aisha-AI-Demo.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Replace API keys with your own.

Run the bot:

```bash
python aisha.py
```

## 🤝 Contributions

We welcome contributions! Feel free to open an issue or submit a pull request.

## 📜 License

MIT License - see the [LICENSE](LICENSE) file for details.

## 📧 Contact

Dimitar S - [dimitars.com](https://dimitars.com)

---

_:heart:_
