# JKUAT Agges Website Challenge for 2021
The challenge is meant to conme up with a JKUAT AGGES website that will serve the club.This will ensure connection with Alumni and even easy naviagation to the Junior students

### This challenge is yet to be launched and Timelines put in place.

## Rules

Your submission will be reviewed by the committe heads. We'll take your experience level into consideration when reviewing.

We value quality over completeness. If you decide to leave things out, please call attention to it in your project's `README file`.

Our assessment covers the following areas:

-   A correct fork, branch and pull request from the main branch.
-   We will use github timestamp
-	Architecture 
        - How have you decided to structure your app? 
        - Is there good separation of concerns or things/pages are cluttered?
-	Code quality 
       - Are you following good coding practices? 
       - Is your code easy to follow and maintain? 
       - Is it testable? 
       - Is it transferable?
-	Correctness 
	   - Does your application work? 
	   - Does it meet the functional spec?
-	Technical choices 
       - Are your choices of libraries, packages, and tooling appropriate?

Bonus points:

-	Testing - Is there adequate test coverage?
-	UX - Is your project easy to use and understand?
-	UI -Is the User interface attractive to the viewer?


## Task
With the asssumption that you are using frontend framework of your choice create a new JKUAT AGGES Club website that will serve the club. 
- Kindly check out the following guidelines:
- You host the site on either heroku, netlify, github pages or the site of your choice.The proposed are free hosting services
- Perfomance and speed is essential
- The Website should be fully responsive

### Areas to redesign

**Home**

- [ ] Make it look like a landing site and as attractive as you can
- [ ] Remove unnecessary clutter
- [ ] Add pictures for various GEGIS and Spatial related stuff.You can link up with [Okomo on Twitter](https://twitter.com/okomojacob) or WhatsApp to provide you with Images and other assests.
- [ ] Remove navigation bar above the footer

**About**
- [ ] AGGES gallery to load efficiently
- [ ] A way of updating the gallery
- [ ] AGGES committee to be available.
- [ ] AGGES committee to have profile picture, current position, linkedin link and twitter link

**Events**
- [ ] Update the events timeline.
- [ ] If there is any upcoming event, it should be updatable easily
- [ ] Provide form for notification via email address.

**Membership**
- [ ] Enable away of contacting the leaders to join AGGES

**Projects**
- [ ] Add a small description of each project.
- [ ] Provide links for individual project content

**GEGIS(GIS) Past Papers**
- [ ] Add a section where students can view and access revision papers for any unit of their choice

**Contact us**
- [ ] Creaate a interactive webMap pointing to JKUAT GEGIS Department on the map.
- [ ] Make feedback button clear.
- [ ] Center the contents.
- [ ] Provide accurate links for the various external links.

**Yearly Archive**
- [ ] Archive for the various members profile photos.
- [ ] The position they held.
- [ ] Events in that year.

### Additional areas
**Blog**
- [ ] Make it have same design as the parent website.
- [ ] Redesign the blog section, so that one can be able to create profile, write a blogs and get user feedback via comments and claps.
- [ ] Make it a better place.


### Technical specs

Choose one of the following technical tracks to build the functionality described in the Functional spec that best suits your skill set:

-	Back-end track: build a REST API and include a minimal front-end (e.g. a browsable API)
-	Front-end track: build your project as a purely client-side app
-	Full Stack: blend the former approaches, but be sure to demonstrate your competence across the stack

#### Front-end

Your project can be built using any JavaScript or CSS framework, though we encourage [ReactJS](https://reactjs.org/), Redux and CSS/SCSS. You are also welcome to use our [React-ions library](https://www.npmjs.com/package/react-ions) to help build your UI.

Alternatively, feel free to swap out similar JavaScript frameworks such as Angular and UI kits such as Bootstrap. In addition to building the application.

#### Back-end

Your task is to build a REST API that can support the functionality of the site. Your project can be built using any API framework/language, though we encourage the use of [Django Rest Framework](http://www.django-rest-framework.org/)/Python. Your API should be able to:

-   Perform CRUD actions for the gallery page, blog page, archive page, events page and about page.
-   Perform analytics from the page e.g number of visits per day, user location

You do not have to build a functional UI unless you want to show off your talents across the stack. We will test your API by using the Browsable API. You are encouraged to write tests to verify your own results.

#### README

In your repo, please include the following items in your README:

-	Whether the solution focuses on back-end, front-end or full stack.
-	Reasoning behind your technical choices, including architecture.
-	Trade-offs you might have made, anything you left out, or what you might do differently if you were to spend additional time on the project.
-	Link to the hosted application (where applicable).

This will give us insight into how you approached the challenge.

### Tips
- Comment your code to show your thought process
- Submit this web design as a directory in your pull request named "{yourname_Task}"
- Make sure your have deployed your site to [netlify](https://www.netlify.com/), [heroku](https://www.heroku.com) or [github pages](https://pages.github.com/)

### Deployment Resources
- [Deploying site to heroku](https://blog.teamtreehouse.com/deploy-static-site-heroku)
- [Deploying site to netlify](https://www.netlify.com/blog/2016/09/29/a-step-by-step-guide-deploying-on-netlify/)
- [Deploying site to github page](https://docs.github.com/en/github/working-with-github-pages)
- Another reference for [github pages](https://medium.com/pan-labs/dynamic-web-apps-on-github-pages-for-free-ffac2b776d45)

### Working on the Challenge

1. Fork the code challenge repository provided [here](https://github.com/jkuatagges/AggesWebsiteChallenge2021).
2. Then git clone the forked repo by running this command in your local terminal
3. Clone (Download) the remote repo to your local working machine:

```shell
 $ git clone https://github.com/jkuatagges/AggesWebsiteChallenge2021.git
```

6. Make a topic branch. In your github, keep the main branch clean. Pull all changes, make sure your repository is up to date.
```shell
$ cd AggesWebsiteChallenge2021
git pull origin main
```

3. Create a new branch as follows
```shell
$ git checkout -b <your_branch_name>
e.g 
git checkout -b frontend
```

4. See all branches created
```shell
$ git branch
    main
* <your_branch_name>
```
5. Pull the remote changes locally
```shell
$ git pull
```
6. Push the new branch to github
```shell
$ git push origin -u <your_branch_name>
```
7. Make changes to the fork following the challenge provided.

8. Check the status of the repo
```shell
$ git status
```
9. Add your changed files
```shell
$ git add .
$ git status
```
10. Commit your changes
```shell
git commit -m "Commit message 😇"
```
11. Push your code changes
```shell
git push --set-upstream origin your_branch_name
```
12. Make a [pull request](https://www.digitalocean.com/community/tutorials/how-to-create-a-pull-request-on-github) to the AggesWebsiteChallenge2021 Repo.


**Submissions later than  0900hr EAT on 30th March 2021 will not be considered**

### Credits
1. [JKUAT SES](https://ses.jkuat.ac.ke/) was a sstarting point to get us started
