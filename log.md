# 100 Days Of Code - Log

### Day 1: February 17, 2022 

**Today's Progress**: Worked on sorting through seed data using SQL commands in the CLI

**Thoughts:**: Really enjoyable; learned quite a bit in regards to database query. This is my first SQL experience, so far everything else "backend" has been through MongoDB.

**Link to work:** https://git.generalassemb.ly/ted-t/sql-lab My work is in: /Carmen/find_carmen.sql and /NFL/nfl.sql


### Day 2: February 18, 2022 
**Today's Progress**: Worked on python basically all day; specifically working on functions in Javascript first, then re-writing them in python. Did some code wars games and then finished the lab linked below.

**Thoughts:**: Python was the first language I learned when deciding to become a developer; and it was really fun revisiting if after 9+ weeks of writing nothing but javascript. Have a good weekend everybody!

**Link to work:** https://github.com/tatcn8/python_practice-/blob/main/python_cuckoo.py


### Day 3: February 19, 2022 
**Today's Progress**: Practiced writing functions in both Javascript and Python. Kept it to mostly basic functions (it is Saturday after all) and all the work was found on Codewars. There is an examply snippet (in both JS and Python) below.

**Thoughts:**: Continuing to enjoy playing with Python. Amazed at how quickly the muscle memory returns after taking a few months off from it. 

**Link to work:** 
Python:
def update_light(current):
    if (current =="green"): return ("yellow")
    if (current =="yellow"): return ("red")
    if (current =="red"): return ("green")

JS:
function updateLight(current) {
  if (current === 'green') return 'yellow';
  if (current === 'yellow') return 'red';
  if (current === 'red') return 'green';
  

}

### Day 4: February 20, 2022 
**Today's Progress**: Built out the front end of a budgeting app. Going to eventually build out the backend using MongoDB to be able to track my expenses over time.

**Thoughts:**: React has been a very familiar front end platform. Really this app was a matter of installing the right dependencies (reactstrap, node) and then writing some basic Javascript for the form functionality. I will post a link when it's finished.

**Link to work:** I will post a Git link when I am finished.

### Day 5: February 21, 2022 
**Today's Progress**: More Python today, worked on a bootcamp assignment for a guessing game involving the state capitals.

**Thoughts:**: Happy President's Day! The hardest part of this coding challenge so far has been targeting list elements from a python dictionary; but once I figured it out it wasn't too bad. Need to work on a for loop so that the game can be played continuously without having to click "play" each time.

**Link to work:** Will post Git Repo when finished :)

### Day 6: February 22, 2022 
**Today's Progress**: Finished the python state capital guessing game. There is one small bug due to the way I am running the for loop, but ran out of time to figure it all the way out. Going to be working on Python all day today.

**Thoughts:**: Had a lot of fun with this one; ran into a lot of blockers and slowly overcame them. Found indentation matters in Python quite a bit. Like I said, one small bug remains, but for the most part the game is playable.

**Link to work:** [State Capitals Game](https://git.generalassemb.ly/ted-t/python-state-capitals)

### Day 7: February 23, 2022 
**Today's Progress**: Worked on Django installs as well as some more python. Worked specifically on the .super() command to pass functions to subclasses.

**Thoughts:**: Still enjoying python but deep down missing javascript. I also started a side project using React/JS and am just now realizing that I probably started that project due to some frustration with python.

**Link to work:** Not much to show today, maybe I'll link my side project tomorrow.

### Day 8: February 24, 2022 
**Today's Progress**: Working on Django for backend data. This is my first experience with a relational database (a decent amount of experience with MongoDB which of course is non-relational). Have successfully deployed two Django backends, and did seed data into both (one is linked below). Also, making good progress on my side project (the ReactJS budgeting app).

**Thoughts:**: Django is interesting. Quite a bit of work to get a backend built, but the UI is REALLLLLY nice compared to MongoDB. Also the SQL data is just easier to look at. Love the built in UI/functionality so far.

**Link to work:** [Deployed book app](https://git.generalassemb.ly/ted-t/django-api-lab) There is some basic seed data in this app.

### Day 9: February 25, 2022 
**Today's Progress**: Continuing to plug away at Django programs, enjoying that so far. Also, built my first Ruby program (which is special because for my work at Brand New Box I will be writing exclusively in Ruby)...That simple file is commented out below.

**Thoughts:**: I read about 65 pages of Ruby documentation from the "Ruby is fun" github...Really enjoying that documentation so far. Django is pretty cool in that it corrects a database plus its own UI.

**Link to work:** Here is my SUPER simple (but first ever) Ruby program!

puts "Your age?"
age = gets
puts "=" * 80
puts "Your age is " + age


### Day 10: February 26, 2022 
**Today's Progress**: Didn't write a whole lot of code today (it is saturday...) but did read quite a bit of Ruby documentation. 

**Thoughts:**: .chomp makes alot of sense. After a "gets" input, the user does press 'enter' so it would make sense that the string contains a new line...    .chomp prevents the line break and I think that's cool.  

**Link to work:** Not much to show today :) 

### Day 11: February 27, 2022 
**Today's Progress**: Ruby Ruby Ruby    

**Thoughts:**: Similar to yesterday, did not code a ton today. But continued to work through the Ruby manual and still enjoying it. Spoke with a tech friend who reccomended learning some "Go" and did a bit of reading on that as well.

**Link to work:** Not much to show; will be a jammed pack week of coding this coming week!

### Day 12: February 28, 2022 
**Today's Progress**: Spent the morning learning userAuth with Django and s3/AWS buckets for image uploads. Spent this afternoon working on mini project (for class) with a Django backend and a React frontend.

**Thoughts:**: Everything went well in regards to fetching the Django data, everything sucked in regards to deleting the Django data. I tried using axios.delete and dynamically passed in the item's ${id} via props, but still couldn't get it. I will eventually.

**Link to work:**: nothing deployed today.

### Day 13: March 1, 2022 
**Today's Progress**: Worked on Python and Django app's all day. Built a little financial data/budgeting tool and it is linked below.

**Thoughts:**: Included user authentication on this project which was really easy using Django. (Way easier than Mongo) I was unable to get it deployed to heroku, which is super lame, but I just ran out of time. It was giving me a pyscopg2 error, which was literally installed and I messed around with it for way too long. 

**Link to work:**: https://github.com/tatcn8/python_mini_project

### Day 14: March 2, 2022 
**Today's Progress**: Built my first Ruby on Rails app (link to my git Repo below). Really pleased with the first day of exclusive rails

**Thoughts:**: Went well. Honestly the hardest part was getting the installs made. Had to go through ASDF to get the most updated version of Ruby, Node, and Yarn installed. Was amazed at how quickly the CRUD functionality and user auth was implemented.

**Link to work:**: https://github.com/tatcn8/rails_blog_demo

### Day 15: March 3, 2022 
**Today's Progress**: Built another Rails app, this one is a budgeting tool. I have not gotten to styling yet, so as of now, it is pretty darn ugly.

**Thoughts:**: Really enjoyed today. Started a ruby specific udemy course. Felt like I got the hang of building a CRUD rails app, sort of got the boilerplate down if that makes sense. So far, so good.

**Link to work:**: https://github.com/tatcn8/rails_budget

### Day 16: March 4, 2022 
**Today's Progress**: Worked through some more of the Ruby udemy course that I started yesterday. Spent about 6 hours on that, and then the rest of the time came up with a lightning presentation for php & laravel for bootcamp.

**Thoughts:**: Ruby is cool. I have enjoyed re-learning "the basics" (data types/objects/classes etc) in this udemy course.

**Link to work:**: nothing today bub

### Day 17: March 5, 2022 
**Today's Progress**: Continued to chip away at my Ruby Udemy course. Going to really ramp up to 10 days of hardcore Ruby on Rails programming beginning on Monday 3/7.

**Thoughts:**: Learned alot of object methods today; really enjoying ruby :)

**Link to work:**: nothing today bub

### Day 18: March 6, 2022 
**Today's Progress**: did not code at all today

**Thoughts:**: BUT I did go to church and then fished all afternoon

**Link to work:**: nothing today bub

### Day 19: March 7, 2022 
**Today's Progress**: did not code at all today

**Thoughts:**: Began my bootcamp's capstone project which is going to be a financial data app (that I mentioned several days ago) As of now, it is super ugly, but I will get around to styling it once all the functionality is there. As of now, I have past data inputs/rendering as well as projected data input/rendering. The site is currently fully CRUDful.

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails

### Day 20: March 8, 2022 
**Today's Progress**: All kinds of ruby on rails today; continuing to bang out my financial data project; pretty happy with today's progress.

**Thoughts:**: Added user authentication via Devise; which was a new technology to me. It has been downloaded almost 90 million times on RubyGems. It definitely was not intuitive, but I found several youtube videos (plus stack overflow) which helped guide me through. 

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails

### Day 21: March 9, 2022 
**Today's Progress**: Continuing to work on my Rails Financial app, got alot done today including a Bootstrap Navbar and some other styling/clean up things.

**Thoughts:**: The site is looking good; need to add some more functionality, but overall I am very pleased with where this thing is.

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails

### Day 22: March 10, 2022 
**Today's Progress**: Continuing to work on Ruby on Rails finance app; did an awful lot of styling today, also worked quite a bit on functionality/basic ruby functions within the pages of the app.

**Thoughts:**:First experience with bootstrap, so as you can imagine quite the learning curve. On the whole, really enjoying it.

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails

### Day 23: March 11, 2022 
**Today's Progress**: Continued to work away on the finance app; got some more styling done and the thing is really starting to look nice.

**Thoughts:**: I will not be coding this weekend :)

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails

### Day 24: March 12, 2022 
**Today's Progress**: Out of town with wife :)

**Thoughts:**:

**Link to work:**: nope

### Day 25: March 13, 2022 
**Today's Progress**: Out of town with wife :)

**Thoughts:**:

**Link to work:**: nope

### Day 26: March 14, 2022 
**Today's Progress**: Deployed website to Heroku! (not going to share it today, because I have some extra stuff to add tomorrow)

**Thoughts:**: Very excited to continue working in rails

**Link to work:**: https://github.com/tatcn8/finance_data_on_rails