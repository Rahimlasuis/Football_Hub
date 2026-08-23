# Football_Hub
It is a website for football from team information, match stimulations to foot ball quiz and other stuff
Football Hub
Football Hub is a fully functional and detailed websites about websites
It features League tables, matches, players, and many more. 
It's literally a website that you can use for things you'll normally do on multiple different websites as long as it's about football.
Football hubs doesn't just displays infos about football.
It also has some responsive features like club histories and quizzes with leaderboards, high scores and reward features. 

The components I used were basically HTML, CSS and JavaScript. Although for some weird reasons I usually prefer to do all the coding in an HTML file instead of creating different JavaScript and CSS file then linking it. 
<img width="693" height="348" alt="table" src="https://github.com/user-attachments/assets/db90d924-c6b1-4259-9712-5c7d650938cc" />


Features in details 
The first feature of this website are the tables for the 5 most popular leagues,
Not just league tables but also tables for highest goal scorers, highest assist and recent matches
I simply used the basic html table feature to achieve all of this
it also has a little info about the champions league games. 
The only problem is that many of this information would have probably been outdated by the time it is being reviewed. 

They are also some links to other websites for some news that mind did not contain.

Below the tables are various club cards of about 30 plus professional clubs. 
These cards contained the clubs name and logo designed by CSS. 
I was able to neatly arrange the cards side by side with the CSS grid arrangement features
When the cards are clicked it directs us to a page for that particular club.
The club's pages contains their current position in the league and also their players in a table with basic info like name,age, position and jersey number.

below the club cards is a button that leads to a player sections. The players sections has player cards with stats, positions, ratings and national team.
users can click on some buttons above to filter the players for displaying legends, stars and young stars. 
At the very top of the page there is a button that returns back to the home page

Then we have the most important and responsive features 
The Quiz features
They are basically two types of quiz one for a general foot ball quiz and the other for clubs loyalty test with cool features like avatar and wallpaper gifts and leaderboards. 
A button takes us to another homepage were that are different cards for different club's quizzes. 
once we click on a particular club it takes us to the main Quiz page of the club card we clicked.

<img width="498" height="399" alt="quizone" src="https://github.com/user-attachments/assets/624fc160-af21-413f-ac07-309796a97691" />

we answer the displayed questions and each options usually have points, some questions are actually relative, for instance a question that ask for your mood when you club wins or lose. 
also some options have points but are still wrong probably close to the answer. 
They are next and previous buttons present and a submit button at the end. 
After the submit button is clicked the result button appears. 

Basically for the questions I created a variable in the JavaScript code for all the questions and then I used . displaytext to instruct it to display the questions and display another once the next button is clicked. 
another smart way I was able to achieve this was buy creating some sort of frame for the quiz or should I call it a template. once I was sure it did everything I wanted perfectly I just copied and pasted the code into the main clubs page and added the questions I wanted to add. 

In the result screen there is an empty div I thought looked cool, a reward section that unlocks depending on score a high score and reset feature and a leaderboard with 6 bot with static scores. 
depending on your score .style.order would automatically fit you into your slot the leaderboard.
<img width="554" height="473" alt="lb1" src="https://github.com/user-attachments/assets/6c242981-88d2-47dc-9bc7-72547c27706e" />

depending on your score you unlocked rewards also include cool avatars and wallpapers. 
<img width="1366" height="768" alt="reward_pack" src="https://github.com/user-attachments/assets/ef3b908f-401d-457d-8b91-03d3372174c5" />
<img width="729" height="768" alt="result" src="https://github.com/user-attachments/assets/19410142-9d4b-4997-80f5-31accf11762a" />

The second quiz is the general quiz it's not as compact as the previous one I talked about but there is some sort of label before yo start the quiz allowing you to pick the difficulty and the number of questions you want.
then at the end you see the number of questions you got right. it's not in percentage like the clubs quiz and there is no reward or leaderboards.
<img width="397" height="445" alt="quiztwo" src="https://github.com/user-attachments/assets/fd871421-7f43-4194-809c-6a81a36a7f0c" />
Then the club history feature. 
At the end of the website homepage is a button that leads to a page where there are different club cards similar to the previous bunch of home cards.
but this time around the cards leads to a page that tells a little story about the club from when it was found till present. Each detail in the history appears in boxes with date and title.
Each box appears below and on the opposite side of the previous one and as one scrolls the boxes smoothly appear.

![Uploading lb1.jpg…]()

<img width="733" height="757" alt="history" src="https://github.com/user-attachments/assets/4cadfa4c-2903-4336-880c-db2fccfaf442" />
