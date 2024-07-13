# Cardiovascular Disease Project

This project focuses on analyzing and querying data related to cardiovascular disease (CVD). It leverages various query engines and machine learning models to provide insights and information about CVD and related health metrics.

## Features

- Load and process CVD-related datasets.
- Utilize various query engines for data analysis.
- Provide detailed information about population demographics and specific details about India.

## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.8 or higher
- Jupyter Notebook
- Required Python libraries (listed in `requirements.txt`)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/yourusername/CVD_Project.git
    cd CVD_Project
    ```

2. Create a virtual environment and activate it:

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Set up environment variables:

    Create a `.env` file in the root directory and add your environment variables. Example:

    ```plaintext
    OPENAI_API_KEY=your_openai_api_key
    ```

5. Ensure the data files are placed in the appropriate directories as referenced in the notebook and scripts.

## Usage

1. Run the Jupyter Notebook:

    ```bash
    jupyter notebook CVD_Project.ipynb
    ```

2. Follow the instructions in the notebook to execute the cells and analyze the data.

3. Use the provided prompts in the notebook to query the data. To stop, simply close the notebook.

## Project Structure

- `main.py`: Main script for setting up and running the query engines and agent.
- `CVD_Project.ipynb`: Jupyter Notebook for exploring and analyzing CVD data.
- `prompts.py`: Contains prompt templates and instructions.
- `note_engine.py`: Defines the note engine used as a tool by the agent.
- `pdf.py`: Contains the India PDF engine for querying detailed information about India.
- `data/population.csv`: CSV file containing world population and demographics data.
- `data/CVD_data.csv`: CSV file containing cardiovascular disease-related data.

## Customization

- To update the query prompts, modify the `new_prompt` and `instruction_str` in `prompts.py`.
- To change the data sources, update the paths and files in the scripts and notebook.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

