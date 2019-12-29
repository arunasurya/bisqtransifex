# Proposal for a new Bisq Transifex Team Structure

## Current State
Currently the Bisq Transifex team has no clear organizational structure, apart from having two official admins and dozens of translators, all of whom working remotely across different time zones. We have over 30 languages and 160+ translators on the Transifex platform, but only 12 of those languages are core (the work for which is compensated), and only a fraction of the translators contribute regularly. 

Since Bisq is an open source project, anyone can become a translator by sending a request to join on Transifex, and all requests to translate are accepted. There is no systematic process to assess and verify the quality of translations and evaluate their usage. There have been some big changes in the client, so there is a strong need for ensuring that all participating translators have a moderately good understanding of the software to be able to convey it in their language.

Since there are no clearly defined roles for most contributors in the team, some contributions may not get fully recognized and properly compensated, which can lead to resentment and loss of trust in the  whole project. Lack of accountability can lead to a sporadic workflow, and lack of hierarchy can cause delays or apathy in some projects.

While we have two admins, one of them (@ripcurlx) is also highly involved in many vital Bisq projects thart require his attention, and the other (@arunasurya) is not available full time. As more and more contributors join, and more core languages are added, it becomes unmanageable for admins to communicate effectively with all the translators.

## Proposal

### Structure
Given these factors, I propose the following web-like team structure, as roughly depicted in the diagram below: 
- Each circle and their respective letters represent *roles, not people*. These include admins, coordinators, translators and reviewers.
- The numbers represent each of the current twelve core languages and their variants.
- Each language team has a coordinator who is typically also a translator, and other translators and reviewers.
- The grey area means that most of the tasks or roles can be done by a single contributor. For instance, a coordinator can also act as a reviewer, and one of the admins can do most of the tasks.
- The solid lines between the roles represent regular communication and close collaboration. Thus, the admins work closely with each other and with the coordinators, while coordinators work closely with the translators and reviewers for their specific language.
- There is open communication on Keybase (#transifex channel) and other platforms where existing translators can share their ideas and concerns and new translators can reach out to anyone in the channel, as represented by dotted lines.
- Admins ensure that all the Bisq translations are accurate and updated, and that everyone in the team has a clear understanding of the project and its goals. While they work closely with the coordinators, they are also available to welcome and answer questions from new contributors, and connect them to the right team coordinator.

All but two language teams already have unofficial [coordinators](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=98383320) who are open to contributing more. Some of the coordinators are also involved in current projects such as @fabiok(@fkrauss) who is looking into automating the website translation.

### Benefits
This web-like structure is in line with the Bisq DAO values such as meritocracy, gradual increase in responsibilities and open communication. It focuses more on roles than on people.
- *All core languages get attention*.
   - This structure ensures that all core languages are given proper attention.
- *There is a clear progression of roles*. 
   - While anyone can become a translator, one needs to demonstrate a high level of competence in their language to gain access to review. Those reviewers who further improve the software or/and translations by finding bugs, reporting issues, etc, can become coordinators, and can ask for compensation for the tasks they have performed. If there is a need for a new admin, the position can be filled by one of the active coordinators.
- *It is more manageable to have regular communication with contributors in each subteam*.
   - In this structure, the admins communicate regularly with each other and with the coordinators, while a coordinator communicates regularly with the translators and reviewers in their language subteam to discuss specific details of their work.
   - New temporary teams can easily arise to solve a specific problem (as seen in purple around C1, R1, PM). They have a similar structure to ensure that important aspects of the project are communicated to everyone. They will consist of an admin, a project maintainer for a specific project in Transifex (who can either be a part of the Transifex team or some other Bisq contributor), and a coordinator from a language team if the project is language specific.
- *Collaboration on new projects*.
   - The internal cohesion in each language team would allow for more effective ambassador work since there is an overlap between translators and ambassadors.


### Responsibilities

#### Admins
The admins will encompass three Transifex roles (an admin, a project maintainer and a team manager). A project maintainer role can also be shared with other contributors whose work is vital to a specific project. Admins may decide between themselves how to best split the responsibilities. At times, both admins are very active in the project, at other times, one may take over most of the tasks. In any case, there is continuous communication between them. Admins are ultimately responsible for the timely and consistent delivery of the high quality product (translations). Only one of the admins has access to merge changes to the software and update translations for each new release. They should have both a high level and a detailed view of the project.

#### Coordinators
A coordinator oversees activities in a specific language and has access to the following features in their specific language:
- Accept/deny join requests and invite translators.
- Assign some translators as reviewers.
- Start a team discussion.
- Review translations.
- Submit translations.

A coordinator is responsible for ensuring the quality, consistency and timeliness of translations in their language.
Coordinators actively participate in the Bisq DAO by voting up or down proposals by the translators in their team. In addition, a coordinator is available to guide new translators, help resolve Transifex issues in their language, and explore opportunities to expand Bisq in their region. Any coordinator who has contributed on a regular basis can become an admin once the position is open.


### Budget
I believe that the Bisq team should have a clear budget which includes:
- Compensation for translators and reviewers.
- Compensation for active contributors.
- Compensation for project maintainers who are not involved in the project full time.
- Compensation for admins.

## Next Steps
We already have a list of coordinators for almost all of the core language teams. I am planning to have regular calls with each of these coordinators. Each coordinator will then reach out to all the current translators and reviewers in their language team.

