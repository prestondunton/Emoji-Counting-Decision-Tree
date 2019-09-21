# Emoji-Counting-Decision-Tree

Python implementation of the ID3 algorithm for decision tree learning on the task of computer vision.

------------------------------------------------------------------------------------------------------------------------------------------

Please excuse the messy code and poor format.  I chose to leave the code untouched so that I could most directly show my understanding of computer science at the time, and thus my progress as a computer scientist since then.

------------------------------------------------------------------------------------------------------------------------------------------

   I developed this project from March 2017 - May 2017. In 2016 and 2017, I was in high school and just beginning to find passion in computer science.  This project reflects my exploration of more complex machine learning topics, as well as marks my first experience in Python.  Most importantly in this project, I was able to learn the process of development for a machine learning model, in which you must take into account the origin and nature of the data you wish to represent. 
   
   I was inspired by the YouTue channel Welch Labs, and his video series Learning to See, in which he incrementally develops a decision tree learning model for computer vision.  What struck me most about his videos compared to the many other machine learning videos on YouTube is that he contextualizes his process and his choices within modern understandings of data driven science.  While my program uses the same algorithm and a similar task, I made it a goal for myself to use his videos as a resource for understanding, and not a guide.  By doing this, I was able to practice the process of development and contextualization in terms of my own task.
   
   The program was made using the Jupyter Notebook editor, which was very useful for input / output analysis of my task.  It also allows for a very linear documentation of my model.
   
   As for the results, my model fails in several ways.  Although I tried my best to consider my methods by purpose, I was too inexperienced with computer science to know of standard methods to reduce noise and best prepare the image for computer vision.  I also now realize that I had taken a regression problem, converted it into a classification problem, and then tried to produce regression results.  This poor understanding of the task also led to the inaccurate count of emojis in the testing data.  While these failures remain, I am proud of them because they show potential for personal growth and guide my studies as I continue to become a better individual.

------------------------------------------------------------------------------------------------------------------------------------------

References:

Greensted, Andrew. "Otsu Thresholding." The Lab Book Pages.  17 June 2010. Web. 11 May 2017.

Quinlan, J. R. "Induction of Decision Trees." (1985): n. pag. Machine Learning Theory.   Klewer 
Academic Publishers, Boston, 2007. Web. 1 May 2017.   <http://hunch.net/~coms-4771/quinlan.pdf>.

Learning To See. Welch Labs, 15 Apr. 2016. Web. 11 May 2017.
<https://www.youtube.com/watch?v=i8D90DkCLhI&t=35s>.
