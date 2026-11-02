<p align="center">{{panel:city}}</p>

{{lights}}

{{flights}}

<details>
<summary>How Commit City works</summary>
<br>
<p>Everything in this city comes from my GitHub activity, and it grows as I commit. The first building cost {{cityFirst}} contributions and each one after costs {{cityStep}} more, so it filled in quickly at first and grows slower now. It never shrinks.</p>
<p>Each building is one of my public repos. Repos I pushed to in the last four months are glass towers, the ones from the last two years are apartment blocks, and older ones are tile-roof houses. The more I committed to a repo this year, the taller it is.</p>
<p>The metro is my contribution graph: one coach per week and one window per day, lit on days I committed. The street under each coach is as busy as that week was. BMTC buses are pull requests merged this year, with the repo and PR number on the side, and the planes carry my DEV posts.</p>
<p>Commit Soudha, the town hall, starts going up at {{soudhaStart}} contributions and opens at {{soudhaDone}}. There's a new tree for every {{treeEvery}}.</p>
<p>The sky follows the time in Bengaluru. A GitHub Action redraws the city a few times a day, so there's no server and nothing to update by hand.</p>
</details>

<p align="center"><sub>City generator: <a href="https://github.com/vineetjk/vineetjk">Commit City</a>.</sub></p>

<p align="center">{{panel:sign}}</p>

<p align="center">{{panel:ticker}}</p>

<p align="center">{{panel:quote}}</p>

<p align="center">{{panel:chart}}</p>

<p align="center">{{buttons}}</p>

<p align="center"><sub>Buttons open a pre-filled issue. Hit <b>Create</b> to place your order.</sub></p>

<p align="center">{{panel:book}}</p>

<p align="center">{{panel:fundamentals}}</p>

<details>
<summary>How does this work?</summary>
<br>
<p>The price follows my GitHub activity. A normal month for me is around {{baseline}} contributions, and that's worth {{listing}} a share. If I stop coding for a month, that drops to half. When the market closes each day, the price moves {{pull}}% of the way toward whatever my last 30 days say it's worth.</p>
<p>During the day you move it. Every share bought pushes it up {{impact}}%, every share sold pushes it down, and you pay the price after your own push. So buying and selling straight away loses you a little.</p>
<p>It can't go more than {{circuit}}% above or below the previous close. Once it hits that limit, buying (or selling, if it's falling) stops until the next day.</p>
<p>The market is open {{open}} to {{close}} IST, Monday to Friday. Orders placed outside those hours wait for the next morning. Close your issue if you change your mind.</p>
<p>You start with {{startingCash}} of play money. Up to {{maxQty}} shares per order.{{cooldown}} Whenever one of my pull requests gets merged, everyone holding shares gets {{dividend}} per share. I can't buy my own stock.</p>
<p>There's no server behind this. A GitHub Action runs at the open, at the close and whenever someone places an order, then redraws these images. Every trade is in <a href="data/market.json">data/market.json</a>.</p>
</details>

<p align="center">{{panel:footer}}</p>

{{coffee}}

{{views}}

<div align="center">

<img src="assets/pond.svg" alt="vyankatesh's pond" width="100%" />

<img src="koi/koi.gif" width="256" alt="My koi" />

<sub>my GitHub profile is a pond now. the koi grows with my commits.</sub>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vyankateshpotdar)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vyankateshpotdar411@gmail.com)
![Pune](https://img.shields.io/badge/Pune,_India-FF6B35?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

<details>
<summary><b>How the koi works</b></summary>

<br>

Everything about the koi comes from my public GitHub activity. The languages I write color it, my contributions grow it, my streaks mark it, and the day that just ended decides how it swims.

A GitHub Action redraws it every night just after midnight UTC and commits a new `koi/koi.gif`. There's no server and nothing to update by hand.

Made with [git-koi](https://github.com/yalongwastaken/git-koi).

</details>

<br>

## 🌊 about me

```python
class Vyankatesh:
    def __init__(self):
        self.role = "CS undergrad, professional task-automator"
        self.grad_year = 2029
        self.location = "Pune, India"
        self.stack = ["Python", "TypeScript", "FastAPI", "PostgreSQL"]
        self.red_flags = ["forgets to check Amazon manually", "lets bots do it"]
        self.actually_doing = "building a bot army so boring tasks fear me"

    def manual_labor(self, task):
        if task.is_repetitive or task.is_boring:
            return "nah, writing a script for that 🤖"
        return "fine i'll do it myself this once"

me = Vyankatesh()
print(me.manual_labor(task="checking 5 sites for a price drop"))
# >>> nah, writing a script for that 🤖
```

## 🪷 what's in the pond

<table>
<tr>
<td width="50%" valign="top">

**📉 Price Tracker & Alert Bot**
<br><sub>May 2026 – now</sub>

Watches Amazon, Flipkart, Ajio, Myntra and Meesho so I don't have to, and pings me when a price drop is actually worth it.

`TypeScript` `Node.js` `Prisma` `PostgreSQL` `node-cron`

</td>
<td width="50%" valign="top">

**🔔 Discord Bump Reminder Bot**
<br><sub>Aug 2025 – now</sub>

Remembers the 2-hour server bump so humans don't have to. `!nextbump` shows how long you've got.

`Python` `discord.py` `AsyncIO`

</td>
</tr>
<tr>
<td width="50%" valign="top">

**₿ Real-time BTC Price Alert Bot**
<br><sub>Aug 2025 – Dec 2025</sub>

Pings Telegram the moment BTC moves ±$500, so I can stop refreshing my crypto app. Anxiety, automated.

`Python` `FastAPI` `Uvicorn` `Binance API`

</td>
<td width="50%" valign="top">

**♟️ Square Focus Chess Club**
<br><sub>Founder & Community Manager · 2020 – now</sub>

Not a bot, an actual community: chess people across Discord, Instagram and YouTube.

`Community Building` `Discord Mgmt` `Social Strategy`

</td>
</tr>
</table>

## 🛠️ tools i swim with

<div align="center">

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Telegram](https://img.shields.io/badge/Telegram_Bot_API-26A5E4?style=flat-square&logo=telegram&logoColor=white)
![Discord](https://img.shields.io/badge/Discord_API-5865F2?style=flat-square&logo=discord&logoColor=white)
![Binance](https://img.shields.io/badge/Binance_API-F0B90B?style=flat-square&logo=binance&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=flat-square&logo=microsoftexcel&logoColor=white)
![Data Viz](https://img.shields.io/badge/Data_Visualization-6F42C1?style=flat-square&logo=tableau&logoColor=white)

</div>

## 🎓 education & certifications

**B.Tech, Computer Science & Engineering**: MIT-ADT University, Pune · 2025 – 2029 *(first year)*

<details>
<summary><b>Certifications (5)</b></summary>

<br>

- 🏆 Advanced C++ Training: Spoken Tutorial, IIT Bombay *(Apr 2026)*
- 🐍 CS50P, Introduction to Programming with Python: Harvard University *(Aug 2025)*
- 💻 C Training: IIT Bombay *(Nov 2025)*
- 📊 Deloitte Australia, Data Analytics Job Simulation: Forage *(Dec 2025)*
- 🤖 AI Aware Badge: Digital India Corporation *(Jul 2025)*

</details>

## 🎯 right now

```
┌──────────────────────────────────────────────────┐
│  🔭  building bots so future-me does less work    │
│  🌱  leveling up on scraping & API witchcraft     │
│  ♟️  running a chess club, unofficial hobby: chaos │
│  📣  social media for ACM-W (yes i make memes)    │
│  ⚡  dms open for internships & cool collabs       │
└──────────────────────────────────────────────────┘
```

<div align="center">

**"life's too short to do boring tasks twice. write the script."** 💀🤖

![Profile Views](https://komarev.com/ghpvc/?username=vyankateshpotdar&color=FF6B35&style=flat-square&label=Profile+Views)

<img src="assets/footer.svg" alt="Just a pond. The koi is redrawn every night." width="100%" />

</div>
