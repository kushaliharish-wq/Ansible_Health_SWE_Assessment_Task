# Ansible_Health_SWE_Assessment_Task
# Markdown to Google Docs

## Brief Description
This project provides a tool to convert markdown formatted meeting notes into a styled Google Docs document using the Google Docs API. Designed to work seamlessly in a Google Colab environment, this tool allows you to easily import meeting notes in markdown format, process them, and output them as a well-formatted Google Docs document with proper headings, bullet points, checkboxes, and assignee mentions.

## Setup Instructions

1. **Clone the Repository:**
   To get started, first clone this repository to your local machine or directly into your Google Colab environment.

   git clone https://github.com/kushaliharish-wq/Ansible_Health_SWE_Assessment_Task.git
   
3.  Create a Google Cloud Project and Enable APIs:
    Go to Google Cloud Console.
    Create a new project.
    Enable the Google Docs API and Google Drive API for your project.
    Create OAuth 2.0 credentials and download the credentials.json file.
    Place the credentials.json file into your project directory or upload it directly to Colab.

4.  Required Dependencies
    This project requires the following Python dependencies:
    
    google-auth-oauthlib
    google-auth-httplib2
    google-api-python-client
    oauth2client
    google-colab
    
    You can install them in your Colab environment by running:
    pip install --upgrade google-auth-oauthlib google-auth-httplib2 google-api-python-client google-colab
    
6.   How to Run in Colab
     Open a new notebook in Google Colab.

     Clone the Repository: In your Colab notebook, clone the repository:

     !git clone https://github.com/kushaliharish-wq/Ansible_Health_SWE_Assessment_Task.git

     Upload the credentials.json: Upload the credentials.json file (generated from Google Cloud Console) by running the following code in Colab:

     Run the Script: After uploading the credentials, you can authenticate and run the script to convert your markdown notes into a Google Docs       document.
