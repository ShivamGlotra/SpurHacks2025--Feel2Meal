# Feel2Meal

Welcome to **Feel2Meal**, a project built for SpurHacks 2025!  
Feel2Meal is an innovative application that connects emotions with food recommendations, aiming to enhance well-being by suggesting meals tailored to your mood.

## Table of Contents
- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Tech Stack](#tech-stack)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## About

**Feel2Meal** leverages emotion detection (via text, voice, or image input) to recommend personalized recipes and meal ideas. Whether you're feeling happy, sad, stressed, or excited, Feel2Meal offers suggestions to match your feelings and nutritional needs.

## Features

- 🧠 Emotion recognition from multiple input types
- 🍲 Personalized recipe and meal recommendations
- 👨‍🍳 Integration with popular recipe APIs
- 🎨 Engaging and intuitive user interface

## Getting Started

### Prerequisites

- [Visual Studio with .NET Framework support (for C# frontend)](https://visualstudio.microsoft.com/)
- [Python 3.10+ (for backend)](https://www.python.org/downloads/)
- [Other requirements, Gemini API]

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ShivamGlotra/SpurHacks2025--Feel2Meal.git
   cd SpurHacks2025--Feel2Meal
   ```

2. **Setup the Python Backend:**
   ```bash
   cd backend
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   pip install -r requirements.txt
   # Set up environment variables, if needed
   python app.py
   ```

3. **Setup the C# Frontend (Windows Forms App):**
   - Open the `frontend` folder in Visual Studio.
   - Restore NuGet packages if prompted.
   - Build and run the solution from Visual Studio.

4. **Configure Environment:**
   - Copy `.env.example` to `.env` (if needed) in both frontend and backend, and fill in necessary API keys and config.

## Usage

- Start the backend server (Python Flask) using the terminal.
- Launch the frontend application (Windows Forms App in C#) from Visual Studio.
- Use the Windows Forms interface to input your current mood.
- Receive meal or recipe suggestions tailored to your emotional state.

## Tech Stack

- **Frontend:** C# (Windows Forms App, .NET Framework, built in Visual Studio)
- **Backend:** Python (Flask micro web framework)
- **APIs:** Gemini API, [list any other APIs used]
- **Other:** Integration between C# frontend and Python backend via HTTP POST requests

## Contributing

We welcome contributions!  
To get started:

1. Fork this repo
2. Create your feature branch (`git checkout -b feature/yourFeature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin feature/yourFeature`)
5. Open a pull request

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

- SpurHacks 2025 organizers and mentors
- Open source contributors
- Google APIs used
- Flask and Windows Forms communities

---

Enjoy using **Feel2Meal**!

