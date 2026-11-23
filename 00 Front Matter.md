# About this document

This library collects a set of threat hunting notes and detection queries for Spectra Analyze and Intelligence Advanced Search. 


# Conventions

- Shaded monospaced blocks are Analyze queries. Text in angle brackets, such as <sha1> or <domain>, is a placeholder to be replaced.
- A query is limited to 1024 characters.
- Operators AND, OR, and NOT are case-insensitive. AND is the default between terms.
- Date modifiers are written from the point of view of age. firstseen:7d- means seen within the last seven days, and 10d+ means ten days old or more.
- References in quotation marks, such as "Command and Control and Beaconing" (section 6.1), point to another section of this document.
