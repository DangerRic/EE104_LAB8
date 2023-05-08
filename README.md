Name: Ricardo Espinosa
SJSU ID: 015317367
Class: EE 104

YOUTUBE LINK : https://youtu.be/FInDJZK12dU
GITHUB LINK : https://github.com/DangerRic/EE104_LAB8.git

About this code:

This project requires the creation of a web scraper to download web files and utilize OpenAI for answering website-related queries. Next, there will be a client-server system to respond to inquiries regarding files present within an organization's intranet.

OpenAI File Q&A: The client-server environment will allow users to ask questions related to files existing inside the intranet across an organization. The OpenAI chat bot will be integrated into the server to answer these questions. The server will be built using Flask and other relevant libraries.

OpenAI Web Crawl Q&A: The web scraper will be responsible for downloading web files to your local drive. These files will be used by the OpenAI chat bot to answer questions related to the website. The web scraper will use Python and libraries such as Beautiful Soup and Requests to scrape the website and download the files.


***MAKE SURE THAT THE FOLLOWING PYTHON MODULES ARE INSTALLED***

Download Python versions 7-10(either or)
Download Node.js (to use NPM)

pip install openai
npm install openai
pip install pandas opena
pip install python-dotenv
pip install tiktoken
pip install numpy
pip install bs4
pip install matplotlib
pip install plotly
pip install scipy
pip install sklearn -use-pep517
pip install -U scikit-learn scipy matplotlib

Instuctions:

- make sure that the modules above are installed

For OpenAI File Q&A
- utilize powershell or command prompt as administrator
- run directories on seperate command prompts for client and server virtual  runenvironments
- for server environment run python app.py (or flask run)
- for client environment run "NPM run dev"
- open the host server through the web link
- upload file that is going to be used 
- utilize chat bot within server by asking it questions related to the file uploaded

For OpenAI Web Crawl Q&A:
- utilize powershell to run openai
- enter domain name and full URL of website that will be scraped in the web-qa.py file lines [38] & [39]
- run virtual enviroment on the web-qa directory
- in powershell run python file (python web-qa.py)
- enter questions related to the website that was scraped