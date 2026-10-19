# ONLYOFFICE Docs Community 10.0.0.169 – Lithuanian UI translation (lt.json)

**Modified by Panda Fix MB on 2026-10-17: added Lithuanian translation (lt.json) for ONLYOFFICE Docs Community 10.0.0.169. Based on ONLYOFFICE Docs by Ascensio System SIA. Licensed under AGPLv3 with additional terms.**

This repository contains the complete source of the modification that Panda Fix MB applies to ONLYOFFICE Docs Community Edition (Document Server) **10.0.0.169** as used in the ARKA service (https://debesis.pandafix.lt). It is offered to all users of that service free of charge, in accordance with Section 13 of the GNU AGPL v3.

This is **not** an official ONLYOFFICE product and is not endorsed by or affiliated with Ascensio System SIA.
ONLYOFFICE is a trademark of Ascensio System SIA.

## What was modified

Only three new files were added. No other ONLYOFFICE code or asset was changed:

| File (path inside `/var/www/onlyoffice/documentserver/`) | Editor | Keys |
|---|---|---|
| `web-apps/apps/documenteditor/main/locale/lt.json` | Document editor | 4505 |
| `web-apps/apps/spreadsheeteditor/main/locale/lt.json` | Spreadsheet editor | 5406 |
| `web-apps/apps/presentationeditor/main/locale/lt.json` | Presentation editor | 3797 |

- Source of the strings: `ONLYOFFICE/web-apps`, tag `v10.0.0.169`, `apps/<editor>/main/locale/en.json`.
- Each `lt.json` has exactly the same key set and key order as the corresponding `en.json`; all placeholders (`%1`, `{0}`, HTML tags, `\n`) are preserved.
- The files are valid for version 10.0.0.169 only.
- Upstream original: https://github.com/ONLYOFFICE/DocumentServer (tag `v10.0.0`) and https://github.com/ONLYOFFICE/web-apps.

## Installation (Docker)

```
docker cp web-apps/apps/documenteditor/main/locale/lt.json     <container>:/var/www/onlyoffice/documentserver/web-apps/apps/documenteditor/main/locale/lt.json
docker cp web-apps/apps/spreadsheeteditor/main/locale/lt.json  <container>:/var/www/onlyoffice/documentserver/web-apps/apps/spreadsheeteditor/main/locale/lt.json
docker cp web-apps/apps/presentationeditor/main/locale/lt.json <container>:/var/www/onlyoffice/documentserver/web-apps/apps/presentationeditor/main/locale/lt.json
```

Then open the editor with `editorConfig.lang = "lt"`. Checksums: `SHA256SUMS.txt`.

## License

Copyright (C) 2009-2026 Ascensio System SIA (original ONLYOFFICE software and `en.json` source strings).
Lithuanian translation (C) 2026 Panda Fix MB.

The translation is a derivative work of ONLYOFFICE web-apps and is distributed under the **GNU Affero General Public License v3 together with the additional terms** in [LICENSE](LICENSE) (the original ONLYOFFICE DocumentServer LICENSE, tag v10.0.0). Non-code elements are licensed under CC BY-SA 4.0 as stated in that file.
All copyright, license and attribution notices of the original ONLYOFFICE software are retained. Use of the ONLYOFFICE name and logo is governed by the ONLYOFFICE Trademark Policy: https://www.onlyoffice.com/trademark-policy

Contact: Panda Fix MB, Lithuania.

---

## Santrauka lietuviškai

Panda Fix MB 2026-10-17 pakeitė ONLYOFFICE Docs Community 10.0.0.169: pridėjo lietuvišką sąsajos vertimą (trys `lt.json` failai dokumentų, skaičiuoklių ir pateikčių rengyklėms). Kitas ONLYOFFICE kodas nekeistas. Paremta ONLYOFFICE Docs (Ascensio System SIA). Licencija – GNU AGPL v3 su papildomomis sąlygomis (žr. `LICENSE`). Šis šaltinis nemokamai prieinamas visiems ARKA (debesis.pandafix.lt) naudotojams pagal AGPL 13 str. Tai nėra oficialus ONLYOFFICE produktas. ONLYOFFICE is a trademark of Ascensio System SIA.
