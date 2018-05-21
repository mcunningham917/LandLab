# Contributing to landlab tutorials

Thank you for contributing to the landlab tutorials! We appreciate
your help as this is largely as volunteer effort! :heart: :heart: :heart:

# How to contribute

## Reporting Bugs

Before creating a bug report, please do at least a cursory check that the
bug has not already been reported. If it has, add a comment to the existing
issue instead of opening a new one.

### Submitting a Bug Report

Bugs are tracked as
[GitHub issues](https://guides.github.com/features/issues/). After you've
determined you've found a new bug, please open a
[new issue](https://github.com/landlab/tutorials/issues).

Explain the problem and include additional details to help maintainers
reproduce the problem. Here are some items that will make it easier
to track down the source of the problem.

*  **Use a clear and descriptive title** for the issue that identifies the
   problem.
*  **Describe the exact steps that reproduce the problem**.
*  **If possible, provide an example that demonstrates the step** as,
   for example, a bash script along with input files.
*  **Describe the behavior you are seeing after these steps**.
*  **Describe the behavior you expect to see after these steps**.

Additionally, the answers to the following questions about your run
environment will be helpful.

*  **Which version of landlab are you using?** This could be a specific
   git sha or a release number.
*  **What is he name and version of you OS?**
*  **What compiler are you using?**
*  **How did you build landlab (if using the development version)?**


## Submitting Changes

:tada: Whoa! This is great! We love it when folks contibute code! :tada:

Changes to landlab tutorials should be submitted as 
[pull requests](http://help.github.com/pull-requests/)).

*  Create a GitHub issue that describes what you propose to do.
*  Create a topic branch that contains your changes.
*  Open a new [GitHub pull request](https://github.com/landlab/tutorials/pull/new/master).
*  Ensure the PR description clearly describes the problem and solution.
   Include the relevant issue number.

## Styleguides

Use the [PEP8 style guide](https://www.python.org/dev/peps/pep-0008/).
You may want to use tools like
[Prospector](http://prospector.landscape.io/en/master/) to help out
with this.

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally
* Consider starting the commit message with an applicable emoji:
    * :art: `:art:` when improving the format/structure of the code
    * :racehorse: `:racehorse:` when improving performance
    * :non-potable_water: `:non-potable_water:` when plugging memory leaks
    * :memo: `:memo:` when writing docs
    * :penguin: `:penguin:` when fixing something on Linux
    * :apple: `:apple:` when fixing something on macOS
    * :checkered_flag: `:checkered_flag:` when fixing something on Windows
    * :bug: `:bug:` when fixing a bug
    * :fire: `:fire:` when removing code or files
    * :green_heart: `:green_heart:` when fixing the CI build
    * :white_check_mark: `:white_check_mark:` when adding tests
    * :shirt: `:shirt:` when removing linter warnings

## Adding new tutorials

If you would like to create a new tutorial that we have just a few
conventions that we would like you to follow.

* Create a new folder that will hold your tutorial notebook
  and data used by your tutorial.
* Start with the blank tutorial template provided in this repository.
* Notice that your first cell of code should import `print_function`
  from `__future__`.  Your tutorial will need to be compatible with
  both Python 2.7 and 3.4+.
* If you will be plotting anything, be sure to use include ipython
  magic command in the first cell to indicate how plots should
  be rendered.
* Your tutorial must be able to run without error for the **most
  recent landlab release**.

Thanks! :heart: :heart: :heart:

The landlab team
