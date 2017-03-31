# ANNEX I

## Information to be made public

Table 1

Description of the type of trading systems and the related information to be made public in accordance with Article 3

Type of trading system Description of the trading system Information to be made public Continuous auction order book trading system A system that by means of an order book and a trading algorithm operated without human intervention matches sell orders with buy orders on the basis of the best available price on a continuous basis. The aggregate number of orders and the shares, depositary receipts, ETFs, certificates and other similar financial instruments that they represent at each price level for at least the five best bid and offer price levels. Quote-driven trading system A system where transactions are concluded on the basis of firm quotes that are continuously made available to participants, which requires the market makers to maintain quotes in a size that balances the needs of members and participants to deal in a commercial size and the risk to which the market maker exposes itself. The best bid and offer by price of each market maker in shares, depositary receipts, ETFs, certificates and other similar financial instruments traded on the trading system, together with the volumes attaching to those prices. The quotes made public shall be those that represent binding commitments to buy and sell the financial instruments and which indicate the price and volume of financial instruments in which the registered market makers are prepared to buy or sell. In exceptional market conditions, however, indicative or one-way prices may be allowed for a limited time. Periodic auction trading system A system that matches orders on the basis of a periodic auction and a trading algorithm operated without human intervention. The price at which the auction trading system would best satisfy its trading algorithm in respect of shares, depositary receipts, ETFs, certificates and other similar financial instruments traded on the trading system and the volume that would potentially be executable at that price by participants in that system. Request for quote trading system A trading system where a quote or quotes are provided in response to a request for quote submitted by one or more members or participants. The quote is executable exclusively by the requesting member or participant. The requesting member or participant may conclude a transaction by accepting the quote or quotes provided to it on request. The quotes and the attached volumes from any member or participant which, if accepted, would lead to a transaction under the system's rules. All submitted quotes in response to a request for quote may be published at the same time but not later than when they become executable. Any other trading system Any other type of trading system, including a hybrid system falling into two or more of the types of trading systems referred to in this table. Adequate information as to the level of orders or quotes and of trading interest in respect of shares, depositary receipts, ETFs, certificates and other similar financial instruments traded on the trading system; in particular, the five best bid and offer price levels and/or two-way quotes of each market maker in that instrument, if the characteristics of the price discovery mechanism so permit.



Table 2

Symbol table for Table 3

Symbol Data type Definition {ALPHANUM-n} Up to n alphanumerical characters Free text field. {CURRENCYCODE_3} 3 alphanumerical characters 3-letter currency code, as defined by ISO 4217 currency codes {DATE_TIME_FORMAT} ISO 8601 date and time format Date and time in the following format: YYYY-MM-DDThh:mm:ss.ddddddZ. — ‘YYYY’ is the year; — ‘MM’ is the month; — ‘DD’ is the day; — ‘T’ — means that the letter ‘T’ shall be used — ‘hh’ is the hour; — ‘mm’ is the minute; — ‘ss.dddddd’ is the second and its fraction of a second; — Z is UTC time. Dates and times shall be reported in UTC. {DECIMAL-n/m} Decimal number of up to n digits in total of which up to m digits can be fraction digits Numerical field for both positive and negative values. — decimal separator is ‘.’ (full stop); — negative numbers are prefixed with ‘–’ (minus); Where applicable, values shall be rounded and not truncated. {ISIN} 12 alphanumerical characters ISIN code, as defined in ISO 6166 {MIC} 4 alphanumerical characters Market identifier as defined in ISO 10383



Table 3

List of details for the purpose of post-trade transparency

Field identifier Description and details to be published Type of execution or publication venue Format to be populated as defined in Table 2 Trading date and time Date and time when the transaction was executed. For transactions executed on a trading venue, the level of granularity shall be in accordance with the requirements set out in Article 2 of Delegated Regulation (EU) 2017/574. For transactions not executed on a trading venue, the date and time when the parties agree the content of the following fields: quantity, price, currencies in fields 31, 34 and 44 as specified in Table 2 of Annex 1 of Delegated Regulation (EU) 2017/590, instrument identification code, instrument classification and underlying instrument code, where applicable. For transactions not executed on a trading venue the time reported shall be granular to at least the nearest second. Where the transaction results from an order transmitted by the executing firm on behalf of a client to a third party where the conditions for transmission set out in Article 4 of Delegated Regulation (EU) 2017/590 were not satisfied, this shall be the date and time of the transaction rather than the time of the order transmission. Regulated Market (RM), Multilateral Trading Facility (MTF), Organised Trading Facility (OTF) Approved Publication Arrangement (APA) Consolidated tape provider (CTP) {DATE_TIME_FORMAT} Instrument identification code Code used to identify the financial instrument RM, MTF APA CTP {ISIN} Price Traded price of the transaction excluding, where applicable, commission and accrued interest. Where price is reported in monetary terms, it shall be provided in the major currency unit. Where price is currently not available but pending, the value should be ‘PNDG’. Where price is not applicable the field shall not be populated. The information reported in this field shall be consistent with the values provided in field Quantity. RM, MTF APA CTP {DECIMAL-18/13} in case the price is expressed as monetary value {DECIMAL-11/10} in case the price is expressed as percentage or yield ‘PNDG’ in case the price is not available Price currency Currency in which the price is expressed (applicable if the price is expressed as monetary value). RM, MTF APA CTP {CURRENCYCODE_3} Quantity Number of units of the financial instruments. The nominal or monetary value of the financial instrument. The information reported in this field shall be consistent with the values provided in field Price. RM, MTF APA CTP {DECIMAL-18/17} in case the quantity is expressed as number of units {DECIMAL-18/5} in case the quantity is expressed as monetary or nominal value Venue of execution Identification of the venue where the transaction was executed. Use the ISO 10383 segment MIC for transactions executed on a trading venue,. Where the segment MIC does not exist, use the operating MIC. Use MIC code ‘XOFF’ for financial instruments admitted to trading or traded on a trading venue, where the transaction on that financial instrument is not executed on a trading venue, systematic internaliser or organised trading platform outside of the Union. Use SINT for financial instruments admitted to trading or traded on a trading venue, where the transaction on that financial instrument is executed on a Systematic Internaliser. RM, MTF APA CTP trading venues: {MIC} Systematic internalisers: ‘SINT’ Publication date and time Date and time when the transaction was published by a trading venue or APA. For transactions executed on a trading venue, the level of granularity shall be in accordance with the requirements set out in Article 2 of Delegated Regulation (EU) 2017/574. For transactions not executed on a trading venue, the date and time shall be granular to at least the nearest second. RM, MTF APA CTP {DATE_TIME_FORMAT} Venue of Publication Code used to identify the trading venue or APA publishing the transaction. CTP trading venue: {MIC} APA: ISO 10383 segment MIC (4 characters) where available. Otherwise, 4-character code as published in the list of data reporting services providers on ESMA's website. Transaction identification code Alphanumerical code assigned by trading venues (pursuant to Article 12 of Commission Delegated Regulation (EU) 2017/580 (1)) and APAs and used in any subsequent reference to the specific trade. The transaction identification code shall be unique, consistent and persistent per ISO 10383 segment MIC and per trading day. Where the trading venue does not use segment MICs, the transaction identification code shall be unique, consistent and persistent per operating MIC per trading day. Where the APA does not use MICs, it should be unique, consistent and persistent per 4-character code used to identify the APA per trading day. The components of the transaction identification code shall not disclose the identity of the counterparties to the transaction for which the code is maintained RM, MTF APA CTP {ALPHANUM-52}



Table 4

List of flags for the purpose of post-trade transparency

Flag Name Type of execution or publication venue Description ‘BENC’ Benchmark transactions flag RM, MTF APA CTP Transactions executed in reference to a price that is calculated over multiple time instances according to a given benchmark, such as volume-weighted average price or time-weighted average price. ‘ACTX’ Agency cross transactions flag APA CTP Transactions where an investment firm has brought together clients' orders with the purchase and the sale conducted as one transaction and involving the same volume and price. ‘NPFT’ Non-price forming transactions flag RM, MTF CTP Transactions where the exchange of financial instruments is determined by factors other than the current market valuation of the financial instrument as listed under Article 13. ‘TNCP’ Transactions not contributing to the price discovery process for the purposes of Article 23 of Regulation (EU) No 600/2014 flag RM, MTF APA CTP Transaction not contributing to the price discovery process for the purposes of Article 23 of Regulation (EU) No 600/2014 and as set out in Article 2. ‘SDIV’ Special dividend transaction flag RM, MTF APA CTP Transactions that are either:   executed during the ex-dividend period where the dividend or other form of distribution accrues to the buyer instead of the seller; or   executed during the cum-dividend period where the dividend or other form of distribution accrues to the seller instead of the buyer. ‘LRGS’ Post-trade large in scale transaction flag RM, MTF APA CTP Transactions that are large in scale compared with normal market size for which deferred publication is permitted under Article 15. ‘RFPT’ Reference price transaction flag RM, MTF CTP Transactions which are executed under systems operating in accordance with Article 4(1)(a) of Regulation (EU) No 600/2014. ‘NLIQ’ Negotiated transaction in liquid financial instruments flag RM, MTF CTP Transactions executed in accordance with Article 4(1)(b)(i) of Regulation (EU) No 600/2014. ‘OILQ’ Negotiated transaction in illiquid financial instruments flag RM, MTF CTP Transactions executed in accordance with Article 4(1)(b)(ii) of Regulation (EU) No 600/2014. ‘PRIC’ Negotiated transaction subject to conditions other than the current market price flag RM, MTF CTP Transactions executed in accordance with Article 4(1)(b)(iii) of Regulation (EU) No 600/2014 and as set out in Article 6. ‘ALGO’ Algorithmic transaction flag RM, MTF CTP Transactions executed as a result of an investment firm engaging in algorithmic trading as defined in Article 4(1)(39) of Directive 2014/65/EU. ‘SIZE’ Transaction above the standard market size flag APA CTP Transactions executed on a systematic internaliser where the size of the incoming order was above the standard market size as determined in accordance with Article 11. ‘ILQD’ Illiquid instrument transaction flag APA CTP Transactions in illiquid instruments as determined in accordance with Articles 1 to 9 of Commission Delegated Regulation (EU) 2017/567 (2) executed on a systematic internaliser. ‘RPRI’ Transactions which have received price improvement flag APA CTP Transactions executed on a systematic internaliser with a price improvement in accordance with Article 15(2) of Regulation (EU) No 600/2014. ‘CANC’ Cancellation flag RM, MTF APA CTP When a previously published transaction is cancelled. ‘AMND’ Amendment flag RM, MTF APA CTP When a previously published transaction is amended. ‘DUPL’ Duplicative trade reports flag APA When a transaction is reported to more than one APA in accordance with Article 17(1) of Delegated Regulation (EU) 2017/571.



(1)  Commission Delegated Regulation (EU) 2017/580 of 24 June 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council with regard to regulatory technical standards for the maintenance of relevant data relating to orders in financial instruments (see page 193 of this Official Journal).

(2)  Commission Delegated Regulation (EU) 2017/567 of 18 May 2016 supplementing Regulation (EU) No 600/2014 of the European Parliament and of the Council with regard to definitions, transparency, portfolio compression and supervisory measures on product intervention and positions (see page 90 of this Official Journal).
