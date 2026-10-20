<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=2F81F7&center=true&vCenter=true&width=520&height=60&lines=Hi%2C+I%27m+Egor;C%2B%2B+%2F+Qt+%2F+SFML;TypeScript+%2F+NestJS+%2F+MySQL;Python+%2F+PyTorch" alt="Hi, I'm Egor · C++ / Qt / SFML · TypeScript / NestJS / MySQL · Python / PyTorch" />

<em>Desktop, backend and machine-learning projects, built end-to-end — from a Russian language model written from scratch to a store API with payments.</em>

</div>

---

## 🛠 Tech Stack

**Languages**&nbsp;
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square)

**Backend**&nbsp;
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white)
![REST API](https://img.shields.io/badge/REST%20API-4A4A4A?style=flat-square)
![JWT / OAuth 2.0](https://img.shields.io/badge/JWT%20%2F%20OAuth%202.0-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

**Desktop & graphics**&nbsp;
![Qt 5.12](https://img.shields.io/badge/Qt%205.12-41CD52?style=flat-square&logo=qt&logoColor=white)
![SFML 2.5](https://img.shields.io/badge/SFML%202.5-8CC445?style=flat-square)
![Eigen](https://img.shields.io/badge/Eigen-5E4FA2?style=flat-square)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)

**Machine learning & data**&nbsp;
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Neural Networks](https://img.shields.io/badge/Neural%20Networks-4B0082?style=flat-square)

**Workflow**&nbsp;
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![ESLint](https://img.shields.io/badge/ESLint-4B3263?style=flat-square&logo=eslint&logoColor=white)
![Prettier](https://img.shields.io/badge/Prettier-F7B93E?style=flat-square&logo=prettier&logoColor=black)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-5C2D91?style=flat-square)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)

---

## 🚀 Projects

### [vinyl_store](https://github.com/lubenkov/vinyl_store) — REST API for an online vinyl store

`NestJS` · `TypeScript` · `MySQL` · `Sequelize` · `Stripe`

A catalog with search, sorting and pagination; sign-in with email or Google; `admin` and `user`
roles; reviews; payments through Stripe; Discogs import; Telegram notifications; an audit log of
everything admins do.

- 70 unit tests in 15 suites, all green; CI runs lint, format check, tests and build on every push
- Swagger documents all 17 endpoints at `/api`

### [jarvis](https://github.com/lubenkov/jarvis) — GPT-style language model

`Python` · `PyTorch` · `Hugging Face Datasets` · `Hugging Face Tokenizers`

A ~112M-parameter decoder-only Transformer for Russian, implemented from scratch. The project
includes a custom byte-level BPE tokenizer, corpus preparation, pretraining → SFT, resumable
AMP/DDP training, KV-cache inference, a console chat and an optional Telegram bot.

- [v1.0.0 release](https://github.com/lubenkov/jarvis/releases/tag/v1.0.0); trained checkpoint and tokenizer on [Hugging Face](https://huggingface.co/Eragon1/jarvis-112m)
  
### [MNIST_MLP](https://github.com/lubenkov/MNIST_MLP) — handwritten digit recogniser for Windows

`C++17` · `Qt 5.12` · `Eigen` · `Arduino`

You draw a digit on the canvas, a network trained from scratch classifies it, and the result is
mirrored onto an Arduino over a serial port.

- Training on the full 60 000-sample MNIST reaches **98.3%** on the 10 000-sample test set

### [CHESSonQT](https://github.com/lubenkov/CHESSonQT) — chess for two players on one computer

`C++` · `Qt 5.12`

Two players share a keyboard and mouse: five-minute clock for each side, castling, en-passant
capture, promotion, sound effects and looping background music.

### [graphical_snake_sfml](https://github.com/lubenkov/graphical_snake_sfml) — Snake with SFML

`C++14` · `SFML 2.5.1`

Menu, five colour themes, score tracking and an optional self-collision rule; the field wraps at
the edges.

- Fully playable: eating an apple grows the snake and bumps the score; the best result is persisted
  in `Score.txt`

### [console_snake](https://github.com/lubenkov/console_snake) — classic Snake in the console

`C++14`

My first step from a single long file to proper classes: `Snake` handles movement, growth and
collisions, `Map` draws the field, `Point` is a coordinate pair.

---

## 🧩 LeetCode

<div align="center">

<a href="https://leetcode.com/u/eragon369/">
  <img src="https://leetcard.jacoblin.cool/eragon369?theme=light,dark&font=Karma&hide=ranking&border=1&radius=8&cache=300" alt="Live LeetCode statistics for eragon369" />
</a>

</div>

<details>
<summary>🇷🇺 По-русски</summary>

<br>

**Стек**

- **Языки:** C, C++, TypeScript, JavaScript, Python, SQL
- **Backend:** NestJS, Node.js, MySQL, Sequelize, REST API, JWT / OAuth 2.0, Stripe, Swagger, Jest
- **Desktop и графика:** Qt 5.12, SFML 2.5, Eigen, Arduino
- **Машинное обучение и данные:** PyTorch, Hugging Face, NumPy, pandas, SciPy, Matplotlib, Jupyter
- **Инструменты:** Git, GitHub Actions, ESLint, Prettier, Visual Studio, Linux

**Проекты**

- **[vinyl_store](https://github.com/lubenkov/vinyl_store)** — REST API магазина винила на NestJS:
  каталог с поиском, сортировкой и пагинацией, вход по email или через Google, роли `admin`/`user`,
  отзывы, оплата через Stripe, импорт из Discogs, уведомления в Telegram, аудит-лог действий
  администраторов. 70 тестов в 15 сьютах, CI на каждый push; не-админ получает `403`,
  некорректный ввод — `400`, whitelist колонок блокирует SQL-инъекцию в сортировке. Swagger
  описывает все 17 эндпоинтов на `/api`.
- **[jarvis](https://github.com/lubenkov/jarvis)** — GPT-подобная авторегрессионная модель для
  русского языка примерно на 112 млн параметров, написанная с нуля на PyTorch. Собственный
  byte-level BPE-токенизатор, подготовка корпусов, pretrain → SFT, AMP/DDP, KV-cache, консольный
  чат и Telegram-бот. Релиз **[v1.0.0](https://github.com/lubenkov/jarvis/releases/tag/v1.0.0)**;
  веса и токенизатор — на [Hugging Face](https://huggingface.co/Eragon1/jarvis-112m).
- **[MNIST_MLP](https://github.com/lubenkov/MNIST_MLP)** — распознавание рукописных цифр на C++17 и
  Qt: сеть обучается с нуля на полном MNIST (60 000 примеров) и даёт **98.3 %** на тесте из 10 000;
  веса сохраняются в `weights.bin`, обучение идёт в отдельном потоке, результат уходит на Arduino.
- **[CHESSonQT](https://github.com/lubenkov/CHESSonQT)** — шахматы для двух игроков за одним
  компьютером: таймер на пять минут каждой стороне, рокировка, взятие на проходе, превращение
  пешки, звук и фоновая музыка. 
- **[graphical_snake_sfml](https://github.com/lubenkov/graphical_snake_sfml)** — «Змейка» на SFML:
  меню, пять цветовых тем, счёт, рекорд в `Score.txt`; поле замкнуто по краям.
- **[console_snake](https://github.com/lubenkov/console_snake)** — консольная «Змейка» как учебный
  проект: классы `Snake`, `Map`, `Point`. 

**LeetCode** — 100+ решённых задач; карточка выше обновляется автоматически, [профиль](https://leetcode.com/u/eragon369/).

</details>
