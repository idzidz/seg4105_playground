# Shape Up - Bet Summary

## Chapter 7 - Bets, Not Backlogs

* No backlogs
    * Backlogs are big time wasters; have to spend time reviewing them as time goes on and potentially updating them to keep them relevant to our ever evolving systems

<br>

* Betting Table - Pitches (Potential Bets)
    * Rather than doing backlogs, we hold a <b>betting table</b> before a six-week cycle.
    * During the betting table, stakeholders will review either pitches from the last six weeks or pitches from previous cycles that have been brought up again.
    * Ensures that we only look at fresh pitches that are still relevant. Saves us the time from reviewing old pitches that may not be relevant anymore.
    * After reviewing the pitches, we decide to bet on a few of them and build them during the upcoming cycle. Pitches that aren't bet on are let go rather than being backlogged.

<br>

* Decentralized Lists
    * Rather than keeping a backlog or a giant centralized list of all bugs, features we want to add, or improvements, we have support or each developer maintain their own lists.
    * Regular meetings between different departments can help them share their ideas and see what should have higher priority.
        * For example, support can discuss with development what customers are having the most difficulties with, and developers would also express what they'd like to fix or potentially add. These two parties can then discuss what they have the biggest appetite for, and what would bring the most value.

<br>

* Important Ideas Reappear
    * Ideas aren't expensive, and are bountiful. If a pitch gets let go, but for example, customers continue to bring up something that the pitch would address, it will naturally re-appear on the betting table.

<br>

## Chapter 8 - The Betting Table

* Cool-down
    * After each six-week cycle, give developers 2 weeks to think about new ideas, create potential pitches, fix bugs, explore new technologies, etc.

<br>

* Teams and Project Sizes
    * In addition to a standard development cycle, team structures are also standardized. One designer, 1-2 Developers, and QA for testing closer to release.
    * <b><u>Big Batch Team</u></b>
        * Spends the entire cycle working on a single project
    * <b><u>Small Batch Team</u></b>
        * Spends the cycle working on several smaller projects
    
<br>

* The Betting Table (During Cool-down)
    * Basecamp example has the CEO, CTO, a senior developer, and a product strategist at the helm of their betting table.
        * Allows for decisions on projects/features to be final. Does not need an approval step from higher-ups on the pitches we bet on

<br>

* Meaning of a Bet
    * Payout - the result of the 6 week cycle. Expects a product finished to some degree, rather than incremental progress in shorter cycles
    * Commitments to specific workloads (Big Batch vs Small Batch)
    * Limited downside - allocate only 6 weeks to something, worst case lose 6 weeks. No rabbit holes of continuing incremental progression over a handful of 2 week cycles.

<br>

* Uninterrupted Time
    * Stepping away from your project for a moment to help somebody else on theirs can have big impacts. "Just one day" can not only spiral into more, but it also ruins the momentum you had on your own project.

<br>

* Circuit Breaker
    * If a project isn't finished in six weeks, it isn't given more time to be completed necessarily. Will get re-evaluated and the team will attempt to locate what rabbit hole lead to this, or what other potential issues may have arose
        * As a result, six-week cycle acts as a circuit breaker to ensure we don't use more resources than we have on a project that overflows out of the six-week cycle
    * Teams are given full authority on the execution of their project. Allows them to ensure that something ships.

<br>

* Bugs
    * Bugs can be categorized into:
        * Severe: System is not usable, and requires immediate fixing
        * Regular: Can wait for the next 6 week cycle to get resolved, does not compromise the use of the system
    * When to fix bugs
        * During cool-down
        * Bring up a bug that is too big to fix during the cool-down to the betting table
        * <b><u>Bug Smash:</u></b> dedicate a whole cycle (usually near end of year/holiday) to just fixing bugs

<br>

## Chapter 9 - Place Your Bets

* Type of Product
    * Existing products
        * Easier to build new features for
    * New products
        * R&D Mode: Spike / Science projecting
            * Experimenting with new product ideas. We're not sure what we need, what will work. Sort of like science project mode.
            * Cannot ship this in one cycle to customers. Requires several cycles for foundation, integration, and preparation. 
            * Senior team will help lead the vision
            * Goal for the cycle is to lay a foundation, not complete the entire project
        * Production Mode: Shaping for Production
            * Want to get the project ready for prod, have multiple teams working in parallel on components A, B, etc.
            * This is where we can deliberately shape again. R&D was more open, but production mode we want to define clear goals and timelines.
        * Cleanup Mode: All teams Bug Smashing
            * Before launch to prod
            * All teams will collaborate if needed. This means teams A and B will group together to finish the integration of their components to the final project
            * Continuously merge into main codebase for features we want to keep, discard features we don't want to keep (leadership discretion)

<br>

* Questions to Ask at the Betting Table
    * Does the problem matter?
        * Solution is irrelevant if the problem isn't important for us to solve in the first place.
        * If the problem matters, explore solution difficulty and potential alternatives
    * Right Appetite?
        * If the appetite is low for a feature, we can try a few things:
            * Re-articulate the problem in a better way for stakeholders to understand
            * Discuss what the turn off is for the feature
            * Go back to the  drawing table and work on a smaller version of the feature to meet the appetite, or do more research to give a better pitch
            * Finally, let it go if stakeholders aren't interested after your attempts to reconcile. 
    * Attractive Solution / Right time / Right people
        * We may want to solve a problem, but there are several ways to achieve a solution. Want to create a solution that won't potentially incur technical debt or other struggles in the future
        * Is it the right time to work on a feature? May want to get all developers to work on a giant feature to get public interest
        * Are the right people available to work on this feature? 
