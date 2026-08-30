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

## Create API Keys

1. [anthropic](https://platform.claude.com/login): 
Models
2. [deepseek](https://platform.deepseek.com/sign_in): 
Models
3. [google](https://accounts.google.com/v3/signin/identifier?continue=https://aistudio.google.com/app/apikey?original_referer%3Dhttps://www.google.com&followup=https://aistudio.google.com/app/apikey?original_referer%3Dhttps://www.google.com&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S-1438952158:1788052697032371): 
Models and cloud
4. [groq](https://console.groq.com/keys): 
Models [FREE]
5. [langsmith](https://smith.langchain.com/): 
framework
6. [nvidia](https://build.nvidia.com/settings/api-keys): 
Models [FREE]
7. [openai](https://platform.openai.com/login?next=%2Fapi-keys): 
Models
8. [openrouter](https://openrouter.ai/): 
Models [FREE]
9. [pinecone](https://www.pinecone.io/): 
Vector database [FREE]
10. [tavily](https://www.tavily.com/): 
Web Search [FREE]
