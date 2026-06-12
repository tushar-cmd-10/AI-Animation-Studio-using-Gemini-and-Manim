# AI Animation Studio using Gemini and Manim

## Overview

AI Animation Studio is a Generative AI project that converts natural language prompts into fully executable Manim animations. The system leverages Google's Gemini LLM, LangChain, and Pydantic to generate structured, error-free Python code, which is then rendered into high-quality educational animations using Manim Community Edition.

The project automates the complete workflow from prompt input to video generation, enabling users to create mathematical and educational animations without manually writing Manim code.

---

## Features

* Convert text prompts into Manim animation scripts using Gemini LLM.
* Structured output validation using Pydantic.
* Automated Python code generation and execution.
* Automatic rendering of animations with Manim Community Edition.
* Video preview directly within Google Colab.
* Prompt-engineered system instructions to enforce animation quality and API safety.
* Layout constraints to prevent overlapping objects and maintain visual consistency.

---

## Tech Stack

* Python
* Google Gemini API
* LangChain
* Pydantic
* Manim Community Edition
* Google Colab

---

## Architecture

User Prompt → Gemini LLM → LangChain Pipeline → Structured Manim Code Generation → Python Script Creation → Manim Rendering Engine → MP4 Animation Output

---

## Project Workflow

1. User enters a natural language animation request.
2. Gemini generates a complete Manim script based on predefined system rules.
3. Pydantic validates the generated output structure.
4. The generated code is saved as `animation.py`.
5. Manim executes the script and renders the animation.
6. The generated video is displayed directly in Google Colab.

---

## Example Prompt

```text
Explain the Pythagorean Theorem with an animated triangle and formula derivation.
```

Generated Output:

```text
Python Manim Script → Rendered Educational Animation Video
```

---

## Installation

### Install System Dependencies

```bash
apt-get update
apt-get install -y libcairo2-dev libpango1.0-dev ffmpeg pkg-config python3-dev
apt-get install -y texlive-latex-base texlive-latex-extra texlive-fonts-recommended dvisvgm
```

### Install Python Packages

```bash
pip install --upgrade pip setuptools wheel
pip install manim
pip install langchain
pip install langchain-google-genai
pip install pydantic
```

---

## Usage

1. Configure your Google Gemini API key.
2. Run the notebook in Google Colab.
3. Enter a prompt describing the animation.
4. The system generates a Manim script automatically.
5. Render the animation and view the generated video.

---

## Key Highlights

* End-to-end AI-powered animation generation pipeline.
* Demonstrates practical use of Large Language Models in code generation.
* Applies prompt engineering techniques for reliable outputs.
* Integrates Generative AI with educational visualization tools.
* Eliminates the need for manual Manim scripting for common animation tasks.

---

## Future Enhancements

* Support for multiple animation styles.
* Web-based interface using Streamlit.
* Animation editing and regeneration.
* Multi-scene video generation.
* Support for voice-over narration and subtitles.

---

## Author

Tushar Deshmukh

Generative AI Project | LangChain | Gemini | Manim | Python
