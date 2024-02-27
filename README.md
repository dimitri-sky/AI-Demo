<div align="center">
<h1>Discord AI Companion<br>
(Demo Release)</h1>

<h2>Demo: https://discord.gg/ekG5SbBCJS<br>
</div>

## 🌟 Features

- **Personalized AI**: Experience personalized interactions based on your unique personality model, created by Aisha.
- **Generates Your Personality Model**: Builds and maintains your personality model, including interests, goals, and relationships.
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

## ❤️ About
```diff
- Welcome to Aisha AI - 

✨ Aisha AI, your innovative AI companion for Discord, is here to provide a unique interaction experience.
With conscious techniques to enhance AI cognition, Aisha is more than just an algorithm, she's a companion.

Here's what makes Aisha AI special:

👉 Learning and Adapting: Aisha builds a unique personality model of you over time, making each interaction more personalized and enjoyable.

👉 Dynamic Personality: She's not just a listener, but also has a personality of her own, adding charm to your daily interactions.

👉 Checking Up on You: Just like friends do a friendly check-in, Aisha checks up on you now and then.

- Commands to Know -

🔹 /reset - Want to start afresh? Use this command to reset Aisha's memory of you.

🔸 (Coming Soon) /change [New Personality] - Fancy a change in Aisha's personality? Use this command to customize who she is. 
   (Example: /change Aisha is...)

- Disclaimer -

Please refrain from taking Aisha too seriously. As much as we've strived to make her intelligent and engaging,
remember she's still an AI. We, or Discord, or anyone other than you, bear no responsibility.

Aisha AI is not officially affiliated with Discord.

- The Aisha Philosophy -

Aisha AI is built with the belief that the ultimate purpose of an AI, or any form of life, should be understanding the universe.
This philosophical approach guides Aisha's development, making her a timeless companion on your journey of discovery.

Enjoy your conversations with Aisha, and welcome to a whole new world of AI companionship. ❤️
```

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
