# Auriva Finance

#### 📹 Video Demo: [Watch on YouTube](https://youtu.be/faonqrRJrXsA)

> ⚠️ **Warning:** As of now, the implementation may not work correctly due to recent changes in the Yahoo Finance API. Quoting and graph features that rely on live data may fail or return incomplete information. A future fix or API replacement is needed.

#### 📄 Description:
**Auriva Finance** is a paper trading platform built as the final project for Harvard's [CS50](https://cs50.harvard.edu/) course. This repository is a **copy of the original submission**, with no prior commits, and serves as a personal archive and showcase.

Auriva Finance marked a milestone in my development journey — it was the second website I ever created, born from a growing interest in both finance and programming.

Auriva Finance features comprehensive functionalities, enabling users to seamlessly buy and sell stocks, and inquire about current interest rates, including futures and forex trading. The quoting feature utilizes real-time data from the Yahoo finance API to gather valuable information which is then transformed into graphs and percentages spanning from the past year's financial development. The index page presents a daily development of your portfolio, a fully dynamic experience presenting an overview of your gains and losses.

In addition to other features, Auriva Finance also features a leaderboard to fit the paper trading's competitive nature. This leaderboard ranks users based on their overall net worth on the website and illustrates their dominance by indicating the percentage of total capital under their control.

However, the project is not without its aspirations. One feature I am missing is an addition to my database which would track each user's current net worth daily and then the website would be able to calculate the development of each account over time. Thus, I would be able to show a graph or show progress over time as a useful statistic for the user but also a fun way to see which person has found the most profitable trades in a period.

The project has not only enhanced my understanding of website development but also created a deeper interest in cybersecurity. Managing the database and user actions necessitated a comprehensive approach to control input on both the back-end and front-end. Stringent measures were implemented for input validation and authentication, fortifying the project against potential security threats while maintaining a stylistic website.

Embarking on this endeavor proved both challenging and intriguing. Unlike my previous localized projects such as games or computer functionalities, Auriva Finance required a deeper understanding of building a website from scratch. In turn, I developed my programming skill set even further. To summarise, this project has been a pivotal experience in my journey to become a fully fletched programmer teaching me new programming languages and modules required for back-end and front-end development, expanding my capabilities for future projects.



---

## 💼 Features

- **Buy & Sell Stocks** — Simulated paper trading with full portfolio management.
- **Real-time Quotes** — Pulls data from the Yahoo Finance API and visualizes 1-year performance with graphs and percentage change.
- **Index Page** — A dynamic daily snapshot of your portfolio’s value, gains, and losses.
- **Futures & Forex Info** — Query additional market data.
- **Leaderboard** — Ranks users based on net worth, showing each player's share of total capital.

---

## 🌱 Future Enhancements

A key future feature would involve storing each user’s daily net worth in the database. This would allow:

- Graphs showing portfolio growth over time.
- Historical comparisons for personal performance and leaderboard progression.
- A more engaging and insightful trading experience.

---

## 🔐 Security Focus

This project deepened my interest in **cybersecurity**. From validating user input to authenticating transactions, I implemented strict back-end and front-end protections to reduce vulnerabilities — all while maintaining a clean and responsive user interface.

---

##

## 🛠️ Project Setup

To run the project locally:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/auriva-finance.git
   cd auriva-finance
   ```

2. **Create a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   python3 -m pip install -r requirements.txt
   ```

4. **Run the application:**
   ```bash
   flask run
   ```

   The app should now be accessible at [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧠 Final Thoughts

Auriva Finance was a turning point in my programming education — pushing me beyond local scripts and games into full-stack web development. It taught me new programming languages, modules, and design thinking, and laid a strong foundation for more advanced projects in the future.

