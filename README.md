
# Music Recommendation System Using Knowledge Graph

This research aims to develop a music recommendation system using a
knowledge graph to represent the relationships between users and music entities.
The knowledge graph is transformed into vectors through the TransM model, which
acts as the graph embedder. To tackle the cold-start problem, the knowledge graph
is supplemented with users' background information, while the Bounded-Greedy
Selection (BGS) algorithm is employed to address diversity issues. By utilizing
information in vector form, the system can calculate the similarity between entities, enabling it to generate recommendations.


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DATASET_FOLDER_PATH`


## Installation

Set your environment variables.

```python
DATASET_FOLDER_PATH='<project-path>/datasets'
```

Create and activate a virtual environment.

```bash
python3 -m venv env

# Using MacOS 
source env/bin/activate

# Using CMD
env\Scripts\activate.bat
```

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install all modules and packages.

```bash
pip install -r requirements.txt
```

Run the codes in `data.ipynb` file. These codes is used for data preparation.

Run the codes in `app.ipynb` file to execute this projects. 

    
## Authors

- Nandito Fatoni Amri
  - GitHub: [@nandito-amri](https://www.github.com/nandito-amri)
  - Email: nandito.f.amri@gmail.com


## Features

- Graph Building
- Graph Embedding Using TransM
- Recommendation Module
- Diversity Module


## License

[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://choosealicense.com/licenses/gpl-3.0/)
