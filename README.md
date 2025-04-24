# AI-Powered Recipe Generator 🍽️

## 📌 Project Overview

This AI-based web application generates personalized recipes based on user-provided ingredients or preferences. Leveraging a language model API, the app creates step-by-step cooking instructions instantly. It showcases how AI can be applied in real-life tools like food tech, allowing users to explore creative and dynamic meal ideas through a simple interface.

## 🚀 Key Technical Highlights

- **Frontend Development**: Built using React.js for dynamic and responsive user interfaces.
- **AI Integration**: Utilizes OpenAI’s GPT model (or equivalent) to generate unique recipe instructions based on user prompts.
- **Form Handling**: Accepts multiple ingredients using controlled input fields.
- **Asynchronous API Calls**: Uses Axios to fetch results from the AI model and handle user queries.
- **Result Display**: Parses and renders AI-generated text as readable recipe cards.

---

## 🛠️ Detailed Steps

### 1. Project Setup

- **Clone the Repository**:
  ```bash
  git clone https://github.com/YashRangucha/AI-Recipe-Generator-main.git
  cd AI-Recipe-Generator-main
## Install Dependencies:
- npm install

## API Configuration:

Get your OpenAI API key from OpenAI
- Create a .env file in the root directory and add:
- REACT_APP_OPENAI_API_KEY=your_api_key_here
## Run the App:
- npm start
- Navigate to http://localhost:3000 in your browser.

## ✨ Feature Implementation
- Ingredient Input: Users can type or paste a list of available ingredients.

- Recipe Generation: When submitted, the app sends the ingredients to the AI API, which returns a structured recipe.

- Display Output: The generated recipe is rendered with ingredients, steps, and tips.

- Regeneration: Users can request a new recipe or modify inputs to try again.

## 📊 Key Insights
Practical example of integrating a generative AI model into a frontend web app.

AI-generated content adapts to nearly any input with detailed cooking instructions.

Encourages experimentation in cooking by using tech to discover new dishes.

## 💡 Future Enhancements
- 📸 Image Generation: Integrate food illustrations using DALL·E or similar tools.

- 🔐 Authentication: Allow users to create accounts and save recipes.

- 🧠 Filters & Tags: Support dietary preferences like vegan, keto, gluten-free.

- 🗂️ History: Enable users to view past recipe generations.

- 📱 Mobile UX: Further enhance mobile responsiveness and accessibility.

## 🧰 Technologies Used
- Frontend: React.js, JSX, Tailwind CSS

- API Integration: OpenAI GPT API

- HTTP: Axios

- State Management: React Hooks (useState, useEffect)

- Version Control: Git & GitHub

- Environment Variables: .env for secure API key handling

