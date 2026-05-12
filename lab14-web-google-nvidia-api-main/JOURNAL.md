# This Journal gets updated automatically by the Journal Logger Agent

# Lab 14 Journal

## Workspace Snapshot

This folder contains a small Python lab focused on calling external APIs and GenAI services from standalone scripts.

## Files Present

- `country-webapi.py` - interactive REST Countries API lookup by country name.
- `google-genai.py` - basic Google Gemini generation example using `GOOGLE_API_KEY`.
- `google-genai-websearch.py` - Gemini example with Google Search grounding and source link output.
- `nvidia-ai.py` - NVIDIA Integrate API example using the OpenAI Python client and `NVIDIA_API_KEY`.
- `requirements.txt` - shared Python dependencies for the scripts.
- `README.md` - setup, run, and troubleshooting instructions.
- `.env` and `.env.example` - local environment configuration for API keys and prompt overrides.
- `prompts_history.md` - prompt history notes for the project.

## Notes

- The scripts share one Python environment.
- The Google examples rely on the `google-genai` package and `python-dotenv`.
- The NVIDIA example uses `openai`, `python-dotenv`, and an NVIDIA hosted model endpoint.
- A `__pycache__` directory is present, which is generated runtime output.

## Current State

Captured on 2026-05-12.

