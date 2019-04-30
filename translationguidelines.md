# Translation Guidelines

*“Fundamentally, translation is about understanding the source document, understanding the subject matter, and writing well.”* 
                                                                                 - A guide to translation project management

## Introduction
These are basic guidelines to help Bisq translators and reviewers do their work effectively. They will be periodically updated to reflect the latest changes in the project and input from other contributors.

## Transifex project
The Transifex project is run by a group of Bisq contributors: Transifex admins, translators and reviewers. [Transifex admins](transifexadmin.md) coordinate various activities and may also contribute as translators and/or reviewers.

All the translations for Bisq need to go through Transifex to be evaluated and reviewed. The exceptions may be translations for videos on the Bisq YouTube channel. This is open to discussion among the translators.

## Communication
Daily communication occurs on the #transifex Slack channel, while major announcements are posted in Transifex (announcements and [team discussions](https://www.transifex.com/bisq/teams/69542/discussions/)), and on [Bisq forum](https://bisq.community/t/internationalization/1700/12) as well as Slack.

## Translators
Anyone can become a translator by creating a [Transifex](https://www.transifex.com/bisq) account and requesting permission to translate. Please note that only translations for the languages that are included in each Bisq release are compensated at any given moment. You can learn more about it [here](translatordocumentation.md).

Each new software release contains the latest translations even though they have not been reviewed. This is done to keep the software translations as up-to-date as possible.

## Reviewers 
Reviews involve checking the translation thoroughly against the original. Ideally, a reviewer performs reviews on someone else's translation, and not on their own. Some language teams may consist of only one active translator. In this case, several options are available:
- Reviews can be postponed till a new translator joins the project.
- Reviews can be done by the translator him/herself if the admins or other translators trust that translator's skill.

A new translator needs to show their skill by translating first. Once their translation can be assessed by the other translators, they can be granted permission to review.

In cases where Bisq is working with a translation agency, the agency has a choice of assigning their own translators as reviewers, and one of the Transifex admins accepts that choice, based on on their judgment (such as past work, etc).

## Language Quality Assurance
- If you notice a mistake in the English version, please report it by adding a comment to that particular string and tagging it as an issue. The admins will be informed of the issue and will take proper action. Also, feel free to raise the issue on the #transifex slack channel.
- In the past, some strings had trailing spaces which caused some problems when updating the translations. Please make sure that there are no trailing spaces in the translated strings.
- Once the translations have been updated in [the next release](https://github.com/bisq-network/bisq/milestones), please check the strings in the updated software.

## Difficult Terms and Queries
Translators/reviewers might face difficulties rendering various terms/words/segments. To help address this issue, we are currently testing the following approach.

Please add queries to the [Query Tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0) so we can try finding solutions collectively (some of translators/reviewers might know the answer) or, if everyone has trouble rendering them, ask the devs to explain them to us / provide synonyms/alternatives. 

Similarly to Review Report, please add the date and Transifex segment number, choose your language and indicate your question. Be sure to add your Transifex ID when leaving a query/answer so that we can get in touch with each other in case we need to elaborate on an issue (there's a sample query for guidance).

## Glossary
- A glossary is needed to provide consistent translations of high frequency terms (such as transaction, private/public key, etc). 
- This initiative is currently lead by @y3v63n, and the updates are communicated on the #transifex Slack channel.

## Style Guide
TBD

## Resources
Feel free to suggest more resources!

[A guide to translation project management](https://courses.comet.ucar.edu/pluginfile.php/27060/mod_resource/content/12/GuideToTranslationManagement_V1a_02102017_final.pdf)

