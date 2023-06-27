# Qilin.Cloud/API/Offer

## Description

The Offer API is used to manage offers. An offer always needs a product as a base to which the offer refers. The product is not merchant-specific (because it describes a product in general), but the offer is.
The offer describes the details at which a merchant wants to offer a product on a specific channel.

### :bulb: Example:

*For the product "Coca Cola, glass bottle, 0.4L", a merchant creates the offer "6-pack, 10 pieces available in stock, each at a price of 4.00 US dollars with a delivery time of 2-4 days". This and similar offer data are managed by the Offer API.*

## Version

The current API version is: **1.0.2**

## Code Quality

We use a variety of state-of-the-art techniques to ensure that our code meets the highest quality criteria.
Some examples are:

- [SOLID principle](https://en.wikipedia.org/wiki/SOLID)
- [Clean as you code:tm: approach](https://www.sonarsource.com/solutions/our-unique-approach/)
- 4-eyes approval on QC
- Semiautomated Unit-, Integration- and End2End-tests
- positive tests / negative tests / destructive tests in aware of false positive results / false negative results
- Sonarcloud

[![Quality gate](https://sonarcloud.io/api/project_badges/quality_gate?project=marcossoftware_Qilin.Core.Offer&token=db2775f834732361879144a856d3bb9e328a3b22)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Offer)

[![Vulnerabilities](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Offer&metric=vulnerabilities&token=db2775f834732361879144a856d3bb9e328a3b22)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Offer) [![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Offer&metric=security_rating&token=db2775f834732361879144a856d3bb9e328a3b22)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Offer) [![Coverage](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Offer&metric=coverage&token=db2775f834732361879144a856d3bb9e328a3b22)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Offer) [![Bugs](https://sonarcloud.io/api/project_badges/measure?project=marcossoftware_Qilin.Core.Offer&metric=bugs&token=db2775f834732361879144a856d3bb9e328a3b22)](https://sonarcloud.io/summary/new_code?id=marcossoftware_Qilin.Core.Offer)

💡 _If you still notice something bad, we are happy to have a strong community to solve the problem together with you: [How to provide feedback](https://github.com/QilinCloud/API-Offer/#how-to-provide-feedback)_

## Useful links to get started

* [Endpoint documentation](https://documentation.api.qilin.cloud/offer/)
* [OpenAPI specification](https://github.com/QilinCloud/API-Offer/tree/main/openapi-specification)
* [Postman pollection](https://github.com/QilinCloud/API-Offer/tree/main/postman-collection)
* [SDKs](https://github.com/search?q=user%3AQilinCloud+SDK)
* [Wiki](https://github.com/QilinCloud/API-Offer/wiki)

## How to provide feedback

Generally, bugs and feature requests for the API or docs should be [Github issue](https://github.com/QilinCloud/API-Offer/issues/new). Everything else should be discussed here [API-Offer Discussion](https://github.com/QilinCloud/API-Offer/discussions).

:warning:  **For vulnerabilities please check out the [security](https://github.com/QilinCloud/API-Offer/security) area.**

## Legal

Note that by submitting your feedback, we have the right to use it.[^1]

[^1]:Legalese-wise, this means it’s considered non-confidential and non-proprietary to you, and you grant Qilin.Cloud a non-exclusive, worldwide, royalty-free, irrevocable, sub-licensable, perpetual license to use and publish those ideas and materials for any purpose, without compensation to you.
