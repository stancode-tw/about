# Instructor instructions

## Setup Account

###### GitHub Organization

- Get invited into __stancode-tw__ organization
- You can access the organization account __Your profile (top-right corner) > Organizations (bottom-left corner) > stancode-tw__

###### GitHub Classroom

- Click on __Grant access to an organization that is not listed__
- Go to __Organization access__, select __Grant__ next to stancode-tw

## Create Classroom

###### GitHub Classroom

- Click on the green button __New classroom__
- Select organization __stancode-tw__
- Fill out the __classroom name__
    - Best practice
        - Name: `<year>-<term>-<course-code>-<region><number>`
            - E.g. 2019-Summer-SC001-TP1
- Give the classroom link to students

## Create Assignment

###### GitHub Organization

- Click on the green button __New__ to create a new repository
- Fill out __Repository Name__ and __Description__. Select __Public__ (or __Private__ if it's available under the current pricing plan), 
and __Initialize this repository with a README__. Click on __Add .gitignore__ and select the appropriate programming language from the dropdown menu.
    - Best practice
        - Repository name: `<course-code>-a<number>-<description>`
            - E.g. sc001-a1-hello-world
        - Description: `Assignment <number> for <course-code>: <description>`
            - E.g. Assignment 1 for SC001: Hello World
- __Create repository__

###### GitHub Classroom

- Click on the green button __New assignment__, select __Create an individual assignment__ (or __Create a group assignment__)
- Fill out __Your assignment title__ (__Your assignment repository prefix__ will be automatically generated). Select __Public__
(or __Private__ if it's available under the current pricing plan), __Give students admin permissions on their repository__,
and __Enable assignment invitation URL__.
    - Best practice
        - Assignment title: `A<number> - <description>`
            - E.g. A1 - Hello World
- In __Add your starter code from GitHub (optional)__, search for and link to the repo you just created under stancode-tw organization.
Select __Import starter code using source importer__ (or __Import starter code using a template repository__ if we know how to use it)
- Set up __Deadline__
- __Create Assignment__
- After the assignment is finished setting up, give the invitation link to students

## Prepare Assignment

###### GitHub Organization

- Clone the repository created for the assignment
- Update the repository locally
- Update `README.md` with instructions
- Push the repository to GitHub

###### Assignment Structure

- Best practice
    - Always create another project directory `Assignment<number>` that contains all the code files, instead of spreading them out in the root directory
    - Always create another asset directory `assets` that contains the necessary instruction-related files (e.g. images)
    - The root directory should only contain the project directory, `assets` directory, `.gitignore` file, and `README.md` file
    - For all generated files, data files, or any files/directories that are not the necessary source codes to be included in the deliverables, add them in `.gitignore`
    - If there are written problems, create a `answer.md` file at the appropriate location, and ask the students to fill it out

## Grade Assignment

###### GitHub Classroom

- Navigate to assignment page, students’ repos are listed below. Click on __View repository__ to access

###### Student Repo

- Run tests
    - Clone the repo
    - Run the tests
- Give Comments
    - On GitHub, go to the relevant file you would like to comment on
    - Click on the line number you wish to comment on (or select multiple lines by holding down the Shift key), and select __Reference in new issue__
    - Fill out the __title__ of the issue, and fill out the __details__ below
    - On the right-hand side, add __Labels__ for the student to know whether the issue is good/bad/needs fix/...
        - You can add new labels via __Edit labels__
    - Click on __Submit new issue__
    - Click on __Close issue__ if the issue is just a compliment. Otherwise, if it is something bad or a bug to be fixed, wait for the student to fix them, review the fix, and close the issue

## Archive Past Assignments

- Since a free organization account does not allow unlimited private repos, we might consider archiving past assignments somewhere that is not publicly accessible
- Suggestion
    - Ask the students to archive their own repos, either via downloading the zip files, or by forking them into private repos (GitHub Education allows unlimited private repos for students)
    - Download and move all student assignments to private storage, or move them to another branch (still publicly available, but students might not notice)
