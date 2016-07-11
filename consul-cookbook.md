1. Does it make sense for this cookbook to be multi-platform?
    yes

2. Is the cookbook attribute or resource driven?
    attribute driven. there are actually no resources.

3. How tightly bound is the cookbook to any dependencies?
    it is tied to Consul, since it installs Consul
    it depends on 9 other cookbooks

4. Are there hidden assumptions based on the current implementation of the cookbook?
    assumed that people are using v0.6.1 or later of consul

5. Are there items that impact the quality of the cookbook reported on the supermarket?
    large, undocumented commits

6. Is any major functionality missing?
    depending on the version, yes.

7. Is there testing?
    yes

8. Is there a fixture cookbook for testing?
    yes, for data bags

9. Are the foodcritic and rubocop rules applicable?
    yes, there are rubocop and foodcritic config files

10. What is the overall test coverage for this cookbook?
    one of the recipies does not have any sort of testing
    there are directories in tests/ for cookbooks, fixtures, integration, and spec testing

11. Is there missing documentation?
    yes, there were some changes made that was unclear to others.

12. Is the scope well defined?
    yes

13. Are dependencies accurate and up to date?
    yes, although if there is a way to put a decpendency on consul version that might help with some confusion
    otherwise there is actually a way to input which version of consul to install

14. Are all resources, recipes, and attributes described?
    These things are not defined in README.md

15. Is there example usage?
    yes

16. Is the platform coverage accurate based on the current cookbook?
    yes

17. Is the project under active development?
    yes

18. Are there a large number of current pull requests? Are any of them useful to implement?
    there is 1 pull request that fixes one of the issues presented. going through the discussion on the PR it
    seems like this would be a usefule implimatation

19. Is there repetitive code that can be converted into a reusable pattern?
    not that we saw

20. Does this project affect/influence any other active projects in this workshop?
    we do not think so
