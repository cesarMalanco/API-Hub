<div align="center">

# 🌐 API Hub
**A multi-API desktop application integrating NASA, Pokémon, X (Twitter), and Chuck Norris APIs**

</div>

---

## >_ About The Project

**API Hub** is a desktop application that demonstrates the integration of multiple public APIs in a single, user-friendly interface. Built with Python and Tkinter, it showcases both GET and POST HTTP request methods.

---

## >_ Features
<div align="center">
<table>
<tr>
<td width="50%">

### 🔭 NASA APOD

- Browse Astronomy Picture of the Day
- Search by specific date
- View high-quality space images
- Read detailed explanations

</td>
<td width="50%">

### 🐦‍🔥 Pokédex

- Search any Pokémon by name
- View official artwork
- Display stats (height, weight, ID)
- Clean, intuitive interface

</td>
</tr>
<tr>
<td width="50%">

### 🐦 X (Twitter) Bot

- Post tweets directly from the app
- Character limit validation (280 chars)
- Quick profile access
- Real-time posting

</td>
<td width="50%">

### 🤠 Chuck Norris Jokes

- Random joke generator
- Instant joke display
- Family-friendly content
- One-click generation

</td>
</tr>
</table>
</div>

---

## 📸 Demo

<div align="center">

### Main Menu

|                Main Hub                 |
| :-------------------------------------: |
| ![Main Menu](screenshots/main_menu.png) |

### API Endpoints

|               NASA APOD                |               Pokédex               |
| :------------------------------------: | :---------------------------------: |
| ![NASA](screenshots/nasa_apod.png?v=2) | ![Pokemon](screenshots/pokedex.png) |

|             X (Twitter) Bot             |           Chuck Norris Jokes           |
| :-------------------------------------: | :------------------------------------: |
| ![Twitter](screenshots/twitter_bot.png) | ![Chuck](screenshots/chuck_norris.png) |

</div>

---

## >_ Installation

### Prerequisites

| Requirement | Version | Download                                      |
| ----------- | ------- | --------------------------------------------- |
| Python      | 3.8+    | [Download](https://www.python.org/downloads/) |
| pip         | Latest  | Included with Python                          |

### Quick Start

```bash
# Clone the repository
git clone https://github.com/cesarMalanco/API-Hub.git

# Navigate to project directory
cd api-hub

# Install dependencies
pip install -r requirements.txt

# Configure environment variables
# Copy .env.example to .env and add your API keys

# Run the application
python API_Hub.py
```

### Dependencies

```bash
pip install requests pillow tweepy python-dotenv
```

---

## >_ Environment Setup

Create a `.env` file in the root directory:

```env
# NASA API
NASA_API_KEY=your_nasa_api_key

# X (Twitter) API
X_CONSUMER_KEY=your_consumer_key
X_CONSUMER_SECRET=your_consumer_secret
X_BEARER_TOKEN=your_bearer_token
X_ACCESS_TOKEN=your_access_token
X_ACCESS_TOKEN_SECRET=your_access_token_secret
```

### Getting API Keys

| API          | Get Key                                                 |
| ------------ | ------------------------------------------------------- |
| NASA         | [api.nasa.gov](https://api.nasa.gov/) (Free)            |
| X (Twitter)  | [developer.twitter.com](https://developer.twitter.com/) |
| Pokémon      | No key required                                         |
| Chuck Norris | No key required                                         |

---

## >_ APIs Used

<div align="center">

|                                                  API                                                   | Type | Endpoint                      | Auth Required |
| :----------------------------------------------------------------------------------------------------: | :--: | :---------------------------- | :-----------: |
|     ![NASA](https://img.shields.io/badge/NASA-E03C31?style=flat-square&logo=nasa&logoColor=white)      | GET  | `api.nasa.gov/planetary/apod` |  ✅ API Key   |
| ![Pokemon](https://img.shields.io/badge/PokéAPI-FFCB05?style=flat-square&logo=pokemon&logoColor=black) | GET  | `pokeapi.co/api/v2`           |      ❌       |
|        ![X](https://img.shields.io/badge/X_API-000000?style=flat-square&logo=x&logoColor=white)        | POST | `api.twitter.com/2/tweets`    |   ✅ OAuth    |
|              ![Chuck](https://img.shields.io/badge/Chuck_Norris-orange?style=flat-square)              | GET  | `api.chucknorris.io/jokes`    |      ❌       |

</div>

---

## >_ Usage

### Running the Application

```bash
python API_Hub.py
```

### Navigation

1. **Main Menu** - Select an API endpoint
2. **NASA APOD** - Enter date (YYYY-MM-DD format) and search
3. **Pokédex** - Enter Pokémon name and search
4. **X Bot** - Write your tweet and submit
5. **Chuck Norris** - Click generate for a random joke

---

## >_ Project Structure

```
api-hub/
│
├── 📄 API_Hub.py          # Main application
├── 📄 .env                # Environment variables (git ignored)
├── 📄 .env.example        # Environment template
├── 📄 .gitignore          # Git ignore rules
├── 📄 requirements.txt    # Python dependencies
├── 📄 README.md           # Documentation
├── 📄 LICENSE             # MIT License
│
└── 📂 screenshots/        # Demo screenshots
    ├── main_menu.png
    ├── nasa_apod.png
    ├── pokedex.png
    ├── twitter_bot.png
    └── chuck_norris.png
```

---

## >_ Requirements

```txt
requests>=2.28.0
Pillow>=9.0.0
tweepy>=4.14.0
python-dotenv>=1.0.0
```

---

## >_ License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## >_ Author

<div align="center">

**César Malanco**

[![GitHub](https://img.shields.io/badge/GitHub-cesarMalanco-181717?style=for-the-badge&logo=github)](https://github.com/cesarMalanco)

---

<sub>Built with ❤️ using Python and Tkinter</sub>

</div>
