WhatsApp Chat Analyzer
A web app that looks at WhatsApp chat data. Tells you interesting things. It shows when people were active what words they used what emojis they liked and stats about each person.
The app takes a WhatsApp chat export file cleans it up and shows you cool charts to understand how people chatted.

WebApp Link ~ https://akshayxchatanalysis.streamlit.app/
                                 
--------------------------------------------------
FEATURES
How it Works
 WhatsApp Chat Export
        -> 
 Cleaning Up Data and Creating DataFrame(preprocessor.py)
        ->
 Creating Functions for analysis(helper.py)
        -> 
 Making Charts with Streamlit
        ->
 Also it works with respect to overall or selected user analysis
 --------------------------------------------------

Project Folders(WhatsApp-Chat-Analyzer):
 README.md
 wtp_chat_analysis.ipynb
 helper.py
 preprocessor.py
 analyser.py
 requirements.txt
--------------------------------------------------

How it was Built:

1. preprocessor.py
  This part cleans up the WhatsApp chat export.
  - It uses
     Re
     Pandas
  - It does things like
    Read chat messages
    Get date time, who sent it and the message
    Make a clean table
    Returns a cleaned-up table.

2. helper.py
  This part does all the analysis for the web app.
  It uses
  - pandas
  - Counter
  - emoji
  - URLExtract
  - WordCloud
    
 and It can
 - Get user stats
 - Make a word cloud
 - Find used words
 - Look at emojis
 - See chat activity over time
   
3. wtp_chat_analyser.py (Streamlit Web App)
  It uses
  - Python
  - Pandas
  - Regex
  - Streamlit
  - Matplotlib
  - Seaborn
  - WordCloud
  - Counter
  - Emoji
 This file contains the Streamlit based web interface for the application.
--------------------------------------------------
