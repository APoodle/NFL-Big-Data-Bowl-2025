<div align="center">
    <img src='https://operations.nfl.com/media/3577/big-data-bowl-transparent.png?mode=max&width=995' style='width:200px' />
    <h1>🏈 NFL Big Data Bowl 2025 🏈<h1>
</div>

### Overview 
NFL's Big Data Bowl is a yearly competition that uses their ['Next Gen Stats'](https://nextgenstats.nfl.com/) player tracking data to create actionable statistics. This year's comptetition focuses on movement before the snap of the ball. Players have 40 seconds after each play has ended to any substitutions, figure out formations and type play, and make any last adjustments. 

### My Current Progress
Right now, I am just looking around the data and seeing what Amon-Ra St. Brown was doing, apparently he has two rush plays that I am looking into.

Day 2: This is much more of a reading and seeing what is possible day. I am learning more about plotly and looking at past competitions winners to see how I should set up a notebook and what kind of questions I should be asking

Day 3: I found a book to read to get to understand more about the strategy of football called Take Your Eye off the Ball, might read this or find another book. Also got to make a more complex plotly graph.

Day 4: Cleaning up the notebook to be more concise, then I hope to find a way to include more plays than just one play at a time, I wonder if there is a way to create a heatmap...

Day 5: I was able to find a way to get it so every play in the game against the Commanders that led to an Amon-Ra St. Brown reception start at an origin (0,0) so it looks a little like this:

![image](https://raw.githubusercontent.com/APoodle/NFL-Big-Data-Bowl-2025/refs/heads/main/pics/Demo%20v.85.png)

Day 6: Was finally able to flip the plays going to the left, so that all plays look like they are going to the right (no idea if I should flip it upside down or not yet). Now I can worry about making a heatmap.

Day 7: Heatmap did not take so long to figure out, the next thing I need to do is compare it with the plays Amon-Ra St. Brown did not get the ball or failed to catch the ball.

Day 8: With limited time today, I decided to just take it easy and just get to learn Kaggle's markdown capabilities. I currently have an image at the top and made a nice little markdown box with the main title.

Day 9: Finished the heatmaps, finished looking at average time before pass was made to St. Brown. Now I am going to be cleaning it up and making the notebook look nice. 

Day 10: Currently sstruggling on what else I can analyze before the snap to make any valuable insights, I have some ideas like seeing what formations lead to Amon-Ra St Brown receptions, or even what formations fail to prevent the sun god himself from getting a reception

Day 11: Was busy watching the games this week, which led me to realize that a lot of plays from the Detroit Lions seem to have Amon-Ra St. Brown go across the field... I wonder why.

Day 12: I have officially reached a stopping point at my creativity to figure out what to do next, so I am going to look at the past winners, read the book and see what inspiration I can get from there. I will be taking a break from constantly updating this Kaggle Notebook from what it seems like.

Day 13: After reading the book, I am going to look into how Tight End formations lead to the possibility of pass plays towards Amon-Ra St. Brown/other receivers. Could also look into Running Backs. I also want to implement where they are facing to see if them looking elsewhere other than the QB leads to more running plays or not

Day 14: Finally getting back around this, I still have not finished the book (though I am reading it a lot currently), but it has given me some ideas. I can look at the offensive linemen's position and orientation to help aid if the play is going to be a rush or a pass. Using these two columns:

o: Player orientation (deg), 0 - 360 degrees (numeric)
dir: Angle of player motion (deg), 0 - 360 degrees (numeric)

I feel like right now, my best chance is to calculate the probabilities of pass plays vs rush plays depending on the player movements and orientation. I would need to probably use the movement of the quarterback as well, but right now I still plan on focusing on Amon-Ra St. Brown

Day 15: Finished the book, my current thing to analyze will continue to be measuring orientation to see likelihood of run play or pass play.

Day 16: I analyzed two plays of Penei Sewell and there is a difference in orientation if its an Amon-Ra play or not, again it is only two plays, but right now I am seeing a problem with going all the way with this right now since I have to make sure I get the plays between line set and ball snap...
