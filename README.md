# Colorado Concealed Handgun Permit Data

_Updated Dec. 28, 2019_

This repo contains data submitted to the Colorado Legislature on concealed weapon permits issued, denied or revoked by Colorado sheriffs from 2003-2017. (The reporting changed to concealed handgun permits in 2016.)

The original PDF reports are in `/reports`. A combined CSV file with data extracted from the PDFs, [`co-concealed-weapons-permits.csv`](co-concealed-weapons-permits.csv), is in the root directory -- each row is one year of permitting data for one county.

### Process
The PDF reports were downloaded from [the website of the County Sheriffs of Colorado](https://coloradosheriffs.org/resources/chp-reports/). I've also got a [Klaxon](https://github.com/themarshallproject/klaxon) feed keeping an eye on changes so I can update the data when new reports are uploaded.

Except for the 2007 file -- an image PDF that I had to key in manually -- I used [Tabula](http://tabula.technology/) to rip the tables into a spreadsheet, where I cleaned, standardized and hand-checked the data against the original reports.

### Known issues/notes
- Do ` `, `-` and `0` entries mean different things? `¯\_(ツ)_/¯` I have a note into the sheriff's association for clarification and will update when/if they get back to me.
- Conejos County did not submit a report in 2004 or 2005. (It looks like it didn't submit a report in 2003, either, but this wasn't reflected in the notes -- checking on this, too.)
- The data doesn't include a breakdown of new permit applications vs. permit renewals until 2012.
