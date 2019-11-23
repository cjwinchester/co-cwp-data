# Colorado Concealed Handgun Permit Data

_Updated Nov. 23, 2019_

This repo contains reports to the Colorado Legislature on concealed weapons permits issued by Colorado sheriffs from 2003-2017. (The reporting changed to concealed handgun permits in 2016.)

The original PDF reports are in `/reports`. CSV files with data extracted from the PDFs will be in `/data`. A combined file, `co-concealed-weapons-permits.csv`, will be in the root directory.

## Process

The PDF files were downloaded from [the website of the County Sheriffs of Colorado](https://coloradosheriffs.org/resources/chp-reports/). I've also got a [Klaxon](https://github.com/themarshallproject/klaxon) feed keeping an eye on changes so I can update when new reports are uploaded.

Except for the 2007 file, which was an image PDF I had to enter manually, I used [Tabula](http://tabula.technology/) to rip the tables out of the PDFs into a spreadsheet, where I manually cleaned, standardized and checked the data against the original reports.
