> **Fork context:** this repository is a fork of [Theil-IT/bcxman](https://github.com/Theil-IT/bcxman). The documentation below retains the original project's authorship. Use the parent repository for its published releases and support guidance; this audit does not establish a separate maintained distribution or promise synchronization.
>
> [Compare this fork with its parent](https://github.com/Theil-IT/bcxman/compare/main...javiarmesto:bcxman:main). The comparison shows the current differences; fork-specific behavior must be assessed from those changes. Static documentation review: **6 October 2026**; no build, installation or service invocation performed.

# BCXMAN · AL translation example

Business Central extension for working with translation projects and terms. The manifest declares BC application **26.0.0.0**, runtime **15.2** and BCXMAN version **16.0.0.0**. Start with [.assets/Setup.md](.assets/Setup.md), then create a translation project. Compile/publish with AL Language in your own compatible sandbox after configuring `launch.json` and downloading symbols. The manifest's “Open-Source” description and `Warrenty.txt` do not establish an applicable reuse license; that remains unresolved in this audit.


# [See Full Documentation here](/.assets/Setup.md)

## Or jump to: 

- [Setup](/.assets/Setup.md)
    - [AI Assisted Translations](/.assets/Setup.md#ai-translate-tools)
- [Creating a project](/.assets/Projects.md)
    - [Project Import](/.assets/Projects.md#project-import)
    - [Reference Projects](/.assets/Projects.md#reference-projects)
- [Working with Translations](/.assets/Translations.md)
    - [Translation Terms](/.assets/Translations.md#translation-terms)

![Bcxman screens](/.assets/bcxman.png)


## Changelog:
Updated and Extended by Jesper Theil Hansen

Web site : http://www.theil-it.dk

Originally Written by Peik Bech-Andersen - Github project available here: [AL-Translate-Tool-15](https://github.com/peikba/AL-Translate-Tool-15)

Web site http://b-a.dk/

Blog: https://dynamicsuser.net/nav/b/peik


## 2025-09-05 
- DeepL translation
- Misc. bugfixes

## 2025-08-29 : Update to version 16,  JTH
- Update to BC26
- Add support for "Equivalent language" 
- Add OpenAI API Translation option     
- Add support for pre-translate terms
- Change Import to be code based instead of XMLPorts
- Add support for exporting complete project with all language files 
- Fixed error when copying duplicate text to duplicates (it copied across other languages)
- Fixed error using occurencies wrong in the AI-supported translate
- Support import of complete project with all files at once
- Occurencies not using language, fixed
- Removed NAV2018 support

## To Do 

## 29-05-2020
Added User Access
Added Role Center and Activities
Replaced "BAC Translation Project Name" with "BAC Translation Project"
Changed Import Translation XML port to handle al-object-target occasionally
Changed Export Translation XML port to correct tag name for source-language
Added fields to Source and Target al-object-target

## 05-07-2020
Enabled importing Base Application Translation Target
