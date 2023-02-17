# ChatGPT-PromptEngineering
This Python script reads an e-book in PDF format, splits the text into prompts, and uses the OpenAI GPT-3 API to generate completions for each prompt. The completions are then saved in three different file formats (Excel, JSON, and text) that can be used to fine-tune your own GPT-3 model.  

# Requirements
Python 3.x
openai package
PyPDF2 package
pandas package

# Setup
Make sure you have Python 3.x installed on your computer.

Install the openai, PyPDF2, and pandas packages by running the following command in your terminal or command prompt:
pip install openai PyPDF2 pandas
Sign up for an OpenAI API key if you don't have one already. You can sign up for a free account at https://beta.openai.com/signup/.

Copy the script ebook_prompt_generator.py to a directory on your computer.

# Usage
Open the ebook_prompt_generator.py script in your preferred text editor.

Replace <insert API key here> with your OpenAI API key.

Replace <insert file path here> with the file path of the e-book that you want to use.

Replace <insert delimiter here> with the appropriate delimiter for your e-book. This is the text that will be used to split the e-book into prompts.

Replace <insert GPT-3 engine here> with the name of the GPT-3 engine that you want to use. See https://beta.openai.com/docs/models/gpt-3 for a list of available engines.

Run the script by typing the following command in your terminal or command prompt:

# Copy code
python ebook_prompt_generator.py
The script will generate completions for each prompt and save the results in the following file formats:

output.xlsx: an Excel file that contains two columns ("prompt" and "completion") and one row for each prompt-completion pair.
output.json: a JSON file that contains an array of prompt-completion pairs, with each pair represented as a dictionary.
output.txt: a text file that contains one prompt-completion pair per line, with each pair represented as a JSON object.
Troubleshooting
If you encounter any errors while running the script, make sure that you have installed the required packages and that you have entered the correct API key, file path, delimiter, and GPT-3 engine name.
If you have any issues with the OpenAI API, check the documentation at https://beta.openai.com/docs/ or contact OpenAI support at https://beta.openai.com/support/.
If you have any questions or feedback about the script, feel free to reach out to the author.

# Credits
This script was created by AJ for educational purposes. Feel free to use and modify it as you see fit. If you found this script helpful, consider giving a shoutout to the author or contributing to the project. Thank you for your interest and happy generating!
