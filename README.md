# Fitzroy Academy, v2.
***The brand spanking new 2019 build of [fitzroyacademy.com](https://fitzroyacademy.com)***

* [High level stuff](#high-level-stuff-)
	* What we're doing this year
	* Business goals and plans
	* Our values and policies
* [How we work](#how-we-work-)
	* People
	* Accounts and logins
	* Release process and project management
	* Data and governance
	* Operational and customer support: Bugs, logging, customers, etc.
	* Working with devs: Chat, video, logging, payment, etc.
* [The tech](#the-tech-)
	* Video provision
	* Design principles
	* Front end	
	* Backend
	* DevOps: Hosting, CDN, etc.

# High level stuff 🥰

The [Fitzroy Academy](https://fitzroyacademy.com) is an online social enterprise school. We create online courses and resources for entrepeneurs, educators and communities.

## What we're doing this year

In 2019 we are rebuilding the entire app, to replace the existing .com with a new app.

## Business goals and plans

We are funded for 2019 to focus on helping our partners achieve scale in South East Asian. High level goals include:

* Rebuild the app fromt scratch using #currentyear dev practice;
* Internationalise the app, starting in Khmer for our Cambodian partners;
* Onboard + test app with 5-10K new users by end 2019;
* Have resilient enterprise-level admin for our institute-level customers;
* Better governance and reporting for our funders, partners, and customers;
* New and more betterer billing + pricing structure;

More on our overall org plans [on our public 2019-2020 plan.](https://docs.google.com/document/d/1L0W1FK7eu5ulAWXFUhMhF7rEpdZ4FMnZD-H3DU5IrlI/edit#)

## Our values and policies

We're a social change org, so treating people well is _super_ important.

* [Core FA values](https://docs.google.com/document/d/1yxG_t3YyqWMZkBnVSjN-I9gKSnDiy5q78N4uGndV-2s/edit#): One page Google doc on our org-level values;
* [Code of conduct](https://fitzroyacademy.com/conduct): Our standards for behaviour;
* _We probably need more high level docs here? - WD_

-------

# How we work 💬

We're a tiny, high quality, distributed team.

## People

We need more people this year. Here's the team:

* **[@willdayble](https://github.com/willdayble):** Front end, Melbourne, AU.
* **[@yuffster](https://github.com/yuffster):** Lead tech, Washington DC, USA.
* **[@quercy](https://github.com/quercy):** Devops + deployment, Cambridge, USA.
* **Maciej:** Backend Dev, Torun, Poland
* **Saaransh Mehta** Data + analytics + ML


## Accounts + logins

We use Google accounts (name@fitzroyacademy.com) as our single point of control for almost everything, so it's easy to give access to everything all at once with one login.

### Plus:

* **Github** for code repos;
* **Trello** for project management;
* **Intercom** for user support;
* **Stripe** for money.

## Release process + project management

* TBD

## Data + governance

Collecting student data is important, using it responsibly is importanter.

### Data Philosophy:

* We aim to be [GDPR](https://eugdpr.org/) compliant by default, whilst gathering _lots_ of data for teachers and institutions;
* We will have a public description of all data we collect from users;
* Any user can download a (reasonable) copy of the data we have on them at any time;
* Users can delete their data from our servers (in a way that doesn't break the app).

### Goals of data collection

1. Help teachers and institutes do better teaching;
2. Better student learning experience;
3. Help our team build better courses and lessons;
4. Provide benchmarks for student activity to help program managers.

## Operational + customer support

* [Intercom](https://www.intercom.com/) for high level customer support.
* **Todo:** We need a support@ email centralisation thing?

## Working with devs

We work remote, so we love devs who:

* Write simple, well commented, clear code;
* Use standard best practice, not hipster-level fashionable frameworks;
* Strongly prefer to work remote than in an office;
* Are chilled out and easy to work with.

### Tools we use for development 🛠

We have a bias towards free, simple tools.

* [Github](https://www.github.com) for code
* [Appear.in](https://appear.in/fitzroyacademy) for video chat 
* [Trello](https://trello.com) for sprints + not forgetting things
* [Slack](https://www.slack.com) for text chat
* [Google docs](https://www.google.com/docs/about/) for writing things down that last
* [AWS](https://aws.amazon.com/) for infrastructure

### How we pay devs:

We are a poor self-funded social enterprise, but everyone gets paid. No interns! :)

* All devs work hour-by-hour;
* Most devs will have real jobs somewhere else;
* Devs report on how many hours done each month, and are paid via Paypal.

### How we onboard new devs:

* Speak to Will Dayble about what we need;
* Do a paid trial writing a few hours / a day-worth of code;
* If everyone's happy, agree to a rough expectation of hours / month and sally forth;

-------

# The tech 🤓

Now for the fun stuff, let's build an LMS together...

## Video provision

We use [Wistia](https://wistia.com/) for video hosting. Video is the most important part of the FA app.

## Design principles

Our core philosophy for visual, experience and app design are our [core values](https://docs.google.com/document/u/2/d/1yxG_t3YyqWMZkBnVSjN-I9gKSnDiy5q78N4uGndV-2s/edit) extended into a set of principles.

### 1. Do the right thing:

* **Use broadly accessible design practices,** e.g. [Material](https://material.io/design/) design or [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/), so that more designers can be involved at a level that suits them.
* **Design Ethically.** Value impact over form, welcome criticism and know your audience. [Mike says it better](https://muledesign.com/2017/07/a-designers-code-of-ethics) than we do!
* **Play nicely** with the whole stack. Drop the ego, avoid edge case hipsterism design fashions.

### 2. Good things take time:
* **Build art together,** and share the joy of design with our students, teachers and friends. We shouldn't go more than a few days of design without showing it to someone and asking for their advice.
* **People first.** The user is not only right, they are good looking and fun to be around. [PEBKAC errors](https://en.wiktionary.org/wiki/PEBCAK) do not exist, all user bugs are a designer's problem to fix.
* **Be healthy:** Design to remove pain and bring joy, not stickiness or addicition. Avoid [dark patterns](https://darkpatterns.org/) like the plague. Draw something, go outside, throw out the drawing and try again.

### 3. Act fast, learnt what works.
* **Guess less:** Ask important questions of our users, and answer them completely, with good design. Build less tech in response to the most important needs. Make it beautiful!
* **Patient impatience:** Fix bugs fast, but consider the long term architecture and language of the experience so they happen less.
* **Jokes!** Get them, make them. Craft moments of joy through design. Trend towards mirth before seriousness.
	
These standards should help answer most fundamental design direction questions, but here's an example for texture:

### Example Use case:

* **As a** first time Khmer student in Siem Riep
* **I need** to feel comfortable watching a video on my phone
* **So I can** know the app is worth my attention
	
### Design process:

1. **Guess less:** Speak to the student, their teacher, and learn about their life and how the app fits their schedule and time
2. Pen and paper sketch a UX flow that charges the user towards completing the "I need" goal with close to zero friction, **people first** for the whole journey.
3. **Build with accessible practices**, to make a prototype of this function in a simple framework, test it immediately with a colleague or friend
4. Do something else for a while, **be healthy**, and sleep on it.
5. Come back the next day, tweak it or throw it out, give it another go, test it again with a friend, because you're **building art together**, not satisfying a brief.
6. Test it with the student, or a good analogue. Test it again with someone else. Think through the **ethics** and impact of this design decision before committing code.

This example of a feature build process is more hands on with humans than the average geekery, because we have to work across cultures and geography *by default.*

If the systems and processes aren't available to get this hands on with people, make them happen! Right now! Have some **patient impatience** for delivering now, considering the long term, nurtutred relationships required to keep things sustainable.

Most design is 'designer done' when it's 80-90% finished and basic user needs are met. Go the extra mile by checking and rechecking with humans. This extra time, love and attention is only possible if we build fewer features overall.


## Frontend

Reinvent as few wheels as possible, use existing (simple) frameworks:

* [Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/) as a basis for the app, because it's simple and because Will D is embarrassingly old-school;
* SCSS!

### Some standards

`fit_` is the namespace preface for everything:

* `.fit_btn` is the special flexbox button 
* `data-fit_foo` is used to attach JS events, i.e. `$("[data-fit_foo]")`

P.S. put all your `data-fit_foo_bar='blerp'` at the END of elements.

### Standard for CSS (that actually cascades is):

* `.fit_foo` for everything
* `.fit_foo .subclass` for anything that cascades. We should never set a class for `.subclass` in this case, only ever `.fit_foo .subclass`
* Leave bootstrap variables as they are.


## Backend

### SDLC

The SDLC of the backend follows the structure of the frontend and the business as a whole; open source by default, declarative, version-controlled, and utilizing existing tools where possible.
* Diagrams errywhere so the system can be analyzed from multiple perspectives
	* Model our data flow/information heirarchies
		* Model the interaction between different users and our services
* Compliance is a state of being
	* Our code should match what exists, and constantly run checks to ensure that state is real
	* SOC 2, ISO 9001 shouldn't be scary words
* Automate all the things

### Service Architecture
* API-based, creating multiple, versioned, medium-sized HTTP-driven services
* Serverless (if possible) on AWS
	* Like a SquirrelBin https://aws.amazon.com/blogs/compute/the-squirrelbin-architecture-a-serverless-microservice-using-aws-lambda/
		* Keep each customer's data separate at the database level (compliance!), and in the right region (GDPR!), and enable end-user data purging
* Find a naming scheme for services and stick with it
* Keep it readable; we may come and go, but the services will remain
* Encapsulate things like Wistia with a facade so it's not hard to switch out if necessary

### Backend code
* Diagram it first, throw it away, diagram it again, and turn that into code
* Probably in Python
* Service size should be medium-small; we don't want 20 microservices to load a page. Maybe 2 or 3.
	* Don't call other services directly; you're talking to other services, not A Lambda Function (unless it's a data pipeline of some sort)

### Infrastructure
* Ideally public, Git driven, and collaborative
* Written in Terraform, ideally with PR-based infrastructure (via a tool like Atlantis) https://youtu.be/TmIPWda0IKg?t=61
* Utilizing AWS native DNS, CDN, and multi-region tools to conform to data privacy regulations
* Cutting edge but not bleeding edge; able to replace technologies (and methodologies) without great pain if they don't meet our needs

### Ops
* Copious telemetry and monitoring to make sure the system works
* Copious logging to facilitate debugging and alerting
	* If we would like to know, notify; if we need to take action, alert heinously
* Tag, tag, tag resources for security, cost management, and searchability

-------

# Other stuff / resources / junk

* Using [this guide](https://github.com/tchapi/markdown-cheatsheet/blob/master/README.md) for readme Markup
