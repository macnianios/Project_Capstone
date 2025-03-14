# Fandango

  This is a project from the udemy class "Python for Machine Learning & Data Science Masterclass" , section 8: Data Analysis and Visualization Capstone Project Exercise
“This project investigates whether Fandango's movie ratings are inflated to encourage ticket sales."
https://www.udemy.com/course/python-for-machine-learning-data-science-masterclass 


#Running the Notebook in Google Colab
  1.	Open Google Colab: Go to https://colab.research.google.com/.
  2.	Upload the Notebook:
  3.	Click on "File" -> "Upload notebook" and select "Project_Capstone.ipynb" from your local machine.
  4.	Alternatively, you can upload the entire project directory (including "Project_Capstone.ipynb") to your Google Drive and open the notebook directly from there.

#Methods Used

    •	Data Manipulation (pandas,numpy)
  
    •	Data Visualization(seaborn,matplotlib)
  

#DATA
  •	This is the data behind the story Be Suspicious Of Online Movie Ratings, Especially Fandango’s openly available on 538's github: https://github.com/fivethirtyeight/data. There are two csv files, one with Fandango Stars and Displayed Ratings, and the other with aggregate data for movie ratings from other sites, like Metacritic,IMDB, and Rotten Tomatoes.

#Results
  • Clearly Fandango is rating movies much higher than other sites so it can sell more ticket for movies. Fandango uses a star rating system, which can lead to rounding up ratings. This might make movies appear more favorably compared to a system that uses decimals or half stars.

