```markdown
# AgenticAI Journey - Run Your First Prompt

## Description
This repository provides an introduction to using Google's Generative AI library in Colab. The notebook **"Run your first prompt"** demonstrates how to query a generative AI model with a simple question and get insightful responses. 

Example prompt: **"Is Bahawalpur a city?"**  
Output: **"Yes, Bahawalpur is a city in Punjab, Pakistan."**

## Features
- Interactive Colab notebook for quick exploration of generative AI.
- Step-by-step guide to configuring and running your first prompt.
- Example integration with Google's `gemini-1.5-flash` model.

```

## Prerequisites
- A Google Cloud API key with access to generative AI.
- A Google Colab account to run the notebook.

## Getting Started
1. Open the Colab notebook **"Run your first prompt.ipynb"** in your browser:
   - [Run your first prompt - Colab]([https://colab.research.google.com/github/your-username/AgenticAI-Journey/blob/main/01%20-%20Quick%20Start/Run%20your%20first%20prompt.ipynb](https://colab.research.google.com/drive/1BMkEAfQwEx268OvRjQLlHCZiI4Hb6751?usp=sharing))

2. Follow the instructions in the notebook:
   - Install dependencies:
     ```python
     !pip install -U "google-generativeai>0.7.2"
     ```
   - Configure your API key:
     ```python
     from google.colab import userdata
     GOOGLE_API_KEY = userdata.get("GOOGLE_API_KEY")
     ```
   - Run your first query using the `gemini-1.5-flash` model.

3. Example usage:
   - Input:
     ```python
     input = "Is Bahawalpur a city?"
     response = model.generate_content(input)
     print(response.text)
     ```
   - Output:
     ```plaintext
     Yes, Bahawalpur is a city in Punjab, Pakistan.
     ```

## Contributing
Contributions are welcome!  
1. Fork the repository.
2. Create a new branch for your changes (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m "Add feature name"`).
4. Push your branch (`git push origin feature-name`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Built using Google's Generative AI technology.
- Inspired by the city of Bahawalpur and its cultural significance.
```
