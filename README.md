# What is l10n¹?

l10n is an easy to use issue tracker for the Windows 10 &amp; 11 Community Language Pack project.

## What is this project about?

We aim to help improve the quality of Windows language packs by giving the community a space to report & discuss any localization issue they stumble upon. This repository has two purposes:

-   Serve as a basis for creating **Community Language Packs** - final solutions for all reported issues will be used to create our own packs
-   Provide an easy to digest pool of feedback for Microsoft, emphasizing the importance of human review before shipping localizations

## Why is this happening?

While there is no official statement on the state of Windows localization, the recent observable trends in software development suggest that cost cutting & consequently relying on machine translations brought us where we're right now. Even with a dedicated localization team Microsoft has consistently shipped incorrect translations in key system areas since the first release of Windows 10 in 2015. Translation issues of course aren't entirely avoidable and while older Windows releases also suffered from them, they didn't use to be as glaring.

## Which Windows versions does this project support?

At the moment we support Windows 10 version 2004 (build 19041) and newer as well as Windows 11.

## How can I help?

Getting started is easy! All you have to do is use one of the Windows versions we support and be on the lookout for bad translations. For best results we recommend focusing on recently redesigned system areas (e.g. Settings), areas sporting modern design elements (e.g. Command Bar atop File Explorer), as well as areas you happen to use on a daily basis. Legacy components are rarely subject to re-translation and the likelihood of finding issues there is low.

These issues fall roughly into three categories:

-   **Incomprehensible translation** (often caused by the original English text using a word with multiple meanings in the target language)
-   **Awkwardly worded translation** (the text can be understood but uses rarely seen words or phrases in given context)
-   **Unnecessary translation** (app/brand names or loanwords that are better understood in their original form and don't need translation)

If you find something, go to the *[Issues](https://github.com/thebookisclosed/l10n/issues)* page in this repository and check if the issue you've found has already been reported. If not, feel free to create a *New Issue*! The template will guide you through the process. You can also look through the existing issues and provide feedback if you have a suggestion for any of them.

## How is using custom language packs possible?

The ability to load language packs delivered from the Microsoft Store found in Windows 10 version 1803 & newer also doubles as a way to load custom translations. The Community Language Pack team is building tools that will help recompile an original Microsoft sourced language pack with community provided corrections slotted on top. No existing system files are modified during this process.

¹*l10n is an abbreviation of "localization"*
