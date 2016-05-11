## Why?
- You will provide your peers with valuable feedback for their cornerstone project.
- You will receive said valuable feedback from **two** peers as well - making your cornerstone project that much better.
- You will gain insight into issues you might have on your own project.
- You will learn how to provide a semi-formal code review. Code reviews **will** be part of your job, its important to learn how they work.


## Guide to giving peer feedback

### Forking the project and preparation:
- 1. Fork your peer's repo into your github account.
- 2. Create a new ```peer_review.md``` file on **your peer project fork**. 
- 3. Copy the contents of **this** file and **paste** them into ```peer_review.md``` file you created on **your fork**.

### Creating peer review pull request:
- 1. Now you should be able to create a **pull request** from your fork back to your peer's original repo.
- 2. Title the pull request with: ```Peer review: Your Name```.
- 3. In the comments section, copy each question from below and answer it!

### Questions to answer:
##### 1. Does the project appear to meet the technical requirements? **Write up one sentence on your findings and give a score 0-3.**
- Is your peer making API calls, using SDK's/third-party libraries?
-Yes, he rely's mostly on yelp for his content.  
- Is your peer making use of Services? If so, are they offloading long tasks to a separate thread, i.e. AsyncTask, Runnable, IntentService, etc.
- no services, retrofit makes call async automatically
- Is your peer making use of Fragments? If so, are they passing data from Fragment to Activity via interfaces? If not, why did absense of Fragments make sense?
- two frags, maps and tablayout. The tabLayout for school details  There is an interface to the yelpAPIprovider
- Is your peer making use of RecyclerView? If so, does it appear to be working correctly ( implementation and otherwise )?
- There is a class called FireBasePrescoop, that alludes to recylcerView in its comments,but it is minimally present right now. The recyclerView is in the mainActivity and displays the schools in a list
- Is your peer making use of some sort of persistent storage, i.e. Firebase or SQLite? If so, why do you think Firebase/SQLite was chosen? Could they have used one or the other instead and why?
- Same as last answer, a class called firebase but the firebase implementation takes place in the main activity. 

##### 2. Does the project appear to be creative, innovative, and different from **any** competition? **Write up one sentence on your findings and give a score 0-3.**
- Is your peer making use of proper UX patterns we learned in class? If not, what are they doing that is unconvetional or that might confuse a user ( you )?
- nothing confusing, basic flow is list of schools to tabbed fragments for the school infor categories from the SchoolDetails activity
- Is your peer making anything cool or awesome that you would like to note or applaud them on?
- Open Schools! Charter Schools! Bussing, integrate now! 2.5

##### 3. Does the project appear to follow correct coding styles and best practices? **Write up one sentence on your findings and give a score 0-3.**
- Are you able to reasonably follow the code without having anyone answer your questions?
- I followed the code well
- Are you able to make sense of what the code is doing or is trying to do?
- yes. 2.5 score

##### 4. Find two pieces of code of any size: one that is ```readable and easy to follow``` and one that is ```difficult to follow and understand```.
- What makes the readable code readable? **Be as detailed as you can in your answer, it can be challenging to explain why something is easy to undertand**
- mainActivity oncreate is nice and succinct, only 8 method calls! I like it
- What makes the difficult code harder to follow? **Be as detailed as you can in your answer**.
- Are these frgment_citations, etc layouts being used? Same with the mapFragment, is it implemented yet? I haven't been able to build the project, I think my studio is broke

##### 5. High level project overview: Take a look at as many individual files as you have time for
- Does this class make sense? 
- Does the structure of the class make sense?
- the main data model class is the preschool class, it's straightforward
- Is it clear what this class is supposed to do?
