Sublime Text Language French
============================

Add French spelling languages to your Sublime Text editor.

Based on the latest dicollecte Hunspell French dictionaries (as of 2013-12-30).

[http://www.dicollecte.org/home.php?prj=fr](http://www.dicollecte.org/home.php?prj=fr "dicollecte")

Languages variants included are the ones provided by the dicollecte Hunspell French dictionaries (fr_FR) :

  * Modern
  * Classical [default]
  * 1990 reform
  * All variants

Installation
------------

### Sublime Package Control

  1. Install the following package : "Language - French - Français"
  2. Choose the language (View > Dictionary > Language - French - Français > fr_FR)
  3. Be sure spelling is activated (F6 / View > Spell Check)
  4. You are done !

### Manual installation

  1. Locate Sublime Text Package folder (Preferences > Browse Packages)
  2. [Download me](https://nodeload.github.com/superbob/SublimeTextLanguageFrench/zip/master "Download manual package") and unzip my contents in this folder (Packages)
  3. Rename the folder in a more suitable name, ex: "Language - French - Français (manual)" (**warning:** there must not be any sub-folder in this folder, depending on your unzipping utility you might need to move files to the parent folder)
  4. Choose the language (View > Dictionary > Language - French - Français (manual) > fr_FR)
  5. Be sure spelling is activated (F6 / View > Spell Check)
  6. You are done !

Compatibility
-------------

Tested with [Sublime Text 3 (Build 3059)](http://www.sublimetext.com/3 "Sublime Text 3 (Build 3059)") (OS X and Linux 64 bit tarball) and [Package Control 2 for ST3](https://sublime.wbond.net/installation#st3 "Package Control 2 for ST3").

Even if I didn't test it, it should work with Sublime Text 2 (any platform) and older versions of Package Control.

License
-------

dicollecte Hunspell French dictionaries are licensed under the MPL 2.

Additional files provided here are licensed under the Simplified BSD "2-Clause" License.

Informations
------------

Last updated with "Hunspell 5.0.1 (2013-12-10)" as of 2013-12-30.

http://www.dicollecte.org/download/fr/hunspell-french-dictionaries-v5.0.1.zip

Q&A
---

**Q:** There is already a [Dictionaries package](https://github.com/SublimeText/Dictionaries "Dictionaries package") for Sublime Text, why another ?

**A:** Dictionaries is a really cool package, but it is big (29 dictionaries, 23 different languages), and all variants are not included for each language. I want to provide a package that has only one main language (fr_FR) with its technical variants. For information, [I also contribute to Dictionaries](https://github.com/SublimeText/Dictionaries/pull/15), to keep it up to date in concordance to this Package. Currently, the French dictionary version included in Dictionaries package is the same as the one provided here.

**Q:** Other languages ?

**A:** You are free to clone this repo, provide any language you wish and add your package to Sublime Package Control. If I'm not lazy enough, I might add one or two other languages, but not more.

**Q:** Can I contribute ?

**A:** If you want to add a newer version of the French dictionaries (fr_FR) you can submit a pull request. But I hope that I will be able to keep it up-to-date by myself.

**Q:** Why the fuck is all this not written in French ?!?

**A:** Even if I love the French language (my first language), I consider this page a little bit technical and I prefer to write technical stuff in English. Moreover I consider that people who want to add packages to Sublime Text are used to read English.

Credits
-------

[dicollecte](http://www.dicollecte.org/ "dicollecte")

[Sublime Text - Dictionaries package](https://github.com/SublimeText/Dictionaries "Sublime Text - Dictionaries package")

[wbond - Sublime Package Control](https://sublime.wbond.net/ "wbond - Sublime Package Control")
