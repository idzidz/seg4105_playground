# Shape Up - Writing a Pitch

### Listening Notes

* Primarily around building new features
* Pitch is a direction; not details, not too specific. We want to add x to y, and why.
  * Does not detail exactly how to solve it, provides a suggestion (800 words). Developer freedom.
* Mostly words, 1 or 2 sketches, and some research if necessary
* If we get too specific and provide the whole workflow and how the feature needs to be developed, we transform from writing a Pitch to a Spec, which is not what we want.
* Levels of detail
  * Too much: developers do not need to understand the feature, they are simply implementing the extremely detailed spec
  * Too little: developers do not know what we want exactly. A one-liner can become many different things depending on who is interpreting it.
* Budgets
  * If we want to budget a feature, we need to leave it as a Pitch, not a spec. It's difficult to timeline a spec, but if the team is given freedom to develop then they can attempt to develop something within that allotted time.
* Formalized pitch: work that we are going to do.
* Informal pitch: providing a very loose idea for something that we would like to have.
* Framing: step before Pitching, where you write up the idea, its possible value, etc. but you do not try to provide the solution.
* A formalized pitch needs to be written by someone who is technologically inclined, understands the domain, and understands the system where the feature is being added. They need to be capable of writing constraints and requirements.
* Problem, Appetite, Solution, Rabbit holes, No Goes
  * Rabbit Holes: For a second, it looks appealing. And then you start going down the rabbit hole, and it just gets deeper and deeper and you're noticing that you keep working and working but aren't going anywhere. Whenever something seems like it's circling around and nothing is coming of it, then that's a rabbit hole that you need to attempt to get out of.
    * Example: Building something where we need to let the user specify a time component. Apple has a feature where it'll automatically look up the timezone provided and adjust scheduling automatically depending on the current timezone. This seemed like a rabbit hole, so rather than trying to programmatically handle this logic, a simple drop-down was used to resolve this. The appetite was not there to spend an incredible amount of time on a single object which wasn't even the main feature of the form being filled out.
    * Science Project: Digging into the rabbit hole to learn with it being clear that there weren't enough time or resources to complete. Even though the feature wasn't successfully completed in time, or ever, it was still an opportunity for the developers to learn.
    * Spike / Tracer Bullet: Invest a day or two to investigate/scaffold the informal pitch to understand what we would need, and how long it would take.


### Summary

A pitch is a directional document used to decide how to build a new feature. It is not meant to be a detailed document that specifies HOW the feature should be built, but rather its purpose and value. Generally, a pitch will be around 800 words with a few pictures and potentially customer feedback; the pitch is meant to give direction to the team developing the feature without going into excruciating detail on how to implement the feature. Once we go into extreme detail, the pitch transforms into a spec which is much harder to work with; it limits the imagination of the development team while also denying them the opportunity to make modifications to the feature to meet the deadline.

It's difficult to strike the perfect balance between not enough detail, and too much detail. If too much detail is provided, then it limits the development team as already mentioned. However, if not enough detail is provided it results in the developers not knowing how the feature is expected to look or behave. For example, if we're given a simple one-liner that says "I want x to be available in our product", it doesn't paint any sort of picture of how it should look, where it should go, and what it should exactly do.

Pitches can be informal and formal; An informal pitch is usually just aiming to throw ideas around without outlining any development details. It's meant to throw ideas around and see which ones seem the most appealing. Formal pitches, on the other hand, are meant to define what has to be done. It's meant to outline what the feature should do and why, without constraining the developers too much in their implementation. Additionally, there is a step before pitching: framing. Framing is meant to define the problem, state its value, and provide additional details such as potential constraints or limitations of the system that the feature is being developed for. As a result, it is necessary that the person creating the formal pitch is technologically inclined, understandings the domain, and understands the product that the feature is being developed for.

Rabbit holes are one of the five points mentioned during the shape-up methodology. They're ideas that look appealing, but as we delve deeper and deeper into their development, we realize that it isn't quite feasible to complete this in time, and it may have been wiser to solve the problem in a different way. An interesting example is provided during the podcast where they talk about a feature in the Apple calendar that will go through quite a bit of effort to automate the handling of scheduling something in a timezone different from the one you are currently on. They spoke about how this would have been an awesome feature to have for a form that was being developed, but it was a clear rabbit hole. It would have required an immense amount of development time for a single line item on a form with several line items; it was not even the main focus of the form. As a result, they discussed how they explored simpler alternatives, such as a drop-down to allow for modification if required. However, some rabbit holes cannot be avoided and can be considered science projects. At the end of the science project, we didn't necessarily make something useful, but we learned quite a bit about the environment we were developing in.

Spikes, or Tracer Bullets, are done when there is uncertainty in how the feature should be developed. Its goal is to collect as much information as possible about the problem, which allows for a better estimation of how large the feature will be, and its potential time to ship.
