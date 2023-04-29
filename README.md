# Build an Ecommerce Chatbot with Redis, LangChain, and OpenAI


>*Powered by [Redis](https://redis.io), [LangChain](https://python.langchain.com/en/latest/), and [OpenAI](https://platform.openai.com)*

In this tutorial we build a conversational retail shopping assistant that helps customers find items of interest that are buried in a product catalog. Our chatbot will take user input, find relevant products, and present the information in a friendly and detailed manner.

The source code here goes along with [this Redis blog post](https://redis.com/blog/build-ecommerce-chatbot-with-redis/). Try various prompt-engineering techniques to improve on this prototype for your use case!

## Getting Started

1. [Get an OpenAI API Key](https://platform.openai.com).
2. Add the API key to the [`docker-compose.yml`](./docker-compose.yml) file here in the repo.
3. Start up the docker compose environment:
    ```bash
    docker compose up
    ```

## Coming Soon

- Extensions to LangChain + Redis integration for conversational memory storage
- Have an idea or contribution to make this even better? Open an issue -- let's collaborate!
