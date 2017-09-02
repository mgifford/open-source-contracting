# Open Source Contracting

Problem: Many institutions use open source software. Unfortunately, the procurement process usually restricts collaboration and participation. By adding these elements to boiler-plate contracts we hope to encourage better practices. Supporting more effective engagement will allow us to build / maintain the code better.


## Principles
- By default all work will be under an open license. Where possible adopt the license of the parent project. 
- External contractors will work with internal IT staff where possible. This allows for an exchange knowledge & transfer responsibilities.
- Any proprietary software licenses will need to give explicit approval.
- Code developed should be releasable if it serves the needs of the broader community. A "Share First" approach will help developers build more re-usable components. 
- Collaboration is never easy, but if it is a stated outcome of the contract it is more likely to happen.
- When evaluating tech solutions contractors are should enhance existing code, rather than build from scratch. Enhancements are pushed upstream to improve the solutions for everyone.
- Patches to existing code are added to the parent project's issue queue (ie. https://www.drupal.org/project/issues) where possible.
- The Client must be informed of any customizations to existing open source projects that will cause problems with upgrades.
- As with all open source licenses, the software does not come with a guarantee / warranty.
- Vendor solution should have developing open source products as their primary business
- Any selection processes should favour bids where it is easy to demonstrate that they have contributed back. It is easy to review contributions by developers and development shops to the open source community. 
- The software "what" (ie. Drupal) is often dealt with in procurement, without mentioning the "how" (with open source approaches). Make sure both are addressed.


## Strategies
- Healthy open source ecosystems have several permanent development shops that can compete with each other. Shops need to be able to work together to be able to cooperate with each other as well. 
- Most contracts should be small ($10-20k). The organization producing the RFP should have full responsibility to clearly define requirements.
- An open reputation system should be established to allow clients to rate their experiences. 
- Contests and hackathons can be useful to generate interest, or seek out new players, but cannot be relied upon. In general they are only useful for short-term sprints. 


## Tactics - Largely from https://gds-operations.github.io/guidelines/

### Projects MUST:
    - include a README
    - include useful and informative commit messages about why a change was made
    - include a CHANGELOG (see [example](https://metacpan.org/pod/CPAN::Changes::Spec))
    - include a valid Open Source LICENSE file (see example)
    - provide a link to a public list of known issues and bugs
    - provide an email address to send security related bug reports to
    - provide a version number compatible with Semantic Versioning

### Projects SHOULD:
    - publish packages to relevant language specific repositories such as PyPi, Ruby Gems, NPM, Puppet Forge, etc.
    - publish contributors guidelines in a CONTRIBUTING file
    - set up any tests to run in a public continuous integration environment

### Projects MAY:
    - include a CONTRIBUTORS file (see example)
    - provide a mailing list for discussion of the project


## Contribution vs Contracting

There are many open source projects which take on contributions and so therefore need an agreement for the license of those contributions. The Fedora Project of RedHat came up with this [Fedora Project Contributor Agreement](https://fedoraproject.org/wiki/Legal:Fedora_Project_Contributor_Agreement?rd=Legal:FPCA) as a model. 

Many contracts are for larger pieces of work and not discrete code checkins.  


## Sample language

All software developed through this contract will be the copyright of [Company X] and licensed under the GNU Public License (GPL). This ensure that the software may be freely used, modified and distributed. Any documentation produced will be similarly licensed under the Creative Commons Share-alike License.

Client accepts and agrees that all developed software will automatically be licensed under the most permissive open license used by software it is integrated into and can be freely distributable. Client acknowledges that they are receiving a substantial cost savings through Vendors use of open source software and this recriprocal license is in clients best interests. 

The works authored by the vendor in the context of the present agreement will be licensed under the [license].
