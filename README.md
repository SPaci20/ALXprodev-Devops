# Pokémon API Automation Script

## 📌 Overview
This project provides a simple **shell script** to automatically fetch data for the Pokémon **Pikachu** from the [PokéAPI](https://pokeapi.co/) and save it locally.  
If the request fails, the error will be logged for troubleshooting.

---

## 🛠 Features
- Fetches Pikachu's complete data from the PokéAPI.
- Saves the JSON response to `data.json`.
- Logs any errors to `errors.txt` with a timestamp.
- Removes incomplete JSON files on failed requests.

---

## 📂 Files
- **`fetch_pikachu.sh`** – Main script to fetch and save data.
- **`data.json`** – JSON output file containing Pikachu's details.
- **`errors.txt`** – Error log file with timestamps.

---

## 🚀 Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/pokemon-api-automation.git
cd pokemon-api-automation
