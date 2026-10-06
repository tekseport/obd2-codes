# OBD-II Diagnostic Trouble Codes, generic SAE J2012 list

The generic OBD-II trouble code list as a plain file. 9,414 codes, each with the code, its standard description, the category and the warning lamp that lights.

## Files

- `obd2-codes.csv` (1.0 MB): comma separated, four columns, one row per code
- `obd2-codes.json` (1.6 MB): the same rows as JSON

## Columns

| Column | Meaning |
|---|---|
| `code` | the trouble code, for example P0420 |
| `description` | the short standard name |
| `category` | the system, for example Powertrain - Fuel/Air Metering |
| `severity` | the lamp that actually lights |

## Source and attribution

Code data from OBD Codes List, https://obdcodeslist.com/code-data.html

Every code also has a page with the meaning, the common causes and the order to check them, at https://obdcodeslist.com/

## License

Free to use, including commercially. One condition: keep the attribution line above somewhere in the product or the documentation, and link to the page rather than to the file, so people land on the current version.

## Notes

- This is the generic list, the codes that mean the same thing on every make (the SAE J2012 set). Manufacturer specific codes are on the per-make sites.
- Severity is the lamp that lights, one of: Check Engine Light, Body Warning Light, ABS Light, Chassis Warning Light, Airbag Light.
- Descriptions are the short standard name, not the full page text.
