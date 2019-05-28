# Translation Guidelines

*“Fundamentally, translation is about understanding the source document, understanding the subject matter, and writing well.”* 
                                                                                 - A guide to translation project management

## Introduction
These are basic guidelines to help Bisq translators and reviewers do their work effectively. They will be periodically updated to reflect the latest changes in the project and input from other contributors.

## Transifex project
The Bisq Transifex project is run by a group of Bisq contributors: Transifex admins, translators and reviewers. [Transifex admins](transifexadmin.md) coordinate various activities and may also contribute as translators and/or reviewers. Currently, we have one active Transifex project, bisq-desktop, to translate the Bisq software, and we have started a new project, bisq-website, to translate certain Bisq pages.

All the translations for Bisq need to go through Transifex to be evaluated and reviewed. The exceptions may be translations for videos on the Bisq YouTube channel (to be discussed further). Currently, we have one active project, bisq-desktop, which involves the translation of the Bisq software into nine core languages. A new project, bisq-website (translating certain Bisq pages), is under way.

## Communication
Daily communication occurs on the #transifex Slack channel, while major announcements are posted in Transifex (announcements and [team discussions](https://www.transifex.com/bisq/teams/69542/discussions/)), and on [Bisq forum](https://bisq.community/t/internationalization/1700/12) as well as Slack.

## Translators
Anyone can become a translator by creating a [Transifex](https://www.transifex.com/bisq) account and requesting permission to translate. Please note that only translations for the languages that are included in each Bisq release are compensated at any given moment. You can learn more about it [here](translatordocumentation.md).

Each new software release contains the latest translations even though they have not been reviewed. This is done to have the software translations as complete as possible.

## Reviewers 
Reviews involve checking the translation thoroughly against the original. Ideally, a reviewer performs reviews on someone else's translation, and not on their own. Some language teams may consist of only one active translator. In this case, several options are available:
- Reviews can be postponed till a new translator joins the project.
- Reviews can be done by the translator him/herself if the admins or other translators trust that translator's skill.

A new translator needs to show their skill by translating first. Once the quality of their work has been assessed by the other translators, they can be granted permission to review.

In cases where Bisq is working with a translation agency, the agency has a choice of assigning their own translators as reviewers, and one of the Transifex admins accepts that choice based on their judgment (such as evaluating past work, etc).

## Language Quality Assurance
- If you notice a mistake in the English version, please report it by adding a comment to that particular string and tagging it as an issue. The admins will be informed of the issue and will take proper action. Also, feel free to raise the issue on the #transifex Slack channel.
- In the past, some strings had trailing spaces which caused some problems when updating the translations. Please make sure that there are no trailing spaces in the translated strings.
- Once the translations have been updated in [the next release](https://github.com/bisq-network/bisq/milestones), please check the strings in the updated software.

## Difficult Terms and Queries
Translators/reviewers might face difficulties rendering various terms/words/segments. To help address this issue, we are currently testing the following approach.

Please add queries to the [Query Tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0) so we can try finding solutions collectively (some of translators/reviewers might know the answer) or, if everyone has trouble rendering them, ask the devs to explain them to us / provide synonyms/alternatives. 

Please add the date and Transifex segment number, choose your language and indicate your question. Be sure to add your Transifex ID when leaving a query/answer so that we can get in touch with each other in case we need to elaborate on an issue (there's a sample query for guidance).

## Glossary
The purpose of the glossary is to provide consistency for the key terminology in a specific language, and to serve as a guide for new translators. This initiative is lead by @y3v63n, and the updates are communicated on the #transifex Slack channel and Team Discussions on Transifex.

Currently, we have over 100 high frequency terms in English, and these should be available in all core languages. The translators are encouraged to add more terms in their own language. Generally, it is best to just add the base form of a word (e.g., a verb in infinitive, or a noun as as subject, and not as a direct/indirect object).

## Bisq-website Project
- If you see, {% text %}, it is a Liquid element and shouldn't be translated.

## Style Guide
TBD

## Resources

[A guide to translation project management](https://courses.comet.ucar.edu/pluginfile.php/27060/mod_resource/content/12/GuideToTranslationManagement_V1a_02102017_final.pdf)

