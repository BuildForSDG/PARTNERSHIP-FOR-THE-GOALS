A one-liner phrase describing this project or app

[![Codacy Badge](https://img.shields.io/badge/Code%20Quality-D-red)](https://img.shields.io/badge/Code%20Quality-D-red)

Check out the built app at https://devsdata.herokuapp.com/

## DEVSDATA
&nbsp;

## PROJECT NAME
PATHERNERSHIP FOR THE GOALS

## PROBLEM
DEVELOP A SOLUTION PLATFORM TO HELP THE AVAILABILITY OF HIGH-QUALITY, TIMELY AND RELIABLE DATA RELEVANT TO AID NATIONAL STATISTICAL PLANNING

## SOLUTION
In national planning, adequate data of all sectors of the economy is needed. The idea is to pick the technological sector and build a solution to provide relevant and timely data to aid further planning (by relevant bodies including the government and others) on this sector and given the tremendous growth in Nigeria’s IT industry and current trends in the world, planning is but crucial.
WHAT SOLUTION EXACTLY DO WE PROVIDE? A platform that shows the amount of tech persons we have in the country, not just the amount but also a more in depth breakdown into how many (web-developers, java developers, .net developers, python developers, cloud Engineers, Network Security expert, and the likes ,e.t.c) and very meaningful relationships. This data is just the starting point, with more to come. With this, the government would be able to plan for the future occurrences like: 
1.What Scholarships in software development do we need to provide to the youths e.g Let’s say we have a lot of (web developers) and as a country / globally we need more (Cloud Engineers) the government can then offer more of Cloud Engineering scholarships to help meet up such needs.
2.What programs can we organise to orientate the (IT sector/industry), that is where our (App/website) comes in they could get the data they need from our site and see what they need to do and where to place their focus on.
Just to mention a few.

HOW DO WE GET THE DATA? This idea is all based on the concept of “being online”. We believe that all developers available in the country will in one way or the other be online (say registered on a popular platform like LinkedIn, Github, Upwork, among others) and we can therefore, build powerful web scrapers to get their data or most likely partner with these platforms to get the data we need. We won’t be needing personal data like email addresses, home addresses, phone numbers, and with this, we think getting the required data won’t be so difficult and won’t violate rights.

## WAYS TO ACCOMPLISH THIS
We created an app that has a list of things.
<ul>
    <li>Data on the current labour force in the software development sector.</li>
    <li>A breakdown of this labour force by states, institutions.</li>
    <li>Coding languages by state.</li>
    <li>Developers by skill sets.</li>
    <li>Women Trends in software development.</li>
    <li>Developers with bachelor’s degrees.</li>
    <li>Developers with CS background by state</li>
    <li>Developers with tech-related background.</li>
    <li>Developers by years of experience.</li>
    <li>Developers looking for jobs.</li>
    <li>Average developer age by state, country.</li>
    <li>A Graph meaningful relationships on all points stated above.</li>
    <li>Useful information for developers like free wifi centers, nearby hubs, latest programs/scholarships, etc.</li>
</ul>

## About

What is this project about. Ok to enrich here or the section above it with an image. 

Once this repo has been setup on Codacy by the TTL, replace the above badge with the actual one from the Codacy dashboard, and add the code coverage badge as well. This is mandatory

This is a simple python starter repo template for setting up your project. The setup contains:

- install: poetry via pip. poetry is a dependecy manager.

- poetry: configuration in pyproject.toml

- flake8: for linting and formatting

## Why

Talk about what problem this solves, what SDG(s) and SGD targets it addresses and why these are important

## Usage
How would someone use what you have built, include URLs to the deployed app, service e.t.c when you have it setup


## Setup
You should have **Python 3.5+** and **git** installed. 

1. Clone the repo you've created from the template herein and change into the directory

    ``
    git clone <Your Repository>
    ``

2. Change into repo directory

    ``
    cd python-starter
    ``

3. Install poetry (for more info: visit <a href="https://python-poetry.org/docs/cli/" target="_blank">poetry official website</a>), a dependecy manager for python.

    On windows, you will need powershell to install it:

    ``
    (Invoke-WebRequest -Uri https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py -UseBasicParsing).Content | python
    ``

    After that you will need to restart the shell to make it operational.

    &nbsp;

    On linux and other posix systems (mac included):

    ``
    curl -sSL https://raw.githubusercontent.com/python-poetry/poetry/master/get-poetry.py | python
    ``

    &nbsp;

    To check that it is correctly installed, you can check the version:
    ``
    poetry --version
    ``

    May be the latest stable version is not installed with the installation script, to update poetry, you can run:

    ``
    poetry self update
    ``

4. With poetry installed, you should install project dependecies by running:

    ``
    poetry install
    ``
    &nbsp;

    &nbsp
    This will install pytest for running tests and flake8, linter for your project.



5. Next, activate the virtualenv by running:
    ``
    poetry shell
    ``
    &nbsp;

    And finally,
    ``
    poetry run python manage.py runserver
    `` 
    &nbsp;
    
    And that should be all.


#### Hints

- Lint: `poetry run flake8`
- Run tests using the command: `poetry run pytest`
- Install dependencies: 
  `poetry add <dependency>`
- Install dev dependencies:
  `poetry add --dev <dev-dependency>`
- Run your project:
  `poetry run app`


## Authors

List the team behind this project. Their names linked to their Github, LinkedIn, or Twitter accounts should siffice. Ok to signify the role they play in the project, including the TTL and mentor

## Contributing
If this project sounds interesting to you and you'd like to contribute, thank you!
First, you can send a mail to buildforsdg@andela.com to indicate your interest, why you'd like to support and what forms of support you can bring to the table, but here are areas we think we'd need the most help in this project :
1.  area one (e.g this app is about human trafficking and you need feedback on your roadmap and feature list from the private sector / NGOs)
2.  area two (e.g you want people to opt-in and try using your staging app at staging.project-name.com and report any bugs via a form)
3.  area three (e.g here is the zoom link to our end-of sprint webinar, join and provide feedback as a stakeholder if you can)

## Acknowledgements

Did you use someone else’s code?
Do you want to thank someone explicitly?
Did someone’s blog post spark off a wonderful idea or give you a solution to nagging problem?

It's powerful to always give credit.

## LICENSE
MIT
