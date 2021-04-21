# numo Indi Software Engineer Internship Summary 

This page documents everything I learned and did as a Software Engineer Intern at numo indi from 01/25/2021 to 04/23/2021. The internship provided an invaluable opportunity to understand the daily routine of a software engineer and to experience SDLC & DevOps process.

---

## Technical Details

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
- Flutter
- Jira
- Mixpanel
- Postman
- Salesforce: Marketing Cloud, Sandbox

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
: Weekly or biweekly meeting with the supervisor/manager to discuss work-related stuffs (direction, blockers, or solutions), check in on performancee, chat about life and ask questions.

- `Agile Kanban Method`
: An agile framework that visualizes projects' workflow on a board and shows what stage of the process (To do, In progress, Code Review, QA, Done) each task is at.

- `All-hands`
: A company-wide meeting where all employees meet and share business updates. indi-all-hands meeting were more intimate than numo-all-hands, with different formats and interesting knowledge sharing (e.g. book reviews and couponing tips). 

- `Code Review`
: Other people review the code I pushed up and leave feedback on the pull request. It was the best way to get feedback on my work and ensure the code to work properly. 

- `Daily Standup`
: Daily meetings where team members share progress from the day before and set goals for the day. Issues that need more discussion can be set aside for a 'parkinglot', which is equivalent to a sidebar meeting right after. The consumer team implemented the Goodman sticky note method, which helped visualizing and prioritizing each task.

- `Demo`
: A biweekly session where team members can present what they have been working on. It was the best way to learn about other teammate's accumulated knowledge. Later in the internship, a new format was introduced where people would give a small TED Talk style presentation on certain topics like RTAC structure.

- `Pairing`
: The best method to get through blockers and cooperate with teammates. Observing how people work, what tools they use and how they explain different processes and concepts was great learning experience. It was also great to get to know people in different stages of their careers and look forward to getting there.

- `Slack`
: A communication tool used in the team. I learned the tone and manner using Slack, especially being responsive and supportive and writing succint messages. The best takeaway is how to ask for help: state the desired outcome, the problem, and failed solutions (things I tried). 

- `Unit Testing`
: Writing tests for the smallest unit of the code, usually a function or a class to make sure that the code is behaving how I intended it to. It usually took much longer to write a passing test to write the actual code.

---

## Resources Accumulated
- Self-Guided Git Pointers [link to GitHub page](https://github.com/hanijeel/resources/blob/main/git_pointers.md)
- Building Lambda functions with Python in AWS documentation [tutorial](https://docs.aws.amazon.com/lambda/latest/dg/lambda-python.html)
- Real Python [link](https://realpython.com/)
- Terraform Tutorial for AWS infrastructure [tutorial](https://learn.hashicorp.com/collections/terraform/aws-get-started)
- AWS: Building Lambda functions with Python [link](https://docs.aws.amazon.com/lambda/latest/dg/lambda-python.html)
- Scala Learning Resources:
    - ScalaTest by artima [link](https://www.scalatest.org/user_guide/using_matchers)
    - Simple Concurrency with Scala Features [link](https://alvinalexander.com/scala/concurrency-with-scala-futures-tutorials-examples/)
    - The Neophyte's Guide to Scala [link](https://danielwestheide.com/books/the-neophytes-guide-to-scala/)
    - Scala Exercises [link](https://www.scala-exercises.org/)
- Dart Language Tutorial [tutorial](https://dart.dev/tutorials)

---

I would like to thank everyone at numo indi for giving this opportunity and helping me throughout the internship. If you have questions for this document, please reach out to me at leejinah7368 at gmail dot com.