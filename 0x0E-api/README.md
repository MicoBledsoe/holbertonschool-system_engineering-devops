### Project: API Interactions

This project explores practical applications of interacting with external APIs using Python scripts. The primary focus is on gathering data, exporting it to various formats, and manipulating JSON data structures.

#### Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [File Descriptions](#file-descriptions)
- [Usage Examples](#usage-examples)
- [Development and Contribution](#development-and-contribution)

#### Introduction

In this project, we utilize Python to interface with a typical REST API to retrieve and manipulate data. The scripts demonstrate data retrieval, conversion to different formats, and local storage.

#### Requirements

- Python 3.5+
- `requests` library installed (`pip install requests`)
- Access to the internet to make API calls

#### File Descriptions

- `0-gather_data_from_an_API.py` - Python script that retrieves data from an API and prints specific parts to the console.
- `1-export_to_CSV.py` - Script that extends the functionality of `0-gather_data_from_an_API.py` to export the data into a CSV file.
- `2-export_to_JSON.py` - Builds upon previous scripts by exporting the retrieved data into a JSON file.
- `3-dictionary_of_list_of_dictionaries.py` - Generates a dictionary of lists of dictionaries, saving the structure into a JSON file, illustrating complex data manipulation.

#### Usage Examples

#```bash
# To run the script that fetches and displays data:
python3 0-gather_data_from_an_API.py

# To export data to CSV:
python3 1-export_to_CSV.py

# To export data to JSON:
python3 2-export_to_JSON.py

# To create a complex JSON structure and save it to file:
python3 3-dictionary_of_list_of_dictionaries.py

## Collaborators
Mico Bledsoe - LinkedIn(www.linkedin.com/in/micobledsoe)
