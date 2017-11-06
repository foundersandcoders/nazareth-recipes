# Contribution guidelines

+ [Before adding or editing a recipe](#before-adding-or-editing-a-recipe)
  + [Labels](#labels)
+ [Recipe Structure](#recipe-structure)
  + [Badges](#badges)
+ [Pull requests](pull-requests)
+ [Instructions for maintainers](#instructions-for-maintainers)

## Before adding or editing a recipe

 1. Search this repo's [issues](https://www.github.com/foundersandcoders/nazareth-recipes/issues) to see if an issue exists for the recipe.
 2. If the issue does not exist, create it.
 3. If your new issue relates to any others, reference those issues in the body. This enables others to follow the history of the topic.
 4. Assign [the appropriate label](#labels). **All recipe issues must have labels**
 5. Once you are sure of what you need to do and that it is needed, assign yourself to the issue.
 6. Clone, and create a new branch for your work

### Labels
Advice for labeling your recipes:

  - Indicate what meal your recipe might apply to (breakfast, lunch or dinner) - it can apply to more than one.
  - Indicate whether or not the meal is vegetarian friendly
  - Add any other labels you feel might be appropriate.

## Recipe Structure
You can use the following skeleton as a guide
```
# Name of Dish Here

- Badges here

**Head Chef:** 

**Sous Chef:** 

**Date Cooked:** 

**Number of servings:** 

**Author of Recipe:** 

## Ingredients
- Add all the ingredients here

## Preparation

1. Add step by step instructions here, ideally including photos of the process and/or finished product
2. etc

Photos of meal participants enjoying the food should come after the recipe
```
### Badges

All recipes should have the following badges: [Difficulty](#difficulty), [Speed](#speed), [Reception](#reception), [Cost](#cost), [Vegetarian](#vegetarian), [Vegan](#vegan)

Feel free to add other any badges you deem appropriate!

The badges can be contructed using the following url: ```https://img.shields.io/badge/<SUBJECT>-<STATUS>-<COLOUR>.svg``` (credit: https://shields.io/)

The subject should be one of the above, see directions below for status and colour guidance.
#### Difficulty ![Difficulty Badge](https://img.shields.io/badge/Difficulty-70%25-orange.svg)
- STATUS: A percentage. Format should be the percentage number followed by ```%25```
- COLOUR: One of 5 colours, corresponding to the status as follows:
  - 0-19% -```brightgreen```
  - 20-39% -```green```
  - 40-59% -```yellow```
  - 60-79% -```orange```
  - 80-100% -```red```

#### Speed ![Speed Badge](https://img.shields.io/badge/Speed-1hr-yellow.svg)
- STATUS: A time, in hours: ```0.5hrs, 1hr, 1.5hrs```
- COLOUR: One of 5 colours, corresponding to the status as follows:
  - < 0.5hrs -```brightgreen```
  - 0.5-0.9hrs -```green```
  - 1-1.4hrs -```yellow```
  - 1.5-1.9hrs -```orange```
  - 2hrs+ -```red```

#### Reception ![Reception Badge](https://img.shields.io/badge/Reception-Positive-green.svg)
- STATUS: A value: ```Very%20Negative```, ```Negative```, ```Ambivalent```, ```Positive```, ```Very%20Positive```
- COLOUR: One of 5 colours, corresponding to the status as follows:
  - Very Postive -```brightgreen```
  - Postive -```green```
  - Ambivalent -```yellow```
  - Negative -```orange```
  - Very Negative -```red```

#### Cost ![Cost Badge](https://img.shields.io/badge/Cost-Cheap-green.svg)
- STATUS: A value: ```Very%20Cheap```, ```Cheap```, ```Average```, ```Expensive```, ```Very%20Expensive```
- COLOUR: One of 5 colours, corresponding to the status as follows:
  - Very Expensive -```red```
  - Expensive -```orange```
  - Average -```yellow```
  - Cheap -```green```
  - Very Cheap -```brightgreen```
#### Vegetarian ![Vegetarian Friendly Badge](https://img.shields.io/badge/Vegetarian-True-brightgreen.svg)
- STATUS: Boolean
- Colour: One of 2 colours:
 - FALSE: ```red```
 - TRUE: ```brightgreen```

#### Vegan ![Vegan Friendly Badge](https://img.shields.io/badge/Vegan-False-red.svg)
- STATUS: Boolean
- Colour: One of 2 colours:
 - FALSE: ```red```
 - TRUE: ```brightgreen```

## Pull Requests

Once you have finished your work, push up your branch and make a pull request. Remember, a pull request should be as small as possible. This makes the review process quick and easy.

Make sure your PR has the following

  1. [A descriptive title](https://gist.github.com/mikepea/863f63d6e37281e329f8#ensure-there-is-a-solid-title-and-summary) - distinct from others and therefore searchable
  2. [A body with details of everything in the pull.](https://gist.github.com/mikepea/863f63d6e37281e329f8#ensure-there-is-a-solid-title-and-summary)
  3. Reference to any/all related issues in description.
  4. Assignees - add all the maintainers of `nazareth-recipes` to every PR:
    + [@sofer](https://github.com/sofer)
    + [@mattlub](https://github.com/mattlub)
    + [@m4v15](https://github.com/m4v15)
    + [@karyum](https://github.com/karyum)

  5. Reviewers
    + add anyone other than the maintainers, who you think should be aware of the recipe  
    e.g. anyone else who ate the food, or has expressed an interest in knowing the recipe
    + if your PR _requires_ a review from a particular person / people _before_ it is ready to be merged, specify this within the body of your PR
    + Only maintainers should merge the PR's - if they are slacking, please feel free to give them a nudge in the comments of the PR.

## Instructions for maintainers
Once a pull request has been reviewed by 3 people **who ate the meal**, as well as or including a maintainer, it can be merged. A PR should never be merged if a reviewer has requested changes and not yet re-reviewed it.

If a PR is up for an unreasonable amount of time without progress, maintainers should consult the creator on whether or not it will be finished at some point, and if not, close it.
# Thank you!

P.S. please star this repo.
