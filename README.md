# game_library_metacritic_scraper
Take a list of Metacritic links and scrape useful data for your game library. 

Have you carelessly been adding free Epic, Amazon, and GOG games to your accounts for years and suddenly realized you've lost track of what you actually do and do not own? No? Don't lie to me. You have and I have as well, and that evergrowing backlog is a constant weight on my mind as I play the same 1-2 games repeatedly every week. To ease my conscience without actually having to play any of these games, I spent a Saturday going through each launcher and making a list of the Metacritic links to each game. Then I wrote code to scrape scores, descriptions, and the release date for each game. Finally, I made a giant Excel sheet listing from 1-5 how much I want to play each game. So now, my backlog is the same as its always been....but itemized. I'm sharing the code so that I can feel that this process was actually worth the time. Ideally, it could pull the titles from your library, search for the metacritic link, and keep itself updated but that part was beyond me. Instead, I just manually add new entries so I keep on top of it.

File List:
Create_Game_Library.ipynb - Jupyter Notebook code. Really friendly Python interface you can run in a browser.
link_list_in.csv - csv file of the metacrtic links
scraped_list_out.csv - What the Python code outputs
example sheet sorted.png - Picture of what a formatted Excel version of the library looks like
library stats.png - basic metadata of my library as of 2022-01-29

If you are unfamiliar with Python but want to run this:
1. Make an Excel sheet of the Metacritic links with the top cell in the column titled "Link"
2. Save as a .csv file named "link_list_in.csv"
3. Download and install Anaconda https://www.anaconda.com/, it comes with Jupyter bundled
4. Launch Jupyter, It should open a window in your default browser that should the folders on your computer
5. Download "Create_Game_Library.ipynb" and save it to the same folder as your list
6. Navigate to it and open it in your Jupyter window
7. Click the 'Run" icon in the bar above the code
8. It should save a file called "scraped_list_out.csv" for you in the same folder as your other files


If you run into issues, let me know. If you want to improve the code and add more functionality (pulling in info from your launchers, additional data, etc) please feel free!




