## Hackathon workflow

- First, we decide which task we're taking up, and sit together with our task-mates.
- In the registration form it is mentioned that you are consenting to being assigned to a team by the event's co-ordinators. So be ready for that. Our tasks are multi-layered, so we want to have heterogenous teams with different competencies.
- Tasks are [defined at length here](https://github.com/opendatapune/Problem-Statements/wiki). At bottom of each task there is a link to the issue in the same repo created for it. Over there you can post that you are starting work on so and so aspect of this task (be precise!).
- Even if others have posted, more people can still post.
- Post questions if you get stuck at the same issue.
- When your work is done, post it online in whichever way is most suitable, and post the link at the issue along with details of what you have done.
- The tags assigned to the issue will be updated by the organisers if the work checks out.


## Getting Started with lab's terminal
- Start it up in ubuntu. (Prefer windows? You're on your own!) You should see a "opendatapune" zip file or folder in your home folder. If it's a zip file, extract it to home folder so that the path is ~/opendatapune

### Getting the Internet working
- If you're not from COEP, ask a COEP student on your team to put in their credentials to get the internet working.

### Working in python 3
- If you're planning to work with python 3, then this `opendatapune` folder contains most of the packages you'll need as a virtual environment. You can activate it in your terminal by the command:  
```
source ~/opendatapune/bin/activate
```
- Now in that terminal you can install packages via `pip install package` - this wasn't possible in the default system environment. But we have most packages covered, so test first.
- We advise you work with Jupyter Notebook, where documentation and code and output are all together in a browser window, and the visualizations are easily rendered. Type in `jupyter notebook` and in some time you'll see it open a tab in your browser. Create a new python3 notebook and you're all set!

### Starting OpenRefine
- In the `opendatapune` folder there should be an `openrefine` folder. Get your terminal path into it, and type:  
```
./refine
```
- That should do it.. in a few seconds OpenRefine should start up in a new tab on your browser.
- You can customize with command line options : increase RAM usage to handle bigger files (the lab systems have good amount of memory), or change the port number if there's a port conflict. Here's a customized openrefine launch command:  
```
./refine -p 3300 -m 3000m
# starts openrefine on port 3300, and using 3gb ram
```
- Check out [their wiki for more](https://github.com/OpenRefine/OpenRefine/wiki/Installation-Instructions).

-----

[see this page on github](https://github.com/opendatapune/opendatapune.github.io/blob/master/Instructions.md)
