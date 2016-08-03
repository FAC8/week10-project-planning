# Topics
## Linting
Choose a linter. Could go for airbnb, has docs and full style guide. Enforce everyone running the same linter. Eg don't allow people to use ES lint OR JS Hint. One or the other.

## Testing suite
Because we're now using ES modules, we can now use tape for everything. Might not be the best option if we're not using ES6 modules.
Benefit: Easier to use CI.
Testing react - Redux is conceptionally difficult. Making the front-end stateless and testable will be too difficult.
Can't enforce automated testing

## Continuous Integration
Travis, using githooks. Can set up a package that stops people merging unless it passes the linter and all the tests.
Planning on enforcing CI pretty harshly.
Consistency makes it easier to work on other people's code. Makes it easier for the code reviewer

## Limited merge access
Might have to set up a new organisation - might be able to be done in the repo.

## Code-review rules
More than one person doing the review. Pull requests should be reviewed in the order they are submitted - should they be merged in the same order? Merge conflicts are for the code writer to fix.

## Provide documentation
Linter, Testing suite, Continuous Integration, File-naming conventions, limited merge access

# Actions
* Research linters and config files and find one that will be appropriate. Sam
* Research tape to see if it will work in the way we want. Matt G
* Research setting up Travis with all the webhooks we want - Come up with a decision on code coverage to that will be enforced. Sam + Matt S
* Research how to do limited merge access in a repo. Mattia
* Writing the docs - include guidelines for reviewers. Everyone
* Deliverable by close of play - A repo with fully configured package.json, travis, webhooks, basic tests. Everyone
