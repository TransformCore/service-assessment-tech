# Service assessment - technical

## 3. Have a multidisciplinary team
Put in place a sustainable multidisciplinary team that can design, build and operate the service, led by a suitably skilled and senior service owner with decision-making responsibility.

- show you understand where gaps may emerge in the team and how to fill them
- explain your plan to transfer knowledge and skills from contractors to permanent staff
- show that there’s a person on your team who’s responsible for user research and usability tests
- show you’ll have a team that can keep improving the service after it goes live
- show the team fully understands the service after it’s gone live

### Example questions
- what different technical specialities do you have within the team?
- how have you engaged with other teams such as QA, centralised devops, technical architecture, technical design authorities, pen testing?
- if one or two people left, how would this impact delivery and how quickly could it be mitigated?
- do you have any single points of failure? how are they mitigated?

## 4. Use agile methods

Build your service using the agile, iterative and user-centred methods set out in the manual.

### You need to
- explain how you’re working in an agile way, using agile tools and techniques
    - stories and spikes
    - PRs
    - automated tested / CI
    - deployment pipeline / CD
- explain how you and your team have reviewed and iterated the ways you work to fix problems
    - tech review / retro
- explain how your team is using agile tools and techniques to communicate with each other
    - Issue tracking e.g. Jira
    - Wiki e.g. Confluence
    - Code and PRs using GitHub
    - Messaging using Slack
- give an example of how the team has responded to user research and usability testing
- show that your governance is agile, based on clear and measurable goals, and has a clear focus on managing change and risk in real time
    - this may be out of your hands
    
## 5. Iterate and improve frequently

Build a service that can be iterated and improved on a frequent basis and make sure that you have the capacity, resources and technical flexibility to do so.

- explain what you’ve built in that phase and why you built it
    - prototypes
    - front-end apps
    - back-end services
    - tests
    - infrastructure as code / deployment pipelines
- describe the lifecycle of a user story from user research to production
- show you understand how your service is built to meet user needs
    - prototyping
    - user testing
    - BDD
    - accessibility / security / performance testing
- explain your process for identifying and prioritising insights from user research
- show you can move user stories quickly and smoothly between user research and production
- show there’s minimal risk associated with the technology you chose
    - you should be using mainstream, open-source tech. Underatand its usage trends
    - you should be avoiding proprietary tech
    - you should understand the prevailing tech landscape
    - you should understand possible support requirements
- prove you have the ability to deploy software frequently with minimal disruption to users
- show you’re analysing user research and using it to improve your service
    - attend user research debrief sessions
    - make coded prototypes available to use
- show you’re solving any technical problems you’ve found

At the beta assessment, you also need to explain:
- how long you expect your service to be in beta and why
- your way of deploying software, ie how you can deploy frequently with minimum impact on users

At the live assessment you also need to explain:
- how you’re practising zero downtime deployments in a way that doesn’t stop users using the service
- how you plan to have enough staff to keep improving the service

### Example questions
- describe your development process and build pipeline (e.g. PRs, unit tests running against these, flexible acceptance tests in an appropriate language)
- is all testing automated (acceptance, security, performance, accessibility)?
- what tech, code or design patterns did you change?
- how long does it take to get a minor change into production?
- how do you know your service is doing the right thing and doing the thing right?

## 6. Evaluate tools and systems
Evaluate what tools and systems will be used to build, host, operate and measure the service, and how to procure them.

### Alpha
To pass point 6 in the alpha assessment, you usually need to describe:

- the languages, frameworks and other technical choices you’ve made in alpha, and how this will affect the decisions you make in beta
    - describe again about avoiding vendor lock-in
    - describe modular development / microservices
- the set of programming tools you’d like to choose for beta and why
    - price / open source
    - popularity
    - accessibility
    - performance / security
    - learning curve
    - shininess
    - what other competing tools were considered and why were they ruled out?
- how you’ll get value for money when buying any tools
- how you’ll monitor the status of your service
    - health checks and automatic re-deployments
    - Pingdom / Datadog
    - AWS CloudWatch / Azure Monitor


### Beta
To pass point 6 in the beta assessment you usually need to explain:

- how you’re managing the limits placed on your service by the technology stack and development toolchain you’ve chosen
- what you’ve bought and how you’re getting value for money
demonstrate how you’ll monitor the status of your service
- the support arrangements you have in place, in normal hours and out of hours
- any decisions you’ve outsourced to third parties and why you chose to do this

### Live
To pass point 6 in the live assessment, you usually need to:

- describe the tech stack changes you made during beta and why
- describe the development toolchain changes you’ve made during beta and why
- explain how you’re continuing to get value for money from the systems you chose and bought at beta
- explain or demonstrate how you’ll check if the service is healthy
- explain the support arrangements that you’ve set up for live
- explain any decisions you’ve outsourced and why you chose to do this

### Example questions
- explain how you decided to use the development tools, languages, frameworks, databases etc.;
- has the service had technical design sign-off at appropriate milestones? Is the tech stack and hosting solution aligned with the organisations wider strategy?
- what have you done to see whether any tech and services you require can be reused from across the department and wider Government?
- how have you avoided vendor lock-in?
- how are you managing the constraints that the selection of technology stack places on you?
- what have you bought and how have you ensured you are getting value for money?

## 7. Understand security and privacy issues
Evaluate what user data and information the digital service will be providing or storing and address the security level, legal responsibilities, privacy issues and risks associated with the service (consulting with experts where appropriate).

### Alpha
To pass the alpha assessment for point 7 you usually need to explain:
  
- how you’ve identified threats to your service, including potential pathways for hackers, and tested ways of reducing them
    - will the service be publicly accessible?
    - will you need authentication and authorisation?
    - what type of data is going where?
    - any bulk upload of data?
- how you plan to keep up to date about threats to your service and how to deal with them
    - monitoring and alerting!
    - intrusion detection and prevention: host-based intrusion detection system (HIDS) can monitor and analyze network traffic, log files, and file access on a host. A HIDS typically integrates with alerting and automated remediation solutions to detect and address attacks, unauthorized / suspicious activities. See https://aws.amazon.com/blogs/security/how-to-monitor-host-based-intrusion-detection-system-alerts-on-amazon-ec2-instances/
    - set up monitoring for things such as attempt to sudo to ROOT, Web server errors (particularly 500 and 400), SSH insecure connection attempt, Login session opened or closed
    - have dashboards in your office
- any threats of fraud (fraud vectors) which exist and the controls you’re prototyping

### Beta and Live
To pass the beta and live assessments for point 7 you usually need to:
  
- describe your team’s approach to security and risk management
- describe the security and privacy threats to your service
- explain the fraud vectors that exist and the controls you’re putting in place
- describe how you’ve worked with the business and information risk teams eg senior information risk owner (SIRO), information asset owner (IAO) and data guardians, and how you’re working to meet any security regulations without putting delivery at risk
- describe any outstanding legal concerns, eg how you’ll protect data or your policy on sharing it 
- explain how you’re keeping your understanding of the threats to your service up to date
- present your cookie and privacy policy and explain how you arrived at it

   
### Example questions
- describe how you have secured your service (e.g. authentication (how)), Virus Scanning, TLS, WAF, firewalls etc.)
- how are production servers accessed?
- how do you ensure that source code and build artefacts are not tampered with?
- what data are you storing and where? Has the data been minimised, redacted encoded etc.? What sort of aggregation? Data retention policies. How is unwanted data removed? Any bulk download of data allowed? MI?
- is there any duplication of data within this service or using data from other services?
- what types of encryption have been used for the service? (in transit, at rest, in use)
- what other services are you integrating with? how have you ensured their data is correct? (e.g. schemas, contracts); do they use / store your data? do you use / store their data?
- who have you liaised with when evaluating security and privacy? e.g. SIRO (Senior Information Risk Owner), IAO (Information Asset Owner
- describe the threats to your service, how you identified them and how you have put controls in place
- what known threats have you left unaddressed as an acceptable risk?
- how do you get alerted to security / intrusion concerns?
- what kind of audit trail do you capture? how?

## 8. Make all new source code open
Make all new source code open and reusable, and publish it under appropriate licences (or provide a convincing explanation as to why this can't be done for specific subsets of the source code).

### Alpha
To pass, you usually need to:

- explain how you plan to make all new source code open and reusable
- confirm that you own the intellectual property

### Beta and Live
To pass, you also need to:

- show your code in an open internet source code repository
- explain the licences you’re using to release code during beta
- explain how you’re using code from other teams or services
- explain how a team in another department can reuse your code

### Example questions
- describe how your source code is open by default; If they are not, why are some components not open source? Is there a plan to make them open source?
- what licences are you using? why? are they aligned with Departmental strategy? what documentation do they have?
- have you produced any code, libraries or services which other departments can use? how can they find out about it? how are they curated? have you had any other contributors external to the team?
- are all useful open source components described on a public (e.g. GitHub) page?
- what libraries and code from other teams/services are you using?

## 9. Use open standards and common platforms
Use open standards and common government platforms where available, including GOV.UK Verify as an option for identity assurance.

### Alpha
To pass your alpha assessment, you usually need to explain how you:

- understand how open standards and common platforms could avoid you getting locked into contracts
    - open standards for the web (HTTP, REST)
    - open standards for data exchange (XML, JSON)
    - open standards for documents
- investigate use common platforms for your system, such as GOV.UK Verify, Defra Identity or HMRC Governemnt Gateway as an option for identity assurance
- identify the common user needs your service meets and what you reuse from across government to help meet those user needs

### Beta and Live
To pass your beta or live assessment, you also usually need to explain how you:

- use open standards and common platforms 
- manage what the service outputs to users is and in what format
- manage common data you hold and your commitment to publishing it
- use common government platforms, such as GOV.UK Verify as an option for identity assurance
- integrate with any external or legacy systems
- identify the common user needs your service meets and what you reuse from across government to help meet those user needs
- manage the common data you hold and meet your open data responsibility


## 10. Test the end-to-end service
Be able to test the end-to-end service in an environment identical to that of the live version, including on all common browsers and devices, and using dummy accounts and a representative sample of users.

To pass the alpha, beta and live assessments, you usually need to show that you:

- have an effective deployment environment
    - deployment pipeline
- can create new environments quickly and easily
    - using infrastructure as code
- know the data that exists in your pre-production environments
    - automated process for creating this data either from scratch or derived from live with appropriate codification
- are designing and testing your service to work with the devices and - browsers your users use - find out the browsers you must test with
- are testing your service in an environment that’s as similar to live as possible
    - see https://www.gov.uk/service-manual/technology/designing-for-different-browsers-and-devices
- know that your service can keep working when the number of expected users try to use it, including for users who need assisted digital support
    - performance testing (including realistic, longer running tests)
    - what is the offline / assisted digital model?
- understand the systems you need and the testing environments for non-digital parts of the service
- are testing your service frequently - you’ll have to explain how you’ve decided how often to test
    - differentiate between automated testing and manual QA, exploratory testing, accessibility testing, pen testing, sanity testing

### Example questions
- what environments do you have?
- how quickly can you spin a new environment up and who can do this?
- how do these environments differ to production?
- how do you get a representative sample of data on pre-production environments? Do you scrub production data?
- how do you identify what browsers / devices you should test against? what automated device testing do you use? is there any manual testing?
- what performance testing have you done in what environments? is it part of CI?

## 11. Make a plan for being offline

Make a plan for the event of the digital service being taken temporarily offline.

### Alpha
To pass the alpha assessment you need to be able to explain
- how users would be affected if your service was unavailable for any length of time.

### Beta and Live
To pass you usually need to also explain:

- how you’re making sure the technology and platforms you’ve selected  meet your availability requirements
- your data recovery strategy and how you’ve tested it / how often
- the most likely causes for the service going offline and how you plan to stop them from happening
- your strategy for dealing with outages, including who’s responsible and the decisions they can make

### Example questions
- how have you evaluated the performance / scalability / throughput requirements of the service?
- what are your SLAs? do the technologies and hosting solutions chosen enable these SLAs to be met?
- horizontal scalability / resiliency? Replication?
- how will you know if the service is healthy? Is this done in the standard way? what monitoring / alerting do you have in place?
- explain the impact upon the users of the service being unavailable for any length of time
- what information is logged? how are the logs accessed?
- what data backups to you have? where are they? are they encrypted? how easily can you restore data?
- what disaster recovery do you have? active-active or active-passive?
- what things are most likely to take you offline and what mitigations you are considering?
- what is your strategy for dealing with an incident and who is responsible for doing this?
- how did you evaluate what support arrangements are needed, and what arrangements have you got in place? Is this aligned with the department's solution for support?

## 13. Make the user experience consistent with GOV.UK
Build a service consistent with the user experience of the rest of GOV.UK including using the design patterns and style guide.

Note that by default server-side-rendering (SSR) and possibly progressive enhancement are expected - https://www.gov.uk/service-manual/technology/using-progressive-enhancement

### Alpha
To pass your alpha, beta, and live assessments you usually need to:
- explain how your team has included designers, content designers and frontend developers
- show you’ve got a start and end page on GOV.UK and that both are optimised for users
- explain how the service has used the GOV.UK design patterns, frontend toolkit and elements
    - Grid layout
    - Colours
    - Typography (New Transport font stack)
    - Buttons, Selection Buttons
    - Phase banner
    - Design patterns include date, check your answers, 

### Beta and Live
To pass the beta and live assessments you also need to show:

- the service is responsive and works on mobile devices
- the headers and footers match the GOV.UK style


## Accessibility note
You must build an accessible service as part of meeting these points:

- point 1 (understand user needs)
- point 2 (do ongoing user research)
- point 12 (make sure users succeed first time)

From alpha you need to undertand how what you have built conforms to:
- WCAG design principles - https://www.gov.uk/service-manual/helping-people-to-use-your-service/understanding-wcag-20
- Whether the service meets an accessibility checklist - https://accessibility.18f.gov/checklist/      
- automated accessibility testing to ensure the service meets level AA of the Web Content Accessibility Guidelines 2.0 (WCAG 2.0) and works on the most commonly used assistive technologies like screen readers and speech recognition tools
