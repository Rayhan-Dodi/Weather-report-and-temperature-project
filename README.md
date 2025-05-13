# Weather Report Script (`rx_poc.sh`)

This project contains a Bash script that fetches and logs the weather data for **Casablanca**, Morocco. It was created as part of a **Coursera course practice**.

## 📌 Script Overview

The script performs the following:

- Fetches the current temperature in Casablanca using `curl` from [wttr.in](https://wttr.in).
- Extracts the forecasted temperature for **noon tomorrow**.
- Logs the date (day, month, year), current temperature, and forecasted temperature to a file named `rx_poc.log`.

## 📄 File Description

| File Name    | Description                                |
|--------------|--------------------------------------------|
| `rx_poc.sh`  | Main Bash script to fetch and log weather. |
| `rx_poc.log` | Log file auto-generated with results.      |

## 📦 Requirements

- `curl`
- Internet connection

## 🚀 Usage

```bash
chmod +x rx_poc.sh
./rx_poc.sh
