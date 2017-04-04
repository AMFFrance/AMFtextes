# ANNEX

## Data to be provided for the purpose of determining a liquid market for shares, depositary receipts, exchange-traded funds and certificates

Table 1

Symbol table

Symbol Data Type Definition {ALPHANUM-n} Up to n alphanumerical characters Free text field. {ISIN} 12 alphanumerical characters ISIN code, as defined in ISO 6166 {MIC} 4 alphanumerical characters Market identifier as defined in ISO 10383 {DATEFORMAT} ISO 8601 date format Dates should be formatted by the following format: YYYY-MM-DD. {DECIMAL-n/m} Decimal number of up to n digits in total of which up to m digits can be fraction digits Numerical field for both positive and negative values. — decimal separator is ‘.’ (full stop); — negative numbers are prefixed with ‘–’ (minus); — values are rounded and not truncated.



Table 2

Details of the data to be provided for the purpose of determining a liquid market for shares, depositary receipts, exchange-traded funds and certificates

# Field Details to be reported Format and standards for reporting 1 Instrument identification code Code used to identify the financial instrument {ISIN} 2 Instrument full name Full name of the financial instrument {ALPHANUM-350} 3 Trading venue Segment MIC for the trading venue, where available, otherwise operational MIC. {MIC} 4 MiFIR identifier Identification of equity financial instruments   Shares as referred to in Article 4(1)(44)(a) of Directive 2014/65/EU;   Depositary receipts as defined in Article 4(1)(45) of Directive 2014/65/EU;   Exchange-traded fund as defined in Article 4(1)(46) of Directive 2014/65/EU;   Certificates as defined in Article 2(1)(27) of Regulation (EU) No 600/2014; Equity financial instruments:   ‘SHRS’ = shares   ‘ETFS’= ETFs   ‘DPRS’ = depositary receipts   ‘CRFT’ = certificates 5 Reporting day Date for which the data is provided Data has to be provided at least for the following dates: — case 1: the day corresponding to the ‘Date of admission to trading or first trading date’ as per Article 5(3)(a); — case 2: the last day of the 4 weeks period starting on the ‘Date of admission to trading or first trading date’ as per Article 5(3)(b)(i); — case 3: the last trading day of each calendar year as per Article 5(3)(b)(ii); — case 4: the day on which a corporate action is effective as per Article 5(3)(b)(iii). For case 1, estimates are to be provided for the fields 6 to 12 as applicable. {DATEFORMAT} 6 Number of outstanding instruments For shares and depositary receipts The total number of outstanding instruments. For ETFs Number of units issued for trading. {DECIMAL-18/5} 7 Holdings exceeding 5 % of total voting rights For shares only The total number of shares corresponding to holdings exceeding 5 % of total voting rights of the issuer unless such a holding is held by a collective investment undertaking or a pension fund. This field is to be populated only when actual information is available. {DECIMAL-18/5} 8 Price of the instrument For shares and depositary receipts only The price of the instrument at the end of the reporting day. The price should be expressed in euros. {DECIMAL-18//13} 9 Issuance size For certificates only The issuance size of the certificate expressed in euros. {DECIMAL-18/5} 10 Number of trading days in the period The total number of trading days for which the data is provided {DECIMAL-18/5} 11 Total turnover The total turnover for the period {DECIMAL-18/5} 12 Total number of transactions The total number of transactions for the period {DECIMAL-18/5}

