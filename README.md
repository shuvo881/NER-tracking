# NER-tracking
The purpose of this project is to evaluate your ability to design, implement, and test an AI-based system capable of extracting Named Entities (e.g., names, organizations, locations, dates, etc.) from a dataset containing over 1000 conversation sentences.


## Installation

1. Clone the repository:
```bash
git clone https://github.com/shuvo881/NER-tracking.git
cd NER-tracking
```

3. Set up environment variables:

```bash
# Create a vertual enviroment
## for Mac and Linux
python -m venv venv

# Active the verual enviroment
## For Mac and Linux
source venv/bin/active
```

```bash
# Export your Open AI API secret key
export OPENAI_API_KEY=your_key_here
```

### Basic Usage

```bash
cd code
# run the main file:
python main.py
```


# File Structure

``` bash
NER-tracking/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── input/
│   │   ├── NER_Training_Data.xlsx
│   │
│   ├── output/
│   │   ├── users_NER.csv
│
├── code/
│   └── main.ipynb


```

Main Project Files:
* README.md: Likely contains project documentation.
* requirements.txt: Contains Python dependencies for the project.
* main.ipynb: Main script for the project, found in the code/ directory.

Data Files:
* input: Contains original ‘NER_Training_Data.xlsx’ dataset
* output: Contains ‘users_NER.csv’ files that appear to have been processed.

