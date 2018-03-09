<h1 align="center">How to choose your first open source project</h1>

The general perception about contributing to open source is that its hard. The hardest part being reading and understanding sommeone else's code and writing your own code on top of that. If this is what popped into your head after reading the last sentence *Sometimes I can't even understand my own old code, how am I supposed to understand someone else's code?* then relax I used to think the same way up until last year.  

Contributing to a project written by sommeone else can be a daunting task but if you take the first step in the right direction it might then this might not be the case. The first step i.e. choosing the project you want to contribute to. This matters a lot and can be instrumental in turning a scared newbie programmer into an open sourcerer.

If an amateur programmer who wants to get started with open source development is advised to check out a project like **git** which is maintained by uber geeks proficient in C with years of software development experience then that's bad advice. I'm not saying that git is a bad choice for an open sourced project to contribute to, its just not beginner friendly. Most devs contributing to git have enough experience to get started without any resources or detailed documentation. Consider this article a check-list of the various beginner friendly features that a project must have and some *dos and don'ts* to make your first open source contribution easy.

## The product
Before contributing to a project you should know how it works. For that you are gonna have to try it for yourself. If you find their product to be cool and something that you/others can use in their day to day lives then this indicates that the project is worth contributing to.

Most beginners make the mistake of trying to contribute without even using the software and end up failing, getting frustrated and eradicating all thoughts of open source development from their minds. If you don't use the software then you don't know how it works. If you don't know how it works then how would you be able to fix a bug or write a new feature.

So remember *"Try it then hack it."* (shamelessly self quoting myself)

## Project status
The next question you should ask yourself should be *Is the project active or not?*

If you send a PR to an unmaintained or dormant project your will be wasting your time since there is a high chance that no one will review your PR and merge it. Projects that have high activity are benificial for new contributors since you will get immediate feedback on your code and your contributions will not go to waste.

The following are indicators of an active project:
- **Number of contributors:** A growing number of contributors indicates the interest of the developer community in a project and also its willingness to accept new contributors.
- **Frequency of commits:** See the last commit date. If it was made within the last week or even a month or two then it means that the project is still being maintained.
- **Number of maintainers:** This ones kind of optional but a higher number of maintainers mean a higher number of potential mentors to guide you.
- **Frequency of conversation in the chat room/IRC:** A busy chat room means instant replies to your queries.

## Resources for beginners
- **Documentation:** A well maintained documentation is very important for a project. Not just beginners but even professionals need to read the documentation in order to understand a project and its inner workings. If the project has a well maintained documentation on Github (or wherever it is hosted) and also a detailed documentation on a separate site like [read the docs](https://readthedocs.org/) with lots of examples will help diving deep into the code. A great example of this is coala ![coala documentation](http://res.cloudinary.com/dpft7mwni/image/upload/v1520542012/coala-doc_srqrjf.png)
They have their own site for containing tutorials, documentation and even all of their API (every class and method) can be accessed from that site with a UI that is pleasing to the eye and makes you wanna keep on reading.
![linter module](http://res.cloudinary.com/dpft7mwni/image/upload/v1520542012/linter_tqw5ox.png)

- **Tutorials:** Existence of tutorials on how to add minor features to the project are helpful for beginners (however this might not be possible for all the projects). *coala (always written with a lowercase c)* has [tutorials for writing bears](http://api.coala.io/en/latest/Developers/Writing_Linter_Bears.html) (which are python wrappers for linting tools to perform code analysis).

- **Labeled Issues:** For a beginner who is even sure of the project he/she should work on, selecting an issue for can be an even tougher task. This is where labelled issues prove to be beneficial in attracting newcomers. ![coala issues page](http://res.cloudinary.com/dpft7mwni/image/upload/v1520623481/coalaissue_fr0y0u.png)
Issues labelled with `difficulty/low`, `difficulty/newcomer`, `good first issue` and `low hanging fruit` can turn out to be a great fit for newbies.

## Miscallaneous
- **The Attitude Of Maintainers Towards New Contributors:** Most of the times you will encounter extremely nice and encouraging people in open source who really want to help newcomers onboard their projects (speaking from personal experience). However there can a few extremely rare ocassions where you will come across certain maintainers and contributors who expect you to know everything and might not be so welcoming (maybe even a little rude) when asking for help. Don't let them discourage you and make you stop contributing. There are plenty of people out there who want to help you out. Just because someone has more experience that you doesn't give them the right to be rude.

- **Review Process/Structure:** Your PR will go through a number of reviews and changes. This is the part where you will learn the most about software development since your code will be getting reviewed by experienced and professional devs and also your peers. A project with a stringent review process is an opportunity for you to write production grade code and to grow as a developer.

- **A Robust CI Pipeline:** Open sourced projects are the place where beginners get introduced to continuous integration and deployment services for the first time. A robust CI pipeline will force you to learn how to read CI logs and make sense of them. It will also give you experience in dealing with failing test cases and code coverage issues.
![coala CI pipeline](http://res.cloudinary.com/dpft7mwni/image/upload/v1520625903/cipiple_vq56dc.png)

- **Participation In Summer Of Code Programmes:** This indicates the organizations' willingness to commit to the long term development of the project and also provides an opportunity for newcomers to get some real life development experience and also get paid for it. Most of the organizations participating in such programmes are welcoming to newbies.

## A list of beginner friendly organizations
This is a non-exhaustive list of beginner friendly open source organizations/projects
- [coala (Python)](https://github.com/coala/coala)
- [Oppia (Python, Django)](https://github.com/oppia/oppia)
- [Duckduckgo (Perl, Javascript)](https://github.com/duckduckgo/)
- [Opengenus (Javascript)](https://github.com/OpenGenus/)
- [Kinto (Python, Javascript)](https://github.com/kinto)
- [Fossasia (Python, Javascript)](https://github.com/fossasia/)
- [Kubernetes (Go)](https://github.com/kubernetes)


## License
Licensed under *Creative Commons BY-SA 4.0*.

**Username:** palash25
