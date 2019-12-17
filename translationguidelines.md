# Translation Guidelines

## Introduction
The aim of this document is to provide guidelines for translators and reviewers to do their job effectively.

## Table of Contents
1. [Language Quality Assurance](##language-quality-assurance)
2. [Reviews](##reviews)
3. [Difficult Terms and Queries](##difficult-terms-and-queries)
4. [Compensation](##compensation)
5. [New Language Proposals](##new-language-proposals)

## Language Quality Assurance

### Mistakes in the Software
- If you notice a mistake in the English version of the software, please report it by adding a comment to that particular string and tagging it as an issue in Transifex. The admins are informed of the issue and will take proper action. Feel free to raise the issue on Keybase, especially if it is urgent.

### Trailing spaces
- In the past, some strings had trailing spaces which caused problems when updating the translations. Please make sure that there are no trailing spaces in the translated strings.
- Once the translations have been updated in [the next release](https://github.com/bisq-network/bisq/milestones), please check all the strings in your language in the updated software.

## Reviews
Reviews involve checking the translation thoroughly against the original. A new translator needs to show their skill by translating first. Once the quality of their work has been assessed by other translators in their language team, they can be granted permission to review. 

Ideally, a reviewer performs reviews on someone else's translation. Some language teams may consist of only one active translator. In this case, several options are available:
- Reviews can be postponed till a new translator joins the project (a string does not need to be reviewed to be included in the next software release).
- Reviews can be done by the same translator if they have shown solid knowledge of their language.

## Difficult Terms and Queries
Translators/reviewers might face difficulties rendering various terms/words/segments.
- Please add queries to the [Bisq query tracker](https://docs.google.com/spreadsheets/d/1P4JMLrcRtSWkxfh9jG7AXkfdgdkEYwgttGgly-ercXc/edit#gid=0) so we can try finding solutions collectively (some of translators/reviewers might know the answer) or, if everyone has trouble rendering them, ask the devs to explain them to us / provide synonyms/alternatives. The queries will be updated regularly, so please review the answers to your questions periodically and mark them as "resolved" if you are satisfied with the answers.
- Please add the date and Transifex segment number, choose your language and indicate your question. 
- Be sure to add your Transifex ID when leaving a query/answer so that we can get in touch with each other in case we need to elaborate on an issue (there's a sample query for guidance).

## Compensation

Currently, translations/reviews for the following languages are compensated: Spanish, Portuguese (Brazil and Portugal), French, Russian, German, Chinese (Mandarin and traditional), Japanese, Persian, Thai and Vietnamese. 

If a language that is currently not part of the core group becomes a core language, then the past translations and reviews for that language are compensated.

### Rates

We use standard rates: 0.07BSQ per word for translations, 0.035BSQ per word for reviews. If you think that your language should have different rates, please raise this issue with your coordinator and admins.

### Process
In order to be compensated for your work, you need to submit a compensation request in Bisq DAO. Please submit details of your work in the request. This is done to help the stakeholders validate your request.

#### Translators
- In Transifex, choose among filters *status: translated*.
- Pick your name/nick in *users: translator*.
- Choose the translation period in *date: translated after/before* to specify the translation to be compensated.
- After that, tick the box right to the filter field to select all strings, and you will see the total wordcount for the selected strings.

#### Reviewers
- Use *status: reviewed*.
- Pick your name/nick in *users: reviewer*.
- Choose the period in *date: translated after/before* to specify the review to be compensated.
- After that, tick the box right to the filter field to select all strings, and you will see the total wordcount for the selected strings.

Please take screenshots of all your work for a certain period and include them in your compensation request. Here is an example of screenshots for reviewing a translation.
  
  ![Transifex comp request: reviewer April 2019](https://user-images.githubusercontent.com/43150241/56221854-4eb89e80-606b-11e9-9eff-1d8f23f4cf4c.png)

![Transifex comp req 3 April 2019](https://user-images.githubusercontent.com/43150241/56221896-5b3cf700-606b-11e9-8ba4-329152107e4a.png)

![Transifex comp req 2 April 2019 ](https://user-images.githubusercontent.com/43150241/56221966-7a3b8900-606b-11e9-9d7e-d22d14834fff.png)

![Transifex comp req 4 April 2019](https://user-images.githubusercontent.com/39760876/56637701-f0944880-6674-11e9-89af-2e0a20e3e876.png)

#### Coordinators & Admins
Please specify the work you have done in this capacity by including links to your work (reports, documentation, etc).

## New Language Proposals
Our main priority is to produce complete and high quality translations of the Bisq software for users in countries where we believe Bisq is needed or used. Although we are open to accepting new translators and requests for new languages, we have budget constraints, and that is why we prioritize core languages over dozens of others that are available in Transifex, and only compensate work done for those core languages.

The Bisq software is currently available in English, Spanish, Portuguese (Brazil and Portugal), French, Russian, German, Chinese (Mandarin and traditional), Japanese, Persian, Thai and Vietnamese. These are core languages the work for which is compensated.

The core language list is based on several factors such as:
- The number of speakers worldwide in that language (e.g., Spanish, Portuguese, Russian, Japanese and Mandarin Chinese).
- Trading activity in that language (e.g., Portuguese, Spanish).
- Competence in English among speakers of a certain language (e.g., Japanese).
- Translator activity level.
- Importance of introducing Bisq to certain markets because of growth opportunities, etc.

### Adding a Language to the Core Group
If you believe that your language should be part of the core group, we suggest that you start by sharing your ideas on #transifex channel on Keybase and engaging other contributors in the dicussion. If you are committed to having your language represented in Bisq, you may want to start by translating the [Bisq vision](https://bisq.network/vision/) page which can help us determine if there is any interest in Bisq.

You can then write [a proposal](https://docs.bisq.network/proposals.html) which you need submit to the Bisq DAO.

Please specify in your request the current state of your language (e.g., what fraction of it has been translated, if any), the total cost for the translation and review of the entire software into your language as well as solid reasons to add your language to the core list. This will make it easier for Bisq stakeholders to assess your proposal and make a decision. 

A new language is most likely to be accepted if there is an active effort to expand its user base via meetups, [liquidity weeks](https://github.com/bisq-network/compensation/issues/62), forums, etc. Also, the stakeholders are more likely to be approve your proposal if they believe that you are committed to the project and will be able to deliver translations and reviews on a regular basis.

Once the proposal is accepted by the stakeholders, a Bisq developer will send a pull request to add the language which will then be accepted by one of the admins.

### Removing a Language from the Core Group
If a core language does not provide any value (e.g., no user interest) or if there is no or sporadic translator activity, that language may be removed from the list. This applies especially to those languages that are not widely spoken or if they are in the European Union. If a language (such as Greek) has been part of the core language list and was recently removed, the past work for that language is still compensated. 

To remove a language from the core list, an admin submits a proposal on the Bisq DAO. As soon as it is accepted, a pull request is sent to remove the language, and one of Transifex admins will accept that request.


