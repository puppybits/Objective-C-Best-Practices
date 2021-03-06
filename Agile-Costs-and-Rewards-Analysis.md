# Agile: A formalized process to simultaneously provide product innovation, produce constant results and methodically improve the processes and team members.

###### * if each sprint isn't getting better then you're doing something wrong.
---

#### Guard rails for starting agile
* [Are you Agile](#are-you-agile)
* [The Default Agile - Getting started on the right foot](#the-default-agile---getting-started-on-the-right-foot)
* [Key Learnings from Agile](#key-learnings-from-agile)
* [Time for self-reflection: Are you doing Agile right?](#time-for-self-reflection:-are-you-doing-agile-right)

#### Piece by Piece Analysis of Agile
* [Fleshing Out Epics & Stories](#fleshing-out-epics--stories)
* [Design Life-Cycle](#design-life-cycle)
* [Pre-Planning](#pre-planning)
* [Planning Meeting](#planning-meeting)
* [TDD (Test-Driven Development) & Unit Testing](#tdd-test-driven-development--unit-testing)
* [Living Style Guide](#living-style-guide)
* [Page Implementation](#page-implementation)
* [BDD - Functional Testing](#bdd---functional-testing)
* [Code Acceptance (Code Reviews, Merging to Master)](#code-acceptance-code-reviews-merging-to-master)
* [Testing and Acceptance Cycle](#testing-and-acceptance-cycle)
* [Continuous Integration](#continuous-integration)
* [Continual Tracked Improvement](#continual-tracked-improvement)
* [Building Out, Not Up (GIT)](#building-out-not-up-git)
* [Dead Simple Agile Start-up](#dead-simple-agile-start-up)

---
### My background
This comes from my personal experience with Agile. I've been on projects than span 5 years and other than last a couple weeks. Some have had great implementations of Agile while others just had issue. There are costs (developer time) associated in order to get the rewards (stable, useful product) in using each part of Agile. The majority of my great Agile experiences come from a single project I worked on and how the processes lead to an amazingly plyable, stable and increasingly useful product. The recommendations come from my experience with balancing the cost and rewards of Agile to create new innovative products.

To me, Agile has become fundamental and revolutionary in what it offers in discovering truths and creating virtuous cycles of improvement. The gold standard of processes has always been the Scientific Method. It progressively teaches us what is "truth" and what is false by continuing through it's processes. But there is one fatal flaw: it requires a control group. A control group means that you have one group that is 100% isolated and a second group that just has the 1 fact changed. In practice control groups are very costly, can be misleading and a lot of the times impossible to have. Agile's twist on this is to create a single group that discovers tiny deficiencies, spends a small amount of time to create a solution and objectively evaluates the implementation of the solution. It's not an end-all-be-all, its instilling constant evolution of ideas into a reality that gets closer to solving problem.

Agile is a huge bundle of processes, all with varying costs and rewards. The goal of this is to set a framework for those who haven't experienced great Agile implementations. Agile does not need a huge long-term project to be beneficial. This framework is geared toward teams jut getting of the ground with only a couple of developers and a designer. This is should be general enough to apply to anyone creating products not just software development. The two main purposes are about creating a structure where the key issues naturally bubble up to be improved upon and secondly to focus on building a stronger team that can build better products. The balance between how much cost needs to go in before reaching a reward is very difficult to weight. A lot of the rewards come from multiple processes working in tandem. The rewards outlined are merely a goal post for when you are evaluating your own implementation to self-assess how much costs you have put in and what rewards you receiving. 

---

# Guard rails for starting Agile

---

## Are you Agile?

---

The first thing is to understand is what is the purpose of Agile. __Agile is a formalized process to simultaneously provide product innovation, produce constant results and methodically improve the processes and team members.__

There are 3 tenants in this definition. If all these 3 are not addressed then your project is not really Agile. Agile is about allowing a project to self-correct, feed good results, build a stronger team and come out with a product that is useful to the end user. 

1. __Innovation:__ Innovation is not magic; it's making small pieces of functionality that can be used, evaluated and refined by the end-user. The main agile process that instills this is the __product review__. When a sprint is completed there is something that has value to the end-user. The work can be evaluated, refined and thrown away (if needed) to progressively build a product that is adapting to the needs of the end-user. The product owner then is responsible to re-prioritize the tasks to work on the next most important items.

2. __Constancy:__ In order to be constant there are 2 parts that needs addressing.  First there must be a proper planning process. The product owner has prioritized the tasks with basic documentation for each task. The process used to refine and explicitly detail each task is critical. A centralized tracking tool must be in place in which the documentation of features are continually refined. These __living documents__ allow for asynchronous work to be done in parallel and leverage of the team member that need to know, while also allowing people to jump in and out of refining the features. Once the documentation has been refined to the point that there is very little ambiguity and no dependencies that would stop the task from being built properly, it can be a candidate for a coming sprint.  The second part of instilling constancy is by having a consistent formalized process to re-evaluate the planning and execution processes. If team members are over or under utilized or tasks are not being completed something is broken and needs to get realigned. __Retrospectives__ at the end of the sprint are the main driver to enable the team to self-evaluate and collectively triage deficiencies in the product. Only the most critical problems need to have actions taken to improve. These actions taken must tracked in order to evaluated the cost and effectiveness of the proposed solution. 

3. __Methodic Improvements:__  Trackable analysis of how effective or ineffective the processes are and how the team is performing is imperative. __Key Performance Indicators__ need to be defined, tracked and visible to the product owner, generally in the product review process. This keeps the project and the team honest by having measurements to show improvements or slippage. The __Service Level Agreement__ of KPI should be continually evaluated and reevaluated in order to weight trade-off between the cost to implement/maintain something and the rewards it is delivering. It is hard to create metrics. They can become misleading if they aren't constantly improved. But without measurements there can be no subjective analysis of progress and decline.

Here's a few bullet points to help self-analyze if you're on the right track:

* Don't use email! Use a centralized system, like a wiki, that allows the team to be iterating on the understanding of what features should and shouldn't be.  
* Have short iterations. 
* The team should have a time to be introspective about what was just build and how it was built. 
* The team needs to cognitively triaging only the most important issues. (This is not a discussion, it requires a structure to allow this to come out naturally)
* Assign owners to action items and track changes. 
* Set expected reward levels and cost with implementing each Agile practice. 
* Continually evaluate processes' costs and rewards. 

#### Benefits
* Building the product is a constant process by creating the most important and useful items, judging their usefulness and re-prioritizing the next items to build. This forces you to build a product that is increasingly most useful to the end-user.
* Gage speed and quality of the output.
* Constant analysis and small effort with completing a task allows for quick changes in direction and reaffirms good decisions sooner.

#### Challenges
* Triaging is extremely difficult. 
* Staying honest and impartial about the progress, deficits and especially declines are hard to gage and take actions to correct.
* Discovering which process are interconnected. How they are structured and connected can either be mutually beneficial or be a waste of time and money. For instance, setting metics with the product owner keeps the team honest about it's progress but if there is no process for continually re-evaluating SLAs and KPIs it can quickly get into a pattern where having to meet an SLA that has been set too high requires a lot of time but without enough rewards coming out of it. Unit Testing can also have downside if there's no metrics to judge the proper amount and focus of unit tests.
* By saying you're "doing Agile" but the process is setup for failure just gives everyone a bad connotation about using Agile.

#### Happy side-effects
* Teams members build each other up by formally sharing knowledge and motivate other team members into the doing things better. This builds a better team that can in turn build better projects.
* The low cost of building something lets you throw out the bad much quicker and more constantly.
* Creating metrics and sharing metrics really do keep you honest and less bias to better self-evaluate. 

---

## The Default Agile - Getting started on the right foot

---

When getting started on Agile it's hard to find the right way to run it. A project with 2 developers for 2 months is very different than a 5 year project with 100s. The keys are to first focus on progressively defining your stories in a centralized tracking tool to allow for asynchronous working. The second is agree on a feature that can be created in a short timeline and to not accept drastic changes/redirections during the build time. And the last is to have a formalized process to let the team decide what the important issues are and take actions to improvement defects in the process. 

For each of these processes I have a couple items I use to self-assess how the process that was implemented is achieving its' goals. If you're just getting started with Agile I'd recommend writing down each process you've implemented, the goals of the process and set some rough KPIs. Here's how I go about structuring a project from scratch:

###### Get a tracking tool. 
1. Break out stories and have the creatives start adding the visuals where, have discussions on the visuals, UX requirements for the task in that story. 
2. There are tons of great tools free and paid. The point is to get something people are comfortable with and can use. A few buzzwords to get you off on the right path would be: JIRA, Basecamp, Pivotal Tracker, Rally.
3. Maintain focus to keep discussion about a story in the tracking tool. Where you have meeting to define a story better, assign one person to enter the progress in the tracking tool.
4. When directions have been taken on a story, hide or delete old conversations and roll it up into a summary.

Self-Assessment:
* Tracking. Make sure all important items are getting progress and the team isn't letting things slide.
* Asynchronous Workflow. By isolating tasks and consistently improving documentation it allows for the work to be shifted around the team better.
* Spreading the workload. If one person is getting overworked then parts of his work can be delegated to another much easier.
* Quick Ramp-up. New people brought on or current people just starting to work on a different section can understand much quicker all the details around what was done and what they should be doing.

###### Agree to a body of work by a set date and then complete the work without modifications.

1. Sprints generally are 2 weeks but they can be a week depending on the type of projects. 
2. The key is to not be changing directions mid-stream. Any change makes it less and less likely you will have a fully complete item. When means it can't be evaluated properly and you can't keep a commitment when something will be finished.
3. The planning process is on-going and should help fill in the gaps on the time actually spend coding.

Self-Assessment:
* Constancy. Improving consistency in the delivery of finished work.
* Evaluate finalized ideas. Making finalized functionality instead of a lot of half-done work that gets trashed instead of building improvements on top of.
* Product Triage. Analyze the defects and benefits of the product and work the most important items first.

###### Retrospectives and Measurements 
1. Although this takes the least amount of effort it pays off in boat loads. It's the core to have the team evaluate themselves and agree which are the important items to improve the process.
2. Try different ways to run the retro and if you're getting what you want out of it. Different ways you run the retro will pay off in different ways.
3. Personally my focus on retro is to get a collective subconsciousness of the group sync on the critical items without discussion. I like running retros when the team voices their issues verbally. Then you go around again and let others +1 to any items that others brought up but affected them. Next you take the top issues, decide if an action can be taken, have some directed discussion what should be done and assign an owner to take the action. During the following retro and product demo review the progress of each action item is reviewed.
4. Have some basic KPIs. There are two groups of KPIs that don't take a lot of time and help to bring bi-partisanship to the project: consistency and quality. For consistency some good ones to start with are having a burndown rate to track your progress during the sprint and second is the of tasks committed to and those completed. For quality the amount of defects in the testing process and time to resolution are some simple ones that can provide insights to the progress of the project. Other things like unit testing, behavior or functional testing or story point velocity are good but the cost to reward ratios can be deceptive and more complex.

Self-Assessment:
* Process Triage. Collectively analyze the main defects and benefits in the process and work towards improving the process.
* Perfectionism. Perfection is continual process of rebalancing. Everything has a cost but understanding and metricing what the rewards are is more difficult.  
* Honesty. Metrics are to keep everyone honest about what the process is and how it is improving or faltering. The metrics need to be consistent but also continually assess as a team what ever metric says about the project and what are the right things to metric. 

---

## Key Learnings from Agile

---

* The building process is about building out, not up. You should be able to have features & services that can be leveraged, refactored or swapped out without breaking the entire project.
* Tech Lead role: 
	* the base level of development skills needed for the project
	* must be coding at least 40% of the time
	* can be, but doesn't need to be, the architect 
	* generally tech leads spend too much time leading and not enough time coding and building up the team
* Architect role:
	* the target for every developer to reach
	* focuses on application strategy with minimal time on keeping the client in touch
	* level sets with tech leads
* Unit Testing has a steep learning curve and a large chasm to gain the true benefits. Also if you don't understand what or why you should or shouldn't be testing a piece of code it's probably useless and just a huge time sink. First and for most is to set KPI, track it and if you're not sure about it then remove unit testing to recalibrate your base.
* Code Reviews done properly are an excellent low-cost method to get everyone a wide knowledge of the code base and bring all developers up to the level of the architect (as well as improving the architect).
* If you schedule down to the minute, you need to make room for process improvement. 
* Getting to a decent level of documentation allows for asynchronous work, allows for more hands to fit in the pot.
* Always start with base-line developer documentation (coding styles, build setup, high-level architecture layout). 
* Tech Leads should always code more, formalize processes and track improvements/slippages. 
* Business-owners, UX, creative and tech must by off on the requirements before a story is ready for a sprint.
* Isolation is the key to most everything. Back-end services should be stubbed first, built later.
* It's not done until a non-tech can use and understand it. 
* Leverage the strengths of QA, functional automation testing and unit testing properly to have more reliable product. The strengths of each don't overlap.
* Keep dependency gathering out of email and into a tracking system.  Periodically roll-up discussion when directions are taken to keep the ramp-up time for others people to a minimum.
* QA needs to understand and test both isolation of work and integration or work.
* everybody codes, everybody is a tech lead, everybody has input in the design/UX/services process
* Using retrospectives to subconsciously have the team filter up the main issues and constantly improve the process where it's most needed. 
* The end of sprint product demos are the key to innovation. Analyze what was done. If it should be changed/improved, reset course if necessary (by queuing up tasks for a future sprint). Bring all the teams together to review the product's usefulness and how to improve.

---

## Time for self-reflection: Are you doing Agile right? 

---

* Do your good developers and testers leave work on time?
* Are you becoming more constant with completing the task agreed upon at the beginning of the sprint?
* Do you have some free time to work on improving the process?
* Are you triaging properly? When you spend time changing something on process does it make developers, testers, creative, business owners and end users happier?
* Do you have anything metric'ed and tracked across sprints? (If you're not then give an SLA to the business owner that gets a bullet point in the product demo)
* Is there enough pain when someone fails to follow and improve the process? If you have a bad coder it should be harder for him to get it bad code accepted in the sprint and simpler for him to do the code right. If they have to stay late to re-write bad code in order to make it into the sprint they will learn how to do it right so they can work less.
* When good things happen are they self-promoting to create more good things? 
* How can you show you're improving something unless it's tracked or documented?
* Are you living in isolated email accounts or collectively building better documentation to decide what/how to work?
* Are developers part of the creative process and creative part of the acceptance process?

---

# Piece by Piece Analysis of Agile

---

## Planning Process

---

### Fleshing Out Epics & Stories

Epics and stories typically come from the business owner having a problem that needs a solution in the project. Generally it is UX related and goes to the creative team to address. Creative works through the problem and solution with open communication between developers. They will be working on stories anywhere from 1 to 4 sprints ahead of development, depending on how the project is run.
Once creative has a workable solution for the epic/story, they would post it to an internal wiki. Generally these epics were for one complete page. UX boards would be annotated with numbered features. The feature would be detailed in the wiki, not the jpg files. Business owners, QA, backend and frontend would be responsible to review the page for completeness. This included that all error paths have been take account of, variants for difference in client environment (older browser with unsupported feature set, mobile, tablet, etc.), any modifications to the feature set of the standard components in the style guide and any changes to the back-end data structures. Through the wiki, all comments were tracked and notify the owner for them to iterate on and comment or post an updated version. If owner had a long delay anyone was able to read the comments and talk to the owner to get progress.
When each group reviews the documentation of the feature they would also update their own documentation. QA would write acceptance criteria for the feature to be make as complete. Back end would update any documentation to the REST API. Front end would review all documentation and either approve or reject stories entering a sprint. If a story was estimated by the front-end team to be too large, it would be broken up into multiple stories.
Once in the sprint, front-end would first build components into the style guide including the static visuals from UX and Visual. He would also build in any variants for the component into the style guide and code for other developers to use in the page. When doing page work, the front end developer would complete feature and include unit and functional testing.

#### Benefits
* Very few details got lost or forgotten along the way from the idea to the implementation of the epic.
* Every group was important in the creation and definition process.
* When a sprint started very few details slipped under the table. This lead to more constant development estimates and developers had a lot of time to focus without distractions.
* designer didn't have to re-explain to each business owner, manager, developer and creative person they talk to.

#### Challenges
* Getting people to use a wiki rather than email.
* Letting people figure out when they should use the wiki and when they should schedule a meeting to talk face-to-face.
* UX/Visual documentation in the wiki is short-term living documentation. It will get to a point that it's stale and takes a lot to time to update with no real benefit. Updating the wiki with links to the longer term living documentation and final implementation will keep the wiki relevant as the master definition for a page/feature. Development leads should include this in the sign-off process for a feature.

#### Happy side-effects
* Asynchronous work flow. This was a huge win to keep things progressing and have design on a separate track but still in sync with development.
* At every step we would be having discussions through the process of refining and detailing out what the feature would and won't do. This leads to a lot of living documentation in the wiki, style guide and automated tests which keeps the project stable and makes it easy for move around developers.
* Every group was involved in the creation process (not to be confused with the implementation process), they felt more involved in the project.
* Cross-discipline sharing is hard, especially in a large group. This process helps educate designers about limitations of the browser environment and developers of the UX/visual concerns.

---

### Pre-Planning

Ad-hoc developers reviewing task documentation from creative, back-end service methods, data model and stubs and QA acceptance criteria. This is a continual process during the sprint. Until a  developer on the team signs off on all the requirements the task can not be included in the sprint.

#### Benefits
* It fills in holes in because story points aren't a 1-to-1 to time estimates.
* Distributes planning and acceptance through-out the team.
* Not planning down to the estimate level allows for a little slack to spend on process improvement.

#### Challenges
* Some developers are weaker at understanding the requirements.

---

### Planning Meeting

Tech Leads gather definitions of tasks for upcoming sprint. Only 100% locked down tasks accepted.  QA works 1 sprint ahead to write Gherkin-style acceptance tests. Design is 1 to 2 sprints ahead to create visuals and filter UX business requirements. Back-end services is 1 sprint ahead with an agreed upon service data stubbed out. Tech Lead stays in sync with QA, Creative and other Tech Leads/Project Architect.

Tech Lead goes through task details with the entire team.  The team discusses dependancies and high-level implementation. After the team feels a task is defined they give story point estimate. Outliers are sell the case for swaying the point value. Stories larger than 5 or over broken out before they can be worked on. Occasional team member swaps to level set all teams across the build process. After the team agrees that 100% of dependancies are met and stories are broken out code-able and qa test-able, developers sign-up for tasks.

Tech Leads would also in a master scrum to help level-set between teams.

#### Benefits
* level-sets the story points based on level of effort for a normal developer
* team's velocity is track-able and compared against historical
* Complete lock on visuals, functionality, services and business-level acceptance prior to starting a sprint.

#### Challenges
* Some dependancies would be found after coding started. Developer would take the lead on fulfilling the missing requirements.
* There was never an up-front place in the process to plan the architecture. This was done after the fact in the code review. I would like to try a separate team meeting to review a proposed implement by the developer who did the pre-planning on the task.

#### Happy side-effects
* developers understood a wider-range of the code base.
* this forced the tech lead to not be leading from the top but freed up to code and focused more on quality of the developers and code and less on process
* kept developers busy with planning while QA was testing near the end of the sprint.

---

## Development Phase

---

### TDD (Test-Driven Development) & Unit Testing

TDD was prompted but not rigorously enforced. What was enforced was that Code Coverage(CC) was at 98% for the server-side page creation where back-end services would be joined with HTML/JS/CSS. Because of this insanely high metric, unit tests were required for every possible pass through the code. Unit tests were part of the build process and required to be fully isolated. Every object used in code required a mock. The mocks are injected in the setup for the test and completely makes your test separated from the rest of the code. Stubbed data needed to be created for every variant of the data that could be returned.

Controllers and models lend themselves much better to fully isolated unit testing than view code. It's almost best to forget about unit testing view code and instead lean on functional testing for views.

With TDD also comes the notation of Code Coverage reporting. Code Coverage tracks every line of code and checks it that line was hit during the unit tests. When developers first start into unit testing and code coverage they might have a tendency to attempt to make sure each line of code it recorded. That is the wrong stance. 

Unit Testing should focus on testing only the _public_ interface for a class and validating that the for a series of inputs the proper output is received. If classes are written with proper encapsulation, private methods should have almost no dependencies on outside code. Leveraging patterns like Dependency Injection, Factories and Decorators will help to keep the internal workings of a class either mockable or be triggered in the code coverage reports. Focusing on the Code Coverage metric along can lead to bad assumptions that code is "stable" when in reality it's only ridge to the process the developer subscribed and not a validation of the positive and negative results of a function being called.

#### Benefits
* The selling benefit of unit testing is that your code is more reliable by creating tests for know instance. This did happen but some of the happy side-effects are where the real gains were.
* Front-end could be isolated from back-end changes and dependancies on the back-end services.
* If an end-user effecting issue comes up, then code a unit test to make sure that is fixed and doesn't happen again (because it will).

#### Challenges
* Unit testing can not cover unknown situations that developer don't predict.
* There is a large increase of time the developer spend to write tests, mocks and stub. Also rewriting tests when things change takes a lot of time.
* If unit testing isn't built into the build process the tests will never get watched and fall by the way-side.
* Writing tests for Code Coverage can be a misdirection. 

#### Happy Side-Effects
* After 3 months of drinking the kool-aid of hard-core TDD. I reverted back to coding my unit tests after the fact.
* The biggest win is by going so in-depth in unit testing is that developer become much better. Developers see connections in code, see why and how to isolate and encapsulate functionality, pick better OO patterns, use a wider range of OO patterns. This is because it take so much "wasted" time for a developer once they get past the huge learning curve and figure out what to test, they start finding ways inside their production code to be better separated and in turn do less work in the unit test but still achieve complete isolation in the test. This did take 3 to 6 months for me to get past the how, what then the why to get there. It's a long process with a lot of grumbling and costs a lot of time. Take it on faith and do it until you've gained the respect of the code.
* I've come to rest on a mixed bag with unit testing. I ALWAYS write unit tests for risky or important code. This is code that is relying on 3rd party services, mission critical business logic, parsers or things dependent on complex state machine(like login stuff). As a project adds developers or becomes more iterative improvements, I start to solidify unit tests by enforcing mocks and stubs. If back-end services are shity then I  have the build script also rerun the back-end unit tests without the mocks/stubs and report and track the stability of back-end services. Take unit testing out for a couple sprints and see if there is an effect on your bug reports and end-user defects? If there's not a big dip you're testing the wrong things or testing too much.
* My experience with developers is generally more about them testing to meet code coverage metrics and not about properly testing all the ways their function could pass or fail. The pick wrong patterns just to give an open interface for testing. I rather spend my time reading individual unit tests to make sure the developers are testing the how the function should pass and fail and making sure they "get it" instead of watching a metric that is very misleading.

---

### Living Style Guide

After a task has all of it's dependancies completed and approved by the team, coding starts. This is front-end development, so the result of everything is that a user can do something (something that QA/automation can test). First was building a component that the site would use. Every component would be first built in the Style Guide. 

The Style Guide is and interactive, internal website. There rare a couple main sections to the Style Guide: components, page layout (some type of grid system), application controllers. Each component would have a static image from visual with all of it's defined functionality and possible visual states. It also has an interactive one that they developer would build and code and notes to leverage this component in the future.

#### Benefits
* developers can get a quick visual lay of the parts of the application and then have sample code to leverage pieces. This builds consistency and reusability of functionality.

#### Challenges
* component and functionality developed away from the end page might if push back from QA to test and validate.
* if the item for the style guide needed to be created in the same sprint as integrating it on the page there was some additional cost of time.

#### Happy Side-effects
* it gave QA, creative, developers and business-owners a place to discuss low-level functionality on a similar platform. 
* Quicker ramp up time and more diversification about which developer to tackle task in a new part of code.
* Overall the Style Guide was a massive win project wide.
* * I would have liked to see it leveraged more and includes more to set a base-line and talk about functionality with creative/ux

---

### Page Implementation


The page creation back-end would retrieve data from the stubbed services. Pull in any of the components detailed in the Style Guide and any other routing/transformation of data that was needed. Server sessions should be never be used. They add lots of dependancies on the back-end's performance and threading. It also adds states which is kills concurrency and creates a lot of side-effects.

#### Benefits
* code reusability is forefront because components are separated into different tasks
* pages are 100% functional it stub data that has been agreed upon with back-end services. QA can fully test and validate that the page works. 

#### Challenges
* end-to-end regression is addressed later when the services are complete and attached to live database data. 

#### Happy side-effects
* focus on functional automation and acceptance on the end results of the page. 

---

### BDD - Functional Testing

After the task is complete and if there is integration into a page, then QA would have previously written acceptance tests to be complete. 
Developer would write functional behavior tests. The pass/fail of the acceptance test was added into CI which would fail if the test failed. 

#### Benefits
* using stubbed data provided a higher degree of accuracy when running functional tests in the build.  * more automation allowed for continuos regression on the entire site. 

#### Challenges
* functional tests, especially restarting the browser for each test to reset a clean slate, take a long time. 
* QA spent a lot of time writing, level-setting and fleshing out testing. 
* Developer spent a lot of time building functional test. Later using a page level and story level class structure helped cut down on CCP metric and gave better reuse ability in the BDD framework. 
* code refractors and changing visuals were more costly. 

#### Happy side-effects
* developer were better in the planning stage because they could see and add a complete list of functionality for a given item. 

---

### Code Acceptance (Code Reviews, Merging to Master)

After a task was completed by the developer they would make sure  all they had created the unit and behavior functional testing. Running the build script would validate code completion and run through the functional testing only for the affected session. This was for performance reasons since behavior tests should be isolated and each test would restart close and reopen the browser it could get tedious. Once a passing grade was received the developer would open a code review.

The code review would need to be linked to the documentation of the back-end services, visual/UX and anything else pertinent. The code would need to be accepted by 1 official code reviewer (approved by the architect) and 2 nonofficial code reviewers. Official code reviewers frequently had the architect review their code as well.

If the code was reject, it would be refactored according to notes in the code review and a new review would be opened. After the code review was accepted, along with a review of the unit test and behavior test the code was allowed into the master branch. If the unit test or behavior test wasn't completed a code review could still be opened for the main task to be in the review process while the developer was working to complete the task. QA testing also was not dependent on code being into the main branch. Since QA was testing functionality of a feature on the page it is separate from end-to-end and regression testing.

#### Benefits
* Non-performant code almost never made it into the release.
* Proper application of OO patterns was enforced.
* Massive amounts of tech debit was averted. Sometimes causing a developer to completely re-write his task mid-sprint.
* The coding style guide document would be continuously updated when new items were addressed in code reviews.
* Have a tool is CRITICAL. Tracking commits and being able to work asynchronously is critical.
* Developers will fill up more end-of-sprint time doing code reviews and understanding a wider base of the application as well ad being able to be critical about the application of other developers OO patterns.
  
#### Challenges
* No architectural planning structure lead to ad-hoc discussions and in the worse cause a developer would be scrabbling to re-factor his entire code at the tail end of a sprint.
* Sometimes an official code reviewer were hard to come by. 

#### Happy side-effects
* Code reviews disseminate best practices from the architect down to all the developers. This is a massive win. It brings up the code of the entire team up very quickly and almost acted as a proxy for the architect coding the entire site himself.
* This was a massive win for getting developers to talk about if they made the right OO design decisions and self-educate the group with tips and tricks.
* commented code, magic numbers, anti-patterns and progressively slipping code quality was almost eliminated.

---

### Testing and Acceptance Cycle

QA creates gherkin-style acceptance testing that is agreed upon with development prior to accepting a task into the sprint. Acceptance criteria is defined prior to a task being accepted in a sprint. 

Generally QA starts a sprint by creating acceptance criteria for the upcoming sprint. At the end of the sprint developer are freed up to review acceptance criteria and either accept or work with the QA to agree on modifications to the tests. 

The second week of the sprint QA is switching focus more to manual testing and regression on the features for the current sprint. During this time developer are wrapping up coding the functionality and focusing more on code reviews, writing the BDDs for the acceptance test and reviewing all the do do documentation for the upcoming sprint. 

#### Benefits 
* having acceptance criteria prior to task acceptance allows for a deeper understanding and exposes more details for the developer to make a better assessment that all dependencies have been completed. 
* acceptance tests also spend the work on the QA more evenly when it tends to cluster into a mad dash and frequent overtime at the end of a sprint. 

#### Challenges
* regressions are a little for sparse while QA is focusing time on creating the acceptance. 
* lots of time is spent writing automated testing a d there is not a counter-factual to judge their worth or what is a comparable level of automation. 

#### Happy side-effects
* QA has a much deeper understanding of what they are testing, what should and shouldn’t be automated and have a better working communication with development. 

---

### Continuous Integration

Continuous Integration centers around the idea of running the test suite every time the code is changed. This keeps all the tests that were written useful. Unless the tests are being run consistently they can't alert team members to any potential changes that will break in production.

The source code repository is watched for changes. When new changes are checked in the CI server triggers. It builds the project and runs through any unit, integration or functional tests. The goal it to always have a build that is functional and free of any known bugs that the automated tests cover. 

#### Benefits
* having a nightly stable build means your fixing problems as they arise. This means less tech debt for the project. 
* keeps the project honest about its progress. 

#### Challenges
* everyone needs to daily maintain the build or having CI is useless. 
* automated testing is only as good as the tests are written. If tests are just checking that functions are called or lines are hit and not that the data flow is correct they aren't doing as much as they should. 
* having CI doesn't help much unless its running a test suite. 

#### Happy side-effects
* CI is a great example of living documentation. Unit tests and functional tests document how you project should pass/fail and running them on a schedule keeps them alive. Iterating on documentation whether automated tests or design or functional specification is the most underrated process but yields some of the highest rewards.  

---

### Continual Tracked Improvement
 
Retrospectives are a key part of agile that should NEVER be left out. A key part of Agile is continuos improvement. Retrospectives are the only point where the team has an formalized open forum to bring up grievances and breaks in the process.

Our retrospectives started by having one developer say one thing that was good and everything bad that came up during the sprint. It would go around the room until all developers had a chance to bring up any issues. It worked best when developers would track issues during the sprint and be able to shotgun through their list in the meeting. Then there would be another pass around for developer to +1 on any task that was a big issue on the sprint. 

The top 3 or 4 items usually would be brought out and discussed until there was something actionable that could happen. One person would volunteer to be the owner of the issue and work towards improvements during the following sprint. 

Retrospectives were tracked and shared across teams. They would also receive a bullet point in the stack holder demo review meeting. It would cover main issues on the teams and what had been improvements had been taken from last sprint. No actions are carried or tracked on past sprint until an item had re-appeared in the current sprint's retrospective.

#### Benefits
* Without triaging issues and taking actions to improve the process there is no Agile
* Continuos self-analysis by everyone.
* Constant incremental improvement on the process. Re-weighting the costs of some process with the rewards.

#### Challenges
* There are many ways to do retrospectives. Going through different techniques and analyzing the strengths and weaknesses of the techniques will create better triaging of the issues.
* Having a well-trained leader for the retrospective is important in getting the most of out it.

#### Happy side-effects
* The implementation of this technique in this manner breeds a wonderful subconscious agreement on what is most critical to fix and what should be done to attempt to fix it.
* It focused on collaboration with no discussion. Only having one person talking and the leader of the meeting writing down the items (almost not having to say anything), and giving other team members a change to reflect and think about the impacts. This turns the tech lead from a director controlling everything into creating an environment and opportunity where the team can collectively rise.

---

### Building Out, Not Up (GIT)

A lot of development practices are still building one task at a time and stacking that work on top of the next. This builds bigger and bigger structures that are all reliant on the complete stack in order to function. 
So many teams are in the mind-set of SVN and Perforce, building features in stacks. This is analogous to building a skyscraper; each piece is inherently connected to the previous. The 40th floor can't be built until the 1st floor is built. 
Instead tools like Git allow for a new base. Building out means there are some common shared features like plumbing, electricity and roads but each structure can be build with rough isolation to the base. They have common components to connect each other but when one structure is needed it can be built or modified without much effect on the rest of the environment.
In real-world terms, this means having commits to the repository be 100% specific to the task. The subject line of the commit to be specific to what it does. Rolling up (or squashing) groups of commits into more flesh out features. Pulling features out of the build with minimal effort to the rest of the build. Creating UI components that contain their own sub-set of the data. Data models that include all the possibly transforms (instead of a view or controller making transforms). Having the possibility that every single developer, QA and user is on a slightly different version of the project and code AND builds can be shared and evaluated between others in the group. This means developers can be building a feature, switch to for a QA version, make a change, push it to QA and while QA is testing the developer can continue developing.

#### Benefits
* Merging, branching, committing and managing multiple variations of a build are possible.
* Making changes locally first, self-validating the that change is correct and then pushing to the group is a massive revolution!
* Asynchronous working between multiple time zones is both faster and more efficient. 

#### Challenges
* Learning Curve. Getting developers to commit properly, understand the workflow and the changes from a CVS. I have never seen anyone go through the learning curve to use git that ever wanted to touch SVN/Perforce again.
* Building the code base in a way that takes advantage of git playability. 
* Code bases can get out of date easier if the team isn't structured to push and pull common code on a regular basis.

#### Happy side-effects
* Developers love their tools more, use to more often and more effectively.
* Iterating on a project and fixing bugs becomes less time consuming do to a better base tool set.
* Developers can have a personal workflow themselves with how to commit and squash and push changes to the group and maintain a more group work flow when it comes to managing features and version.


---


# Dead Simple Agile Start-up

---

**This is the lightest version of agile that I've found. It's a simple base that can be built on top of as the project grows.**  

* Use a wiki tool to review version of visual designs and detail out the feature set. Do NOT work through emails. Face-to-face can also cause problems if the team is more than 2 people or details are being defined during the sprint.
* Use kanban or an agile tool to break the epics from the UX/visual team into functional stories that give the user a workable feature.
* In the planning phase, review the requirements in wiki and accept stories that are important and don't have any ambiguity. 
* Each story needs a clear defination of what complete means from the product owner and QA.
* Start the sprint by have the team walk through the stories, estimate the work and agree what can be done for the sprint.
* Development should be a little staggered. Smaller tasks can be completed earilier to get QA testing. All development work should be done in time for QA to test and any bug fixes to happen in the sprint window.
* The outcome of the sprint must have something useable by the end-user.
* The product demo will be the final sign off from the product owner on the work.
* Each sprint MUST have a retrospective. This is critical for the team to address the issues and take action items to improve only the most important issue to improve the following sprint.

<table border=0 cellpadding=0 cellspacing=0 width=100% style='border-collapse: collapse;table-layout:fixed;width:100%'> <col width=212 style='mso-width-source:userset;mso-width-alt:9045;width:212pt'> <col width=65 span=10 style='width:65pt'> <tr height=42 style='mso-height-source:userset;height:42.0pt'><td height=42 width=212 style='height:42.0pt;width:212pt'></td><td class=xl65 colspan=3 width=195 style='mso-ignore:colspan;width:195pt'>Sample2 week Sprint cadance</td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td><td width=65 style='width:65pt'></td> </tr> <tr height=20 style='height:20.0pt'><td height=20 class=xl66 style='height:20.0pt'>Developers</td><td colspan=10 style='mso-ignore:colspan'></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt'>days</td><td class=xl68>1</td><td class=xl68>2</td><td class=xl68>3</td><td class=xl68>4</td><td class=xl68>5</td><td class=xl68>6</td><td class=xl68>7</td><td class=xl68>8</td><td class=xl68>9</td><td class=xl68>10</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>reviewingrequirements</td><td class=xl69>50%</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl69>10%</td><td class=xl69>20%</td><td class=xl69>30%</td><td class=xl69>10%</td><td class=xl69>30%</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>coding</td><td class=xl69>50%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>60%</td><td class=xl69></td><td class=xl70></td><td class=xl70></td><td class=xl70></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>code hardening(testing/bug fixing)</td><td class=xl70></td><td class=xl69></td><td class=xl69></td><td class=xl69></td><td class=xl69></td><td class=xl69></td><td class=xl69></td><td class=xl69>40%</td><td class=xl69>60%</td><td class=xl69>60%</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>code reviews</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl69>10%</td><td class=xl69>60%</td><td class=xl69>30%</td><td class=xl69>30%</td><td class=xl70></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>behaviortesting</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl69>20%</td><td class=xl69>20%</td><td class=xl70></td><td class=xl70></td><td class=xl70></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>planningmeeting (w/ QA and creative)</td><td class=xl70>x</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>retrospective(w/ QA)</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70>x</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>scrum</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td> </tr> <tr height=48 style='mso-height-source:userset;height:48.0pt'><td height=48 class=xl66 style='height:48.0pt'>QA</td><td colspan=10 style='mso-ignore:colspan'></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt'>days</td><td class=xl68>1</td><td class=xl68>2</td><td class=xl68>3</td><td class=xl68>4</td><td class=xl68>5</td><td class=xl68>6</td><td class=xl68>7</td><td class=xl68>8</td><td class=xl68>9</td><td class=xl68>10</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>accectanceplanning for future sprint</td><td class=xl69>50%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>50%</td><td class=xl69>50%</td><td class=xl70></td><td class=xl69></td><td class=xl69></td><td class=xl69></td><td class=xl69></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>Testing/creating bugs</td><td class=xl70></td><td class=xl69></td><td class=xl69></td><td class=xl69>50%</td><td class=xl69>50%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>100%</td><td class=xl69>100%</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>retrospective(w/ QA)</td><td class=xl70>x</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>retrospective</td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70></td><td class=xl70>x</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>acceptance/validationof task completion</td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl71></td><td class=xl70>x</td><td class=xl70>x</td> </tr> <tr height=15 style='height:15.0pt'><td height=15 class=xl67 style='height:15.0pt;border-top:none'>scrum</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td><td class=xl70>x</td> </tr></table>



