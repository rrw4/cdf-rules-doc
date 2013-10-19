pandoc: https://github.com/jgm/pandoc

Convert to rtf:
pandoc -f markdown-tex_math_dollars -t rtf -o output/rules.rtf --standalone rules.md
