# Metal Jackets Team 2068 FRC Resources

A hopefully growing list of FRC Resources for Team 2068 that will hopefully be helpful to other FRC Teams.

## Github

While Github isn't the only player in the game they certainly have a huge marketshare and make it very easy to collaborate within the team and with other teams.

Some ways to take more advantage of Github are:

### Student Pack

The [Github Student Pack](https://education.github.com/pack) which gives access to tons of great tools for free, or free for a significant chunk of time.

### Github Pages

[Github Pages](https://pages.github.com/) are "Websites for you and your projects", free if it's a public repository.  Actually it's a requirement that the pages site be public, so that's important to know if you want to publish code from a private repository.

The beauty of Github Pages are:

- they take plain text files, written with minimal markup ([Markdown](https://daringfireball.net/projects/markdown/) in this case)
- they are based on git which makes collaboration easy
- the default github style is quite nice when the markdown is rendered

#### Team Pages

One obvious use for a free (as in rootbeer) hosted static site is a Team Page.  There are a number of tools for statically generating sites from simple [Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) files including:

- [Jekyll](https://jekyllrb.com/) written by a Github contributor and runs all READMEs.
- [Hugo](https://gohugo.io/) an increasing popular alternative to Jekyll written in Go.

There are many, many themes available commercially and free for both generators.  Some free resources are:

- [Jekyll Themes](https://jekyllthemes.io/)
- [More Jekyll Themes](http://jekyllthemes.org/)
- [Hugo Themes](https://themes.gohugo.io/)

You can find commercial and free resources from google searches or looking at sites like [Theme Forest](https://themeforest.net/), though more generic sites might not be worth the effort to customize to use with Hugo/Jekyll unless you have excess time or access to someone familiar with those systems.

If you're looking for inspiration:

**FRC Team 1418** uses Jekyll and Github Pages for their site, you can see:

- [source code](https://github.com/frc1418/frc1418.github.io)
- [Team 1418's Live Site](http://1418.team/)

**FRC Team 1533 Triple Strange** uses Hugo and Github Pages for their site, you can see:

- [source code](https://github.com/triplestrange/triplestrange.github.io)
- [Team 1533's Live Site](https://howstrange.me/)

### READMEs

This is an often overlooked and under utilized part of your Github repository but building on top of Markdown and Github Pages this single page can be very useful.

#### Programming, Setup, etc

This is an obvious use and some teams do this much better than others.  The easier it is for someone new on the team to pull down, build and run code the better.

Here are some examples of some IMHO better READMEs for FRC teams to emulate:

##### Team 2168

Their [2017 Steamworks](https://github.com/Team2168/2017_Main_Robot) README covers lots of topics including:

- Robot Requirements
- Student Requirements (mostly software related)
- Information on some of the software they use during competitions and how to access
- Coding workflow, including
- Checklists to follow before commiting code
- Subsystem breakdown and responsible student

##### Team 4931

Their [2017 Steamworks](https://github.com/frc-4931/2017-Robot) repository covers:

- Requirements (admittedly light, as they assume all laptops are preconfigured)
- Build instructions (using ant, to build and deploy)
- Information on how to contribute code to the repository

##### ILITE Robotics

Their [2018 Power Up](https://github.com/iliterobotics/FRC-Robot-2018#commiting-code-to-github) repository has:

- Setup and build instructions
- Documentation on how to commit code to the repository

#### Wiki's

[Team 4931](https://github.com/frc-4931) has a number of repositories and a dated but extensive [wiki](https://github.com/frc-4931/2014/wiki) with over 20 documents that demonstrate a number of uses a FRC team might have for wikis:

- Team Application
- Parent Information
- Robot Design and Code information
- Robot parts (can link directly from the wiki to the supplier for business subsystem, book keepers, etc)
- Safety Procedures
- CAD (how to set up and documents generated)
- Inventory
- Resources (similar to what this README is attempting to do)

Some other uses might include:

- Sponsor Contact Information (would probably want in a private repository)
- Sponsor Letters
- Fundraising Ideas
- Fundraising Templates
- Business Plan
- Checklists (packing, pit setup, match, scouting, competition retrospective, etc)
- Onboarding instructions (e.g. add user to discord, trello and remind, etc.)
- Training

[Checklists](http://atulgawande.com/book/the-checklist-manifesto/) are hugely useful if you use them.  Why do you think NASA, Airline Pilots, and Surgeons to name a few use them?

## Programming

_TODO_ Flesh this area out, currently a dumping ground for things to investigate.

### Code Quality

- [Writing Testable Robot Code for FRC](https://speakerdeck.com/frc4931/writing-testable-robot-code-for-frc) slides from a presentation by FRC Team 4931.

### Debugging

- https://wpilib.screenstepslive.com/s/4485/m/13809/l/242588-debugging-a-robot-program

### Continuous Integration / Building

[Continuous Integration](https://en.wikipedia.org/wiki/Continuous_integration) (CI) is a system that responds to changes in a repository and then attempts to build the software.

Many things can happen during the CI cycle including:

- run automated tests
- run linting, style guides and other static analysis tools

But at a minimum it can at least tell you if your code will compile.  Because this is done on a separate server you'll need to be able to build without IDEs (in most cases).

Some resources to help you get started are: 

- [GradleRIO](https://github.com/wpilibsuite/GradleRIO) is a powerful Gradle Plugin that allows teams competing in the FIRST robotics competition to produce and build their code.
- [Gradle](https://gradle.org/) is a build tool, frequently used with Java projects.
- [FRC Java JUnit template](https://github.com/246overclocked/frc-java-junit-template) is a JUnit and Ant template
- [Older instructions on installing code to the RoboRIO](https://willhaley.com/blog/frc-roborio-java/)
- [FRC Team 1360](https://github.com/FRC1360/Stronghold2016) is an example of a team using [Travis CI](https://travis-ci.org/FRC1360/Stronghold2016) to run CI on their FRC solution.

## Scouting

### Tools

- [The Blue Alliance](https://www.thebluealliance.com/) "The Blue Alliance is the best way to scout, watch, and relive the FIRST Robotics Competition."
- https://www.reddit.com/r/FRC/comments/2tfme1/tableau_scouting/
- https://public.tableau.com/s/
- https://github.com/frc2052/FRC-Krawler (not a lot of info yet)
- https://github.com/cgund98/frc-scouting
- https://github.com/SUPERCILEX/Robot-Scouter
- https://github.com/triplestrange/StrangeScout (no idea, runs in docker)

## Field Management

Practice like you compete.

- [Cheesy Arena](https://github.com/Team254/cheesy-arena) "An alternative field management system for the FIRST Robotics Competition."

## Driving

- [Shuffleboard](https://wpilib.screenstepslive.com/s/currentCS/m/shuffleboard/l/814689-tour-of-shuffleboard) a replacement to SmartDashboard.
- [FRC Dashboard](https://frcdashboard.github.io/) is a community driven "Extensible, JavaScript-based driving dashboard framework for the FIRST Robotics Competition".  [Github repo](https://github.com/FRCDashboard/FRCDashboard)

## Training

- [Onboarding Programmers](https://github.com/Team997Coders/TrainingResources) links to a [presentation](https://gitpitch.com/Team997Coders/BootCamp/master?grs=github&t=sky) that Team 997 uses to onboard their coders.  They use gradle and [VS Code](https://code.visualstudio.com/) as their development platform of choice.
- [FRC Team 3255's Java Tutorial](https://github.com/FRCTeam3255/FRC-Java-Tutorial) links to a presentation explaining how to code FRC solutions in Java using VS Code.

## Resources of Resources

- [awesome frc](https://github.com/andrewda/awesome-frc) is a list in the "[awesome](https://github.com/sindresorhus/awesome)" style for FRC.
- [frc.link](http://frc.link/) is a mnemonic shortener to help you get to e.g. a team's profile page on the official FRC website by a direct, logical link (http://frc.link/t/2068) instead of navigating through a ton of menus.

### Markdown and Related Tools

- [GitPitch](https://gitpitch.com/) hosted markdown presentations


## Contributing

Contributions, corrections, enhancements are welcome via pull request.