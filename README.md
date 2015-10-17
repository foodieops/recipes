## Recipes

### Purpose
Sharing recipes is great but we have all made tweaks to ones we had found over the years and it would be great if we could collect all of them together in a single place with a history of what was changed so others may look and see if similar substitutions could work for them, I mean, isn't this how our codebases and infrastructure grows? To this effect we have a repo that stores all our recipes and by looking at the commit history of each file we can see any changes over time.

I would like to encourage people to be open to building a community of food "hackers". We all enjoy food and the art or building things, be it a Mesos infrastructure or a dutch oven filled with chili. Lets combine those shared passions and see what happens!

### Layout
We have tried to keep the layout as simple as possible. If you would like to make a suggestion than open a PR and we would be happy to consider it. Please keep in mind that periodically this entire repo is built into a pdf using [pandoc](http://pandoc.org/) that will be suitable for offline printing so some things are built with this purpose in mind.

### How to contribute
**where to add the recipe**

If you should have any questions about where to drop a recipe have no fear, just open a PR against the root directory and we will merge and move it to where it belongs.

**food allergy's**

When possible we try to keep food allergy's in mind. To this effect if a recipe is safe for a specific food sensitivity listed below please include it in the recipe title, ex: **[NUT FREE] Molasses Cookies**.

- nut free
- gluten free
- vegan
- vegetarian

If you have any question please don't add it and mention this in the PR. Several of us are experienced cooks and chefs and will be more than happy to help or suggest a possible modification. Part of the fun is creating new comparable ingredient lists!

**NOTE**: Do to the nature of this project please use your own judgement when making a recipe with regards to any food sensitivities. We will try our best to ensure something is safe but we don't claim to be nutritional or medical personal and will accept no liability for any adverse reactions.

**recipe format**

In the root you will find a sample recipe, please follow that format. If your PR is not in that format we will ask you to put it into that format before merging. This is done as we will be converting each recipe to LaTex on the backend for proper typesetting and then building the repo into a pdf cookbook that will be made available for printing.
