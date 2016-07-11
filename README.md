# Cookbook Assessments

As part of Lab 6 in the Chef Conf 2016 Crafting Reusable Cookbooks, we will be assessing cookbooks.

The assessment should include information that answers the following:

* Does it make sense for this cookbook to be multi-platform?
* Is the cookbook attribute or resource driven?
* How tightly bound is the cookbook to any dependencies?
* Are there hidden assumptions based on the current implementation of the cookbook?
* Are there items that impact the quality of the cookbook reported on the supermarket?  Quality metrics on the supermarket currently only measure the output of a foodcritic run, and whether the cookbook has more than 1 collaborator. https://github.com/chef-cookbooks/cookbook-quality-metrics
* Is any major functionality missing?
* Is there testing?
 * Is there a fixture cookbook for testing?
 * Are the foodcritic and rubocop rules applicable?
 * What is the overall test coverage for this cookbook?
* Is there missing documentation?
 * Is the scope well defined?
 * Are dependencies accurate and up to date?
 * Are all resources, recipes, and attributes described?
 * Is there example usage?
 * Is the platform coverage accurate based on the current cookbook?
* Is the project under active development? 
 * Are there a large number of current pull requests? Are any of them useful to implement?
* Is there repetitive code that can be converted into a reusable pattern?
* Does this project affect/influence any other active projects in this workshop?
* Is the investment (time) required to correct existing issues/extend the cookbook greater than a doing a full-rewrite?
* Does it make sense to incrementally improve or completely rewrite the cookbook?


## Files should be named in the format of COOKBOOK.md within this repo. 

