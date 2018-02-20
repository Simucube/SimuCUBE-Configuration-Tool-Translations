# SimuCUBE Configuration Tool translation contribution

The purpose of this repository is to make it possible for users to contribute translations to SimuCUBE Configuration Tool.


## Tools required

Download Qt software package, and make sure QLinguist is included. Note, that Qt is quite large distribution. You will not need most of the packages.

User manual to make translations is available here:

http://doc.qt.io/qt-5/linguist-translators.html

* You will need to follow the instructions in "Translating Strings" section up to the point that every translation string shows up as being translated.
* There is no need to run the release tool, we will run it later.


## License

All contributors must agree to the Granite Devices Contributor License Agreement, posted at
https://granitedevices.com/wiki/Granite_Devices_Contributor_License_Agreement

All Granite Devices legal documents, such as the EULA, can be found from https://granitedevices.com/legal


## How to submit 

Translate the appropriate file using QLinguist. Simucubetuner is the internal name of the tool. Do not change the filenames. Submit your contribution by making a pull request, and include the following into the comment field to let us know that you agree upon the terms and conditions:

    I accept the Granite Devices Contributor License Agreement

Pull requests without this text will not be included.


## FAQ

Q: Do I need to keep the translation updated?

A: It would be nice, but not mandatory. Eventually, if enough changes are made, non-up-to-date translation will be dropped from the SimuCUBE Configuration Tool distribution.
<br>&nbsp;


Q: A language is missing, can I still translate to that language?

A: Yes. For missing languages, please write it as an issue or let us know otherwise, and we will add the appropriate template file for that language.
<br>&nbsp;


Q: Whats up with the %1 %2 etc. markers in the text?

A: Usually, the are used to make the text **bold**, stop making text bold, or to add html tags at those positions to generate the surrounded text as a link to a WWW site. Also, in some cases, a lonely %1 will get replaced by a numeric value. 


Q: I have other questions?

A: Yes, please ask them in an issue on this repository or in our Community Forum at 
https://community.granitedevices.com/
