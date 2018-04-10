## Put in place a sustainable multidisciplinary team that can design, build and operate the service


### Example questions
- what different technical specialities do you have within the team?
- how have you engaged with other teams such as QA, centralised devops, technical architecture, technical design authorities, pen testing?
- if one or two people left, how would this impact delivery and how quickly could it be mitigated?
- do you have any single points of failure? how are they mitigated?

## Build a service that can be iterated and improved on a frequent basis

### Example questions
- describe your development process and build pipeline (e.g. PRs, unit tests running against these, flexible acceptance tests in an appropriate language)
- is all testing automated (acceptance, security, performance, accessibility)?
- how long does it take to get a minor change into production?
- do you use feature branches or feature switches?
- how do you produce release notes? If so, who reads them?

## Evaluate what tools and systems will be used to build, host, operate and measure the service

### Example questions
- explain how you decided to use the development tools, languages, frameworks, databases etc.;
- has the service had technical design sign-off at appropriate milestones? Is the tech stack and hosting solution aligned with the organisations wider strategy?
- what have you done to see whether any tech and services you require can be reused from across the department and wider Government?
- how have you avoided vendor lock-in?
- how are you managing the constraints that the selection of technology stack places on you?
- what have you bought and how have you ensured you are getting value for money?

## Evaluate what user data service will be providing or storing, and address the security level, legal responsibilities, privacy issues and risks

### Example questions
- describe how you have secured your service (e.g. authentication (how)), Virus Scanning, TLS, WAF, firewalls etc.)
- how are production servers accessed?
- how do you ensure that source code and build artefacts are not tampered with?
- what data are you storing and where? Has the data been minimised, encoded etc.? What sort of aggregation? Data retention policies. How is unwanted data removed? Any bulk download of data allowed? MI?
- is there any duplication of data within this service or using data from other services?
- what types of encryption have been used for the service? (in transit, at rest, in use)
- what other services are you integrating with? how have you ensured their data is correct? (e.g. schemas, contracts); do they use / store your data? do you use / store their data?
- who have you liaised with when evaluating security and privacy? e.g. SIRO (Senior Information Risk Owner), IAO (Information Asset Owner
- describe the threats to your service, how you identified them and how you have put controls in place
- what known threats have you left unaddressed as an acceptable risk?
- how do you get alerted to security / intrusion concerns?
- what kind of audit trail do you capture? how?

## Make all new source code open and reusable, and publish it under appropriate licences

### Example questions
- describe how your source code is open by default; If they are not, why are some components not open source? Is there a plan to make them open source?
- what licences are you using? why? are they aligned with Departmental strategy? what documentation do they have?
- have you produced any code, libraries or services which other departments can use? how can they find out about it? how are they curated? have you had any other contributors external to the team?
- are all useful open source components described on a public (e.g. GitHub) page?
- what libraries and code from other teams/services are you using?

## Test the end-to-end service in an environment identical to that of the live version, including on all common browsers and devices

### Example questions
- what environments do you have?
- how quickly can you spin a new environment up and who can do this?
- how do these environments differ to production?
- how do you get a representitive sample of data on preproduction environments? Do you scrub production data?
- how do you identify what browsers / devices you should test against? what automated device testing do you use? is there any manual testing?
- what performance testing have you done in what environments? is it part of CI?

## Monitor the live service / support / make a plan for the event of the digital service being taken temporarily offline.

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