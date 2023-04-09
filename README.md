<h1 align="center">
 babyagi-streamlit

</h1>

# Installation

1. Install the required packages:
````
poetry install
````

2. Copy the .env.example file to .env: `cp .env.example .env`. This is where you will set the following variables.

# Usage

Run streamlit.
````
poetry run streamlit run app/main.py 
````

You can now view your Streamlit app in your browser.

Local URL: http://localhost:8501
Network URL: http://xxx.xxx.xxx.xxx:8501

To stop the Streamlit server, press ctrl-C.

# Acknowledgments

I would like to express my gratitude to the developers whose code I referenced in creating this repo.
Special thanks go to 
@yoheinakajima (https://github.com/yoheinakajima/babyagi)
@hinthornw (https://github.com/hwchase17/langchain/pull/2559)
