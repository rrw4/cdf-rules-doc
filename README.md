Chicago Dynasty Football rules document

Uses pandoc (https://github.com/jgm/pandoc) to convert rules document in markdown to RTF.  Allows us to see text diffs of rules updates between versions and still have a document in RTF.

Convert rules.md to rules.rtf:

`` pandoc -f markdown-tex_math_dollars -t rtf -o output/rules.rtf --standalone rules.md ``
