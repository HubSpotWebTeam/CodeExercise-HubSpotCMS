# Code Exercise HubSpotCMS

Welcome to another HubSpot Web Team's coding exercise! 👋

The goal of this exercise is to create a HubSpot theme so we can gauge your proficiency in the following skills:

* Familiarity with the HubSpot CMS and CMS concepts in general
* HTML/CSS
* General resourcefulness

It's not mandatory but recommended that you take the [HubSpot CMS for Developers Course][academy-hubspot-cms-for-devs] (Duration ~2.5 hours). That course will help you to familiarise with HubSpot CMS and other CMS concepts. So, if you are a Web Developer with no experience with any CMS or no contact with the HubSpot CMS, that HubSpot Academy course will be quite helpfull!

**Make sure you read these instructions carefully before you start. If you have any questions please reach out to your recruiting specialist.**

---

# Objective: Create a theme

# Important pre-condition

You will need to make sure you have access to a HubSpot Portal or a Developer Sandbox. That's easy!
* [You can create a free HubSpot CMS Developer Sandbox][free-sandbox], or;
* [Just get the HubSpot CMS Hub free trial][cms-hub-free-trial]!

## Directions

1. Review all the requirements on this page.

2. Create a HubSpot theme from scratch. (note: in production situations we recommend using the boilerplate theme as a starting point, but for this assessment please create one from scratch). The basic folder and file structure should look like this:

* Theme folder
** CSS folder
*** At least one css file
* Modules
** At least one module (with html, css, js, fields, meta files)
* Templates
** At least one template file
** Partials folder
*** Partials for header and footer
* Fields.json
* Theme.json

3. Use the page editor to create a page from your template. Make sure it behaves like the page in the demo gifs. If you are an experienced HubSpot CMS user and [want to use the HubSpot CLI][hubspot-cms-cli-docs], that's fine too!

4. Make sure your code is versioned! You will need to share a link of the Github repository containing all your code with us when submiting this assessment.

## The finished page

![Finished page image][img-hubspot-cms-code-exercise-finished]

## Requirements

* All work must be your own. During the grading process we will check the revision history. Submissions that do not meet this requirement will not be considered.
* Global template partials for header and footer
** Header must have editable quote

![Global header editable quote][img-global-header-editable-quote]

*Editing the global header and changing the quote.*

* Drag and drop area
** Must have two columns with an image module and a rich text module.
** These modules must have default content set inside the template

![Global header editable quote][img-two-column-drag-and-drop]

*Dragging the two column drag and drop area in the page editor.*

* Team module
** Must use repeating groups of fields to allow editors to add and subtract team members
** Must be at least 3 columns on large screens with at least one media query to change layout to 2 columns on screens below 900 pixels

![Global header editable quote][img-resizing-page-breakpoints-effect]

*Resizing the browser and triggering the breakpoint where the columns switch from 3 to 2.*

* Theme fields
** The theme must have at least 2 theme fields to control the font and the accent color used in the header and footer

![Global header editable quote][img-theme-fields]

*Editing the theme field that controls the header accent color.*

## Bonus points

* Use modern JavaScript (ES6+), but be wary of browser support (see the FAQ section for a list of browsers we'll check support for).
* Use a Javascript framework, e.g. React, Angular, Vue etc.
* Use linting/prettify for neater code.
* Add fuzzy search to the search field.
* Anything that improves the experience for the user.

## Tips

* Use the HubSpot themes and the boilerplate to figure out the specifics of techniques and syntax for these challenges.
* You’ll probably want to use the layout.css file from the boilerplate to make your drag and drop area perform as expected.
* You can build this locally or in the Design Tools.
* The subject of the theme is up to you. If you're not a fan of cats, feel free to use any topic you'd like. Creativity is encouraged.

---

# How to Submit

Fill out the submission.md file before submitting. If you deviated from the instructions or have any feedback, that's the place to put it! **Make sure you provide the link of your live page!**

Once complete, email either (a) a zip of your work or (b) a link to your GitHub repository to your recruiting specialist so they can forward it to the web team.

---

# FAQs

## When is the assessment due?
Please submit your exercise within four (4) days of receiving it. If you need extra time please reach out to your recruiting specialist.

## Which browsers should I support?
We'll look for compatibility with the following browsers:

* Google Chrome (latest version)
* Apple Safari (latest version)
* Mozilla Firefox (latest version)
* Microsoft Edge (latest version)
* What color values should I use?
* The exact color values don't matter; just try to get as close to the mockup as you can. You could also use a Chrome extension such as this color-picker.

## I'm running out of time, may I skip some of the requirements?

Although we expect you to finish the exercise completely, we understand that life happens. If you aren't able to finish on time, focus on the Team Module (its responsive behaviour for the final page viewed and easy of use from a Page Publisher perspective). Please use the submission.md fil to give us some insight as to what requirements your submission is missing and what you would have done.

[academy-hubspot-cms-for-devs]: https://academy.hubspot.com/courses/cms-for-developers
[free-sandbox]: https://offers.hubspot.com/free-cms-developer-sandbox
[cms-hub-free-trial]: https://app.hubspot.com/signup/trial-signup?intent=trial&trialId=18&dtt_source=get-started-page&hubs_signup-url=www.hubspot.com/products/get-started&hubs_signup-cta=getstarted-cmstrial&hubs_content=www.hubspot.com/&hubs_content-cta=homepage-nav&hs_chatflow=BOT117_VarA&_ga=2.209061524.766654493.1626950831-623576512.1624288828
[hubspot-cms-cli-docs]: https://developers.hubspot.com/docs/cms/guides/getting-started
[img-hubspot-cms-code-exercise-finished]: ./img-hubspot-cms-code-exercise-finished.png
[img-global-header-editable-quote]: ./img-global-header-editable-quote.gif
[img-two-column-drag-and-drop]: ./img-two-column-drag-and-drop.gif
[img-resizing-page-breakpoints-effect]: ./img-resizing-page-breakpoints-effect
[img-theme-fields]: ./img-theme-fields
