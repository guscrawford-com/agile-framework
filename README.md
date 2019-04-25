# Agile Sessions

## Session 1 - Apr 23 2019

### Forward

#### About the Trainers

Instructor is [Kris Adams](kadams@sscinc.com)

Methods and content developed by [Henrik Knilberg](henrik.knilberg@crisp.se)

#### Goals, Introductions and Working Agreement

*My team's goals*

* Faster scrums (Joe)
* Sprint grooming is more conventional (Joe)
* Fitting epics (Derek)
* Developers tracking their time and status (Derek)
* Retrospectives (Joe)
* Understanding (from Phone)

#### Perceived Problems

* Too many meetings (Daren)

#### Agenda

* Agile
* Scrum
  * Iteration and roles
  * Events and artifacts
* User Stories and Estimation
  * Grooming / Backlog refinement
  * Planning Poker
* Additional agile concepts
* Scrum for Stakeholders

#### My Pre-existing Knowledge of Agile

* Working at level of requirments with most atomic definition of an application feature
* Working on features composed of Stories
* Working in short sprints
* Distinct and Important Meetings
  * Retrospective meetings
  * Grooming / refinements
  * Task planning and splitting meetings
  * Scrum / stand-ups


### What is Agile?

*My definition* "A work-management convention that prioritizes small iterative changes."

"Early delivery of business value"

#### Most IT Projects Fail.  And are Late.

* IT Project Success Rate 1994: `16%`
  * Average cost & time overrun: `170%`
* IT Project Success Rate 2004: `34%`
  * Average cost & time overrun: `70%`

#### We Tend to Build the Wrong Thing

 * 45% of features *never* get used
 * 19% Rarely
 * 16% ...
 * etc.

#### Big Bang = Big Risk

* *Big Bang* the deliverable comes at the end of a cumulative period of cost
* As *cumulative cost* and *value* increase, so does risk
  * Poor assumptions:
    * The customer knows what they want
    * The developers know how to build it
    * Nothing will change during development

#### Long Projects get Longer

* More likely to interrupt
* More likely to get extended
* More likely to suffer scope creep

#### Agile = Homing Missile

* Good assumptions:
  * Customer will discover what he wants
  * The developers discover how to build it
  * Things keep changing

### The Agile Umbrella

* Scrum
  * Scrumbut
  * Scrumand
* Kanban
* et al

### Iterative & Incremental

* Each jump in value adds risk
* Don't build horizontal increments of code
  * i.e. Increment 1) Create a Schema > 2) Develop an API > 3) Client / UI

<table>
    <tr>
        <td>Client</td>
        <td>3</td>
    </tr>
    <tr>
        <td>Server</td>
        <td>2</td>
    </tr>
    <tr>
        <td>Database</td>
        <td>1</td>
    </tr>
</table>

#### Delivering a Car Incrementally, Horizontally as an Example

 1. Delivered a tire >:(
 2. Delivered a chasis |:(
 3. Delivered a body with a chasis (:|
 4. Delivered a whole car :)

### Vertical Increments

#### Delivering a Conveyance Incrementally, Vertically

1. Skateboard "Need to move" :)
2. Scooter "Need to stay on conveyance" :)
3. Bike "Need speed" :)
4. Motorcyle "Need power" :)

<table>
    <tr>
        <td>Client</td>
        <td>1</td>
        <td>2</td>
    </tr>
    <tr>
        <td>Server</td>
        <td>1</td>
        <td>2</td>
    </tr>
    <tr>
        <td>Database</td>
        <td>1</td>
        <td>2</td>
    </tr>
</table>

#### Keep Your Iterations Short

* Short releases
* Testable
* Clear

### Planning

#### Estimates are Always Wrong

* Estimates in time working out to a "day" are generally closer
* "Anchoring estimates" happens when an expert gives an opinion first

### Velocity Based Release Planning

To know the future, you need to know the past

If we have a backlog of equally sized items; you can determine your velocity by averaging out previous cadences.

### Estimating

#### Features Have Different Sizes

Two ways to deal with size:

1. Ignore it
   1. It evens out over time
   2. Track velocity
2. Rough size
   1. Don't estimate time
   2. Estimate relative size of features
   3. Measure velocity per sprint
   4. Derive release plan
3. (Scrum rule) Estimates are done by people who are going to **do the work**
4. **RE**-estimate regularly
   1. Do not trust early estimates
5. Prefer verbal communication over detailed, written specifications.
6. **Avoid false precision**
   1. Better to be roughly right than precisely wrong
7. Maximize Value, not Output

### The Development Team

* Resource optimization vs Time-to-market optimzation
  * Old way
    * Specialized tasks -> Specialists
  * New way
    * Cross-functional team
      * Colocatd
      * Small (3-7 people)
    * Clear mission and product owner
    * Empowered to deliver
    * Direct contact with users & stakeholders
    * Focused.  No multitasking.
    * Transparent
    * Releasing must be *really* easy
    * The team balances long-term and short-term work

### Succeding with Software Development

#### What have we learned?

Top 5 reasons for success

1. User involvement
2. Executive management support
3. Smaller projects

### The price of agile

* Infrastructure Investments
* Reorganizaton
* New Skills
* New Habits
* Transparency

### Big is Bad



# Agile Manifesto
[The Agile Manifesto](https://agilemanifesto.org/)

## Manifesto for Agile Software Development

We are uncovering better ways of developing
software by doing it and helping others do it.

### Through this work we have come to value:

**Individuals and interactions** over processes and tools

**Working software** over comprehensive documentation

**Customer collaboration** over contract negotiation

**Responding to change** over following a plan

That is, while there is value in the items on
the right, we value the items on the left more.

### In Application:

* Satisfy the customer
* Welcome changing requierments [late in development]
* Deliver working software frequently
* Business people and developers must work together daily
* Motivated individuals build projects; give them the environment, support and trust they need
* Face-to-face conversation is the most efficient way to communicate
* Working software is the primary measure of progress
* Sustainable Development
* Technical excellence
* Simplicity, maxmizing work not done
* Self-organizing teams make the best product
* Reflecting how to be more effective as a team

----

## Session 2 - Apr 24 2019

### Scrum: an Introduction, the Iterations and the Roles

#### Recapping

*What does my team remember?*

* "Earliest delivery of business value"
* Less bureaucracy
* Minimize risk at all levels, maximize value
* Client "learning" what they want versus "already knowing" beforehand

*What are the primary Agile values?*

1. Values working code over documentaion
2. Communication [individuals and interactions] over process and tools
3. Responding to change over following a plan
4. Customer collaboration over negotiation

*Estimates*

* Always wrong
* "Relative" is better than "perceived actual"

*Development team*

* More vertically structured (cross-functional)

#### "Scrum"

*"We're losing the relay race"*

&mdash; Hirotaka Takeuchi and Ikujiro Nonaka, ["The New New Product Development Game" *Havard Business Review*](https://hbr.org/1986/01/the-new-new-product-development-game)


##### Scrum is...

* an agile framework that allows us to focus on delivering the highest business value in the shortest time.
* rapidly and repeatedly inspecting actual working software (every two weeks to one month)
* the business etting the priorities.  Teams self-oranized to determine the best way to deliver the highest priority features.
* seeing real working software and deciding to release as is or continuing enhancement

###### Characteristics

* Self-organizing teams
* Product progresses in a series of equally sized "sprints"
* Requirements are captured as items in a list of "product backlog"
* No specific engineering practices prescribed
* Uses generative rules to create an agile environment for deliverying projects
* One of the "agile processes"

*Many teams use **scrum** and then make modifications to their processes (scrumbut)*

<table>
    <tr>
        <td>Product Backlog</td>
        <td>Sprint Backlog</td>
        <td>Potentially Shippable Product Increment</td>
    </tr>
    <tr>
        <td>📥📦📦📦📦</td>
        <td>📤📦📦</td>
        <td>📦</td>
    </tr>
    <tr>
        <td>➡</td>
        <td>➡ Scrum everyday</td>
        <td>↪ 2-4 weeks</td>
    </tr>
</table>

###### Sprints

* Scrum projects make progress in a series of "sprints"
  * Analogous to Extreme Programming iterations
* Typical duration is 2-4 weeks or a calendar month at most
* A constant duration leads to a better rhythm
* Coded and tested within the sprint

###### Sequential vs. Overlapping Development

`Requirements` ➡ `Design` ➡ `Code` ➡ `Test`

*"Rather than doing all of one thing at a time... Scrum teams do a little of everything all the time"*

###### No Changes during a Sprint

* Plan sprint durations around how long you can commit to keeping change out of the sprint
* If a story will no longer provide business value; quit working on it
  * Re-plan; deliver as much value as is remaining

##### Framework

* Roles
  * Cross-functional team members (dev team)
    * Typically 5-9 people, ideally co-located
    * Cross-functional:
      * Programmers
      * Testers
      * UX Designers
    * Full-time
      * *There are some exceptions*
    * Membership only changes between sprints
  * Product-owner *never a Scrum Master*
    * Defines the features of the product
    * Makes scope and schedule decisions
    * Responsible for maximizing the value of the product
    * Prioritizes the product backlog
    * Adjust features and priority every sprint as needed
    * Accept or reject work results
  * Scrum-master *could be a member of the dev team* **role is prioritized over any others**
    * Enacts Scrum values and practices
    * Removes impediments
    * Coaches the team to their best performance
    * Enables close cooperation across all roles and functions
    * Facilitates meetings and events
    * Conflict mediation
    * [*Shit bad Scrum Masters say:*](https://www.youtube.com/watch?v=GGbsgs611MM)
      * Not participating in Retro
      * Changing sprint duration
      * Trying to manipulate velocity
      * PM and PO
      * Long standups
      * Pressuring rather than shielding
      * Allowing scrum to be non-interactive
      * Not removing impedements
* Events
  * 
* Artifacts

#### The Ball Point Game

* Pass as many balls as possible through each team meber in 2 minutes
* Rules:
  * Start point is the end point
  * Everyone must touch the ball
  * Ball must have air time
  * Ball must touch the floor
  * You cannot pass the ball to your direct neighbor

* www.scrumguides.org/scrum-uide.html
* www.mountaingoatsoftware.com/scrum
* www.scrumalliance.org
* www.scrum.org/forum
* blog.crisp.se
