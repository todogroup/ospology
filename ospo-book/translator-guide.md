# Translator's Guide

Guidance on how to contribute translations to the OSPO Book project.

## Understand the i18n Structure

The OSPO Book project utilizes an internationalization (i18n) system to support multiple languages.

### Locale Code Format (BCP 47):

The standard format for locale codes used in many i18n systems (including the one you're likely using) is defined by BCP 47. The most common format is: `<language-code>-<country-code>`
 - `<language-code>`: Two-letter lowercase [ISO 639-1 code](https://localizely.com/iso-639-1-list/) (mandatory).
 - `-`: Separator hyphen.
 - `<country-code>`: Two-letter uppercase [ISO 3166-1 alpha-2 code](https://localizely.com/iso-3166-1-alpha-2-list/) (optional, but often used for regional variations).

**Remember:** Not all languages will have a country code identifier.

### Language Configuration Files

Translations are managed through dedicated language configuration files:
 - `config.toml`
 - `i18n/[locale-code].toml`

The translation files are located within a dedicated directory in the project structure. For the OSPO Book, you'll create the translation files within the `content` directory.
 - `content/[language-code]/`

## Translate Content

 - Add the new language setting to the `config.toml` file, adjusting the `[languages]` section.
 - Create a new configuration file `i18n/[locale-code].toml` (suggestion: make a copy of the `i18n/en.toml` configuration file and translate the content)
 - Create a new directory `content/[language-code]/` that will contain the contents of the book that will be displayed when selecting the respective language. Each file must be translated following the same pattern.

**Key Considerations During Translation:**

 - **Context is Crucial:** Understand the context of each phrase or word within the website. A single English word can have multiple translations depending on how it's used.
 - **Maintain Consistency:** Ensure consistency in your terminology throughout the translation. If you translate a term one way, stick with that translation across all files.
 - **Use Natural Language:** Aim for translations that sound natural and idiomatic. Avoid overly literal translations that might sound awkward.
 - **Respect Formatting:** Pay attention to any formatting within the original English text (e.g. bold, italics). Preserve this formatting in your translations where appropriate.
 - **Handle Placeholders:** Some strings might contain placeholders (e.g., `%s`, `{}`). Ensure these placeholders are correctly placed and handled in your translations.
