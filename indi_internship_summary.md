# numo Indi Software Engineer Internship Summary 

This documents a summary on everything I learned and did 
during numo indi software engineer internship (01/25/2021 - 04/23/2021).

---

(Insert TLDR summary here)

---

## Interacted with..

### Languages
(in the order of frequency)
- Python
- Git
- Serverless
- Dart
- Terraform
- Scala
- Java

### IDEs and Editors
- Visual Studio Code
- IntelliJ CE
- Vim

### Platforms and Services
- AWS: 
    CloudWatch, IAM, Lambda, Secrets Manager, Simple Queue Service, S3
- Confluence
- Jira
- Salesforce: Marketing Cloud, Sandbox
- Mixpanel
- Flutter

---

## Jira Tickets Worked

### FR-2969: Learn about AWS & Python
A task ticket to learn about different services in AWS and basic Python.

### FR-3009: Research Terraform
A task ticket to learn about Terraform.

### FR-3005: Research an external Email API service
A task ticket to learn about an external Email API service and read the documentation.

### FR-2632: Determine all consumers of an internal repo
A spike ticket to determine the counsumers of a repo, to explore pros and cons of different options in changing the message structure, and to determine where in the internal system the data can be acquired from.

### FR-2633: Syncing data with an external API
A spike ticket to understand if the external API meets our needs: what the API uses as unique identifiers, the possible source of data pushed and the options of syncing the data with the API.

### FR-2679: Change date format for Salesforce
A task ticket to change formatting of date data field to ISO format so that Salesforce can automatically recognize the data as date. It had to be patched later to account for variants in the existing date data.
  
### FR-2681: Send address to Salesforce
A task ticket to automatically save new and updated user addresses to Salesforce. The biggest challenge was to understand the mechanism of compound data field in Salesforce. It was returned to dev from the QA stage as some of the acceptance criteria was not accounted for the first time.

### FR-2685: Send a new notes field to Salesforce
A task ticket to send a new notes data field from PAS to Salesforce. This was the first time I interacted with the internal API and RTAC messages.

### FR-2672: Send application date data to Mixpanel
A task ticket to send the date a user creates and submits an initial application for better analysis. 

### FR-2765: Reduce API calls from an internal repo
A task ticket to refactor a number of redundant methods calling the same internal API route.

### FR-3083: Send username to Mixpanel in mobile app
A task ticket to send username data from the mobile application to Mixpanel. This was the first time I learned Dart and Flutter.

---

## Industry/Company Culture Learned

- `1 on 1`
: Weekly or biweekly meeting with the supervisor/manager to discuss work-related stuffs (direction, blockers, or solutions), check in on performancee, chat about life and etc.

- `Agile Kanban Method`
: Visually pleasing method

- All-hands
: Getting to know company wide goals and achievements
    Sharing interesting, intellectual and frugal knowlege (i.e. couponing)

- Daily Standup
:    Share daily progress and goals for the day
    Parking-lots(sidebar) to discuss blockers and etc
    The only regularly scheduled meetup with real humans (covid special)
    The Goodman sticky note method implemented in consumer team standup

- Demo
:    Present what people have been working on
    Best way to learn about other teammates' accumulated knowledge

- Slack
:    Tone and manner: Being responsive and supportive, Writing succint messagnes
    Efficiency: Integrating Zoom, Outlook and reminders
    Lots of Schitt's Creek giffys (or jiffys)

---

## Resources Accumulated
- Self-Guided Git Pointers [link to GitHub page](https://github.com/hanijeel/resources/blob/main/git_pointers.md)
- Self-Guided Homebrew Pointers [link to GitHubpage](here)
- Building Lambda functions with Python in AWS documentation [Tutorial](https://docs.aws.amazon.com/lambda/latest/dg/lambda-python.html)
- Terraform Tutorial for AWS infrastructure [Tutorial](https://learn.hashicorp.com/collections/terraform/aws-get-started)
- Scala Learning Resources:
    -ScalaTest by artima [link](https://www.scalatest.org/user_guide/using_matchers)
    -Simple Concurrency with Scala Features [link](https://alvinalexander.com/scala/concurrency-with-scala-futures-tutorials-examples/)
    -The Neophyte's Guide to Scala [link](https://danielwestheide.com/books/the-neophytes-guide-to-scala/)
    -Scala Exercises [link](https://www.scala-exercises.org/)
