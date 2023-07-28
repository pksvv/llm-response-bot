# llm-response-bot
A rasa bot that can generate and rephrase responses on the fly using LLMs

## Deploying
To deploy and run the bot, `docker` and `docker-compose` is required.
1. Clone the repository and do `cd llm-response-bot`
2. Make sure to copy the `.env.template` to `.env` and add your open-ai API key under the `OPENAI_COMPLETIONS_API_KEY` key
3. Go to the project root directory and run `docker compose up -d` to run everything
4. Widget should be available @ http://localhost:80

## Talking to the bot
The bot is a demo Pizza Shop bot that can do the following:
- say greet
- show the Pizza Shop menu
- tell about Pizza prices
- tell price for an order
- say welcome
- say goodbye

All the bot responses are generated or rephrased using Open AI GPT-3 `text-davinci-003` completions model.  

In case the rate limit is met (3 requests within a minute last I checked), bot will utter the default rephrase response.



Thank you so much for inviting me to be a part of this incredible journey with Rasa. I'm genuinely excited about this opportunity and would love to pursue it.

As I consider making a move to a new location, I have some professional commitments that require me to complete a critical project before I can join Rasa. I had discussed this during my interviews with xxxx, and it's important for me to uphold my verbal commitment to this project. I believe the project's success depends on my involvement, and I don't want to leave my current employer in a difficult position.

Nevertheless, I'm committed to keeping the connection warm and thriving. I'm more than willing to contribute in any way possible during this transition period so that our bond remains strong. Let's work together to make the most of this time and create a wonderful journey ahead with Rasa.
![image](https://github.com/pksvv/llm-response-bot/assets/8981899/5f70ff3e-b7f7-4f93-84c2-916e26ca27fe)
