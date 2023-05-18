# Instagram-Clone-Description
Description of my Instagram clone project from Web Systems class (EECS 485) at the University of Michigan

The goal of this series of projects was to learn about important web development tools such as React, HTML/CSS, REST APIs, Flask, serverside and clientside dynamic pages through recreating Instagram. 

Main features of the product:
- The ability to log in or create a new account
  - The password needed to be secured via hashing with salt
- Ability to scroll through, like, or comment on posts from followed users on the index page
- An explore page where users can see other users they do not follow
- A profile page in which all of a user's profile information such as username, email, followers, and posts are stored, as well as a way to   edit one's profile

The project was completed in three separate stages. The first stage comprised of static pages using the Jinja2 library where most of these features were included however a page refresh was always necessary, and all posts were hard-coded. In the next stage, a REST API and Flask were added to the project, allowing for users to create posts from scratch, as well as like and comment. However, every page was still serverside dynamic, and required a page refresh after user actions. Finally, in stage 3 I utilized React to make the index page a clientside dynamic page which would update without a page refresh, and would send all user actions to the REST API after so it would also update upon refreshing.

All data was stored in a local SQLlite relational database, but I understand that in a real Instagram clone this would not work, and it would be more optimal to choose a product like MySQL instead.

Due to the university's academic integrity policies, I cannot attach my code, however the specs to all three projects are attached below! 
https://eecs485staff.github.io/p1-insta485-static/
https://eecs485staff.github.io/p2-insta485-serverside/
https://eecs485staff.github.io/p3-insta485-clientside/
