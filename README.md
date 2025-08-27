# Agentic AI Researcher

This project is an **Ai-powered research assistant** that leverages DeepSeek AI and LangChain to analyze recent research papers, identify promising new research directions, and generate new research papers with mathematical equations and LaTeX PDF rendering.

## Features

- Search and read papers from arXiv.org
- Summarize and analyze research papers
- Suggest new research directions
- Write new research papers with equations
- Render papers as LaTeX PDFs
- Uses DeepSeek AI for advanced language understanding

## Architecture
![Overall Architecture](images/Architecture_Diagram.png)

*The diagram above shows the overall architecture of the Agentic AI Researcher system.*

## Installation

1. Clone the repository:
    ```
    git clone https://github.com/yourusername/agentic_ai_researcher.git
    cd agentic_ai_researcher
    ```

2. Install dependencies:
    ```
    pip install -r requirements.txt
    ```

3. (Optional) Set up your DeepSeek API key in the code or via environment variables.

## Usage

Run the main script:
```
python ai_researcher.py
```
or
```
python ai_researcher_2.py
```

Follow the prompts to interact with the AI researcher.

## Folder Structure

- `ai_researcher.py` / `ai_researcher_2.py`: Main agent scripts
- `arxiv_tool.py`, `read_pdf.py`, `write_pdf.py`: Tool modules
- `images/`: Contains architecture diagram and other images

## License

MIT License

---

*For questions or contributions, please open an issue or pull request!*