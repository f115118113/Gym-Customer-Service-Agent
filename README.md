# Gym Customer Service Agent

A gym customer service AI Agent built with an OpenAI-compatible LLM API, SQLite, and Gradio.

## Features

- Answer gym information questions
- Search membership plans and prices
- Calculate total membership or training fees
- Transfer special cases or complaints to staff
- Display tool calls and results in the Gradio interface

## Tools

The Agent uses four tools:

1. `get_gym_info`
2. `get_membership_plan`
3. `calculate_membership_fee`
4. `transfer_to_staff`

## Database

The project uses two CSV files:

- `gym_info.csv` — gym information
- `membership_plans.csv` — membership plans and prices

The SQLite database is generated locally and is not included in this repository.

## Setup

Create a `.env` file based on `.env.example` and add your own API key.

```env
LLM_API_URL=YOUR_API_URL
MODEL_NAME=YOUR_MODEL_NAME
API_KEY=YOUR_API_KEY
