# Codevert

Codevert is an AI-powered code conversion tool that allows you to convert code snippets between different programming languages while maintaining identical functionality, inputs, and outputs. It leverages the Gemini API for intelligent code translation.

## Features

*   **AI-Powered Conversion**: Utilizes the Gemini API for accurate and idiomatic code conversion.
*   **Multiple Language Support**: Convert between Python, C++, and Java.
*   **Text Input & File Upload**: Easily input code directly or upload source code files.
*   **Syntax Highlighting**: Improved readability with language-specific syntax highlighting.
*   **Copy & Download**: Conveniently copy converted code to clipboard or download as a file.
*   **Responsive UI**: A clean and intuitive user interface built with Next.js and Shadcn UI.

## Setup and Installation

To get Codevert up and running on your local machine, follow these steps:

1.  **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/codevert.git
    cd codevert
    ```

2.  **Install dependencies**:
    ```bash
    npm install
    # or yarn install
    # or pnpm install
    ```

3.  **Set up environment variables**:
    Create a `.env` file in the root of your project and add your Gemini API key:
    ```
    GEMINI_API_KEY=YOUR_GEMINI_API_KEY
    ```
    You can obtain a Gemini API key from the Google AI Studio.

4.  **Run the development server**:
    ```bash
    npm run dev
    # or yarn dev
    # or pnpm dev
    ```

    The application will be accessible at `http://localhost:3000`.

## Usage

1.  **Open the application** in your browser (`http://localhost:3000`).
2.  **Select Input Mode**: Choose between "Text Input" to paste your code directly or "File Upload" to upload a `.py`, `.cpp`, or `.java` file.
3.  **Select Source Language**: Choose the original language of your code.
4.  **Select Target Language**: Choose the language you want to convert your code to.
5.  **Convert**: Click the "Convert Code" button to initiate the AI-powered conversion.
6.  **Review & Use**: The converted code will appear in the "Converted Code" section. You can copy it to your clipboard or download it as a file.
