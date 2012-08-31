en.xml contains explanations of the format, and should be the base you start from.
MASGAU automatically loads up to three langauge files:
1. en.xml to ensure there are always strings
2. If found, an xml file that is named the two-letter language code your system provides (such as fr.xml of ne.xml)
3. If found, an xml file named the language code from above, a dash, then the country code your system provides (such as en-US.xml or fr-FR.xml)

If you provide MASGAU with the command-line arg "-language_file file.xml", it will load ONLY that file.
This can make it a lot easier to see which strings still need provided.