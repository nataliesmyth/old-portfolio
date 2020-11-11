[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Portfolio Template

Use this template and guide to build your portfolio.

## Objectives

By the end of this, developers should be able to:

- Have something to show to potential future employers/recruiters/friends
- Work on a portfolio and implement more and more features throughout SEI

## Installation

1. [Download](../../archive/master.zip) this template.
1. Unzip and rename the template directory.
1. Empty [`README.md`](README.md) and fill with your own content.
1. Move into the new project and `git init`.
1. Create a [Github User Site](https://pages.github.com/) repository as the remote for your portfolio.
1. Push to your user site `master` branch to deploy or update your site.

## Purpose

What do you want people to find when they google you?
What do you want someone's first impression of you to be?
Your portfolio is the portal to your professional online presence.
It consolidates the content you've created on multiple platforms and presents
it in digest form, making it easier for future employers to learn more about you.

## User Stories to Get Started

- As a non-technical HR manager, I want to quickly evaluate whether this candidate has the skills and experience to fill an open position at my company.
- As a mid-level engineer, I want to evaluate a junior developer’s coding skills by reviewing their projects and reading their code.
- As a friend of the person who built this portfolio, I want to understand what they do as a developer and what they have created.

## Required Sections

- About Me: Short blurb explaining who you are, and some background info
- Skills: All the skills you have that may be helpful on the job
- Contact info: LinkedIn, Github, city, email or contact form
- Resume: View and download
- Project Showcase: Feature your GA projects (more details below)

### Optional Sections

- Personal hobbies/interests
- Professional Timeline (a visual representation of your work history)
- Additional work samples (visual design, writing samples, a link to your photography blog)
- Relevant social profiles (Twitter, Instagram, if they highlight you professionally, not just what your meals look like)
- Blog posts (links to relevant articles you've published on platforms like Medium or LinkedIn)

## Highlighting Your Projects

Your projects should be featured prominently on your portfolio.  You'll want future employers to see what you accomplished both while you were at GA and after completing this program.

- **List projects in reverse chronological order.**  Your capstone is likely the project that best showcases your skills.  Make sure it's featured prominently as the first project in your portfolio.
- For your team project, be sure to fork, clone, and individually redeploy your project to maintain individual ownership over the site showcased on your portfolio.
- Include links to your live site as well as front-end and back-end repos.
- Summarize the functionality of the app as well as what technologies you used to build it.
- Briefly describe your process for building each app. If you have a blog post that goes into detail for each project, link to that post.
- Make sure your projects are user-friendly to an unacquainted visitor.
  - The home page should explain the site’s functionality
  - **Random users might not want to sign up/sign in.** Consider adding dummy credentials on the homepage that they can use (and explain that), or make sure they can interact with the site without signing up.
- After you've completed the program, **revisit your projects and refactor them**.  Add new features.  Improve the user experience.  Fix any open issues.  Enhance the app's design aesthetic.
- **Clean up test data** and create some seed data that you can use to easily refresh your database.  If you want to get fancy, you can write a [scheduled task](https://devcenter.heroku.com/articles/scheduler) that drops, recreates, and reseeds your database periodically.

### Design Hints for the Non-designer

The visual appeal of your portfolio is important.  Here are some recommendations to help you produce a portfolio that you're proud of:

- **Choose a template as the basis for your portfolio and customize it.**  There are many professionally designed templates available for free that you can use as the basis for your portfolio.  Of course premium templates are also available, but you don't need to spend money to have a great looking portfolio. If you're determined to build from scratch, use a template as design inspiration.  Treat it as a mockup and faithfully reproduce the layout, paying special attention to the spacing, sizes of elements, and font family choices of the template's designer.

- **Start with a framework.** [Bootstrap](http://getbootstrap.com/css/), [Materialize](http://materializecss.com/), and [Foundation](http://foundation.zurb.com) are the most popular options but there are many others.  Even if you have a very specific design in mind, use a framework to incorporate all of the base styles, then customize from there.  This will improve consistency across browsers and devices, and it will save you time. An added benefit is that many employers are specifically looking for people with familiarity with one or more popular frameworks.

- Even if you don't have any design knowledge, you can use some designer tricks to make your portfolio look great.  There are a few things that can radically improve any design:

  - **Add padding**.  White space, sometimes referred to as negative space, is a professional designer's secret weapon and a shortage of it is the hallmark of an amateur.  Let your content breathe!  You almost can't use too much of it, so if you think you've got enough, go back and add some more.  Checkout the result and ask others what they think.
  - **Keep font families simple and to a minimum**. Stick with either one or two font families for your entire portfolio. If you're using one, choose different weights for headings versus your content. If you choose two fonts, use two that have high contrast.  For example, use a serif for the body content and a sans-serif font for your headings.  :warning: Stay away from cursive, script, or highly decorative fonts altogether.
  - **Simplify your color palette**.  Pro designers spend years learning about color theory.  You don't have the time for that. :smiley: Choose one color and use it sparingly throughout as an accent.  Perhaps use it in your buttons and your top-level headings.  Restraint is the name of the game here.
  - **Line things up.**  Alignment is key to making a clean, professional portfolio.  Use the grid in your framework of choice.  Just use it!

## Deploying Your Portfolio

To deploy your portfolio, you'll only need to push to your **User Site** repository master branch.

### Github “User Site” vs. “Project Sites”

[Link to github pages](https://pages.github.com/)

Github provides only ***one*** “User Site” per account/organization with the url `username.github.io`. Your user site should be used for your portfolio since it will showcase the rest of your projects on Github. The user site is unique in that it is served from the `master` branch of your repository. Read more about [User Sites here](https://help.github.com/articles/user-organization-and-project-pages/#project-pages).

Other web apps/sites you host on Github are known as “Project Sites”. These will have URLs in the form of `username.github.io/project_names` and are served from the `gh-pages` branch of your repository. You can have an unlimited number of project sites.  At the conclusion of this program, you'll have at least four —  one for each of your projects — but we hope you develop many more!  Read more about [Project Sites here](https://help.github.com/articles/user-organization-and-project-pages/#user--organization-pages).

> #### A Quick Note on Technology :triangular_flag_on_post:
> As you know by now, in SEI we use [browser-template](https://git.generalassemb.ly/ga-wdi-boston/browser-template) to create
web apps.  Don't use this for your portfolio.  Browser template will only deploy to the gh-pages branch and ideally, your portfolio should be hosted on your user page.  If you want to use an npm package, speak with a consultant to get assistance adapting this template instead of opting for browser-template.

## What if I Have Questions...

Ask yourself if it's a technical or non-technical question: If your question is "Is it helpful to show that I'm
also a donut fanatic on my portfolio page?" you should direct that towards
Outcomes. If your question is "Is it appropriate to put a photo of me passed out
 at a bar?" the answer is "No." If your question is "How come I have an error `Cannot read property of
 undefined`?" you probably want to check what is to the left of the `.` and then
 open an issue [here](https://git.generalassemb.ly/ga-wdi-boston/portfolio-template/issues).

## Additional Resources

- [Start Bootstrap Free Templates](https://startbootstrap.com/themes/portfolio-resume/)
- [Showcase Your Skills With These 15 Free Portfolio Templates](https://skillcrush.com/2016/09/06/free-portfolio-templates/)
- [FontAwesome](https://fontawesome.com/)
- [Devicon](https://konpa.github.io/devicon/)
- [Unsplash | Beautiful, free photos](https://unsplash.com/)
- [Beginner's Guide to the Programming Portfolio](https://leerob.io/blog/beginners-guide-to-the-programming-portfolio)
- [SEO: How I achieved #1 on google search results for full-stack developer portfolio](https://caferati.me/labs/seo-part-one-google-search-for-full-stack-developer-portfolio)
- [The Portfolio Hack That Will Make Everyone Want To Hire You](https://www.freecodecamp.org/news/the-portfolio-hack-that-will-make-everyone-want-to-hire-you-58079cfed0b/)
- [10 Easy Design Tips for Non Designers](https://medium.com/makeamark/10-easy-design-tips-for-non-designers-b83405e49179)

## [License](LICENSE)

1. All content is licensed under a CC­BY­NC­SA 4.0 license.
1. All software code is licensed under GNU GPLv3. For commercial use or
    alternative licensing, please contact legal@ga.co.
