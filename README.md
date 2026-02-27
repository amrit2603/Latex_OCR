# LaTeX-OCR

This project leverages Llama 3.2 vision and Streamlit to create a LaTeX OCR app that converts images of LaTeX equations to LaTeX code.

## Demo Video



Click below to watch the demo video of the AI Assistant in action:

[Watch the video](https://github.com/user-attachments/assets/eb4b67cc-89ed-471d-9384-4b0ec5c782c2)

## Installation and setup

**Setup Ollama**:

   *On Linux*:
   ```bash 
   curl -fsSL https://ollama.com/install.sh | sh
   # pull llama 3.2 vision model
   ollama run llama3.2-vision 
   ```

   *On MacOS*:
   ```bash 
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"    # get homebrew
   xcode-select --install
   brew install ollama    # install ollama
   ollama pull llama3.2-vision    # pull llama 3.2 vision model
   ollama run llama3.2-vision 
   ```


**Install Dependencies**:
   Ensure you have Python 3.11 or later installed.
   ```bash
   pip install streamlit ollama
   ```

---

## Contribution

Contributions are welcome! Please fork the repository and submit a pull request with your improvements.
