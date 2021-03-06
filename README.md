CONTRAX.io 
==========


  - [Description](#Description)
    - [Inspiration](#Inspiration)
    - [Motivation](#motivation)
    - Features
  - [Installation](#installation)
  - [Help](#Help)
    - Documentation
    - Mailing List
    - Wiki

  - [Contributing](#contributing)
  - [Credits](#credits)
    - [Contibutors](#contributors)
    - [Inspiration](#inspiration)
    - [Alternatives](#alternatives)
    - [Projects using this library](#projects-using-this-library)
  - [License](#license)

# HOPEFULLY IT IS OBVIOUS THAT THIS REPO IS VERY MUCH STILL UNDER CONSTRUCTION

The first order of business is a [decent ReadMe](https://changelog.com/top-ten-reasons-why-i-wont-use-your-open-source-project/)

# Description
CONTRAX.io is fundamentally a blockchain-based messaging platform that can work with a [variety of decentralized apps (DAPPs)](http://dapps.ethercasts.com/) ... for a very particular type of message ... it starts with prospecting followed by qualification and negotiation followed by a contract followed by an initial payment followed by customer fulfillment followed by final payment followed by data artifacts and proof-of-work to used in the future path from prospecting to negotiation to delivery ... all about the data for contracts and more contracts.

The aim of CONTRAX.io is an accelerated negotiation and customer fulfillment process for smart lightweight agreements. The overall goal is in lowering the barriers to entry for negotiation and the elimination of frictions, unnecessary costs and uncertainties in transactions. It is believed that the best overall way to achieve this is to foster a processs of trust building through successive conpletion of smaller, progressively more complex and involved assignments.     

# Motivation

	

# Installation


# Contributing

## How to contribute

Third-party patches are essential.  We simply can't access the huge number of platforms and myriad configurations for running
CONTRAX.io. We want to keep it as easy as possible to contribute changes that get things working in your environment. There are a few guidelines that we need contributors to follow so that we can have a chance of keeping on top of things.

### Core vs Modules

New functionality is typically directed toward modules to provide a slimmer Core, reducing its surface area, and to allow greater freedom for module maintainers to ship releases at their own cadence, rather than being held to the cadence of Puppet releases. With Puppet 4's "all in one" packaging, a list of modules at specific versions will be packaged with thevcore so that popular types and providers will still be available as part of the "out of the box" experience.

Generally, new types and new OS-specific providers for existing types should be added in modules. Exceptions would be things like new cross-OS providers and updates to existing core types.

If you are unsure of whether your contribution should be implemented as a module or part of Core, you may visit
[#CONTRAX-dev on Freenode IRC](https://freenode.net) or ask on the [CONTRAX-dev mailing list](https://)
for advice.

### Getting Started

* Make sure you have a [Jira account](https://tickets.puppetlabs.com)
* Make sure you have a [GitHub account](https://github.com/signup/free)
* Submit a ticket for your issue, assuming one does not already exist.
  * Clearly describe the issue including steps to reproduce when it is a bug.
  * Make sure you fill in the earliest version that you know has the issue.
* Fork the repository on GitHub

### Making Changes

* Create a topic branch from where you want to base your work.
  * This is usually the master branch.
  * Only target release branches if you are certain your fix must be on that
    branch.
  * To quickly create a topic branch based on master; `git checkout -b
    fix/master/my_contribution master`. Please avoid working directly on the
    `master` branch.
* Make commits of logical units.
* Check for unnecessary whitespace with `git diff --check` before committing.
* Make sure your commit messages are in the proper format.

````
    (PUP-1234) Make the example in CONTRIBUTING imperative and concrete

    Without this patch applied the example commit message in the CONTRIBUTING
    document is not a concrete example.  This is a problem because the
    contributor is left to imagine what the commit message should look like
    based on a description rather than an example.  This patch fixes the
    problem by making the example concrete and imperative.

    The first line is a real life imperative statement with a ticket number
    from our issue tracker.  The body describes the behavior without the patch,
    why this is a problem, and how the patch fixes the problem when applied.
````

* Make sure you have added the necessary tests for your changes.
* Run _all_ the tests to assure nothing else was accidentally broken.

### Making Trivial Changes

### Contributing to Documentation

For changes of a trivial nature to comments and documentation, it is not always necessary to create a new ticket in Jira. In this case, it is appropriate to start the first line of a commit with '(doc)' instead of a ticket number.

````
    (doc) Add documentation commit example to CONTRIBUTING

    There is no example for contributing a documentation commit
    to the Puppet repository. This is a problem because the contributor
    is left to assume how a commit of this nature may appear.

    The first line is a real life imperative statement with '(doc)' in
    place of what would have been the ticket number in a
    non-documentation related commit. The body describes the nature of
    the new documentation or comments added.
````

### Submitting Changes

* Sign the [Contributor License Agreement](http://links.contrax.io/cla).
* Push your changes to a topic branch in your fork of the repository.
* Submit a pull request to the repository in the puppetlabs organization.
* Update your Jira ticket to mark that you have submitted code and are ready for it to be reviewed (Status: Ready for Merge).
  * Include a link to the pull request in the ticket.
* The core team looks at Pull Requests on a regular basis in a weekly triage
  meeting that we hold in a public Google Hangout. The hangout is announced in
  the weekly status updates that are sent to the puppet-dev list. Notes are
  posted to the [Contrax Community community-triage
  repo]()
  and include a link to a YouTube recording of the hangout.
* After feedback has been given we expect responses within two weeks. After two
  weeks we may close the pull request if it isn't showing any activity.

# Additional Resources

* [Puppet Labs community guidelines](https://docs.puppetlabs.com/community/community_guidelines.html)
* [Bug tracker (Jira)](https://tickets.puppetlabs.com)
* [Contributor License Agreement](http://links.puppetlabs.com/cla)
* [General GitHub documentation](https://help.github.com/)
* [GitHub pull request documentation](https://help.github.com/send-pull-requests/)
* #puppet-dev IRC channel on freenode.org ([Archive](https://botbot.me/freenode/puppet-dev/))
* [puppet-dev mailing list](https://groups.google.com/forum/#!forum/puppet-dev)
* [Community PR Triage notes](https://github.com/puppet-community/community-triage/tree/master/core/notes)
## License

Github Changelog Generator is released under the [Apache License](http://www.opensource.org/licenses/Apache).
