# Requirements and Stakeholder
The ReportEditor feature requires user can have report data and organize it into one document. Stake holder is A department.
# Constraints
Some kind of data is not available in the data system yet. they are operation log, operator comments and etc.
# Context
The feature will be a page (Name: ReportEditor) on currect AAA application which is a single page application, authentication and logging is alreay done.
User is data specialist
# Solution strategy
quality goals
1. For most user scenario, user can complete the editing in 5 minutes.
2. Loading and saving result request in 1 sec.

| Frontend | Backend |
| ----------- | ----------- |
| ReportEditor page | ReportService, DataService |

# Building block view
to be uploaded
# Runtime view
1. Happy workflow
2. Negative workflow
# Deployment view
to be uploaded
# Crosscutting concepts
1. Report
2. User role and Feature management
3. Logging
# Architectural decisions
Since currently only static data is available in report, DataService only desined one api to provide data, other apis will be designed later.
No notification to other users once a report is ready.
# Quality tree and -scenarios
# Risks and technical debt
# Glossary
