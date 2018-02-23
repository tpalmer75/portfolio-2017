# Lucid Design System

![](cover.png)

## Purpose
When I first arrived at Lucid, there was a loose style guide for only small, specific sections to the product. Everything else had been designed and built from scratch by engineers before the design team formed.

In late 2016, we began laying the ground work for a complete redesign of Lucid’s flagship product, Lucidchart. As the engineering team worked to develop a new codebase from the ground up, the design team stayed in step by crafting reusable patterns and components for a cleaner front end.

![Components Overview](overview.png)

## My Role
Many hands touch a design system, and any good design system is robust enough to take input from an entire team. Because I was the lead designer on the Lucidchart redesign, a significant portion of that work became (unknowingly) the foundation of a new visual style for Lucid products.

Since then, I’ve met frequently with engineering team leads and other stakeholders to ensure consistency and compatibility, while also carefully striking the balance between constraint and evolution. Because a design system can’t account for every design problem, it needs a framework to allow for the introduction of new patterns.

## Experiments and Testing
The Lucid design team has hovered around 6 designers for the past few years. Those designers worked on different cross-functional teams, and sometimes iterated and innovated on existing patterns. To propose this pattern to the design system, they place it on a page in the design system Sketch file called “Experiments and Testing.” We review this page in our biweekly team meetings.

## Innovating on the Handoff Workflow

![Using Zeplin.io for Handoff](zeplin.png)


When redlining apps like Zeplin and Avocode started to show up in 2016, we were quick to jump on board. We’ve used Zeplin for design handoff ever since. It’s even adjusted to deliver the appropriate Less CSS color variables from our design system.

While a design system promotes accuracy and consistency among designers, however, it’s not always analogous with an engineering component library. Every attempt to create such a library at Lucid had failed in the past. Rather than continue in vain to promote a component library to 60 engineers on different teams, the design team took the burden of documentation on themselves, and we created what we call “The Bill of Materials.”

Essentially, it’s a list of the engineering (in this case, Angular 2) components that were used to compose the design. It contains some unique information that’s helpful for construction of the interface:

* The code name of the component (ex: <lucid-button>)
* The name of the designer who originally designed it
* The name of the engineer who originally built it
* A few example locations where it can be found to see how it was implemented
* A component status: is this brand new, already existing, needing modification, etc.

![An example Bill of Materials](bill-of-materials.png)

With these tools in hand, we empowered engineers to understand exactly what they’re building and who to talk to if they have questions.

With each story, we try to handoff a Zeplin link for redlining and a Bill of Materials for component review.

## Lessons Learned
We tend to review and revise our design system about every year (in additional to the bi-weekly check-ins). Along the way, there are certain things I wish we had tackled from the beginning. For example:

### 1. Missing steps in the design system
Some designs systems refer to these as “Foundations”, but we simply ignored the basic buildings blocks of any style guide. Spacing, grid, and typography are completely lacking, so some components don’t quite feel like they’re part of the family.

### 2. Don’t just show it, explain why
When new hires come on the team, they see an endless wall of Sketch components and symbols. What’s missing is understanding _when_ and _why_ to use these different components. When should a designer use a dropdown, radio buttons, check boxes, or a toggle switch? These answers might be different for each organization, but it should be the same across the design team.

### 3. A design system needs a lot more than components.
In my [Lucid Voice and Tone](http://taylorpalmer.co/projects/lucid-voice-and-tone/) project I showed how important messaging and copy is to design. These, and other fine-tuned philosophies, can help a brand feel cohesive. We hope to add even more guidelines, like motion, in the future.

## Next Steps
At the time of writing, February 2018, I and another team member are working on the revising the design system and implementing the new ideas mentioned above.