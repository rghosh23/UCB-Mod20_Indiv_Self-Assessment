# Module 20 Individual Self-Assessment

## *Self Assessment*

My primary role in this project was to generate the visualization dashboards showcasing interactive patient information, preliminary trends in patient data, and machine-learning model based data. Below is a segment by segment summary of my roles throughout the project:

- *Segment 1*: Worked on the Presentation portion by editing the ReadMe.md including the communication protocols used, and helped create a technology.md file to have an inventory of technologies used. During team discussions, we were collectively able to decide which columns to keep and for what kind of future visualizations. We were also able to come up with a game plan to approach the machine learning modeling.
- *Segment 2*: Worked on generating a bare bones working dashboard with placeholders for visualizations. I also updated Google Slides with details of technologies used for the dashboard and descriptions of its interactive element. We decided on potential databases, machine learning models, visualizations for the dashboard, and presentation type together during a weekly 30-minute sync up before class that was established as well as discussions during class.
- *Segment 3*: I transformed our data which was in a .csv format to 3 separate dictionaries. I concatenated these dictionaries into one single dictionary, that is I then converted to a .json file. This .json file is used to populate the dashboard for the patient data visuals. I researched various CSS and Bootstrap components to edit 'Initial Findings' segment and the 'Machine Learning Outcomes' segment of the website. 
- *Segment 4*: Worked on finalizing visualization dashboard with visualization input from Shane and Janell. Included video of dashboard working in the Slides. I was responsible for the dashboard files upload on the main branch.

My greatest personal challenge was to build the initial pieces of the dashboard. In the first week, collaborating with the rest of the fantastic group members helped a lot as it helped me crystallize the direction this project will be taking in the future. Keeping clear communication between group members, keeping track of tasks, and planning future milestones, we were able to have a clear view of the path we had to follow to finish this project.

## *Team Assessment*

Below is the summary of roles for each of the other team members had for each segment

- *Segment 1*:
    - Shane: Created the project repository, and a google doc for collaboratory project notes. We were each responsible for creating our own branches on the main github repository. Shane also cleaned the .csv data used for our project.
    - Amit & Janell: Tested various machine learning models
- *Segment 2*:
    - Shane: Created the SQLite database in jupyter notebook, created 2 tables, and performed a join. He also created the Google Slides updated his progress on the Google Slides
    - Amit: Continued to focus on machine learning and update his findings on the Google Slides
    - Janell: Edited the contents of the Google Slides, technology.md, communication.md and ReadMe.md.
- *Segment 3*:
    - Shane: Generate machine learning based visualization for the dashboard.
    - Amit: Finalized machine learning model, and give information to Shane to generate visulaization for dashboard.
    - Janell: Continue to work on Presentation Slides and generate initial analysis visualization for the dashboard. She also updated ReadMe.md and technology.md files.
- *Segment 4*:
    - Shane: Responsible for main branch, data clean-up files, machine learning data visualization, and all database files.
    - Amit: Responsible for all machine learning files for dasboard.
    - Janell: Responsible for all .md files, initial visualization, and Google Slides

Most of the communcations were handled during our breakout rooms and during a 30-minute sync-up call before class. During our discussions we set clearly defined expectations of each other for the week. We used a Google doc to start planning the project and Slack to message each other and share information.  The most challenging aspect was to align our schedules to meet up since all members werent in the same time zone. But with compromise we were able to come up with a common meeting time to update each other, and assign future roles while working on the project individually during class and outside of class. The team members were amazing and with clear expectations and communications we never really had a conflict.

The biggest advice for this project thus, is to have clear communication methods set at the very beginning of the project that defines roles for each segment and also sets a meeting time for all team mebers to update each other frequently each week so they stay on the same page. This was our strength as a team and it allowed us to exacute the project smoothly.


## *Summary of Project*

As a team we were interested in the effect of lifestyle choices on a health outcome such as  lung cancer so we looked at a pre-encoded lung cancer patient dataset (as an interactive view: the user can select patient ID on our HTML/Javascript dashboard to view lifestyle scores, symptoms scores and cancer severity). We hypothesized  **Alcohol Use, Smoking, and Passive Smoking** as the top 3 factors to predict cancer severity based on  our initial data exploration (charts displayed on dashboard as images). Out of 6 possible Machine Learning models ran, we saw that the  **SVM Machine Learning Model** was the best model for predictions with (~88% accurate, bubble chart with feature importance of lifestyle habits from each ML model is displayed on dashboard as an image). However, other possible ML models like Multinomial Logistic Regression can also be run in the future in a search for a more accurate model for predictions. 

Technologies in our project:

- Data clean-up
  - Python, pandas
- Database
  - SQLite
  - Python
- Machine Learning
  - Supervised Learning
    - Logistic Regression (LR)
    - Support Vector Machine (SVM)
- Dashboard
  - Javascript, d3.json
  - Bootstrap
  - CSS
  - HTML
  - Python
