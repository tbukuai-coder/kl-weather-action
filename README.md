# 🌤️ KL Weather Action

A GitHub Action that fetches the current weather and forecast for Kuala Lumpur, Malaysia.

## How it works

- Runs daily at **8:00 AM Malaysia time** (UTC+8)
- Can also be triggered manually via `workflow_dispatch`
- Fetches data from [wttr.in](https://wttr.in)
- Outputs a JSON summary + one-liner to the Actions log
- Uploads full JSON as a workflow artifact (retained 7 days)

## Output includes

- Current temp, feels-like, humidity, wind, visibility, UV index
- 3-day forecast with hourly breakdown (temp, description, rain chance, humidity)

## Setup

1. Fork / clone this repo
2. Ensure GitHub Actions are enabled in your repo settings
3. The workflow runs automatically on schedule
4. Or go to **Actions → Fetch Kuala Lumpur Weather → Run workflow** to trigger manually
