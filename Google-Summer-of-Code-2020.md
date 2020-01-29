## Table of Contents
* [Getting started](#getting-started)
* [FAQs](#faqs)
* [GSoC Proposal Template](#gsoc-proposal-template)
  * [Tips for writing a good project plan](#tips-for-writing-a-good-project-plan)
  * [Sample proposals from past years](#sample-proposals-from-past-years)
* [Types of work related to Oppia projects](#types-of-work-related-to-oppia-projects)
* [Selection Criteria](#selection-criteria)
* [Oppia's Project Ideas List](#oppias-project-ideas-list)
* [Other useful information](#other-useful-information)
    * [Dates and Deadlines](#dates-and-deadlines)
    * [List of Mentors](#list-of-mentors)
    * [Communication](#communication)

Oppia has applied to participate in [Google Summer of Code 2020](https://summerofcode.withgoogle.com/)! GSoC is a global program which offers post-secondary students an opportunity to discover and work with open source organizations over the course of 3 months, while being paid a stipend. Students work closely with one or more mentors from an open source organization in order to implement either a project idea by the organization, or a proposal of their own.

Since GSoC mentoring organizations will not be announced until February 21, 2020, it is not yet known whether Oppia will be participating in GSoC 2020. This page will be updated accordingly once it is known whether Oppia is participating.

You might be interested in our GSoC info pages from previous years: [2019](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2019), [2018](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2018), [2017](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2017), [2016](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2016).

Also, please note that acceptance into GSoC isn't a prerequisite for becoming an Oppia contributor. The Oppia project is run by the community for the community, and we warmly welcome anyone who'd like to help out! You can get started by following the instructions [here](https://github.com/oppia/oppia/wiki).

# Students
GSoC is an excellent opportunity for students to get paid to work on an open source project. If you're interested in applying as a student, you should definitely read the following resources:

* [Google Summer of Code student guide](https://google.github.io/gsocguides/student/)
* [Google's list of resources](https://developers.google.com/open-source/gsoc/resources/)
* [GSoC FAQ](https://developers.google.com/open-source/gsoc/faq)

## Getting started

If you're interested in applying to work with Oppia for GSoC, please follow these steps:

1. Sign up to the [oppia-gsoc-announce@](https://groups.google.com/forum/#!forum/oppia-gsoc-announce) mailing list in order to receive important notifications about Oppia's participation in GSoC. If you like, you can also sign up to the [oppia-gsoc-discuss@](https://groups.google.com/forum/#!forum/oppia-gsoc-discuss) mailing list to participate in general discussion related to Oppia's involvement in GSoC (see point 6 below, too). Make sure to set your preferences correctly so that you actually get the emails!

2. Get a better understanding of what Oppia is all about by taking a look at our [user documentation](http://oppia.github.io/#/) -- this will help you become familiar with important concepts like explorations and interactions. We also recommend having a go at playing lessons on [Oppia.org](https://www.oppia.org/splash), which hosts a live instance of Oppia.

3. Read and follow the instructions in the [contributors' guide](https://github.com/oppia/oppia/wiki/Contributing-code-to-Oppia#setting-things-up) carefully.

4. Consider taking up one or more starter projects in order to become familiar with the contribution process. This will help us get an idea of what it's like to work with you -- e.g. how independent, resourceful, responsive, etc. you are. It will also help you get a better understanding of the codebase, so that you can write a good, detailed project proposal.
    - **Pro-tip!** Quality is more important than quantity; we want to see examples of your best work. So, please make sure to follow the [dev workflow](https://github.com/oppia/oppia/wiki/Contributing-code-to-Oppia#instructions-for-making-a-code-change) carefully, manually test your code before submitting (to ensure it does what you want it to and doesn't break anything else), ensure that your code conforms to the [style rules](https://github.com/oppia/oppia/wiki/Coding-style-guide), and pay attention to small details. These are good skills to learn when developing software in general, and they will also help you build credibility as a responsible developer who can be trusted to be a good steward of the Oppia codebase.

5. Once you've merged at least 2 pull requests, you will get an invitation to become a collaborator to the Oppia repository and be officially onboarded! **This step is a prerequisite** to applying for GSoC.

6. Now, you can select one or more GSoC projects that you're most interested in, and write your project proposal! We strongly encourage you to discuss your project ideas and share your proposal with the community, so that you can get feedback and ensure that what you're writing makes sense to others. The best way to do this is to put your proposal into a collaborative editing tool like Google Docs, allow others to comment on it, and share a link to it on the [GSoC discussion mailing list](mailto:oppia-gsoc-discuss@googlegroups.com). You can also email this mailing list if you have any questions about a project, or would like to discuss your approach with the Oppia community and get feedback. Please be specific when asking questions, since this makes it easier for us to help you.

## FAQs

**Q: What technical skills do I need to work on Oppia?**

A: Familiarity with AngularJS (v1), Angular8, Python 2.7 and Google App Engine is useful and recommended for most Oppia work. In addition, UI design skills are useful for frontend, user-facing work. Please see the individual project ideas to determine whether these skills are recommended for the project in question.

**Q: How can I increase my chances of getting selected?**

A: Writing a good project proposal, engaging with the community, helping other students, successfully contributing patches, and demonstrating that you can work independently can all help you. We've also compiled some notes below on the [selection criteria](#selection-criteria) we'll be using this year.

**Q: Can you be flexible around my other commitments in the summer?**

A: GSoC is intended to be a full-time commitment, so the main concern is whether you can still get the project done on time. Be upfront about your other commitments and make sure you schedule your time accordingly when creating your proposal. Other commitments you should list include time when you'll be in school and will commit less time to GSoC, time when you'll be travelling and away from GSoC work, any summer jobs you need to commit to, etc. We will try to be flexible around other time commitments, as long as your proposal convinces us that you will have enough time to complete the project by the end of the summer. On the other hand, if you do not disclose other commitments, and it turns out that you are unable to commit to what you wrote on your proposal, this is grounds for failing the program.

**Q: Which projects are most important for Oppia?**

A: All the projects we've listed here are important, and we'd be very happy to see good progress made on any of them! Projects are treated as equally important during selection. Note that the relative importance of a project to Oppia is not part of the [selection criteria](#selection-criteria). We would encourage you to pick a project that you would enjoy doing over the summer.

**Q: Can I submit more than one proposal to Oppia?**

A: Yes you can. However, we strongly recommend picking one project and writing a solid proposal for it. Splitting attention across multiple projects might not be a great idea. 

**Q: How early should I start working on the proposal?**

A: As early as possible. Make sure to get feedback from mentors before finally submitting the proposal. This will help you to write a better proposal as you can refine the details based on the feedback you receive. The mentors would need some time to review, and hence it is a good idea to begin as early as possible.

**Q: I only discovered this project recently. Does this mean that, during selection, my application would automatically be ranked lower than those by other applicants who have a longer tenure with Oppia?**

A: Definitely not! Here are the [selection criteria](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2020#selection-criteria) we use when selecting students for GSoC; note that tenure is not part of these criteria. Also, our philosophy is to consider each application based on its own merits, not relative to other applications, and we try to accept every student whose application "meets the bar". The only cases in which we'd need to compare applications against each other are when a project idea receives multiple applications, or we receive fewer "slots" to host students than we originally applied for.

## GSoC Proposal Template

When submitting a proposal, please use the provided [GSoC proposal template](https://docs.google.com/document/d/1C6OgWa5I2wTWYPLTOqoZMVvWrVQ10BGXbe4SNEBMu-s/edit). We will only consider proposals submitted using this template.

You are welcome to ask mentors for reviews during the proposal preparation phase. Mentors will review proposals incrementally. That is, they will work through the Mocks section, and, only after they are satisfied with it, they will review the Technical Design section, and, similarly, only after that section looks good, they will review the Milestones section. This is meant to help ensure that later sections of the proposal are building on a solid baseline.

**Important:** Please make sure that your final proposal is self-contained. In particular, to be fair to all applicants, key components of the proposal should not be editable after the deadline, and you shouldn't assume that reviewers will follow external links.

### Tips for writing a good project plan

Here's some advice about proposals and milestone timeline planning that we collated from previous students and mentors:

- Choose a project you're interested in! If you have a strong interest in your project, this will help you pick up necessary skills and tackle any unforeseen difficulties that arise during GSoC.
- Familiarize yourself with the relevant part of the codebase for your project, especially if you haven't touched it before. It's important to think about how to integrate your project with the current Oppia structure -- don't design in a vacuum.
- Define milestones with enough detail to get a proper ETA for each milestone (so, don't just say "write e2e tests"), otherwise you run the risk of significantly underestimating the timeline.

### Sample proposals from past years

If you'd like to get a sense of what a proposal might contain, please see our [GSoC 2019 page](https://github.com/oppia/oppia/wiki/Google-Summer-of-Code-2019) for examples of proposals that we accepted in 2019. Note that the [GSoC Proposal Template](https://docs.google.com/document/d/1C6OgWa5I2wTWYPLTOqoZMVvWrVQ10BGXbe4SNEBMu-s/edit) was only created in 2020, so although it may seem like none of the previous proposals follow the template, please be sure to follow it this year.

_**Note:** although some of these proposals are a bit on the long side, there's **no** formal length requirement for your proposal. In general, the quality of what you write is much more important than the amount of text you write, and we encourage you to write shorter proposals that still convey the main aim of the project. For the actual requirements, please see the [GSoC Proposal Template](#gsoc-proposal-template) section above._

## Types of work related to Oppia projects
In order to ensure a well-rounded engineering experience, developers will do some or all of the following depending on their project:
- Meet with their mentors regularly
- Meet with other contributors related to their project area
- Read and understand parts of the code base related to their project
- Receive code reviews for all code they write for their project
- Write automated tests for their projects
- Create UI mocks (if doing frontend development)
- Write design documents (if implementing large features or introducing new systems)

**[NEW!]** We asked our previous students what they learned during GSoC. Here are the collated answers:
- Technical ability
  - Writing clean code with comments
  - Writing tests
  - My debugging skills improved a lot.
  - Refactoring skills.
- Technical domain knowledge
  - I'm much more fluent in Python and AngularJS.
  - I feel that I can now pick up any new framework/language/skill easily, without much uncertainty.
  - I got to know about the one-off jobs in detail.
- Technical leadership skills
  - Single-handedly releasing a big feature end-to-end.
  - Reviewing others' code
  - Technical design skills (and validation of technical ideas)
  - Organizing release testing teams
  - I feel that I can think about a feature end to end and prune out all the not so essential features, so that we can create a minimum viable product!
  - I learnt how to coordinate with folks around me.
- Communication
  - Putting forward my thoughts more systematically and deeply so that everyone can understand me well.
  - Better communication skills.
  - How to write a good proposal.
- I learned a lot other than coding, including writing technical documents, doing meetings, presentations, testing, etc. This was also the first time I was writing well-tested backend code, which was also an interesting learning experience for me.

## Selection Criteria

In order to select students for GSoC, we will mainly be looking at three things:

- The quality of the submitted proposal
- The quality of the applicant's previously-submitted PRs (in order to assess their ability to code, debug, break down complex tasks, etc.). Note that quantity isn't a prerequisite in itself, though contributors who've submitted multiple PRs are likely to have had more opportunities to demonstrate the abilities needed to succeed in GSoC.
- Our prior experience working with the student (do they keep commitments, communicate well, demonstrate independence/initiative/responsiveness, help others, etc.)

We believe that strong performance in these dimensions is likely to correlate well with the student having an enjoyable, fulfilling and productive experience over the summer, and successfully completing the GSoC program.

For the proposal, we generally look for a clear indication that the student has a good, deep understanding of the project, and has broken it down sufficiently well, in a way that makes it very likely to succeed. Some indicators that could help with this include:
- A clear analysis of (and good design decisions that build on top of) the original project idea, with a strong focus on creating a simple, intuitive experience for end users.
- A concrete, specific breakdown of the work to be done for each milestone. Here's an [example](https://docs.google.com/document/d/1vuwXvHOYXqfM2S2B2KIWhZrAa1PL59wJRUYsqJEd67E/edit) from a previous design doc. (Note that, in the implementation plan, the author has carefully considered and listed which tests need to be written alongside the code; this is a positive indicator.)
- Sufficient concreteness (e.g. references to particular files and methods) to demonstrate that the applicant is familiar with both the scope of the problem and the existing codebase.
- A description, if applicable, of how the applicant plans to mitigate risks that could potentially derail the project.
- Clear, unambiguous communication. (This is important; your proposal will be read by many mentors!)

## Oppia's Project Ideas List

The following is a list of Oppia's 2020 GSoC project ideas. (Please note that all mentor assignments listed below are provisional, and may change depending on which proposals are eventually accepted.)

You are welcome to choose among these ideas, or propose your own! However, if you're planning to propose something original, it's essential to engage with the Oppia community in order to get feedback and guidance to improve the proposal. We also recommend taking a look at [Oppia's mission](https://github.com/oppia/oppia/wiki/Oppia's-Mission) and seeing if there is a natural way to tie your idea to the Oppia project's goals, otherwise it might not be a good fit at this time.

This year, the Oppia team is offering projects in four categories: Full-stack, Backend, Frontend and Android. Some of the project ideas are annotated with notes and suggestions from the mentors, but please bear in mind that the main purpose of these notes is simply to suggest ideas or possible starting points; they aren't meant to be prescriptive. You'd also be welcome to include discussions of other relevant aspects (that aren't mentioned in the notes) in your proposal. For more information, see: [Tips for writing a good project plan](#tips-for-writing-a-good-project-plan).

### Full-stack Projects

1.1. [Fix Exploration Saving Flows](#fix-exploration-saving-flows)

1.2. [Generate Images for LaTeX expressions](#generate-images-for-latex-expressions)

1.3. [Bulk Upload of Voiceovers](#bulk-upload-of-voiceovers)

1.4. [SVG Diagram Editor in the RTE](#svg-diagram-editor-in-the-rte)

1.5. [Provide an easy, lightweight way for students to log in to save progress](#provide-an-easy-lightweight-way-for-students-to-log-in-to-save-progress)

1.6. [Improvements to TextClassifier for ML based response to student inputs](#improvements-to-textclassifier-for-ml-based-response-to-student-inputs)

1.7. [Image contributions](#image-contributions)

## Full-stack Projects

### Fix Exploration Saving Flows

There are several serious issues with current workflows in the exploration editor that can occasionally cause loss of work. In particular:
* Add support for creators to indicate whether changes to explorations are major/minor, in order to provide signal to Android app users for when they might want to update their lessons.
* Implement generalized migration system for all model types and move migration methods to separate files
* When an exploration is updated, any existing suggestions in the feedback tab should be updated accordingly. Currently, such suggestions are not updated, resulting in a version mismatch and a loss of work when the exploration creator subsequently tries to apply the suggestion.
* When changes cannot be saved to an exploration, a "lost changes" modal pops up so that the creator can make a copy of their edits and then reapply them. However, the code for this modal is not robust, and in particular it does not take into account draft changelists that were stored in an older format. Thus, when it tries to display such drafts, it breaks and ends up not showing anything.
* It is difficult to change an interaction into a slightly different one (e.g. from text input to number-with-input) without losing all the associated responses, hints and solutions. It would be nice to declare a suitable transformation that allows this data to be carried over from one interaction type to a closely-related one, and to auto-migrate as much of the responses as possible so that the creator does not lose their work.

The aim of this project is to fix any three of these issues.

**Team**: Learner and Creator Experience

**Potential Mentors**: @seanlip (primary), @kevintab95, @aks681

**Consider taking up this project if you...**

* Enjoy debugging and tracing through Python and JavaScript code to find out how something works
* Are familiar with the flow of logic between the Oppia backend and frontend
* Have good analytical and technical design skills

**Suggested Milestones**

Choose three of the issues above, and fix them. Fixing each issue counts as a single milestone.

**Notes**

Your proposal should include clear explanations for how you plan to solve each of the problems you decide to tackle. (This may entail repeating the sections suggested in the proposal template three times, since this GSoC project is essentially made up of three separate mini-projects.)

### Generate images for LaTeX expressions

Introduce SVG rendering for all LaTeX expressions, so that MathJax can be removed from the learner pages

**Team**: Learner and Creator Experience

**Potential Mentors**: @kevintab95 (primary), @aks681

**Consider taking up this project if you...**

* Enjoy full-stack development.
* Have good technical design skills.

**Suggested Milestones**

1. Populate the SVG field for newly-created math expressions
2. Migrate all existing expressions on the server to have SVGs in them.
3. Use the SVG instead of the LaTeX when showing the formula to the user. Remove MathJax libs from the frontend display.

### Bulk Upload of Voiceovers

Voiceover recording is an important feature for giving lessons life in more than one language. As one of the most used features for creators, there are 2 ways voiceovers can be added to the platform: recording and uploading files. Recently there was a concern raised with the workflow for uploading files. The workflow that currently exists for uploads is that one section of the lesson can be updated one at a time. The main premise of this project is to address this by providing voice artists and creators the ability to bulk upload files and give them improved control of setting the individual audio files to desired sections of the lesson. This will streamline the process for improved efficiency and experience.

**Team**: Audio and Translations

**Potential Mentors**: mzaman07 (primary)

**Consider taking up this project if you...**

* If you enjoy designing UI and care about UX.
* You want to expand on your Front End Development skills.
* Have great analytical and technical design skills.

**Suggested Milestones**

1. Implement a bulk upload function based on the UI mockup design. Create a form that will take the resulting file upload(s). Cache all the files in the browser. Provide a way to empty/ refresh the cache by the user.
2. Implement a UI piece that will allow the user to see all the cached files, play them as a preview and set it to a lesson card. Also allow the user to set how the language the voiceover is for. (Can apply to more than one lesson card.) If this makes the existing one file upload button redundant, justify why this should be removed. Make upload feature more dynamic as it probably does not need to refresh the screen. For network performance, consider designing the file uploading to the server work similarly to a FTP queue.
3. Apply minor cosmetic indicators to show that the file can be uploaded to Oppia. Display it’s byte size / duration, and mime type. (Optional) If certain browser(s) have niche constraints then indicate that to the user.

**Notes**

Think about the design and problem at hand. The main goal of this is to improve the workflow for its users. The proposal should clearly explain the design and how it improves the experience. You may need to research constraints of saving raw audio file data on the browsers. Each browser may have different constraints.

### SVG Diagram Editor in the RTE

Introduce an SVG diagram editor in the RTE. Creators can use this to create custom informative diagrams for their lessons in the browser itself. The images produced would then be stored as SVG for use in the lesson.

**Team**: Learner and Creator Experience

**Potential Mentors**: @kevintab95 (primary), @aks681

**Consider taking up this project if you...**

* Enjoy debugging and tracing JavaScript code to find out how something works
* Are familiar with the flow of logic between the Oppia backend and frontend
* Have good analytical and technical design skills

**Suggested Milestones**

* Milestone 1:
  * Complete backend changes for introducing literallycanvas, svgedit or a similar editor to the RTE framework (eg. saving/retrieving SVG data). Include tests.
* Milestone 2:
  * Complete frontend changes for the SVG editor.
  * Complete the frontend and end-to-end tests.
* Milestone 3:
  * Add 2 custom diagrams (eg: circles and rectangles) to the svg editors like geometrical shapes.

**Notes**

Your proposal should contain a detailed plan for each of the milestones and it must include mocks of how the SVG editor will look like once it has been integrated to the RTE.

### Provide an easy, lightweight way for students to log in to save progress

Currently, the only way for a user to save his/her progress in an exploration is to log in with a Google account, which not every person may have or know how to create. So, the aim of this project is to create a lightweight and intuitive way to signup and login without having a google account, by just asking the user for a username, password, and optional email / mobile number, and then allowing them to login using these. Here, the mobile number, email and username should be validated to be unique. (If a mobile number / email is provided, this can be used for profile recovery if the password is lost.)

Another feature that is to be added is to add functionality in that user’s profile page to support the upgrading of such an account into a “full account” later on, if the user wants to link a google account to it.

**Team**: Learner and Creator Experience

**Potential Mentors**: @aks681, @seanlip

**Consider taking up this project if you...**

* Are familiar with the flow of logic between the Oppia backend and frontend
* Are interested in creating an end-to-end user flow
* Have good technical design skills

**Suggested Milestones**

1. Finish the backend for signup, login and implement the migration to add the mobile number field to the user model. Also, make sure the email and mobile number fields are optional in the user model.
2. Create the signup and login page frontend that communicates with the backend, created in the previous milestone.
3. Integrate these pages into the main website by editing the Signup button on the top right to show 2 options when clicked. Make sure login with redirect URL works as well. Also, write e2e tests for this functionality.

**Notes**

Proposal should discuss design decision: is it better to build profiles on top of the existing UserModels or should there be a separate LightweightUserModel created.
Proposal should think through all the workflows (e.g. if using two separate models, does lightweight model get deleted when linked to an account).

### Improvements to TextClassifier for ML based response to student inputs

Oppia is used by many tutors around the world to teach new concepts through explorations. A major part of the consumers of these explorations are students. Oppia provides several ways to interact with the students when they are going through an exploration. Text input interaction is one such interaction in which students provide their answers as a text. As of now, Oppia uses hard defined rules such as ‘answer contains xyz’, ‘answer starts with abc’ etc… to figure out proper response to student inputs. Providing a proper response is very important as improper response may confuse students and they may leave explorations in the middle. These rules are created by the creators of exploration. However, it is impossible to enumerate all possible conditions. 

Recent advances in Machine learning / Deep learning could prove to be very useful. The creator simply labels student inputs with proper responses which could be treated as training data to train an ML model. The goal of this project is to do so. To be specific, the goal of this project is to research and implement a machine learning model which can be used to provide appropriate response to the user inputs. The training data is of classification in nature where the model has to predict appropriate class which is a response that should be used by Oppia.

Currently, Oppia has implemented a naive version of such classifier which uses a Bag-of-Words and SVM model. The aim is to use techniques from recent advances in distributed representational learning and improve upon the current mode.

**Team**: Machine learning

**Potential Mentors**: @prasanna08

**Consider taking up this project if you...**

* Are excited about recent research in the NLP community (esp. deep learning based models such as BERT, GPT).
* Enjoy reading deep learning research papers, critically analysing them, and implementing state-of-the-art models for your own experiments.
* Enjoy applying cutting-edge ML techniques to real-world, production environment specifications.
* Have a fair amount of experience with implementing models in Python (note that Oppia currently uses Python 2.7).
* Have experience coding in AngularJS or Angular.

**Suggested Milestones**

1. **Literature review**: Compile relevant research papers. Explore their methodologies, and implement them (possibly adapting code published by researchers), then test your implementations on the proposed datasets and compare the results with 1-2 baselines. Provide working implementations and a report of the results for at least the initially-proposed idea and the baselines. Submit a list of at least 4 ideas that you would like to try in the next month.
2. **Experiment and build a classifier**: Experiment with the ideas proposed in the previous milestone, and provide a report on the results, including a clear specification of the model you are going to implement in Oppia, as well as a full list of changes that are required to implement the classifier using the current ML pipeline. The performance of the final classifier must be adequate (compared to state-of-the-art performance on the proposed datasets), and it must satisfy the constraints in the “notes” section below. You will need to provide sufficient evidence to show that the classifier meets these criteria. 
3. **Implement and test**: Implement the final classifier in the Oppia code base, and create a dummy exploration on which it can be tested. Note that the responses given by the classifier are more important than the on-paper test results. Also, depending upon the model you propose, you might need to make some changes to the existing ML pipeline.

**Notes**

The ML pipeline implemented in Oppia performs the classification in the browser of a student's machine. The models are trained by a backend server called “Oppia-ML”, and then they are transferred to the frontend where prediction is carried out in the browser in JavaScript. Hence, there are several constraints on the model which need to be adhered to:
1. The model must be small, i.e., it should fit within a few MBs. 
2. Inference must be fast on a machine with nominal specifications (4GB RAM, i3 process, no GPUs).
3. It must be possible to implement the inference code in JavaScript in the frontend. The backend could be anything Python-based (e.g. tensorflow, pytorch), but the inference code has to be implemented in JavaScript.
4. The model must have reasonably good performance (compared to state-of-the-art benchmarks) on natural language inference datasets (e.g. SNLI or equivalent).

The student proposal should focus on the following points. (Important: While preparing your proposal, please use [this](https://docs.google.com/document/d/1RiOlOKcztnjv69wyhUI-n17lmSN81Y2jKLpnna39bPs/edit?usp=sharing) template instead of the default one for the “Project Details” section of the proposal.)
* **Selection of promising techniques**. Start by providing a list of at least 3 deep learning / NLP / ML techniques that could potentially be used to address this problem. From this list, pick the most promising options and explain why you think they are the most promising; also, explain why the rejected options are not worth pursuing. Develop the promising options into initial ideas that (i) can be implemented and tested quickly and (ii) could form baselines for further experiments that you will do during GSoC. (These ideas do not need to be complex.)
* **Baselines**. Provide baseline models that you are going to compare against, and specify which metrics you will be using for comparison. Student should propose an ambitious baseline, rather than something simple such as “SVM with tf-idf”. (It may happen that, at the end of your experiments, your baseline turns out to perform the best; that is OK.)
* **Datasets**. Specify the datasets on which the classifier will be tested. One such example is SNLI, but you can use any dataset you wish, as long as you give an explanation on why that particular dataset would be a good choice.
* Prior experience. Provide details of any previous experience you may have with researching such models.

### Image contributions

Art and graphics form an integral part of most explorations on Oppia, and are especially important for making lessons learner-friendly and communicating key concepts to learners, especially since good graphics can transcend language barriers. However, one major blocker when creating lessons is the lack of an easy way for designers/artists to add images to lessons. We would like to enable artists to contribute to lessons as easily as developers can contribute to GitHub repositories.

**Team**: Contributor Experience team

**Potential Mentors**: @DubeySandeep, @sagangwee

**Consider taking up this project if you...**

* Are familiar with the flow of logic between the Oppia backend and frontend
* Familiar with the state migration functionality
* Familiar with the Rich text editor workflow 
* Have good technical design skills

**Suggested Milestones**

1. Building a seperate section for images in different entities, writing migration (if required) and allowing owner/editor to add placeholder images in exploration.
2. Adding new models for the exploration opportunities and presenting the available opportunities in community dashboard page.
3. Allowing contributors to submit a suggestion for available opportunities and reviewers to review the suggestions.

**Notes**

A few things should be consider while writing design doc:
1. There should be a separate section in the state object which should have reference to images. (Similar to RecordedVoiceover and WrittenTranslation.)
2. This will help us to have a separate section which can be edited by the contributors.
3. While designing the workflow for Rich text editor consider this editor is used in most of the places like story, topics etc. and as of now we don’t need image suggestion there but in future we can, so it should be simple to re-use the changes in RTE for other paces.
 
## Frontend Projects

### Editor Redesigns

The aim of this project is to redesign the topic, exploration, story and skill editor pages so they are more visually appealing and work better on mobile, while retaining all of their features. Some initial mocks that we created visualizing these changes can be found here (will be linked when they are ready). Though, in general, feel free to suggest changes to the mocks if you think that would enhance the learner experience.

**Team**: Learner and Creator Experience

**Potential Mentors**: @aks681, @kevintab95

**Consider taking up this project if you...**

* Are interested in UI/UX design
* Enjoy debugging and tracing JavaScript (and Typescript) code to find out how something works

**Suggested Milestones**

1. Complete the topic and skill editor pages redesign.
2. Complete the story editor page redesign.
3. Complete the exploration editor page redesign.

**Notes**

* The mocks for the editor pages would be provided, the student has to implement it.
* The proposal should explain the files that would be changed and the changes themselves briefly.
* Proposal review would be based on if the student understands the codebase well enough and past PRs related to the editor pages.

### Solve all typescript and webpack issues in the codebase

Complete all remaining typescript + webpack tasks to ensure a smooth development workflow. In particular:
* Remove all custom typings for typescript
* Remove "any" types for third-party stuff
* Remove all "any" types from the codebase
* Replace third_party and remaining <script> imports with webpack
* Reduce the overall time for webpack compilation (under 8s for develop and 60s for production builds)
* Add documentation on all typescript and webpack errors and solutions on how to fix them.
 
**Related issues**: 7601, 7434, 6431, 6351

**Team**: Dev Workflow

**Potential Mentors**: @vojtechjelinek, @ankita240796

**Consider taking up this project if you...**

* You want to work with TypeScript and Webpack.
* You will be working mainly on the build process and not on the final product, so be prepared for that.
* This project should simplify the TypeScript and Webpack part of the build process as simple as possible for the ordinary developer, so you should always have that in mind.

**Suggested Milestones**

1. Remove all custom typings for typescript. “Custom typings” denotes the extra typing files that we have for jQuery, html element and scope defs. We have custom type definitions for third party libraries [here](https://github.com/oppia/oppia/tree/develop/typings). We need to remove these and add our own typedefs for third party libraries instead of defining them as any.
2. Remove "any" types for third-party libraries. Remove all "any" types from the codebase. (Here, "any" types denotes all the declarations which do not have a type specified, or where the type specified is ‘any’.)
3. Replace third_party and remaining <script> tags with webpack. Reduce the overall time for webpack compilation. Add documentation on all typescript and webpack errors, and solutions on how to fix them.

### Frontend testing of controllers and directives

This project aims at improving the frontend test coverage of controllers and directives to a 100%.

**Team**: QA Team

**Potential Mentors**: @nithusha21

**Consider taking up this project if you...**

* Are interested in testing. Most of the project would involve writing unit tests. 
* You will be reading through a lot of the source code of Oppia, so you should have the ability to read through someone else’s code, and understand what needs to be tested.
* Like to handle technical challenges! It will be very likely that you run into problems while trying to test the code as is, and will need to research and come up with solutions to test certain constructs.

**Suggested Milestones**

1. Develop a pattern for testing controllers and directives and implement it for about 20% of the files.
2. Fully cover 60% of the controllers and directives.
3. Fully cover 100% of the controllers and directives.

### Accessibility Project

Ensure that the entire Oppia website is fully accessible to screen readers (i.e., all pages should score 100% on the Chrome browser’s inbuilt Accessibility audit tool), and that automated tests are put in place to ensure this is the case going forward.

**Team**: Learner and Creator Experience

**Potential Mentors**: @kevintab95 (primary), @aks681

**Consider taking up this project if you...**

* Enjoy debugging and tracing JavaScript code to find out how something works.
* Have good technical design skills.

**Suggested Milestones**

* Milestone 1: 
  * At the end of this milestone, the following pages should score 100% in the accessibility audit:
    * Learner dashboard
    * Creator dashboard
    * Topics and Skills dashboard
    * Classroom page
    * Exploration editor page
  * Ensure automated tests are in place (eg. axe-core, protractor-accessibility-plugin, lighthouse CI)
* Milestone 2:
  * At the end of this milestone, the following pages should score 100% in the accessibility audit: 
    * Editor page (stats, history, feedback)
    * Topics editor
    * Skills editor
  * Complete “Keyboard navigation” feature (eg. Facebook’s shortcuts):
    * Keyboard shortcuts for navigation across Oppia (eg. moving to a particular section of the same page, navigating to a new page).
    * Must include an easy to access “quick reference”.
* Milestone 3: 
  * At the end of this milestone, the following pages should score 100% in the accessibility audit: 
    * Story editor
    * Preferences
    * Profile
    * Library
    * Splash and remaining pages.

**Notes**

Your proposal should contain a detailed plan with technical details for each of the milestones and it must include mocks.

# Other useful information

## Dates and Deadlines

Noteworthy dates for 2020:
* **Jan 15 - Feb 6**: Mentoring organizations apply
* **Feb 21**: Mentoring organizations are announced
* **Mar 16 - Mar 31**: Student application period
* **Apr 27**: Accepted students are announced
* **Apr 27 - May 18**: Community bonding period
* **May 18 - Aug 10**: Students enjoy the summer by contributing code to their projects
* **Aug 25**: GSoC officially ends

## List of Mentors

TBD

## Communication

**Chat**

Oppia doesn't have an official IRC channel, but we do have a real-time chat channel on [Gitter](
https://gitter.im/oppia/oppia-chat)! You can log in using your GitHub account (Gitter will ask to be associated with your GitHub account for authentication) and you will then be able to talk in it. Please feel free to use Gitter if you just want to say hi to the community or if you have any questions related to getting started. For project-specific questions, please direct your queries to the [GSoC discussion mailing list](mailto:oppia-gsoc-discuss@googlegroups.com).

**Email**

If you have questions pertaining to "how-to-get-started", please ask them on [Gitter](
https://gitter.im/oppia/oppia-chat), or the oppia-dev@ mailing list. Please be specific when asking questions; this makes it easier for us to help you. Also, please make sure to read our ["getting started" wiki page](https://github.com/oppia/oppia/wiki/Contributing-code-to-Oppia#setting-things-up) before sending an email, since the answer to your question might already be contained there!

To discuss your project ideas, or share your proposal for feedback from the community, please email the [GSoC discussion mailing list](mailto:oppia-gsoc-discuss@googlegroups.com). You can also use this list for specific questions about GSoC.