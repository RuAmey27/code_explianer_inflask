# Project Code Explainer with ChatGPT

## Overview

This Flask-based project aims to provide an interactive platform for code explanation using OpenAI's ChatGPT. Users can input code snippets either as text or through images (using OCR), and the application will generate detailed explanations and responses based on the input.

## Features

- **Code Input:**
  - Accepts code input from users either as plain text or through image uploads.
  - Uses OCR (Optical Character Recognition) for extracting code from images.

- **ChatGPT Integration:**
  - Utilizes the ChatGPT API to generate informative responses and explanations for the provided code.
  - Enables a conversational interface for users to ask questions and seek clarifications.

- **Internal Input:**
  - The internal input accompanying each request is considered to enhance the contextual understanding of the code.

## Getting Started

### Prerequisites

- Python 3.x
- Flask
- OpenAI API key for ChatGPT (refer to [OpenAI API documentation](https://beta.openai.com/docs/) for obtaining an API key)

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/RuAmey27/code_explianer_inflask.git
   pip install -r requirements.txt
   
## Acknowledgements

- [OpenAI](https://www.openai.com/) for providing the ChatGPT API.
- Contributors to the Flask, OpenCV, and OCR libraries for making this project possible.

## License

None

## Contributing

Contributions are welcome! Please follow the steps below to contribute to this project:

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
   ```bash
   git clone https://github.com/RuAmey27/code_explianer_inflask.git
   git checkout -b feature-or-bugfix-branch
   git commit -m "Your descriptive commit message"
   git push origin feature-or-bugfix-branch

## Docker Support

No need to worry about setting up dependencies or configurations! We provide a Dockerfile for easy containerization of the project.

1. Ensure Docker is installed on your machine. If not, download and install it from [Docker's official website](https://www.docker.com/get-started).
2. Now you can enjoy the project without worrying about the setup in your local environment!


