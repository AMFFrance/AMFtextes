# ANNEX II

## Format for daily Reports

Table 1

Symbol table for Table 2

SYMBOL DATA TYPE DEFINITION {ALPHANUM-n} Up to n alphanumerical characters Free text field. {DECIMAL-n/m} Decimal number of up to n digits in total of which up to m digits can be fraction digits Numerical field for both positive and negative values: — decimal separator is ‘.’ (full stop), — negative numbers are prefixed with ‘–’ (minus). Where applicable, values are rounded and not truncated. {DATEFORMAT} ISO 8601 date format Dates shall be formatted in the following format: YYYY-MM-DD. {DATE_TIME_FORMAT} ISO 8601 date and time format — Date and time in the following format: YYYY-MM-DDThh:mm:ss.ddddddZ. — ‘YYYY’ is the year, — ‘MM’ is the month, — ‘DD’ is the day, — ‘T’ — means that the letter ‘T’ shall be used, — ‘hh’ is the hour, — ‘mm’ is the minute, — ‘ss.dddddd’ is the second and its fraction of a second, — Z is UTC time. Dates and times shall be reported in UTC. {ISIN} 12 alphanumerical characters ISIN code, as defined in ISO 6166 {LEI} 20 alphanumerical characters Legal entity identifier as defined in ISO 17442 {MIC} 4 alphanumerical characters Market identifier as defined in ISO 10383 {NATIONAL_ID} 35 alphanumerical characters The ID is that set out in Article 6 of the Commission Delegated Regulation (EU) 2017/590 (1) on transaction reporting obligations under Article 26 of Regulation (EU) No 600/2014 of the European Parliament and of the Council (2) and Annex II to that Regulation. {INTEGER-n} Integer number of up to n digits in total Numerical field for both positive and negative integer values.



Table 2

Tables of fields to be reported for all positions across all maturities of all contracts for the purposes of Article 2

FIELD DETAILS TO BE REPORTED FORMAT FOR REPORTING Date and time of report submission Field to be populated with the date and time on which the report is submitted. {DATE_TIME_FORMAT} Report reference number Field to be populated with the unique identifier given by the submitter unambiguously identifying the report to both submitter and receiving competent authority. {ALPHANUM-52} Date of the trading day of the reported position Field to be populated with the date on which the reported position is held at the close of the trading day on the relevant trading venue. {DATEFORMAT} Report status Indication as to whether the report is new or a previously submitted report is cancelled or amended. Where a previously submitted report is cancelled or amended, a report which contains all the details of the original report and using the original Report Reference Number should be sent and the ‘Report status’ should be flagged as ‘CANC’. For amendments a new report that contains all the details of the original report and using the original Report Reference Number with all necessary details amended should be sent and the ‘Report status’ should be flagged as ‘AMND’. ‘NEWT’— New ‘CANC’— Cancellation ‘AMND’— Amendment Reporting entity ID The identifier of the reporting investment firm. Field to be populated with the Legal Entity Identifier code (LEI) for legal entities or {NATIONAL_ID} for natural persons not having an LEI. {LEI} or {NATIONAL_ID} — Natural persons Position holder ID Field to be populated with the Legal Entity Identifier code (LEI) for legal entities or {NATIONAL_ID} for natural persons not having an LEI. (Note: if the position is held as a proprietary position of the reporting firm, this field shall be identical to field ‘Reporting entity ID’). {LEI} or {NATIONAL_ID} — Natural persons Email address of position holder Email address for notifications of position-related matters. {ALPHANUM-256} Ultimate parent entity ID Field to be populated with the Legal Entity Identifier code (LEI) for legal entities or {NATIONAL_ID} for natural persons not having an LEI. Note: this field may be identical to field ‘Reporting entity ID’ or ‘Position holder ID’ if the ultimate parent entity holds its own positions, or makes its own reports. {LEI} or {NATIONAL_ID} — Natural persons Email address of ultimate parent entity Email address for correspondence in relation to aggregated positions. {ALPHANUM-256} Parent of collective investment scheme status Field to report on whether the position holder is a collective investment undertaking that makes investment decisions independently from its parent as set out by Article 4(2) of the Commission Delegated Regulation (EU) 2017/591 (3). ‘TRUE’— the position holder is a collective investment undertaking that makes independent investment decisions ‘FALSE’— the position holder is not a collective investment undertaking that makes independent investment decisions Identification code of contract traded on trading venues Identifier of the commodity derivative, emission allowance or derivative thereof. See field ‘Trading venue identifier’ for treatment of OTC contracts that are economically equivalent to contracts that are traded on trading venues. {ISIN} Venue product code Field to be populated with a unique and unambiguous alphanumeric identifier utilised by the trading venue grouping together contracts with different maturities and strike prices in the same product. {ALPHANUM-12} Trading venue identifier Field to be populated with the ISO 10383 segment MIC for positions reported in respect of on-venue contracts. Where the segment MIC does not exist, use the operating MIC. Use MIC code ‘XXXX’ for off-venue positions in economically equivalent OTC contracts. Use MIC code ‘XOFF’ for listed derivatives or emission allowances traded off-exchange. {MIC} Position type Field to report whether the position is in either futures, options, emission allowances or derivatives thereof, commodity derivatives defined under point (c) of Article 4(1)(44) of Directive 2014/65/EU of the European Parliament and of the Council (4) or any other contract type. ‘OPTN’— Options, including separately tradable options on FUTR, SDRV or OTHR types, excluding products where the optionality is only an embedded element ‘FUTR’— Futures ‘EMIS’— Emission allowances and derivatives thereof ‘SDRV’— Commodity derivatives defined under point (c) of Article 4(1)(44) of Directive 2014/65/EU ‘OTHR’— any other contract type Position maturity Indication of whether the maturity of the contract comprising the reported position relates to the spot month or to all other months. Note: separate reports are required for spot months and all other months. ‘SPOT’— spot month, including all positions in position types EMIS and SRDV ‘OTHR’— all other months Position quantity Field to be populated with the net position quantity held in the commodity derivative, emission allowances or derivatives thereof expressed either in lots, when the position limits are expressed in lots, or units of the underlying. This field should be populated with a positive number for long positions and a negative number for short positions. If the position is in commodity derivatives defined under point (c) of Article 4(1)(44) of Directive 2014/65/EU this field shall be populated with the number of units held. {DECIMAL-15/2} Notation of the position quantity This field shall be populated with the units used to report the position quantity. ‘LOTS’— if the position quantity is expressed in lots {ALPHANUM-25}— a description of the units used if the position quantity is expressed in units of the underlying ‘UNIT’— if the position quantity is expressed in units Delta equivalent position quantity If the Position Type is ‘OPTN’ or an option on ‘EMIS’, then this field shall contain the delta-equivalent quantity of the position reported in the ‘Position Quantity’ field. This field should be populated with a positive number for long calls and short puts and a negative number for long puts and short calls. {DECIMAL-15/2} Indicator of whether the position is risk reducing in relation to commercial activity Field to report whether the position is risk reducing in accordance with Article 7 of Delegated Regulation (EU) 2017/591. ‘TRUE’— the position is risk reducing ‘FALSE’— the position is not risk reducing



(1)  Commission Delegated Regulation (EU) 2017/590 of 28 July 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council with regard to regulatory technical standards for the reporting of transactions to competent authorities (OJ L 87, 31.3.2017, p. 449).

(2)  Regulation (EU) No 600/2014 of the European Parliament and of the Council of 15 May 2014 on markets in financial instruments and amending Regulation (EU) No 648/2012 (OJ L 173, 12.6.2014, p. 84).

(3)  Commission Delegated Regulation (EU) 2017/591 of 1 December 2016 supplementing Directive 2014/65/EU of the European Parliament and of the Council with regard to regulatory technical standards for the application of position limits to commodity derivatives (OJ L 87, 31.3.2017, p. 479).

(4)  Directive 2014/65/EU of the European Parliament and of the Council of 15 May 2014 on markets in financial instruments and amending Directive 2002/92/EC and Directive 2011/61/EU (OJ L 173, 12.6.2014, p. 349).
