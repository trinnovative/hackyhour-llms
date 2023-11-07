# HackyHour-LLMs

## Setup

Use [poetry](https://python-poetry.org/docs/) to set up the project.

Install dependencies:
```
poetry install
```

Activate virtual environment:
```
poetry shell
```

Add `.env`-File containing your OpenAI API key like this:
```
OPENAI_API_KEY=<your_api_key_here>
```

## Promptfoo

Install promptfoo: 
```
npm install -g promptfoo
```

or run it directly with:
```
npx promptfoo@latest
```

Set your OPENAI_API_KEY environment variable.

Run the evaluation:
```
npx promptfoo@latest eval
```

After evaluation, open the web viewer:
```
npx promptfoo@latest view
```

For additional information see the promptfoo [documentation](https://promptfoo.dev/docs/intro).