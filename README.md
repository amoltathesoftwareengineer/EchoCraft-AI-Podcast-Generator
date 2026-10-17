# EchoCraft – AI Podcast Generator

An AI-powered application designed to transform text, documents, and ideas into podcast scripts and audio experiences.

## Overview

EchoCraft simplifies podcast creation by helping users convert written content into structured conversations, narration scripts, and generated audio.

The platform is designed to support content creators, educators, students, and professionals who want to produce audio content efficiently.

## Key Features

- Generate podcast scripts from text input
- Convert documents into structured podcast content
- Create introductions, discussions, and conclusions
- Support configurable podcast length and tone
- Generate speech using a text-to-speech engine
- Preview generated scripts before audio generation
- Download generated audio when supported
- Handle invalid input and generation errors

## Technology Stack

- Python
- Streamlit
- Language model integration
- Text-to-speech engine
- PyPDF for PDF text extraction
- FFmpeg, if required by the selected audio pipeline

## Project Workflow

Text or Document Input → Content Extraction → Script Generation → Text-to-Speech → Audio Output

## Project Structure

```text
EchoCraft-AI-Podcast-Generator/
├── app.py
├── script_generator.py
├── document_loader.py
├── speech_generator.py
├── requirements.txt
├── .env.example
├── .gitignore
├── README.md
└── tests/
```

## Installation

```bash
git clone https://github.com/amoltathesoftwareengineer/EchoCraft-AI-Podcast-Generator.git
cd EchoCraft-AI-Podcast-Generator
python -m venv .venv
```

Activate the environment on Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## Run the Application

After implementing the required components:

```bash
streamlit run app.py
```

Configure any required model credentials locally. Never commit API keys or secrets.

## Use Cases

- Educational audio content
- Study material narration
- Document-to-audio conversion
- Podcast prototyping
- Content creation workflows

## Limitations

Audio quality and generated content depend on the selected models and configuration. Generated scripts should be reviewed before publication.

## Future Enhancements

- Multiple speakers and voices
- Multilingual podcast generation
- Background music and audio mixing
- Podcast chapter generation
- Audio transcription and subtitles
- Exportable podcast metadata

## Author

Amol Tathe

GitHub: https://github.com/amoltathesoftwareengineer

## License

Add an appropriate open-source license before permitting reuse.
