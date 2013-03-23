BITeamwork Translations
=======================

This repository is established as a community-based extension to the popular BITeamwork plug-in for Oracle BI 11g.  It provides the means for users and developers of Oracle BI to contribute correct translations of the BITeamwork software in their native language.  Users can fork the repository, create a push request with a brand new language template by replacing the English values with those in a language which they natively speak. This type of collaboration assists in the global user adoption of BITeamwork and native speaking users.

General Direction
-----------------
Clearly this repository is housing translations for the BITeamwork plug-in framework. Initially our goal is to map locales to an arbitrary standard of the following list of Locales.

Wiki [Locales for Translation page](https://github.com/artofbi/BITeamwork-Translations/wiki/Locales-for-Translation).


Instructions
------------
To contribute to the language translation you may clone the repository.  If you are new to this process, first you must download the git software to your laptop/workstation.  Clone the repository via the command line by:

'git clone https://github.com/artofbi/BITeamwork-Translations.git'

This will create a new directory called /BITeamwork-Translations in the directory from which you ran the command.

Open the new directory and locate the two main template files: _messages_template.properties and _application-template.json

Save these files on your machine with the respective locale suffixes that you intend to translate the english values into.  For example, _messages_zh.properties and _application-zh.json or _messages_zh-CN.properties and _application-zh-CN.json respectively.

Country specific locales use a hyphen (-) not an underscore (_) to separate language and country code. For example, zh-CN and not zh_CN.

Once the files have been saved to the appropriate locale name, use your favorite editor and systematically translate the values (right side of the = or : signs) to the language leaving the english key names intact.

Save your translations and then post your updates by using the following git commands:
* 'git add *'
* 'git commit -m "Updates to Localization"'
* 'git push origin master'


Contributors
------------
All of the individuals who have humbled BITeamwork with their time and effort are listed here.  Special Thanks goes to:

* Google Translate

