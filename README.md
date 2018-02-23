# Name of Student: Sam Kissee

## Name of Project: Konnexion Music Festival App

###Project’s Purpose or Goal: Allow offline access to schedule and activities

color code #44fbbb

s

List the absolute minimum features the project requires to meet this purpose or goal:

* Loading Screen
* Home Page With the weekends Music Schedule

What tools, frameworks, libraries, APIs, modules and/or other resources (whatever is specific to your track, and your language) will you use to create this MVP? List them all here. Be specific.

* React Native
* Possibly Ignite or Another CLI

If you finish developing the minimum viable product (MVP) with time to spare, what will you work on next? Describe these features here: Be specific.

* Workshop Schedule Page
* Live Update Schedule Page - Shows what is happening currently, what just happened, and will happen next.
* Artist Page - List of Artists and their Bio



We'll use these steps to plan and develop our capstones over the next two Fridays.

1. Break the UI into a Component Hierarchy
  Project Layout MVP:
    Home/Loading Screen with enter button to enter into the app:
    Next Screen Shows The Full Weekends Music Schedule on one page.

  Project Layout past MVP:
    Home/Loading Screen with enter button to enter into the app:
    Next Screen Shows a menu with options to look at artists/ workshops/ or schedules
      This Home screen will show what artists the last artist to have played, who is playing now, and who is playin next. <- This will only work on weekend of event if all goes well.

    Artist Page will be a grid layout of each artist. Picture, name, short bio, style of music, when they play.

    Workshop will be a grid layout of all the workshops in order of when they will be happening, they will have a brief description of what the workshop is about and who is teaching it and when and where it will be happening.

After outlining a layout/design you're happy with, sketch out the corresponding component structure in a diagram.

Add the visual representation of your layout/appearance and a component tree diagram to your repo before advancing.
2. Build a Static Version
Using your component tree diagram, build a static version of the app using only functional components. Hard-code any data you plan on eventually receiving from APIs, databases, Redux, or other sources for now.

Before advancing, add a link to your static site's repo to your planning repo.
3. Identify the Minimum (But Complete!) Representation of UI State
Now that your application is more than just user stories, carefully consider how you'll organize its state. Outline what state slices you'll need, and how they'll be structured. Be careful here; incorrectly structured state can later lead to tricky issues.

Add a list of state slices your application requires and how they will be structured to your planning repo before moving to the next step.
4. Identify Where State Should Live (AKA Lifting State)
Then, determine where you'll lift this state. After that, refactor your tree of static components to include these state values in the locations you identified. Remember, even if you'll later use Redux the rules of lifting state still apply.

Before advancing identify where your state will be lifted in your planning repo. You could do this in a list, by adding indicators to your component diagram, or any other format. Then, add that state to your static project.
5. Inverse Data Flow (ie: basically everything else)
What the article calls "inverse data flow" is actually the process of integrating all other backend/business logic into your UI. If you've followed these steps carefully, your UI will be ready for this.

But do not tackle this until all previous steps are complete! It may be tempting, but this process exists in this order because it's decidedly the most intuitive, efficient way to develop React projects.

Also, keep in mind we don't expect you to complete your entire capstone before next Friday! You'll have all of week 5 to continue integrating "inverse data flow" and all other tools and features your project needs.
