# DIACN-Standard (DRAFT) 

## Summary

The Digital Identification Academic Certificate Number, abbreviated as DIACN is a unique digital content identifier for non-digital (in paper form) certificates issued by academic organisations. A DIACN when stored on a decentralized, distributed and public digital ledger like the Ethereum Blockchain acts like a proof-of-existence of a certificate issued to an individual.


An example DIACN file is as follows:

    ID: ASTON.AC.UK-1895-GBR-0121-AQADDQEODAUFAQIJBAIBBQ
    ACADEMIC ORGANISATION NAME: ASTON UNIVERSITY
    TITLE: MASTER OF SCIENCE
    ISSUANCE DATE: TEN JULY 2017
    EXPIRY DATE:
    NAME OF CERTIFICATE HOLDER: MR. IAN SMITH
    OTHER DATA:

## Detailing a DIACN structure
* The name of the file can be anything with file type as .diacn. E.g. fileName.diacn
* The content of a DIACN document consists of four mandatory and three optional fields.
* The four mandatory fields are ID, ACADEMIC ORGANISATION NAME, ISSUANCE DATE, NAME OF CERTIFICATE HOLDER.
* The three optional fields are TITLE, EXPIRY DATE, OTHER DATA.

Below lists a detailed structure of each of the fields:

Field Name  | Content Structure | Example
------------- | --------------  | -----------
ID  | DO-YY-CC-AA-UU  | OX.AC.UK-1096-GBR-01865-AQACCQEODAUFAQIJBAIBBQ
    
    DO: Web domain name of the organisation (Min/Max length: 2/~)
    YY: Organisation founded in year (Min/Max length: 1/~)
    CC: Country Code as ISO alpha-3 (Min/Max length: 3/3)
    AA: Area or regional code (Min/Max length: 1/~)
    UU: Base64 encoeded UUID also known as ShortUUID or ShortGUID (Min/Max length: 6/~)

Work in progress.

### Copyright and License

Copyright 2018 Jay Bhosle.
