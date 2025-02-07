# PDF-Scraper
A PDF scraper tool designed to extract titles, lists, tables, and images from PDF documents. This is the first version of the project and is still under development, with many features and improvements to be added in future versions.

## Setup Instructions:

1. **Clone the Repository** <br />
   First, clone the repository to your local machine:
   ```bash
   git clone git@github.com:AnasDorgham11/PDF-Scraper.git
   cd PDF-Scraper
   ```
      <br />
2. **Create a Virtual Environment** <br />
   To create and activate a virtual environment, follow these steps:
- **<div style="display: flex; align-items: bottom;"><span>Linux/macOS </span><a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=linux&theme=light" alt="linux" width="20px" height="20px" style="position: relative; top: -10px;"/></a> :</div>** 
   ```
   python3 -m venv venv          # Create virtual environment
   source venv/bin/activate      # Activate virtual environment
   ```


- **<div style="display: flex; align-items: bottom;"><span>Windows </span><a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=windows&theme=light" alt="Windows" width="20px" height="20px" style="position: relative; top: -10px;"/></a> :</div>** 
    - Command Prompt (CMD):
    ```
    python -m venv venv          # Create virtual environment
    venv\Scripts\activate        # Activate virtual environment
    ```
    - PowerShell:
    ```
    python -m venv venv          # Create virtual environment
    .\venv\Scripts\Activate.ps1  # Activate virtual environment
    ```
     <br />
3. **Install Dependencies**<br />
   After activating the virtual environment, install the required libraries using the ```requirements.txt``` file:
   ```
   pip install -r requirements.txt
   ```


   <br />
4. **Run the Scraper**<br />
   Once the environment is set up and dependencies are installed, run the scraper to collect match data:
   ```
   python3 scraper.py
   ```

   <br />
5. **Find scraped data**<br />
   You can find scraped data in a folder named as the name of the PDF file.

   <br />
6. **Deactivate the Virtual Environment**<br />
   When you're done, deactivate the virtual environment, by running:
   ```deactivate```

   <br />
## Notes:
   - PDF-Scraper is still under development and lacks of a lot of features.
