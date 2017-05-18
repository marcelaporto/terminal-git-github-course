# <dev/Mission>
## Git & Terminal Exercise
*Instructor(s): Marcela, Yaritza | Expected Length: 1 Session*

## Show everyone who's boss

You just got hired as the CTO of Nasa. They asked you to do some things directly with the terminal, because the want to be more productive and look fancy.

You will need to
1. Enter your terminal
2. See if you have git installed: `git`
3. If not, let's download git so we can start to kick ass in space.
* [Download Git](https://git-scm.com/downloads)
4. Now that we have set this super secret space tool, people need to know who is working at this terminal. They need to know it's the boss. Let's set your name and email.
Unfortunately, that wasn't in your 'How to be Nasa's CTO' course. Good thing you have the internet! Let's start with these to links, but feel free to look up in other places that make more sense to you:
[Setting you name in Git](https://help.github.com/articles/setting-your-username-in-git/)
[Setting you email](https://help.github.com/articles/setting-your-email-in-git/)
*Don't forget to put the same email we are putting in Github!!*


## Navigate inside your computer
Now that you have set up Git, your super secret space tool, let's navigate to somewhere where you can easily access your files, also known as **your computer's Desktop**.

Be sure you know where you are! What was that command that prints the current path/directory again?

## Create NASA HQ - San Francisco

Now that you have your fancy super secret tool and you are in a manageable place to create awesome stuff, let's get to the duties of being the CTO of Nasa, because with great power comes great responsibility.

You were summed to open a new NASA HQ in San Francisco. Good thing, in this reality we are in, creating a NASA HQ is as easy as generating a new directory on your desktop.


## Create the Astronauts and Equipments Section in NASA HQ
You are directly responsible for bringing in the Astronauts and Equipments of the new NASA HQ as well.

Let's create a directory inside NASA HQ for Astronauts, and one for Equipments.

### Add the Astronauts
Time to do some recruiting! You found some young souls with a lot of potential to go to NASA, since Mars is kind of 'the new thing'.

They are not going to Mars, but you don't need to tell them that yet.

Let's add those Astronauts to you Astronauts directory - in this world, people are just files in `.txt` form.

## Keep a log of what is happening
You feel like your productivity and awesomeness has become a curse, since it's hard to keep up with everything you've been doing. Time to create a log of your deeds, so you can show off later.

1. First, let's make sure no one else is doing the log already: `ls -a`
2. If not, let's start this!

### Add existing things to Git

1. Understand the status of your log `git status`
2. Add
3. Commit

## Add favorite color in astronauts files

It is crucial that we understand's the Astronaut's favorite colors, so you can decide the next color for their outfits when you send them to space.

Open the file for each astronaut, add their favorite color, and use git workflow to add and commit.

## Add Cali branch
You want to create some new equipments in your HQ, so NASA can have a more California feel to it.

It is still in test phase, so you don't want to merge it to the HQ yet. You will need to create a branch to test out some stuff, before it becomes official.

Create a `california-features` branch, and, in the Equipments repo, add the following files:
- Outer space yoga mats
- Kale for Astrounauts
- Coffee Shop Space Station
- Any other ideas you have

Add and commit your changes, and then merge it to master.

## Connect to outerspace station
It's time to connect your HQ to outer space, and send some astronauts!! This is going to look so bad ass on your resume man!

Let's do this:

1. Set up your Github Profile
2. Clone the [space station](https://github.com/marcelaporto/space-station)
You will be asked your email and password: it's classified info you are pulling, space stuff!!
3. Create a new branch: `sf-astronauts`
4. Move the Astronauts from Nasa HQ to the space-station/astronauts repository.
You need to make some executive decisions. Only some astronauts are allowed to go, so you cannot move the whole astronauts repo
> When in doubt, use `pwd` to remember where you are! Write full paths and, if you feel confortable, use `..` to navigate through higher folders in your computer

5. Add and commit your changes
6. Push to origin **with your branch name**
7. Create a Pull Request

## Send NASA HQ info to your Github Account
People need to know what you've been up to, because it's pretty awesome. Since Facebook and Instagram are basically dead, what you really care about is sending your accomplishments to GitHub.

You are not an expert on it, good thing Github has got you covered! Create an empty repo on you github profile with the name of NASA HQ, with nothing in it. It will show you the instructions to **push an existing repository from the command line**.

Since you created the NASA HQ locally, in your computer, the file does not know what origin it needs to go. **Don't forget to add origin**.

## Last thing: Fork this repo so you have the info we talked about at your fingertips!

https://github.com/marcelaporto/terminal-git-github-course
