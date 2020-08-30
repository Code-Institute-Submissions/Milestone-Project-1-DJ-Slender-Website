# Milestone Project: User-Centric Frontend Development - Code Institute

### djslenderuk.co.uk - Website

I wanted to provide a bit more of an insight to me as a DJ. 
To get to know a bit about me, to hear my mixing skills, to follow me on social media and to contact me for any enquiries.


### UX & Design

**Strategy**

To be easily accessible, get an idea of me as a dj and to make enquiries.

**Scope**

For potential event planners, i wanted to create an opportunity for them to access a variety of mixes for all ocassions 
and to be able to contact me for bookings for events or mixes. I gave a brief overview of what you would get from my site on the home page,
gallery was to provide an idea of all the different places I have dj'd and the different set ups. Mixes is showcasing my abilities and skills,
about me is to show im just a normal guy.

**Structure**

The landing page I wanted everything on my site to be accessible in one place with a small breif about each page. Each page to have the 
something benefical for each user, whether to book me or to know more about me or to listen to my mixes

**Skeleton**

[Home wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

[About wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

[Mixes wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

[Gallery wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

[Enquiries wireframe](https://github.com/Code-Institute-Solutions/StudentExampleProjectGradeFive/blob/master/wireframes/about.png)

**Surface**

I have seen a few sites and the common theme to make it look sleek is using a greyscale.


**Technologies**
1. HTML

2. CSS

3. boostrap

4. google fonts

5. wireframe

**Testing** 

There wasnt an issue I didnt encounter throughout the whole project. The most mermorable ones were very simple fixes such as closing tags.

An issue i had was `.col-6-xs` it wasnt working how i though it was meant to untill i spoke with a mentor (Tim) who directed me to Anna's bootstrap grid layout explaination on youtube.

It was then i realised that the i was working the wrong way around. Bootstrap starts with small screens first then to large.  so had to change it to `.col-4-lg.`

The other issue was the `z-index` not being include in the navbar to stop the image from covering the navbar.

`.navbar-light .navbar-brand` was not picking up the color so i had to use `!important`.


### Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order
for the site to deploy correctly on GitHub pages, the landing page must be named index.html.


### Credits

**Acknowledgements**

To the multiple Code Institue mentors (Tim, Stephen, Anna, Michael Hayley and the infamous RoboDuck)

Special Mentions to Hayley Schafer - readme.md was guided using what she done. To the code institue mini project - Running Club, massively inspired by this, wih some
adaptations and using bootstrap.
