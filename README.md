# AI Recipe Rescue 🍳

Type in whatever ingredients you have at home — messy, informal, or very short input is fine (e.g. "chicken" or "2 eggz, som rice idk") — and the app suggests one realistic recipe you can cook right now.

If your ingredients are too sparse for a full dish, it asks one combined clarifying question (e.g. "Do you have any vegetables or a starch?") instead of guessing. If what you have still isn't enough for a real meal (e.g. just lemon or salt), it tells you honestly instead of inventing a fake recipe, and offers a small side/garnish idea if one exists. A "Surprise Me" button skips clarification and returns a more creative recipe at higher temperature.

**How to run (Google Colab):**
1. Run the pip install cells (`groq`, `gradio`).
2. Run the core logic cell — it will prompt you to paste your Groq API key (get one free at console.groq.com).
3. Run the Gradio UI cell — a public link will be printed; open it to use the app.

**What I used AI for:** Used an AI assistant (Claude) to help write and debug the Python code — the prompt design (clarifying questions, ingredient-honesty rules, insufficient-ingredient detection), the Groq API integration, response parsing, and the Gradio UI logic, including fixing bugs like model deprecation and indentation errors along the way.
