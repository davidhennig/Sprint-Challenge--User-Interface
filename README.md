# Sprint Challenge: User Interface and Git - Multi-Page Website

This challenge allows you to practice the concepts and techniques learned over the past week and apply them in a concrete project. This Sprint explored User Interface and Git. During this Sprint, you studied Semantic HTML, CSS Fundamentals, CSS Flexbox Module, and Git. In your challenge this week, you will demonstrate proficiency by creating a multi page website that has some missing HTML elements as well as CSS specificity problems that need to be solved. You will also create an additional web page that will be linked to from a navigation you will build.

## Instructions

**Read these instructions carefully. Understand exactly what is expected _before_ starting this Sprint Challenge.**

This is an individual assessment. All work must be your own. Your challenge score is a measure of your ability to work independently using the material covered through this sprint. You need to demonstrate proficiency in the concepts and objectives introduced and practiced in preceding days.

You are not allowed to collaborate during the Sprint Challenge. However, you are encouraged to follow the twenty-minute rule and seek support from your PM and Instructor in your cohort help channel on Slack. Your work reflects your proficiency in user interface and your command of the concepts and techniques in semantic HTML, CSS fundamentals, CSS flexbox module, and git.

You have three hours to complete this challenge. Plan your time accordingly.

## Commits

Commit your code regularly and meaningfully. This helps both you (in case you ever need to return to old code for any number of reasons and your project manager.

## Description

In this challenge, you build a missing header (navigation and image) on the home page, update some CSS styling on the home page, and create an additional page (About) which will link from the navigation you created.

In meeting the minimum viable product (MVP) specifications listed below, your web page should look like the solution screen shots of the home and about pages:

[Click here for the home page example](https://tk-assets.lambdaschool.com/39a49225-8ac9-43da-aa90-514fd60ae99a_sprint-challenge-ui-home-example.png)

[Click here for the about page example](https://tk-assets.lambdaschool.com/ede1bb1a-63ff-4801-8c02-3efa2f603190_sprint-challenge-ui-about-example.png)

## Self-Study Questions

Demonstrate your understanding of this week's concepts by answering the following free-form questions.

Edit this document to include your answers after each question. Make sure to leave a blank line above and below your answer so it is clear and easy to read by your project manager

1. If you were to describe semantic HTML to the next cohort of students, what would you say?

Semantic HTML is not necessary in order for the HTML to work properly. As far as the computer is concerned you could only write with <div></div> and have the computer understand what was going on. With semantic HTML, it gives the computer, and other programmers, context for what is going on. Now they will be able to differentiate a paragraph of text from an image, from a navigation link, from headline. Not using semantic HTML would be like having a conversation with somebody where you were referring to many different people within a whole group of people and you only used the word “they” to refer to any one particular person. Yes the words you are speaking make sense, but they provide no context for who you’re talking about. Now let’s say you’re a huge masochist and don’t care about the ease of use for computers or other people. You will still want to use semantic HTML as it makes the rest of your work easier in the long run. As you call back to the HTML in CSS, you’re work becomes more streamlined with the proper semantic HTML in place.

2. Name two big differences between `display: block;` and `display: inline;`.

One of the more obvious differences between display:block and display:inline is that display block will have the element automatically take up the entire width of the container that it’s in, while display:inline will only take up the width of the content. Another key difference goes hand-in-hand with the previous one, in that an element using display:block will always have its own individual line, while display:inline has the ability to share its space with other elements, because it only has a width as far as its content.

3. What are the 4 areas of the box model?

The box model acts like a shell, the nut within the shell being the actual content itself. Whatever you content is, be it text or an image or just about any other thing, it’s going to take up a certain amount of space on the screen. That would designate the size of the content. Surrounding that content is padding, which can have a variable width on all four sides. Surrounding that padding is the border, which can be used, or not, to show the edges of the padding and give the overall content a solid set space on the page. Further encapsulating that border is the margin, which acts as a buffer from other content away from the border.

4. While using flexbox, what axis does the following property work on: `align-items: center`?

Using “align-items:center” would cause all of the items to benter on the x-axis. Rather, the content would have equal spacing on the top and bottom.

5. Explain why git is valuable to a team of developers.

Git implements a lot of ideas that make a great tool for collaborative work. The most important one that we’ve seen so far is the ability for a team to work on a project together. Having where you can send live updates to a central location that multiple people can access seems like a baseline ability for a team to thrive. Git also keeps a record of every push that was sent, making it easier to look back on past work and try to focus in on where a problem may have originated, should one arise.

You are expected to be able to answer all these questions. Your responses contribute to your Sprint Challenge grade. Skipping this section _will_ prevent you from passing this challenge.

## Project Set Up

- [ ] Create a forked copy of this project.
- [ ] Add your project manager as collaborator on Github.
- [ ] Clone your OWN version of the repository (Not Lambda's by mistake!).
- [ ] Create a new branch: git checkout -b `<firstName-lastName>`.
- [ ] Implement the project on your newly created `<firstName-lastName>` branch, committing changes regularly.
- [ ] Push commits: git push origin `<firstName-lastName>`.

Follow these steps for completing your project.

- [ ] Submit a Pull-Request to merge <firstName-lastName> Branch into master (student's Repo). **Please don't merge your own pull request**
- [ ] Add your project manager as a reviewer on the pull-request
- [ ] Your project manager will count the project as complete by merging the branch back into master.

## Minimum Viable Product

Your finished project must include all of the following requirements:

### Home Page

[Review the provided design file for the home page](design-files/home.png). Notice the navigation and header images are missing.

- [ ] Build the HTML and CSS to create the missing navigation and header.
- [ ] Link the `About` navigation item to the [about.html](about.html) page

You will also notice there are 10 boxes on the home page that need background colors. Use this list below to correctly style each box:

- [ ] box1: `teal`
- [ ] box2: `gold`
- [ ] box3: `cadetblue`
- [ ] box4: `coral`
- [ ] box5: `crimson`
- [ ] box6: `forestgreen`
- [ ] box7: `darkorchid`
- [ ] box8: `hotpink`
- [ ] box9: `indigo`
- [ ] box10: `dodgerblue`

### About Page

[Review the provided design file for the about page](design-files/about.png). You have been provided the HTML wrapper, footer, and page content for the about page. Create the rest of the missing HTML and CSS to match the design file.

- [ ] Copy and paste your home page navigation and header into the about page
- [ ] Update the header image with the about page image
- [ ] Link the `Home` navigation item back to the `index.html` page.
- [ ] Build the rest of the about page layout to match the design

In your solution, it is essential that you follow best practices and produce clean and professional results. Schedule time to review, refine, and assess your work and perform basic professional polishing including spell-checking and grammar-checking on your work. It is better to submit a challenge that meets MVP than one that attempts too much and does not.

## Stretch Problems

After finishing your required elements, you can push your work further. These goals may or may not be things you have learned in this module but they build on the material you just studied. Time allowing, stretch your limits and see if you can deliver on the following optional goals:

- [ ] Build a page of your choosing from the navigation items. Come up with content and images that fit the theme.
- [ ] Introduce CSS animations to your site.
- [ ] Build a contact page and create a form with several inputs of your choosing
- [ ] Add responsive breakpoints to your code by using media queries
