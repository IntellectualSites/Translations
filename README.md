# Translations

This repository contains a read-only mirror of Crowdin translations for our projects:

- [FastAsyncWorldEdit](https://github.com/intellectualSites/FastAsyncWorldEdit)
- [PlotSquared](https://github.com/intellectualSites/PlotSquared)
- [FastAsyncVoxelSniper](https://github.com/intellectualSites/FastAsyncVoxelSniper)

New translations are queried automatically on a weekly basis.

If you want to contribute to the translations, please do so at [Crowdin](https://intellectualsites.crowdin.com/).
For issues with the source file (English translation file), please report and/or fix those via the matching project
repository.


> [!NOTE]
> <b>Why does my language only / primarily contain English messages?</b>
> <p>
> This can have two reasons: Either, there are simply not many strings translated - or the translated strings haven't been reviewed / approved yet.<br>
> For the latter, this project contains a <a href="https://github.com/IntellectualSites/Translations/tree/not-reviewed">second branch with all translations</a> (approved translations are prioritized, then translations with the most upvotes). 
> As a result, some translations might be of low quality.
> </p>

### Installation

The "installation" of the translation(s) depend on the project:

- **FastAsyncWorldEdit / FastAsyncVoxelSniper**: replace the `lang/strings.json` with content of the translated file (keep
  the filename as is)
- **PlotSquared**: place the translated file alongside the pre-existing `lang/messages_en.json`. Change the value of the
  `default-locale` setting in settings.yml to use the new file.