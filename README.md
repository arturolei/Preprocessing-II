# Preprocessing II: Fun Bus Website

Fun Bus is a travel agency looking for some help on their website.  They want a new navigation, new header, and new buttons on the home page. They also want a mobile version of their site styled.  Use your preprocessing knowledge to accomplish their tasks.

## Task 1: Set Up The Project With Git

* [X] Fork the project into your GitHub user account
* [X] Clone the forked project into a directory on your machine
* [X] You are now ready to build this project with your preferred IDE

## Task 2: Set up your preprocessor
* [X] Verify that you have LESS installed correctly by running `lessc -v` in your terminal, if you don't get a version message back, reach out to your project manager for help.
* [X] Open your terminal and navigate to your preprocessing project by using the `cd` command
* [X] Once in your project's root folder, run the following command `less-watch-compiler less css index.less`
* [X] Verify your compiler is working correctly by changing the `background-color` on the `html` selector to `red` in your `index.less` file.
* [X] Once you see the red screen, you can delete that style and you're ready to start on the next task

## Task 3: Import LESS Files

* [X] Navigate to your `index.less` file. Notice the file is blank.  In order for you to see the styles for this project you must import them in a certain order.  That order is as follows:

1. `variables.less`
2. `mixins.less`
3. `reset.less`
4. `global.less`
5. `navigation.less`
6. `footer.less`
7. `home-page.less`


## Task 4: Desktop Updates Needed
* [X] Review the [desktop design file](design-files/fun-bus-desktop.png).  Notice the navigation, header, and buttons at the bottom of the page are missing.
* [X] Navigation: Use the `navigation.less` file for all your navigation styling
* [X] Main Header: Use the `home-page.less` file for the header styling.
* [X] Buttons: Create a parametric mixin that can create the missing buttons in the design file. Use the `mixins.less` file to create your mixin.


## Task 5: Mobile Updates Needed
* [X] Use escaping to create a variable named `@mobile` that contains this value: `(max-width: 500px)`.  Use the `variables.less` file to house your styling.
* [X] Review the [mobile design file](design-files/fun-bus-mobile.png). You will see several design updates that need updating. 
* [X] Match the design file at `500px` as well as you can 

## Stretch Goals: 
* [ ] Create an animation mixin using parametric mixins
* [ ] Introduce a form with inputs allowing users to select a vacation package and a submit button at the bottom of the page. Introduce inputs for name, email, phone number, and an area for them to leave special instructions. 
* [ ] Style the site to look good at all sizes, not just desktop and phone

## Notes:

## Pull Request Link:
[https://github.com/arturolei/Preprocessing-II/pull/1](https://github.com/arturolei/Preprocessing-II/pull/1)

### What I Accomplished:
- I completed the MVP for Preprocessing II and read the TK. I also studied on my own mixins and functions in less. 


### What I need to finish before tomorrow:
- I need to prep for the sprint and review any potential weakpoints I have and revise how I approach design projects (focus less on the details and more on the gestalt or the bigger picture)
- I want to go back and refactor a lot of my old projects before

### Breakthroughs/Blockers
- I am beginning to get the hang of breaking down what would have been a long, barely readable CSS into readable components. I still need to get used to using variables and employing mixins actively, not just because the assignment asks me to. I understand the utitility; it's more about the strategic use thereof.
- The design file was unclear with regard to what the bottom border of the header section was supposed to be. However, I think this reflects "real life" more, where design might not be clear-cut; sometimes judgment calls are needed. 
- I keep forgetting the viewport bit in the <head>

