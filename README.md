# OpenTED

OpenTED is a project aiming to open up the [EU Tender Electronic Daily](http://www.ted.europa.eu/) archive for journalistic and analytical purposes.

The actual scraper for TED data is not contained in this package, but in [monnet](http://github.com/pudo/monnet), a package that is shared with the [OpenInterests.eu](http://openinterests.eu) project which uses the same data.

To operate, this site will require that ``monnet`` is set up in the same virtual environment and a fully-extracted database of TED data is available (i.e. the output of running ``make ted`` in the ``monnet`` folder).

## What information is available?

The [relevant EU regulation](http://eur-lex.europa.eu/LexUriServ/LexUriServ.do?uri=CONSLEG:2004L0018:20120101:EN:PDF) mandates that the following information must be made available. These requirements are not met by some member states, but they can serve as a guideline:

**CONTRACT AWARD NOTICES**

1. Name and address of the contracting authority.
2. Award procedures chosen. In the case of negotiated procedure without prior publication of a contract notice (Article 28), justification.
3. Public works contracts: nature and extent of the contract, general char­acteristics of the work. Public supply contracts: nature and quantity of products supplied, where appropriate, by the supplier; nomenclature reference number. Public service contracts: category and description of the service; nomen­clature reference number; quantity of services bought.
4. Date of contract award.
5. Contract award criteria.
6. Number of tenders received.
7. Name and address of the successful economic operators.
8. Price or range of prices (minimum/maximum) paid.
9. Value of the tender (tenders) retained or the highest tender and lowest tender taken into consideration for the contract award.
10. Where appropriate, value and proportion of contract likely to be subcon­
tracted to third parties.
11. Date of publication of the tender notice in accordance with the technical specifications for publication in Annex VIII.
12. Date of dispatch of the notice.
13. Name and address of the body responsible for appeal and, where appropriate, mediation procedures. Precise information concerning the deadline for lodging appeals, or if need be the name, address, telephone number, fax number and email address of the service from which this information may be obtained.
