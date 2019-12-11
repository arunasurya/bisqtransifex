# Transifex Quality Assurance

## Introduction
The aim of this document is to help translators and reviewers provide 

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

Please add queries to the [Bisq query tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0) so we can try finding solutions collectively (some of translators/reviewers might know the answer) or, if everyone has trouble rendering them, ask the devs to explain them to us / provide synonyms/alternatives. The queries will be updated weekly, so please review the answers to your questions periodically and mark them as "resolved" if you are satisfied with the answers.

Please add the date and Transifex segment number, choose your language and indicate your question. Be sure to add your Transifex ID when leaving a query/answer so that we can get in touch with each other in case we need to elaborate on an issue (there's a sample query for guidance).

## Glossary
The purpose of the glossary is to provide consistency for the key terminology in a specific language, and to serve as a guide for new translators. This initiative is lead by @y3v63n.

Currently, we have over 100 high frequency terms in English, and these should be available in all core languages. The translators are encouraged to add more terms in their own language. Generally, it is best to just add the base form of a word (e.g., a verb in infinitive, or a noun as as subject, and not as a direct/indirect object).

## Bisq-Website Transifex Project
There are several symbols that don't need to be translated or changed. They should be market in Transifex as "notranslate". Here are a few examples.
- If you see `{% text %}` it is a Liquid element and should not be translated.
- `_blank` should not be translated.
- `&#8217;` is an apostrophe, like in `I'm`, and will appear in the software as an apostrophe.

## Style Guide
The purpose of the style guide is to set certain translation standards for our projects. It covers the tone of the target language, style and various nuances for specific languages, and discusses how to deal with hard to translate terms such as Bitcoin or blockchain. 

The style guide should be available directly in Transifex in the future. At this moment, we are using the Bisq query tracker to write down a list of hard to translate terms. If you don't know whether to leave a certain term as it is, translate or transliterate it, please take a look at the tracker, see how other translators approached the term, and enter your thoughts there.

## Resources

[A guide to translation project management](https://courses.comet.ucar.edu/pluginfile.php/27060/mod_resource/content/12/GuideToTranslationManagement_V1a_02102017_final.pdf)

