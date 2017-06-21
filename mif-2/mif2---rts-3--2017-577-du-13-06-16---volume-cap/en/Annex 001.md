# ANNEX

## Table 1

Symbol table for Table 2

SYMBOL DATA TYPE DEFINITION {ALPHANUM-n} Up to n alphanumerical characters Free text field. {DECIMAL-n/m} Decimal number of up to n digits in total of which up to m digits can be fraction digits Numerical field for both positive and negative values. — decimal separator is ‘.’ (full stop); — the number may be prefixed with ‘–’ (minus) to indicate negative numbers. Where applicable, values shall be rounded and not truncated. {CURRENCYCODE_3} 3 alphanumerical characters 3 letter currency code, as defined by ISO 4217 currency codes {DATEFORMAT} ISO 8601 date format Dates should be formatted by the following format: YYYY-MM-DD. {ISIN} 12 alphanumerical characters ISIN code, as defined in ISO 6166 {MIC} 4 alphanumerical characters Market identifier as defined in ISO 10383



Table 2

Formats of the report for the purpose of the volume cap mechanism

Data field name Format Reporting period {DATEFORMAT}/{DATEFORMAT} where the first date is the beginning of the reporting period and the second date is the end of the reporting period. Reporting entity identification Where the reporting entity is a trading venue: {MIC} (segment MIC or, where appropriate, operational MIC) or {ALPHANUM-50} if the reporting entity is a CTP. Trading venue identifier {MIC} (segment MIC, where available, otherwise operational MIC). Instrument identifier {ISIN} Currency of the transactions {CURRENCYCODE_3} Total volume of trading (per currency) {DECIMAL-18/5} Total volume of trading under Reference Price waiver as defined under Article 4(1)(a) of MiFIR (per currency) {DECIMAL-18/5} Total volume of trading under Negotiated Transactions waiver as defined under Article 4(1)(b)(i) of MiFIR (per currency) {DECIMAL-18/5}

