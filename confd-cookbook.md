###Does it make sense for this cookbook to be mult-platform?
Yes, confd is not only for one distribution

###Is the cookbook attribute or resource driver?
It is resource driven with some attributes that can be changed.

###How tightly bound is the cookbook to any dependencies?
it depends of poise >= 2.2, poise-service >= 1.0, rc >= 1.3

###Are all resources, recipes, and attributes described?
No. Only confd_template is described. There are 3 more no described. None of the attributes are described.

###Is there exampel usage?
Only for confd_template resource
