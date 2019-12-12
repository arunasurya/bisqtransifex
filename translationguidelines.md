# Translation Guidelines

## Introduction
The aim of this document is to provide guidelines for translators and reviewers to do their job effectively.

## Translations


## Reviews
Reviews involve checking the translation thoroughly against the original. Ideally, a reviewer performs reviews on someone else's translation. Some language teams may consist of only one active translator. In this case, several options are available:
- Reviews can be postponed till a new translator joins the project (a string does not need to be reviewed to be included in the next software release).
- Reviews can be done by the same translator if they have shown solid knowledge of their language.

A new translator needs to show their skill by translating first. Once the quality of their work has been assessed by other translators in their language team, they can be granted permission to review. 

## Language Quality Assurance

### Mistakes in the Software
- If you notice a mistake in the English version, please report it by adding a comment to that particular string and tagging it as an issue in Transifex. The admins will be informed of the issue and will take proper action. Also, feel free to raise the issue on the #transifex keybase channel.

### Trailing spaces
- In the past, some strings had trailing spaces which caused some problems when updating the translations. Please make sure that there are no trailing spaces in the translated strings.
- Once the translations have been updated in [the next release](https://github.com/bisq-network/bisq/milestones), please check all the strings in your language in the updated software.

## Difficult Terms and Queries
Translators/reviewers might face difficulties rendering various terms/words/segments.
- Please add queries to the [Bisq query tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0) so we can try finding solutions collectively (some of translators/reviewers might know the answer) or, if everyone has trouble rendering them, ask the devs to explain them to us / provide synonyms/alternatives. The queries will be updated weekly, so please review the answers to your questions periodically and mark them as "resolved" if you are satisfied with the answers.
- Please add the date and Transifex segment number, choose your language and indicate your question. 
- Be sure to add your Transifex ID when leaving a query/answer so that we can get in touch with each other in case we need to elaborate on an issue (there's a sample query for guidance).

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

# Compensation

Currently, translations/reviews for the following languages are compensated: Spanish, Portuguese (Brazil and Portugal), French, Russian, German, Chinese (Mandarin and traditional), Japanese, Persian, Thai and Vietnamese.

## Rates

We use standard rates: 0.07BSQ per word for translations, 0.035BSQ per word for reviews. If you think that your language should have different rates, please raise this issue with your coordinator and admins.

## Process
In order to be compensated for your work, you need to submit a compensation request in Bisq DAO. Please submit details of your work in the request. This is done to help the stakeholders validate your request.

### Translators
- In Transifex, choose among filters *status: translated*.
- Pick your name/nick in *users: translator*.
- Choose the translation period in *date: translated after/before* to specify the translation to be compensated.
- After that, tick the box right to the filter field to select all strings, and you will see the total wordcount for the selected strings.

### Reviewers
- Use *status: reviewed*.
- Pick your name/nick in *users: reviewer*.
- Choose the period in *date: translated after/before* to specify the review to be compensated.
- After that, tick the box right to the filter field to select all strings, and you will see the total wordcount for the selected strings.

Please take screenshots of all your work for a certain period and include them in your compensation request. Here is an example of screenshots for reviewing a translation.
  
  ![Transifex comp request: reviewer April 2019](https://user-images.githubusercontent.com/43150241/56221854-4eb89e80-606b-11e9-9eff-1d8f23f4cf4c.png)

![Transifex comp req 3 April 2019](https://user-images.githubusercontent.com/43150241/56221896-5b3cf700-606b-11e9-8ba4-329152107e4a.png)

![Transifex comp req 2 April 2019 ](https://user-images.githubusercontent.com/43150241/56221966-7a3b8900-606b-11e9-9d7e-d22d14834fff.png)

![Transifex comp req 4 April 2019](https://user-images.githubusercontent.com/39760876/56637701-f0944880-6674-11e9-89af-2e0a20e3e876.png)

### Coordinators & Admins
Please specify the work you have done in this capacity by including examples of your work (reports, documentation, etc).




