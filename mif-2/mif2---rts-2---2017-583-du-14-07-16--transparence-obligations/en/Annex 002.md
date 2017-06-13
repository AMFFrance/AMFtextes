# ANNEX II

## Details of transactions to be made available to the public

Table 1

Symbol table for Table 2

SYMBOL DATA TYPE DEFINITION {ALPHANUM-n} Up to n alphanumerical characters Free text field. {CURRENCYCODE_3} 3 alphanumerical characters 3 letter currency code, as defined by ISO 4217 currency codes {DATE_TIME_FORMAT} ISO 8601 date and time format Date and time in the following format: YYYY-MM-DDThh:mm:ss.ddddddZ. Where: — ‘YYYY’ is the year; — ‘MM’ is the month; — ‘DD’ is the day; — ‘T’ — means that the letter ‘T’ shall be used — ‘hh’ is the hour; — ‘mm’ is the minute; — ‘ss.dddddd’ is the second and its fraction of a second; — Z is UTC time. Dates and times shall be reported in UTC. {DECIMAL-n/m} Decimal number of up to n digits in total of which up to m digits can be fraction digits Numerical field for both positive and negative values: — decimal separator is ‘.’ (full stop); — negative numbers are prefixed with ‘-’ (minus). Where applicable, values shall be rounded and not truncated. {ISIN} 12 alphanumerical characters ISIN code, as defined in ISO 6166 {MIC} 4 alphanumerical characters Market identifier as defined in ISO 10383



Table 2

List of details for the purpose of post-trade transparency

Details Financial instruments Description/Details to be published Type of execution/publication venue Format to be populated as defined in Table 1 Trading date and time For all financial instruments Date and time when the transaction was executed. For transactions executed on a trading venue, the level of granularity shall be in accordance with the requirements set out in Article 3 of Commission Delegated Regulation (EU) 2017/574 (1). For transactions not executed on a trading venue, the date and time shall be when the parties agree the content of the following fields: quantity, price, currencies (in fields 31, 34 and 40 as specified in Table 2 of Annex I of Delegated Regulation (EU) 2017/590, instrument identification code, instrument classification and underlying instrument code, where applicable. For transactions not executed on a trading venue the time reported shall be granular to at least the nearest second. Where the transaction results from an order transmitted by the executing firm on behalf of a client to a third party where the conditions for transmission set out in Article 5 of Delegated Regulation (EU) 2017/590 were not satisfied, this shall be the date and time of the transaction rather than the time of the order transmission. Regulated Market (RM), Multilateral Trading Facility (MTF), Organised Trading Facility (OTF) Approved Publication Arrangement (APA) Consolidated tape provider (CTP) {DATE_TIME_FORMAT} Instrument identification code type For all financial instruments Code type used to identify the financial instrument RM, MTF, OTF APA CTP ‘ISIN’ = ISIN-code, where ISIN is available ‘OTHR’ = other identifier Instrument identification code For all financial instruments Code used to identify the financial instrument RM, MTF, OTF APA CTP {ISIN} Where Instrument identification code is not an ISIN, an identifier that identifies the derivative instrument based on the fields 3 to 5, 7 and 8 and 12 to 42 as specified in Annex IV and fields 13 and 24 to 48 as specified in the Annex of Delegated Regulation (EU) 2017/585 and the grouping of derivative instruments as set out in Annex III. Price For all financial instruments Traded price of the transaction excluding, where applicable, commission and accrued interest. In the case of option contracts, it shall be the premium of the derivative contract per underlying or index point. In the case of spread bets it shall be the reference price of the underlying instrument. For credit default swaps (CDS) it shall be the coupon in basis points. Where price is reported in monetary terms, it shall be provided in the major currency unit. Where price is currently not available but pending, the value should be ‘PNDG’. Where price is not applicable the field shall not be populated. The information reported in this field shall be consistent with the value provided in field Quantity. RM, MTF, OTF APA CTP {DECIMAL-18/13} in case the price is expressed as monetary value {DECIMAL-11/10} in case the price is expressed as percentage or yield ‘PNDG’ in case the price is not available {DECIMAL-18/17} in case the price is expressed as basis points Venue of execution For all financial instruments Identification of the venue where the transaction was executed. Use the ISO 10383 segment MIC for transactions executed on a trading venue. Where the segment MIC does not exist, use the operating MIC. Use MIC code ‘XOFF’ for financial instruments admitted to trading or traded on a trading venue, where the transaction on that financial instrument is not executed on a trading venue or systematic internaliser or organised trading platform outside of the Union. Use SINT for financial instrument submitted to trading or traded on a trading venue, where the transaction on that financial instrument is executed on a Systematic Internaliser. RM, MTF, OTF APA CTP {MIC} –trading venues ‘SINT’ — systematic internaliser Price notation For all financial instruments Indication as to whether the price is expressed in monetary value, in percentage or in yield RM, MTF, OTF APA CTP ‘MONE’ — Monetary value ‘PERC’ — Percentage ‘YIEL’ — Yield ‘BAPO’ — Basis points Price Currency For all financial instruments Currency in which the price is expressed (applicable if the price is expressed as monetary value) RM, MTF, OTF APA CTP {CURRENCYCODE_3} Notation of the quantity in measurement unit For commodity derivatives, emission allowance derivatives and emission allowances except in the cases described under Article 11(1) letters (a) and (b) of this Regulation. Indication of measurement units in which the quantity in measurement unit is expressed RM, MTF, OTF APA CTP ‘TOCD’ — tons of carbon dioxide equivalent Or {ALPHANUM-25} otherwise Quantity in measurement unit For commodity derivatives, emission allowance derivatives and emission allowances except in the cases described under Article 11(1) letters (a) and (b) of this Regulation. The equivalent amount of commodity or emission allowance traded expressed in measurement unit RM, MTF, OTF APA CTP {DECIMAL-18/17} Quantity For all financial instruments except in the cases described under Article 11(1) letters (a) and (b) of this Regulation. The number of units of the financial instrument, or the number of derivative contracts in the transaction. RM, MTF, OTF APA CTP {DECIMAL-18/17} Notional amount For all financial instruments except in the cases described under Article 11(1) letters (a) and (b) of this Regulation. Nominal amount or notional amount For spread bets, the notional amount shall be the monetary value wagered per point movement in the underlying financial instrument. For credit default swaps, it shall be the notional amount for which the protection is acquired or disposed of. The information reported in this field shall be consistent with the value provided in field Price RM, MTF, OTF APA CTP {DECIMAL-18/5} Notional currency For all financial instruments except in the cases described under Article 11(1) letters (a) and (b) of the Regulation. Currency in which the notional is denominated RM, MTF, OTF APA CTP {CURRENCYCODE_3} Type For emission allowances and emission allowance derivatives only This field is only applicable for emission allowances and emission allowance derivatives. RM, MTF, OTF APA CTP ‘EUAE’ — EUA ‘CERE’ — CER ‘ERUE’ — ERU ‘EUAA’ — EUAA ‘OTHR’ — Other (for derivatives only) Publication Date and Time For all financial instruments Date and time when the transaction was published by a trading venue or APA. For transactions executed on a trading venue, the level of granularity shall be in accordance with the requirements set out in Article 2 of Delegated Regulation (EU) 2017/574. For transactions not executed on a trading venue, the time reported shall be granular to at least the nearest second. RM, MTF, OTF APA CTP {DATE_TIME_FORMAT} Venue of publication For all financial instruments Code used to identify the trading venue and APA publishing the transaction. CTP Trading venue: {MIC} APA: {MIC} where available. Otherwise, 4 character code as published in the list of data reporting services providers on ESMA's website. Transaction Identification Code For all financial instruments Alphanumerical code assigned by trading venues (pursuant to Article 12 of Commission Delegated Regulation (EU) 2017/580 (2) and APAs and used in any subsequent reference to the specific trade. The transaction identification code shall be unique, consistent and persistent per ISO 10383 segment MIC and per trading day. Where the trading venue does not use segment MICs, the transaction identification code shall be unique, consistent and persistent per operating MIC per trading day. Where the APA does not use MICs, it should be unique, consistent and persistent per 4-character code used to identify the APA per trading day. The components of the transaction identification code shall not disclose the identity of the counterparties to the transaction for which the code is maintained RM, MTF, OTF APA CTP {ALPHANUMERICAL-52} Transaction to be cleared For derivatives Code to identify whether the transaction will be cleared. RM, MTF, OTF APA CTP ‘true’ — transaction to be cleared ‘false’ — transaction not to be cleared



Table 3

List of flags for the purpose of post-trade transparency

  Flag Name of Flag Type of execution/publication venue Description   ‘BENC’ Benchmark transaction flag RM, MTF, OTF APA CTP All kinds of volume weighted average price transactions and all other trades where the price is calculated over multiple time instances according to a given benchmark.   ‘ACTX’ Agency cross transaction flag APA CTP Transactions where an investment firm has brought together two clients' orders with the purchase and the sale conducted as one transaction and involving the same volume and price.   ‘NPFT’ Non-price forming transaction flag RM, MTF, OTF CTP All types of transactions listed under Article 12 of this Regulation and which do not contribute to the price formation.   ‘LRGS’ Post-trade LIS transaction flag RM, MTF, OTF APA CTP Transactions executed under the post-trade large in scale deferral.   ‘ILQD’ Illiquid instrument transaction flag RM, MTF, OTF APA CTP Transactions executed under the deferral for instruments for which there is not a liquid market.   ‘SIZE’ Post-trade SSTI transaction flag RM, MTF, OTF APA CTP Transactions executed under the post-trade size specific to the instrument deferral.   ‘TPAC’ Package transaction flag RM, MTF, OTF APA CTP Package transactions which are not exchange for physicals as defined in Article 1.   ‘XFPH’ Exchange for physicals transaction flag RM, MTF, OTF APA CTP Exchange for physicals as defined in Article 1   ‘CANC’ Cancellation flag RM, MTF, OTF APA CTP When a previously published transaction is cancelled.   ‘AMND’ Amendment flag RM, MTF, OTF APA CTP When a previously published transaction is amended. SUPPLEMENTARY DEFERRAL FLAGS Article 11(1)(a)(i). ‘LMTF’ Limited details flag RM, MTF, OTF APA CTP First report with publication of limited details in accordance with Article 11(1)(a)(i). ‘FULF’ Full details flag Transaction for which limited details have been previously published in accordance with Article 11(1)(a)(i). Article 11(1)(a)(ii). ‘DATF’ Daily aggregated transaction flag RM, MTF, OTF APA CTP Publication of daily aggregated transaction in accordance with Article 11(1)(a)(ii). ‘FULA’ Full details flag RM, MTF, OTF APA CTP Individual transactions for which aggregated details have been previously published in accordance with Article 11(1)(a)(ii). Article 11(1)(b) ‘VOLO’ Volume omission flag RM, MTF, OTF APA CTP Transaction for which limited details are published in accordance with Article 11(1)(b). ‘FULV’ Full details flag RM, MTF, OTF APA CTP Transaction for which limited details have been previously published in accordance with Article 11(1)(b) Article 11(1)(c) ‘FWAF’ Four weeks aggregation flag RM, MTF, OTF APA CTP Publication of aggregated transactions in accordance with Article 11(1)(c). ‘FULJ’ Full details flag RM, MTF, OTF APA CTP Individual transactions which have previously benefited from aggregated publication in accordance with Article 11(1)(c). Article 11(1)(d) ‘IDAF’ Indefinite aggregation flag RM, MTF, OTF APA CTP Transactions for which the publication of several transactions in aggregated form for an indefinite period of time has been allowed in accordance with Article 11(1)(d). Consecutive use of Article 11(1)(b) and Article 11(2)(c) for sovereign debt instruments ‘VOLW’ Volume omission flag RM, MTF, OTF APA CTP Transaction for which limited are published in accordance with Article 11(1)(b) and for which the publication of several transactions in aggregated form for an indefinite period of time will be consecutively allowed in accordance with Article 11(2)(c). ‘COAF’ Consecutive aggregation flag (post volume omission for sovereign debt instruments) RM, MTF, OTF APA CTP Transactions for which limited details have been previously published in accordance with Article 11(1)(b) and for which the publication of several transactions in aggregated form for an indefinite period of time has consecutively been allowed in accordance with Article 11(2)(c).



Table 4

Measure of volume

Type of instrument Volume All bonds except ETCs and ETNs and structured finance products Total nominal value of debt instruments traded ETCs and ETNs bond types Number of units traded (3) Securitised derivatives Number of units traded (3) Interest rate derivatives Notional amount of traded contracts Foreign Exchange Derivatives Notional amount of traded contracts Equity derivatives Notional amount of traded contracts Commodity derivatives Notional amount of traded contracts Credit derivatives Notional amount of traded contracts Contract for differences Notional amount of traded contracts C10 derivatives Notional amount of traded contracts Emission allowance derivatives Tons of Carbon Dioxide equivalent Emission allowances Tons of Carbon Dioxide equivalent



(1)  Commission Delegated Regulation (EU) 2017/574 of 7 June 2016 supplementing Directive 2014/65/EU of the European Parliament and of the Council with regard to regulatory technical standards for the level of accuracy of business clocks (see page 148 of this Official Journal).

(2)  Commission Delegated Regulation (EU) 2017/580 of 24 June 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council with regard to regulatory technical standards for the maintenance of relevant data relating to orders in financial instruments (see page 193 of this Official Journal).

(3)  Price per unit.
