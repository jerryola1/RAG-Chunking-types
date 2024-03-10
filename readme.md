
# LangChain Text Chunking and Processing

This repository contains a Python script that demonstrates various techniques for text chunking and processing using LangChain, a library designed to facilitate building language model applications. These techniques include character-based splitting, recursive character splitting, document-specific splitting, semantic chunking, and proposition-based chunking.

## Features

- **Character Text Splitting**: Splits text into chunks based on a specified number of characters.
- **Recursive Character Text Splitting**: Splits text recursively at different granularity levels based on character count.
- **Document Specific Splitting**: Splits texts according to their formats, like Markdown or programming languages (Python, JavaScript), understanding the structure of these formats to make meaningful splits.
- **Semantic Chunking**: Uses semantic analysis to split texts based on the understanding of content, aiming to keep contextually related content together.
- **Proposition-Based (Agentic) Chunking**: Breaks down text into propositions or semantically meaningful units, based on the model's understanding of the text, aimed at extracting actionable or significant statements.

## Requirements

- Python 3.10 or higher
- LangChain
- rich

## Setup

To run this script, you will need to install the required Python packages. You can install these packages using `pip`:

```bash
pip install langchain rich
```

### Environment Variables

- For semantic chunking, an `OPENAI_API_KEY` is required to utilize OpenAI's embeddings. Set this environment variable with your OpenAI API key:
  
  ```bash
  export OPENAI_API_KEY='your_openai_api_key_here'
  ```

## Usage

Once you have installed the necessary dependencies and set up the environment variables, you can run the script using the following command:

```bash
python app.py
```

This will execute the text chunking processes and print the results to the console.

## Contributing

Contributions are welcome! If you have a suggestion for improving this script or want to add more text chunking techniques, please feel free to open an issue or submit a pull request.

## License

This project is open source and available under the [MIT License](LICENSE).
