# EhPanda Japanese Tag Database

> [!IMPORTANT]
> This database has moved to [ehpanda-tag-database](https://github.com/EhPanda-Team/ehpanda-tag-database),
> which publishes every language from one repository.
> Releases here stay available for EhPanda versions before 3.0.
> The database is the `db.raw.json` asset of the latest release.

Provides Japanese tag translations and a searchable tag index for EhPanda.
Tags without a Japanese translation retain their original keys so the app can display the English names.

## Sources and Licenses

The tag inventory is derived from EhTagTranslation/Database:
https://github.com/EhTagTranslation/Database

The upstream data is licensed under Creative Commons Attribution-NonCommercial-ShareAlike
3.0 China Mainland. The original license text is preserved in sources/upstream-LICENSE.md.
Source URLs and SHA-256 hashes are recorded in sources/manifest.json.

Japanese attribute translations are sourced from e-hentaidb.com under
Creative Commons Attribution 4.0 International:
https://e-hentaidb.com/tag/
https://creativecommons.org/licenses/by/4.0/

Existing Japanese translations are distributed under CC BY 4.0 and also credit
the E(x)Hentai Japanese tag userscript by Nu (script 391216):
https://sleazyfork.org/scripts/391216
No additional userscript content is imported by this updater.

Modifications preserve baseline translations and metadata, apply exact-key
attribute translations, and add missing tag keys with empty translation fields.
Unmodified source snapshots and original license texts retain their source languages.
These notices do not relicense upstream material.
