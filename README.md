# WEB-Crawler-Python

This crawler takes some seed urls from the user in the form of txt file (sample Seed_URL file is also uploaded). Then start crwaling the each website, extracts urls form each web page filter them against the robot.txt file of the website and check for duplicates urls, then it saves the html extracted from each website on mongodb Atlas.

**How to Run**
1. Clone the Repo
2. open the pyhton notebook and in the Second cell (prompt has been given in notebook) enter the connection string of your own Mongodb Atlas.
3. Provide your own seed url file path.
4. Run the notebook.
