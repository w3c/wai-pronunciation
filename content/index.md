---
title: "Pronunciation Overview"
permalink: /pronunciation/
ref: /pronunciation/
lang: en
last_updated: 2021-05-19   # put the date the translation was completed or updated
# translators:   # Uncomment (remove #) for translations, one - name line per translator.
# - name: Translator 1
# contributors:
# - name: Contributor 1
github:
  repository: w3c/wai-pronunciation
  path: 'content/index.md'
feedbackmail: wai@w3.org
footer: >
  <p><strong>Date:</strong> Updated 19 May 2021.</p>
  <p><strong>Editors:</strong> <a href="http://www.w3.org/People/Shawn/">Shawn Lawton Henry</a> and <a href="http://www.w3.org/People/roy/">Ruoxi Ran</a>.</p>
  <p>Developed with input from the <a href="https://www.w3.org/WAI/APA/task-forces/pronunciation/">Pronunciation Task Force</a>.<p>
---

{::nomarkdown}
{% include box.html type="start" title="Summary" class="" %}
{:/}

This page introduces work to enable screen readers and voice assistants to pronounce words correctly.

The goal is to provide standards and best practices for text-to-speech (TTS) synthesis of HTML content.

Quick link to latest publication:
* [Specification for Spoken Presentation in HTML _(Working Draft Note)_](https://www.w3.org/TR/spoken-html/)

{::nomarkdown}
{% include box.html type="end" %}
{:/}

{% include toc.html %}

## Introduction

Most people who are blind rely on text-to-speech (TTS) software called screen readers. Some people with cognitive disabilities who have difficulty processing written text also use screen readers. Text-to-speech is essential for people with disabilities and useful for all.

TTS is now widely used in popular applications such as voice assistants. Many computers and mobile devices today have built in text-to-speech functionality that is used by people without disabilities in different situations, such as when they lose their glasses or their eyes are tired.
 
Accurate pronunciation is essential in many situations, such as education and assessment (testing students).

Currently text-to-speech pronunciation is often inaccurate and inconsistent because of technology limitations. For example, incorrect pronunciation may be based on context, regional variation, or emphasis.

{::nomarkdown}
{% include box.html type="start" title="Examples:" %}
{:/}

The address:<br>"123 Maple Dr., St. Paul, Minn" is often spoken by TTS as:<br>"123 maple doctor, street paul, min"  instead of:<br>"123 Maple Drive, Saint Paul, Minnesota".

"Reading" is pronounced differently if it is the city in England or in the phrase "reading a book".

{::nomarkdown}
{% include box.html type="end" %}
{:/}

W3C is developing normative specifications (standards) and guidance on best practices so that text-to-speech (TTS) synthesis pronounce HTML content (for example, web pages) correctly. This will allow content creators to specify how words should be pronounced.

## Explainer and User Scenarios

[Explainer: Improving Spoken Presentation on the Web](https://www.w3.org/TR/pronunciation-explainer/) provides an overview of the work. It:

- Briefly introduces the context for W3C work on pronunciation
- Describes the advantages and disadvantages of two approaches
- Poses questions for additional input

[Pronunciation User Scenarios](https://www.w3.org/TR/pronunciation-user-scenarios/) provides examples of:
- End-users, including screen reader users
- Content providers, including educators
- Software developers, including content management systems

## Exploring Technical Solutions

The Pronunciation Task Force has been exploring technical options for content authors to provide pronunciation information. A challenge is developing a solution that will be used by screen readers. One aspect of that work is analyzing how required features for accurate pronunciation are covered in existing technical specifications, including HTML5. 

[Pronunciation Gap Analysis and Use Cases](https://www.w3.org/TR/pronunciation-gap-analysis-and-use-cases/) provides details on the analysis. It:
- Provides more detailed context
- Describes required features for pronunciation and spoken presentation
- Describes specific implementation approaches for introducing presentation authoring markup into HTML5 (called “use cases”)
- Provides a gap analysis
- Describes how the required features may be met by existing approaches

**[Specification for Spoken Presentation in HTML](https://www.w3.org/TR/spoken-html/)** provides details on two markup approaches. Both satisfy the requirements and provide consistent results. We seek feedback from authors and implementors on which approach would be most implementable across all spoken presentation applications.

## Who Develops the Pronunciation Documents

Pronunciation documents are developed by the [Pronunciation Task Force](https://www.w3.org/WAI/APA/task-forces/pronunciation/) of the [Accessible Platform Working Group (APA WG)](https://www.w3.org/WAI/APA/), which is part of the World Wide Web Consortium ([W3C](http://www.w3.org)) Web Accessibility Initiative ([WAI](http://www.w3.org/WAI/)). For more information about the Task Force, see the [Pronunciation Task Force page](https://www.w3.org/WAI/APA/task-forces/pronunciation/).

## Contributing to the Work

Opportunities for contributing to Pronunciation and other WAI work are introduced in [Participating in WAI](https://www.w3.org/WAI/about/participating/).

To get notifications of drafts for review, see [Get WAI News](https://www.w3.org/WAI/news/subscribe/) for links to WAI tweets, RSS feed, and WAI Interest Group (WAI IG) emails. An email address for sending comments on the pronunciation documents is included in the "Status of this Document" sections.

If you are interested in becoming a participant of the Pronunciation Task Force or have questions regarding its work, e-mail [Task Force Facilitators Irfan Ali and Paul Grenier, and W3C Staff Contact Roy Ran](mailto:iali@ets.org?pgrenier@gmail.com?CC=ran@w3.org&Subject=Personalization%20Task%20Force).
