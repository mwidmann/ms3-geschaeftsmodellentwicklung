# latexTemplate
Master Digital Transformation - Latex Template

# Latex Commands

A collection of useful LaTeX commands for quick reference.

## Useful LaTeX Commands

| Command | Description |
|---------|-------------|
| `\emph{...}` | Emphasized text (italic by default) |
| `\enquote{...}` | Quoted text, requires \usepackage{csquotes} |
| `\textbf{...}` | Bold text |
| `\textit{...}` | Italic text |
| `\euro` | Euro symbol (€), requires \usepackage{eurosym} |
| `{\textendash}` or `--` | En dash (–), width from an n |
| `{\textemdash}` or `---` | Em dash (–), width from an m |

## Additional Commands

| Command | Description |
|---------|-------------|
| `\underline{...}` | Underlined text |
| `\texttt{...}` | Monospaced / code font |
| `\ldots` / `\dots` | Ellipsis (...) |
| `\textsuperscript{...}` | Superscript |

## Citation Commands (biblatex)

| Command | Output |
|---------|--------|
| `\textcite{john_doe_2025}` | Doe (2025) |
| `\textcite[2]{john_doe_2025}` | Doe (2025, S.2) or: p.2 depending on language settings |
| `\pagecite[20]{john_doe_2025}` | (p.20) |
| `\parencite{jane_doe_2025}` | (Doe, 2025) |
| `\parencite[2]{jane_doe_2025}` | (Doe, 2025, S.2) or: p. 2 depending on language settings |
| `\citeauthor{john_doe_2025}` | Doe |

## Acronym Commands

| Command | Description |
|---------|-------------|
| `\ac{...}` | First occurrence: Full form (abbreviation), subsequent: abbreviation only |
| `\acf{...}` | Always full form (abbreviation) |
| `\acs{...}` | Abbreviation only |
| `\acl{...}` | Full form only |
| `\acp{...}` | Plural form, first occurrence: Full form (abbreviation), subsequent: abbreviation only |
| `\acfp{...}` | Plural form, always full form (abbreviation) |
| `\acsp{...}` | Plural form, abbreviation only |
| `\aclp{...}` | Plural form, full form only |