# Open Referral UK

These pages define the UK profile of the Open Referral - Human Services Data Specification version 3.0 (HSDS 3.0) and the associated Human Services Data Application Programming Interface (HSDA). The original UK profile was not versioned, we're now versioning to match the version number of the full HSDS from which the profile is defined.

The profile is subject to consultation in 2024. Thereafter it will be the official latest version of the Open Referral UK standard and publishers are encouraged to migrate to it from the version described in the [Open Referral UK developer pages](https://developers.openreferraluk.org/).

The UK profile contains a subset of the tables and fields that make up the full HSDS specification. The data structure is illustrated by the [Entity Relation Diagram](erd.md) comprising a set of related tables whose structure is given in the [Schema Reference](schema_reference.md) page.

Although represented here as a set of relational tables and in the Open Knowledge Foundation’s Tabular data structure format, from version 3.0 the standard is made up of a set of JSON classes which are given here.

## What constitutes UK compliance?
The standard is endorsed by the UK Government’s Central Digital & Data Office -  See [government guidance](https://www.gov.uk/government/publications/open-standards-for-government/record-and-share-information-about-public-services-in-local-authorities). Hence it is encouraged in local government and required where appropriate in central government.

As Open Referral UK is an interchange standard, compliance means providing open API endpoints as described in the [API Reference](api_reference.md) and [Swagger](https://open-referral-uk-profile.readthedocs.io/en/latest/openapi.html) documentation.

API feeds compliant with the initial version of Open Referral UK can be [validated here](https://validator.openreferraluk.org/). Compliant feeds are listed on this [Dashboard](https://openreferraluk.org/dashboard). The Validator and Dashboard will soon be updated to work for the UK profile of HSDS 3.0 given here.

The main [Open Referral UK website](https://openreferraluk.org/) gives guidance on adopting the standard and case studies from early adopters.

## Changes in this version
Changes from the initial version of Open Referral UK are listed in the [Changelog](changelog.md). Changes are largely to achieve consistency across tables and to remove parts of the initial standard that were not taken up.

## Consultation and Feedback
Use the [Open Referral Forum](https://forum.openreferral.org/) to stay up to date, ask questions and share learning. Private matters can be raised by email to [hello@openreferraluk.org](mailto:hello@openreferraluk.org). 

You can ask on the forum or email if you have a query about compliance.

If you publish a compliant feed, [advise us by email](mailto:hello@openreferraluk.org) so we can add you to the Dashboard and publicise your work.

```{eval-rst}

.. toctree::
   :maxdepth: 1
   :caption: Reference

   Swagger API <https://open-referral-uk-profile.readthedocs.io/en/latest/openapi.html>
   schema_reference
   erd
   profile_compliance
   changelog

```

