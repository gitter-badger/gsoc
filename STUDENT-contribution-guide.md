<!-- markdown-toc start - Don't edit this section. Run M-x markdown-toc-generate-toc again -->
**Table of Contents**

- [Contributing Guide for Students](#contributing-guide-for-students)
    - [Getting Started Early](#getting-started-early)
    - [Am I experienced enough?](#am-i-experienced-enough)
    - [Our Expectations From Students](#our-expectations-from-students)
    - [Default Instructions](#default-instructions)
        - [How to write a great Proposal](#how-to-write-a-great-proposal)
        - [Dividing your project](#dividing-your-project)
        - [How to estimate time needed for development](#how-to-estimate-time-needed-for-development)
        - [Final Proposal](#final-proposal)

<!-- markdown-toc end -->


# Contributing Guide for Students

## Getting Started Early

Experience shows that the best thing to help your application is to contact the
organization you want to work with early. For this you can introduce yourself on
the mailing list of the organization, maybe fix a small
bug. [The opensource guide](https://opensource.guide/how-to-contribute/) has a
good introduction how to start contributing to open source projects.

## Am I experienced enough?

The answer is generally: **Yes**. We value creativity, intelligence and
enthusiasm above specific knowledge of the libraries or algorithms we use. We
think that an interested and motivated student who is willing to learn is more
valuable than anything else. The range of available projects should suit people
with different backgrounds. At the same time if you have experience using your
project of choice or one of it's dependencies (e.g. language) make sure to let
us know about that as
well.
[FLOSS manual](http://write.flossmanuals.net/gsocstudentguide/am-i-good-enough/)
gives a good overview of this part for GSoC.

## Our Expectations From Students

### During the application phase

*The tips listed here can help your application. They are not required*

Organizations usually favor students that show a regular communication with
possible mentors / organization until Google announces the accepted projects.

Establishing a regular communication is good for 2 reasons. It shows that you
are a reliable student and that you have good communication skills. Good
communication skills are an important part of GSoC since a student and mentor
can rarely meet in person.

When we evaluate an application we use the following point system to get a
baseline comparison of students. We are listing those points to help you
successfully apply and not missing an obvious point. You can always do more, but
please check those points. We will be fair, we promise. You can always ask us
and we will help you.

- 5pts Communicated with us org mentors ?
- 5pts Communicated with the community ?
- 5pts Do you reference projects you coded WITH links to repos or provided code?
- 5pts Do you provide all demanded ways of contact (email, skype, mobile/phone, and twitter, chat and/or skype if available)
- 3pts Do you add a preliminary project plan (before, during, after GSOC)?
- 3pts Do you state which project you are applying for and why you think you can do that?
- 3pts Do you have time for GSOC? This is a paid job! State that you have time in your motivation letter, and list other commitments!
- 1pts Added a link to ALL your application files to a cloud hoster like github or dropbox? (easy points! 😉 )
- 0pts Be honest! Only universal Karma points. 🙂
- 5pts Did you do push code to the existing code? Or did a bugfix?
- 5pts Communication until accepted students are announced.

### During the summer

*The items here are a requirement for students during the summer*

**Communication**

- Write a short report for us every second week in a blog
- Commit early and commit often! Push to a public repository (e.g. github) so
  that we can see and review your work.
- Actively work on our project timeline and communicate with us during the
  community bonding period.
- Communicate every working day with your mentor. Preferably in public using the
  standard channels of your project.
- If there is a reason why you can't work or can't contact us on a regular basis
  please make us aware of this.
- If you don't communicate with us regularly we will fail you.

**Evaluations**

- Set a realistic goal for all evaluation deadlines. If you fail to meet your
  own goal we are more likely to fail you in the evaluations.
- Communicate ASAP with the project mentor if evaluation metrics are unclear.

**Blog**

- keep a regular journal of your experience as a student and blog at least once
  every 2 weeks.

## Default Instructions

**This is a general guide. Organizations can have different instructions and you
must follow their instructions**

Projects proposed by mentors are listed at our [issues page](https://github.com/ESIPFed/gsoc/issues).

You are welcome to propose your own project. If you wish to do so, please
contact the organization you want to work with before you start writing your
proposal and explain your idea to them. If you choose to propose your own
project idea you will need to find a mentor for the project. **Proposals without
a mentor will not be considered.**

### How to write a great Proposal

Firstly, think about your choice of project carefully, you're going to be doing
it for a couple of months, so it's important that you choose something you're
going to enjoy. Once you've made your mind up:

1. Make sure you've thought about the project and understand what it entails.
2. Contact us early! The earlier you contact us the earlier you will be able to
   get feedback from us to improve your application.
3. Don't be afraid to come up with original solutions to the problem.
4. Don't be afraid to give us lots of detail about how you would approach the
   project.

Overall, your application should make us believe that you are capable of
completing the project and delivering the functionality to our users. If you
aren't sure about anything, get in touch with us, we're happy to advise you.

### How to estimate time needed for development

To get experience with a code base we recommend you try to fix some
easy/beginner bug or refactor a piece of code that doesn't conform to the
current style guides. Look at the code that you want to change, check if it
follows our coding guidelines. Do some research on the API's you want to use,
plan what classes you will add and how their public API will look. Write down
your algorithms in pseudo code. The better your research is and the better you
plan ahead the easier it will be to judge how long a given task will take. For
your time estimates you should also consider that you can do less stuff during
exams and try to be a bit conservative. If you have never done anything like
GSoC before you will tend to underestimate the time to complete a task. We know
that giving these estimates is not easy and that also professionals have
problems with it. Having a good plan, knowing its weak and strong points will
help a lot.

### Final Proposal

Your final proposal must be submitted to [GSoC](summerofcode.withgoogle.com) as
a PDF file, using [this template](https://github.com/ESIPFed/gsoc/blob/master/STUDENT-proposal-template.md). Your proposal name should start with *[esip-member-name]* to make
identification easier for the mentors. To convert a draft that you have written
before into PDF you can use [Pandoc][Pandoc].

~~~
$ pandoc -f markdown -t pdf YYYY/proposals/your-name.md
~~~

[issues]: https://github.com/esip/gsoc/issues
[GSoC]: http://summerofcode.withgoogle.com/
[Pandoc]: http://pandoc.org/
