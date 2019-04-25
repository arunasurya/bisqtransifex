# Translation Guidelines

*“Fundamentally, translation is about understanding the source document, understanding the subject matter, and writing well.”* 
                                                                                 - A guide to translation project management

## Introduction
These are rough guidelines to facilitate a smooth translation process and produce accurate and up-to-date translations. All the translations for Bisq need to go through Transifex to be evaluated and reviewed.

## Transifex project
The Transifex project is run by a group of Bisq contributors: Transifex admins, translators and reviewers. [Transifex admins](transifexadmin.md) coordinate various activities and often also contribute as translators and/or reviewers.

## Translators
Anyone can become a translator by requesting permission to translate. Please note that only translations for certain languages are compensated at any given moment. You can learn more about it [here](translatordocumentation.md).

## Reviewers
Reviews involve checking the translation thoroughly against the original. Each new software release contains the latest translations even though they have not been reviewed. This is done to provide the users with as complete translations as possible.

Ideally, a reviewer performs reviews on someone else's translation, and not on their own. Some language teams may consist of only one active translator. In this case, several options are available:
- Reviews can be postponed till a new translator joins the project.
- Reviews can be done by the translator him/herself if the admins trust that translator's skill.

A new translator with no prior translation work in Bisq needs to show their skill by translating first. Once their translation can be assessed by the other translators, they can be granted permission to review.

## Transifex-specific quality control
- If you encounter unclear terms on Transifex, please add them to the [Bisq Query Tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0). The list will be shared with the developers to gain clarity.
- If you notice a mistake in the English version, please report it by adding a comment to that particular string and tagging it as an issue. The admins will be informed of the issue and will take proper action. Also, feel free to raise the issue on the #transifex slack channel.
- In the past, some strings had trailing spaces which caused some problems when updating the translations. Please make sure that there are no trailing spaces in the strings.
- Once you are done with your translation and think that it is ready for a new release, please check your translation in the software itself.

## Glossary
- A glossary is needed to provide consistent translations of high frequency terms (such as transaction, private/public key, etc). 
- This initiative is lead by @y3v63n, and the updates are communicated on the #transifex Slack channel.

## Style Guide
TBD 

## Resources
Feel free to suggest more resources!

[A guide to translation project management](https://courses.comet.ucar.edu/pluginfile.php/27060/mod_resource/content/12/GuideToTranslationManagement_V1a_02102017_final.pdf)

