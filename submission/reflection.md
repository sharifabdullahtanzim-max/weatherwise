# ✍️ Project Reflection

## AI Tools Used

I used ChatGPT as my primary pair-programmer and reviewer, and used gemini to generate the menu part. Moreover, I've used the optional hands-on-ai library in Colab for intent classification. ChatGPT helped design the app flow (manual vs conversation mode), refactor code into clear functions (get_weather_data, parse_weather_question, visualisers), and debug tricky issues like the PyInputPlus prompt not reappearing and converting rain volume → probability. I also used it to create readable error payloads when fetch_my_weather.get_weather() failed on bad locations.

## Prompting Techniques
  Which intentional prompting strategies did you apply?

## What Worked Well?
The modular architecture. Parsing → fetch → present is clean, with parse_weather_question() routing intents and pyinputplus handling inputs. Visualisations are simple and informative. The precipitation chart uses a principled method: P(any rain) = 1 − ∏(1 − pᵢ) from hourly chances, clamped to 0–100%. Error handling is practical: bad locations return a readable message instead of crashing. This made demos reliable.

## What Would You Do Differently?
Trim dependencies and simplify exception paths (some helpers are defensive to a fault). Add unit tests (pytest) for regex parsing and probability math, and a tiny mock for the weather client. Cache responses for the session to reduce calls. Long-term, package the app with a CLI flag (e.g., --mode manual|chat) and try a light Streamlit UI for accessibility.
I'd also try to make the exception handling better for user prompts.
## Final Thoughts
Any parting comments on your learning experience?
This project was a challenge for me, as I do not have any previous programming experience. I kept rewriting and renewing the template over and over, and finally I got to learn how to actually complete this project on the last day. This was an immense learning journey. This app pulled together APIs, lightweight NLP, and visualisation into a user-centred tool. For me, the biggest lesson was how I can use prompts to transform initial codes into cleaner and debugged code . Overall, I’m proud of the clarity of the flow and the visualizations, it feels like a small, well-engineered product.
