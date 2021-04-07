# numo Indi Software Engineer Internship Summary 
(01/25/2021 - 04/23/2021)
This is a summary on everything I learned and did during internship.

## Interacted with..

### Languages
(in the order of frequency)
- Python
- Git
- Serverless
- Terraform
- Scala
- Java

### IDEs and Editors
- Visual Studio Code
- IntelliJ CE
- Vim

### Services
- AWS: 
    CloudWatch, IAM, Lambda, Secrets Manager, Simple Queue Service, S3
- Confluence
- Jira
- Salesforce: Marketing Cloud, Sandbox
- Mixpanel


## Jira Tickets Worked On

### FENDER-2969: Learn about AWS & Python Lambdas
### FENDER-3009: Research Terraform
### FENDER-3005: Research Sendgrid API
### FENDER-2633: SendGrid: Syncing contact data
### FENDER-2679: Change ApplicationDate format in Salesforce
    ```py
    sf["ApplicationDate__c"] = profile["applicationDate"].replace(" ", "T")
    ```
    
    Reformatted the existing application date data from YYYY-MM-DD HH:MM:SS 
    to YYYY-MM-DDTHH:MM:SS to comply with formatting in Salesforce. Later the
    code above needed to be replaced with more elegant fix (see below) by Bruce because
    the existing data in Prod environment had more variants.

    ```py
    pendulum.parse(fuzzy).to_iso8601_string()
    ```
    
### FENDER-2681: Send user Address information to Salesforce
    When the user submits the application, the user address is saved in Okta and Visa, but
    the data was not relayed to Salesforce. For the story, the new user address data was taken
    from `fender-application-processor`, sent to `fender-force` and put on 
    `customer-service-queue` lambda. For existing users, when the user address is updated,
    the updated address is taken from profile_processor in `fender-RTAC`, and sent to 
    `fender-force`. There was an extra challenge of finding out what compound data field 
    must look like for Salesforce.

### FENDER-2685: Send a user's PAS Special Instruction notes to Salesforce
    

### FENDER-2672: Send application date user profile data to Mixpanel
### FENDER-2765: Reduce API calls from RTAC Status Processor


## Paired With
- Matt, Natalie, Kate, Bruce, Aiton, Jess


## Observed


## Industry/Company Culture Learned

1 on 1
- Check in on performance, work, blockers and etc

Agile Kanban Method
- Visually pleasing method

All-hands
- Getting to know company wide goals and achievements
- Sharing interesting, intellectual and frugal knowlege (i.e. couponing)

Daily Standup
- Share daily progress and goals for the day
- Parking-lots(sidebar) to discuss blockers and etc
- The only regularly scheduled meetup with real humans (covid special)
- The Goodman sticky note method implemented in consumer team standup

Demo
- Present what people have been working on
- Best way to learn about other teammates' accumulated knowledge

Slack
- Tone and manner: Being responsive and supportive, Writing succint messagnes
- Efficiency: Integrating Zoom, Outlook and reminders
- Lots of Schitt's Creek giffys (or jiffys)


## Resources Accumulated
- Git Pointers: See the [link](LINK HERE) in GitHub.
