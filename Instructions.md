[<- back to home page](https://opendatapune.github.io)

## Hackathon workflow

### Step 0: Zen mode
- Put your mobile on silent. _Shushh_.
- Repeat to self : All is well, All is well.

### Step 1: Get a task, join a team
- Decide (or be told) which task you're taking up, and sit together with your task-mates.
- In the registration form you have consented to being assigned to a team by the event's organisers. Be ready for that. Our tasks are multi-layered, so we want to have heterogenous teams with different competencies.
- Settle down in your seat, get your workstation or laptop up and running, get internet on. If you're not from COEP, get help from a student for net access.
- Tasks are [defined at length here](https://github.com/opendatapune/Problem-Statements/wiki). At bottom of each task there is a link to an issue created for it. Over there your team lead can post about what you're doing. (be exact and descriptive! "We will do this" nahin chalega).
- You can also browse through the tasks through the [issues section](https://github.com/opendatapune/Problem-Statements/issues) where we've tagged things as per their technical nature.
- If lost, go to the **Control Desk** where organisers will tell you what to do. But wait in queue because if you are lost then 10 others will also be just like you.
- Keep a lazy eye on the telegram group as well for announcements, but don't waste your time on it. We'll probably put the important announcements on the projector screen only.

### Step 2: Get busy
- As a team, go through all your datasets and plan. You can step outside the lab if you want to plan loudly. _(Shushh!)_
- **Parallel Processing** : If there is data cleaning AND analysis to be done (mostly the case), then work in parallel. Analysis people can take 10 rows, clean them quickly and start building their stuff, while data cleaning people work their way through the whole data.
- Start with simple and work your way up.
- Post questions at the issue if you get stuck. Keep the issue tab open and keep checking in to see if anyone's posted any useful updates.

### Step 3: Yay we did something!
- Pat yourselves on the back and give each other a silent high-five. (or step outside the lab if you want to celebrate loudly. _Seriously, shushhh!_)
- Write a `Readme.md` doc explaining what you've done and mention how you did it. (_No Submission without Documentation!_)
- Take screenshots if needed, post them on imgur.com or google photos or whatever and put their links in.
- Post your done work online in whichever way is most suitable : google drive, own server, own github repo - all mediums are welcome. At your task issue, post the link to your done work along with details of what you have done (team lead can post on behalf of team).
- Put up code files also if any. `.ipynb` notebooks are readable on github.
- Go to the **Control Desk** to inform the organisers.
- Take a selfie with your work and team and post in on social media with the hashtags : #opendatapune and #hackathon
- Give organisers some time to review your work. Confirmation or feedback will be posted to the issue by the organisers.

### Step 4: Next level
- Check out the task's wiki page again. 
- We may have posted more things that can be done while you were in Step 2 and 3.
- Repeat from Step 2.

### Step 5: Ab kya karein / Kuch aur karna hai yaar
- Approach the Control Desk.
- They will probably send you to the Mapping track, unless you proactively offer to take up something interesting. Remember the consent clause in registration form.
- _Just FYI_, certificates will be given to those who have stuck around from 2pm till 6pm and have some proof of work to show.

------

## Getting Started with lab's workstation
- Start it up in ubuntu. (Prefer windows? Valid, but you're on your own.) 
- You should see a "opendatapune" zip file or folder in your home folder. If it's a zip file, extract it to home folder so that the path is ~/opendatapune

### Getting the Internet working
- If you're not from COEP, ask a COEP student on your team to put in their credentials to get the internet working.

### Working in python 3
- If you're planning to work with python 3, then this `opendatapune` folder contains most of the packages you'll need as a virtual environment. You can activate it in your terminal by the command:  
```
source ~/opendatapune/bin/activate
```
- Now in that terminal you can install packages via `pip install package` - this wasn't possible in the default system environment. But we have most packages covered, so test first.
- We advise you work with Jupyter Notebook, where documentation and code and output are all together in a browser window, and the visualizations are easily rendered. Type in:  
```
jupyter notebook
``` 
- And in some time you'll see it open a tab in your browser. Create a new python3 notebook and you're all set!
- To get out of the virtual environment, type : `deactivate` on the terminal

### Starting OpenRefine
- In the `opendatapune` folder there should be an `openrefine` folder (or zip. Or [download it here](http://openrefine.org/)). Get your terminal path into it, and type:  
```
./refine
```
- That should do it.. in a few seconds OpenRefine should start up in a new tab on your browser.
- You can customize with command line options : increase RAM usage to handle bigger files (the lab systems have good amount of memory), or change the port number if there's a port conflict. Here's a customized openrefine launch command:  
```
./refine -p 3300 -m 3000m
# starts openrefine on port 3300, and using 3gb ram
```
- Check out [their wiki for more](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions), or see their videos on youtube. It's an awesome tool for data cleaning, use in conjunction with LibreOffice Calc.

-----

## Universal Note
In case of problems, **improvise**.  
Shift to another workstation, step out of lab with laptop to catch net signal, do something else, help someone else - make do and move forward.


[see this page on github](https://github.com/opendatapune/opendatapune.github.io/blob/master/Instructions.md)
