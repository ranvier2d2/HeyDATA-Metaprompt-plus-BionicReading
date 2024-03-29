# HeyDATA-Metaprompt-plus-BionicReading
Run Claude 3 Anthropic's metaprompt with any Large Language Model supported by https://chat.HeyDATA.org  (pretty much any existing model. Soon even Grok-1). Use it as input to activate any DATA Skill. 

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ranvier2d2/DATA-metaprompt-BionicReading/blob/main/meta-data-alternative-markdown.ipynb)

This Jupyter Notebook provides a framework for generating custom prompt templates using Claude, an AI assistant powered by Anthropic. The notebook allows you to input a task, optionally specify input variables, and generate a structured prompt template that can be used to guide other models in completing the task or Skill requested. 

## Features

- Easy-to-use interface for creating prompt templates
- Automatic generation of input variables based on the provided task
- Customizable prompt structure with placeholders for input variables
- Testing functionality to try out the generated prompt template with user-provided variable values
- Integration with the Anthropic API for seamless communication with Claude

## Getting Started

1. Make a copy of the notebook by clicking on "File" -> "Save a copy in Drive"
2. Enter your Anthropic API key in the designated cell
3. Specify your task and optionally provide input variables
4. Run the notebook to generate the prompt template
5. Test the prompt template by providing values for the input variables

## Requirements

- Python 3.x
- Jupyter Notebook
- `requests` library
- Anthropic API key

## Notebook Structure

1. **Quickstart**: This section allows you to input your task and optional variables. It then generates a prompt template based on the provided information.

2. **Testing your prompt template**: In this section, you can test the generated prompt template by providing values for the input variables. The notebook will send the prompt to Claude and display the AI's response.

## Example Usage

1. Enter a task such as "Transform the following {python_code} into pseudocode and then into a {web_framework_name} + tailwind + typescript code. Assume i have the necessary credentials. Reason in pseudocode per the following {instructions}"

2. Optionally specify input variables like `["PYTHON_CODE", "WEB_FRAMEWORK_NAME", "INSTRUCTIONS"]`

3. Run the notebook to generate the prompt template

4. In the testing section, provide values for the input variables when prompted

5. Review Claude's response based on the provided prompt and variable values

## License

This project is open-source and available under the [MIT License](LICENSE).

## Acknowledgements

- [Anthropic](https://www.anthropic.com/) for providing the Claude AI assistant
- [Jupyter Notebook](https://jupyter.org/) for the interactive development environment
- [heyDATA](https://chat.heydata.org)


 ## Contact: 

Feel free to conact me on X for ML related stuff. Happy to talk! [![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/Dis_Trackted.svg?style=social&label=Follow%20%40Dis_Trackted)](https://twitter.com/Dis_Trackted)

Contributions are always welcome.
