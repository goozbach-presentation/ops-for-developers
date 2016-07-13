author: Derek Carter aka 'goozbach'  
company: Goozbach Infrastructure Solutions  
title: Ops for Developers  
subtitle: Because I can't bring myself to use the term 'DevOps'  
footer: Derek Carter  -- derek@goozbach.com  
subfooter: http://presentation.goozbach.com/  

# Historically
Developers  
vs  
Operations  

# Contrary Objectives (devs)
* Product Specs/Features
* Bug Fixes
* Fast Fast Fast

# Contrary Objectives (ops)
* Uptime is king
* Resources
  * Hardware
  * Bandwidth
* Disaster Recovery
* Capacity Planning
* Security
 
# Tools (devs)
* Test Driven Development
* Scrum
* Agile
* Waterfall
* Libraries and Frameworks

# Tools (ops)
* CapEX
* Maintainers Windows
* Change management
* Install Servers
* SSH
* Bash

# There is a Better Way
* `DevOps` movement
* Less `us vs them`
* More `All of us for the customer/product`

# Building Blocks of DevOps
* Source Control
  * SCM
    * SVN
    * Git
  * Versioning
    * http://semver.org

# Versioning
* This

        http://example.com/api/foo/new/

* VS This

        http://example.com/api/1.0.0/foo/new/

# Self Service Infrastructure
* Reduce dependency on Ops team
* No more `waiting on sysadmin to buy/hang/configure servers`
* Configuration management
  * Ansible
  * Puppet
  * Chef
* Functional Tests
* Continuous Integration

# Making DevOps Work
* Proper `Stacks`
  * production
  * QA/Testing/Preprod
  * Development

# Stack holy grail
* Production not touched by human hands
  * If you logged in you have failed.
* QA stack matches Production as closely as possible
* Dev stack *VERY* cheap to produce/destroy
* Multiple Dev stacks
  * Vagrant files anyone?

# Keeping Tabs
* You cannot improve what you do not measure
* Monitoring
* Trending
* Alerting

# What do we aspire to?
* Etsy
* Fuse

# Where do I start?
http://www.opsreportcard.com/

# References
* Devops
  * [devops and enterprise inertia](https://major.io/2014/04/17/devops-and-enterprise-inertia/)
  * [the developer is dead](http://www.paperplanes.de/2014/4/17/the-developer-is-dead.html)
  * [killing the developer](http://jeffknupp.com/blog/2014/04/15/how-devops-is-killing-the-developer/)
  * [distilling devops](http://michaeldehaan.net/post/19059316216/distilling-devops)
  * [Code as craft](http://codeascraft.com/)
* Books
  * [Information Technology corrosion competitive advantage](http://www.amazon.com/Information-Technology-Corrosion-Competitive-Advantage/dp/1591394449)
* Virtual Environments
  * [Vagrant](http://www.vagrantup.com/)
  * [Vagrant Boxes](http://www.vagrantbox.es/)
  * [Virtualbox](https://www.virtualbox.org/)
* Config Management
  * [Ansible](http://docs.ansible.com/)
  * [Puppet](http://puppetlabs.com/)
