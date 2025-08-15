# Style

Cross-language style rules that apply to all content regardless of target language. These complement the language-specific style files and technical formatting rules.

## Languages

Each language has specific authority sources listed following this general hierarchy:

1. **Official language academy** - Primary orthographic and grammatical authority
2. **Standard dictionary** - Lexicographic authority  
3. **Style guides** - Professional writing conventions
4. **Typography standards** - Punctuation and formatting rules

### English

- Target variant: American English
- [Merriam-Webster Dictionary](https://www.merriam-webster.com)
- Garner's Modern English Usage, by Bryan A. Garner
- The Elements of Typographic Style, by Robert Bringhurst
- Chicago Manual of Style (for publishing conventions)
- AP Stylebook (for news and web writing)

### Spanish

- Target variant: _español peninsular_ (_castellano_)
- [Diccionario de la lengua española](https://dle.rae.es)
- [Diccionario panhispánico de dudas](https://www.rae.es/dpd/)
- [Gramática de la lengua española](https://www.rae.es/gramatica)
- [Ortografía de la lengua española](https://www.rae.es/ortografia)

### Catalan

- Target variant: _català central_
- [Diccionari de la llengua catalana](https://www.diccionari.cat/)
- [Gramàtica de la llengua catalana](https://giec.iec.cat/inici)
- [Ortografia catalana](https://oiec.iec.cat/inici)

## Capitalization

### On titles and headings

- Always use sentence case for titles, headings, and subheadings in all languages.
- Maintain proper noun capitalization within sentence case titles.
- **Never use title case**, even for major headings or formal documents.
- **Always capitalize** the first word after a colon in headings: "Step 1: Identify the problem"

### On UI elements

- Capitalize UI elements as they appear in the interface.

## Punctuation

### Commas

- In English, use the serial comma (Oxford comma) before the final "and" or "or" in lists.
- In Spanish and Catalan it is incorrect to use the serial comma.

### Em dashes

- Use em dashes with spaces for parenthetical statements.
- Example: "The new feature — released in Summer '24 — improves performance significantly."

### Ellipses

- Use ellipses (…) without spaces when at word end: "word..."
- Use ellipses (…) with spaces when between words: "word ... word"

### Quotation marks

- Use language-appropriate quotation marks:

  - In English: double quotes for primary quotations (" "), single quotes for nested quotations.
    - She said, "The error message was 'Invalid credentials' exactly."
  - In Spanish and Catalan: angular quotes (« ») for primary quotations, double quotes (" ") for nested quotations. Place punctuation inside quotation marks when it's part of the quoted material.
    - Dijo: «El mensaje de error era "Invalid credentials" exactamente».
    - Va dir: «El missatge d'error era "Invalid credentials" exactament».

## List formatting

### Parallel structure

- Maintain consistent grammatical structure across list items.

### Capitalization in lists

- Use sentence case for list items, with periods only if items are complete sentences.

## Numbers, dates and measurements

### Number rules

- Spell out numbers one through nine, use numerals for 10 and above.
- Exceptions:
  - Ages: "a 5-year-old system"
  - Percentages: "un incremento del 5 por ciento"  
  - Technical specifications: "3GB de memòria"

### Date formats

- **Short dates**: Always use ISO format YYYY-MM-DD
- **Long dates** by language:
  - **English**: Month Day, Year (December 15, 2024)
  - **Spanish**: Day de Month de Year (15 de diciembre de 2024)
  - **Catalan**: Day de Month de Year (15 de desembre de 2024)

### Time format

- Always use 24-hour format: "14:30"

### Numerical values

- Use numerals for all measurements.
- Use points for [decimal values](https://en.wikipedia.org/wiki/Decimal_separator): "3.14", "0.99"
  - [ISO 31-0](https://www.iso.org/standard/26120.html) and its successors recommend using either points or commas.
  - RAE [splits that recommendation between countries](https://www.rae.es/ortografía/los-números-decimales-y-el-separador-decimal). Spain uses commas, whereas Mesoamerica and the US use points.
  - We use points to maintain a single criterion.
- Use only spaces for thousands separators: "1 000", "10 000 000"
  - Thousands separators are optional, and they can only be used when the number expresses a value or a quantity (e.g. the population of a city).
  - They must not be used when the number designates an element within a sequence (e.g. years, pages, postal codes, identifiers).
  - This guidance follows RAE's [_Ortografía de la lengua española_](https://www.rae.es/ortografía/los-números-enteros-y-el-separador-de-millares) position on thousands separators.
  - If possible use non-breaking spaces to avoid breaking numbers across lines.
- Round appropriately for the audience and context.

### Units

- Separate numbers and units with a space, which should be non-breaking: "100 ms", "2 GB"
- Use consistent units within the same context and specify them clearly.
- Use standard abbreviations for units.
- Use only the International System of Units at all times.
- For memory units, use standard abbreviations (KB, MB, GB, TB) and only use binary prefixes (KiB, MiB, GiB, TiB) when necessary to clarify the context.

## Grammar

### Voice preference

- Prefer active voice over passive voice when possible.
- "The system generates the report" is preferable to "The report is generated by the system".

### Formality

- For languages with habitual formal/informal distinction in second person (Spanish, Catalan), use informal address ("tú", "tu") to maintain professional closeness.
- In English, contractions may be acceptable in conversational content and opinion pieces only.

### Inclusive language

- In English, use singular "they" for unknown gender references.
- In languages where nouns are explicitly gendered (Spanish, Catalan), use inclusive language naturally, always avoiding forced constructions. Being inclusive is an opportunity to make prose more refreshing, and should never be a burden that reduces text readability. When in doubt, it is appropriate to revert to masculine generic forms.
- For example: "desarrollador(es)" is better than "persona(s) desarroladora(s)", but "equipo de desarrollo" may be an alternative that works well according to context.

### Foreign words and borrowings

- Avoid unnecessary foreign terms when clear equivalents exist in the target language.
- Foreign words not included in the standard dictionary of the target language should be indicated in italics. If included in the dictionary, write them in the format indicated.

## Code

- Maintain target language grammar when discussing code concepts.
- Method, class, and variable names will be in English, but comments and explanations should be in the target language. Do not assume the reader knows the English meaning of the names.

### Inline code

- Use monospace formatting for exact code references: `getAttribute()`, `console.log()`, `npm install`
- Use regular text for conceptual discussion, but preserve monospace formatting to explicit references to a part of the text:
  - "logging to console", as a reference to `console.log()` in JavaScript
  - "the `getAttribute` method"
  - "package installation"

### Code blocks

- Always use syntax highlighting when the platform supports it.
- Preserve exact capitalization and spacing as required by the language or platform.
- Use meaningful variable names in examples, not abbreviations or nondescriptive placeholders.

### Code comments

- Include comments in code examples only when they add clarity.
- Write comments in the same language as the surrounding prose.

### Command line

- Use `$` to indicate shell prompt: `$ git commit -m "Update documentation"`
- Use monospace for all commands, flags, and arguments: `git commit`, `-v` flag, `--verbose` option
- Do not include the prompt when showing command output.

### File and directory paths

- Use monospace for all file system references: `/src/components/`, `package.json`, `README.md`
- Include trailing slash for directories: `/api/v1/`
- Use forward slashes regardless of operating system context.
- Use relative paths when possible for clarity: `./components/Header.js` rather than `/full/absolute/path/`

## Version numbering

### Software versions

- Use lowercase 'v' prefix in code: `v2.1.3`, `v1.0.0-beta`
- Use full words and regular case in text: "version 2.1", "release 3.0"

### Release terminology

- Use sentence case: "beta release", "release candidate", "general availability"
- In non-English languages, introduce first the local term, then use the English equivalent if it is different.
- Common abbreviations like RC (release candidate) or GA (general availability) are acceptable, but weigh their use against the audience's familiarity.

## URLs and links

### Link formatting

- In prose, make links descriptive: "Salesforce REST API documentation"
- Avoid referencing the link directly (like "click [here](#)" or "[this link](#)") if there is a natural way to present the link in context.
- When showing literal URLs, use monospace: `https://developer.salesforce.com`

### URL structure references

- Use monospace for URL patterns: `/api/v1/users/{id}`, `*.example.com`
- Use curly braces for variables: `{userId}`, `{apiVersion}`

## Technical abbreviations

### Pluralization

- Add 's' to form plurals of abbreviations: APIs, URLs, SDKs
- In English only, use apostrophes for Saxon genitive (possessive) forms: "the API's documentation". This is not used in Spanish or Catalan.

### First use convention

- Spell out abbreviations on first use: "Application Programming Interface (API)"
- Exception: Terms universally known to target audience (HTML, URL, HTTP)
- Use the abbreviation freely after first introduction.
- Do not introduce the abbreviation if the term is only used once in the text.
- Titles should not be considered for the purposes of this rule: Do not introduce abbreviations in titles or headings, and do not count titles as subsequent uses.

## System output

### Exact quotations

- Use monospace for exact system text: `REQUIRED_FIELD_MISSING`, `404 Not Found`
- Use regular text for paraphrased explanations: "The system indicates a required field is missing"
- Preserve exact capitalization and spacing in system messages.

### Status codes and identifiers

- Use monospace for technical identifiers: HTTP `200`, record ID `003xx0000004TmiAAE`
- Use regular text when discussing concepts: "HTTP success status", "record identifier"
- Differentiate between logical entities and attributes in a data model ("Accounts and their names") and their physical expression ("`Account` records", "`Name` field").