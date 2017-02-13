# Voting System Flaws

Even though it has been requested numerous times, Atom doesn't have an Issue or PR voting system and, so long as I am the Community Manager, never will. There are multiple reasons for this ...

## Voting Systems Unrealistically Favor Change

Consider this situation:

1. There is a feature that is unpopular with a small fraction of people
1. The feature is liked or ignored by the vast majority of people
1. Changing the feature will require work
1. Changing the feature will disrupt the workflow of at least all of the people that like the current feature

With a voting system on Issues and PRs, the people that favor change will have a strong incentive to vote yes and encourage others who agree to vote yes. The people that favor the status quo have no incentive to even _go look to see that a vote is being held_. So a voting system for these kinds of things are already biased by design.

And if you believe that the above situation is uncommon, you would be wrong. By my experience, the above is by far the **most** common when dealing with change requests.

## Voting Systems Only Measure Popularity

When determining priority recommendations, quality assurance teams consider only two things:

1. How often is a flaw going to be encountered
1. How severe is the effect of the flaw &mdash; from highest to lowest
    1. Data loss
    1. Crashing
    1. Broken workflow
    1. Broken workflow with workaround
    1. Cosmetic

A voting system doesn't measure either of these directly and only gauges the first of the two very indirectly and inaccurately.

## Design By Committee is a Bad Idea

And if design by committee is bad, design by mob rule is even worse :scream:
