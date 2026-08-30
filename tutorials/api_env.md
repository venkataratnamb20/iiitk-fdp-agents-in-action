# APIs and API keys

## Instructions

1. `requirements.txt`: Install only used prividers and remove all other dependencies
2. copy `.env.example` to `.env`
3. Keep API keys that will be used in the development. Remove other API keys.
4. Make sure you are loading teh environment variables with the following code in the main file (appropriate file)

    ```python
    from dotenv find_dotenv, load_dotenv

    load_dotenv(find_dotenv())
    ```

5. Never disclose .env file. Make sure `.env` is in ignore files like `.gitignore` or `.dockerignore` etc.