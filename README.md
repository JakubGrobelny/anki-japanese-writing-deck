# AnkiWeb

Also see on AnkiWeb: https://ankiweb.net/shared/info/2132288273

# What is this?

This is an Anki deck for Japanese writing practice that allows you to practice drawing the characters.
It contains hiragana, katakana and 2136 Jōyō Kanji. For every character the meaning and sample vocabulary are shown.

# How to Import This Deck into Anki

This deck uses the CrowdAnki format, which stores everything in clean JSON files for better version
control and transparency. To import it into Anki.

To use this deck:
1. Download the repository
2. Install the [CrowdAnki](https://github.com/Stvad/CrowdAnki) add-on
3. Restart Anki
4. File -> CrowdAnki: Import from disk
5. Choose the folder containing the json file

# How does this work?

This uses an external website with excellent Japanese writing exercises - [kakimashou.com](kakimashou.com).

Each note only contains only the character. Script on the card generates an URL of a quiz on kakimashou for that character, then loads it in an `<iframe>` element.

This effectively turns Anki into a custom kanji/kana learning app (as long as the website stays up, if it ever disappears we are cooked).

Internet connection is required for it to work.

