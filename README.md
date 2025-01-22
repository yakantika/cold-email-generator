# Cold Email Generator for Services Company

## Overview
This application is designed to streamline the outreach process for service based software development company. By inputting the URL of a company's careers page, our tool automatically extracts job listings and crafts personalized cold emails. These emails integrate relevant portfolio links from a vector database, matching the specific job requirements.

## Features
- **URL Input**: Users can enter the URL of a company’s career page to extract job listings.
- **Email Generation**: Generates personalized cold emails aimed at potential clients.
- **Portfolio Integration**: Includes relevant project links from the Vector data base portfolio that align with the job description.

## Getting Started

### Prerequisites
Ensure you have an API key from Groq:
1. Obtain an API_KEY from [Groq API Console](https://console.groq.com/keys).
2. Store your API_KEY in the `app/.env` file under `GROQ_API_KEY`.

### Installation
Install the required dependencies:
```bash
pip install -r requirements.txt
