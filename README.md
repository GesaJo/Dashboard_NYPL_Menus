# Dashboard_NYPL_Menus

A peek into the New York Public Libraries Collection "What's on the Menu?"

Link to dashboard [here.](http://3.120.225.151/public/dashboard/b0c08b2a-a627-41ab-95a8-baf31a340b27) (Not deployed right now)

Data from the [New York Public Library Project](http://menus.nypl.org/data), from the 16th of March 2020.

This project has been developed in week 6 of the Spiced-Bootcamp.

## Drawbacks of the dataset:
- very messy data due to digitalisation by volunteers (text & numeric values both, e.g. prices , dates)
- transcription-guidelines try to balance historic accuracy and practicability (e.g. preservation of typos, abbreviations etc.)
- not representative due to origin of menus (many upscale restaurants/hotels)
- imbalance: strong focus on years around 1900
- many features with majority of values being null

# Tools used:
Metabase,
Postgres,
AWS RDS, EC2
