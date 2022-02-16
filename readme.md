﻿# Open Banking OAS Specification Diff

## Current APIs

### Majors/Minors

| OAS | Base | Revision | Breaking changes only | Full Diff |
| --- | --- | --- | --- | --- |
| accounts | [1.0.3](swagger-apis/accounts/1.0.3.yml) |  |  |  |
| acquiring-services | [1.0.0](swagger-apis/acquiring-services/1.0.0.yml) |  |  |  |
| admin | [1.0.2](swagger-apis/admin/1.0.2.yml) | [2.0.0](swagger-apis/admin/2.0.0.yml) | [YAML](diffs/admin/1.0.2_2.0.0-breaking-only.yml) | [YAML](diffs/admin/1.0.2_2.0.0.yml) |
| channels | [1.0.2](swagger-apis/channels/1.0.2.yml) | [2.0.0](swagger-apis/channels/2.0.0.yml) | [YAML](diffs/channels/1.0.2_2.0.0-breaking-only.yml) | [YAML](diffs/channels/1.0.2_2.0.0.yml) |
|  | [2.0.0](swagger-apis/channels/2.0.0.yml) | [3.0.0](swagger-apis/channels/3.0.0.yml) | [YAML](diffs/channels/2.0.0_3.0.0-breaking-only.yml) | [YAML](diffs/channels/2.0.0_3.0.0.yml) |
| common | [1.0.2](swagger-apis/common/1.0.2.yml) |  |  |  |
| consents | [1.0.3](swagger-apis/consents/1.0.3.yml) |  |  |  |
| credit-cards | [1.0.4](swagger-apis/credit-cards/1.0.4.yml) |  |  |  |
| customers | [1.0.3](swagger-apis/customers/1.0.3.yml) |  |  |  |
| financings | [1.0.4](swagger-apis/financings/1.0.4.yml) |  |  |  |
| insurances | [1.0.0-rc1.0](swagger-apis/insurances/1.0.0-rc1.0.yml) |  |  |  |
| investments | [1.0.0](swagger-apis/investments/1.0.0.yml) |  |  |  |
| invoice-financings | [1.0.4](swagger-apis/invoice-financings/1.0.4.yml) |  |  |  |
| loans | [1.0.4](swagger-apis/loans/1.0.4.yml) |  |  |  |
| participants | [1.0.0](swagger-apis/participants/1.0.0.yml) |  |  |  |
| payments | [1.0.1](swagger-apis/payments/1.0.1.yml) |  |  |  |
| products-services | [1.0.2](swagger-apis/products-services/1.0.2.yml) | [2.0.0](swagger-apis/products-services/2.0.0.yml) | [YAML](diffs/products-services/1.0.2_2.0.0-breaking-only.yml) | [YAML](diffs/products-services/1.0.2_2.0.0.yml) |
|  | [2.0.0](swagger-apis/products-services/2.0.0.yml) | [3.0.0](swagger-apis/products-services/3.0.0.yml) | [YAML](diffs/products-services/2.0.0_3.0.0-breaking-only.yml) | [YAML](diffs/products-services/2.0.0_3.0.0.yml) |
| resources | [1.0.2](swagger-apis/resources/1.0.2.yml) |  |  |  |
| unarranged-accounts-overdraft | [1.0.4](swagger-apis/unarranged-accounts-overdraft/1.0.4.yml) |  |  |  |

### All revisions

| OAS | Base | Revision | Full Diff |
| --- | --- | --- | --- |
| accounts | [1.0.0-rc6.5](swagger-apis/accounts/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/accounts/1.0.0-rc6.6.yml) | [YAML](diffs/accounts/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/accounts/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/accounts/1.0.0-rc6.7.yml) | [YAML](diffs/accounts/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/accounts/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/accounts/1.0.0.yml) | [YAML](diffs/accounts/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/accounts/1.0.0.yml) | [1.0.1](swagger-apis/accounts/1.0.1.yml) | [YAML](diffs/accounts/1.0.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/accounts/1.0.1.yml) | [1.0.2](swagger-apis/accounts/1.0.2.yml) | [YAML](diffs/accounts/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/accounts/1.0.2.yml) | [1.0.3](swagger-apis/accounts/1.0.3.yml) | [YAML](diffs/accounts/1.0.2_1.0.3.yml) |
| acquiring-services | [1.0.0](swagger-apis/acquiring-services/1.0.0.yml) |  |  |
| admin | [1.0.0-rc5.1](swagger-apis/admin/1.0.0-rc5.1.yml) | [1.0.0-rc5.2](swagger-apis/admin/1.0.0-rc5.2.yml) | [YAML](diffs/admin/1.0.0-rc5.1_1.0.0-rc5.2.yml) |
|  | [1.0.0-rc5.2](swagger-apis/admin/1.0.0-rc5.2.yml) | [1.0.0-rc5](swagger-apis/admin/1.0.0-rc5.yml) | [YAML](diffs/admin/1.0.0-rc5.2_1.0.0-rc5.yml) |
|  | [1.0.0-rc5](swagger-apis/admin/1.0.0-rc5.yml) | [1.0.0](swagger-apis/admin/1.0.0.yml) | [YAML](diffs/admin/1.0.0-rc5_1.0.0.yml) |
|  | [1.0.0](swagger-apis/admin/1.0.0.yml) | [1.0.1-rc1.0](swagger-apis/admin/1.0.1-rc1.0.yml) | [YAML](diffs/admin/1.0.0_1.0.1-rc1.0.yml) |
|  | [1.0.1-rc1.0](swagger-apis/admin/1.0.1-rc1.0.yml) | [1.0.1](swagger-apis/admin/1.0.1.yml) | [YAML](diffs/admin/1.0.1-rc1.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/admin/1.0.1.yml) | [1.0.2](swagger-apis/admin/1.0.2.yml) | [YAML](diffs/admin/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/admin/1.0.2.yml) | [2.0.0](swagger-apis/admin/2.0.0.yml) | [YAML](diffs/admin/1.0.2_2.0.0.yml) |
| channels | [1.0.0-rc5.1](swagger-apis/channels/1.0.0-rc5.1.yml) | [1.0.0-rc5.2](swagger-apis/channels/1.0.0-rc5.2.yml) | [YAML](diffs/channels/1.0.0-rc5.1_1.0.0-rc5.2.yml) |
|  | [1.0.0-rc5.2](swagger-apis/channels/1.0.0-rc5.2.yml) | [1.0.0-rc5](swagger-apis/channels/1.0.0-rc5.yml) | [YAML](diffs/channels/1.0.0-rc5.2_1.0.0-rc5.yml) |
|  | [1.0.0-rc5](swagger-apis/channels/1.0.0-rc5.yml) | [1.0.0](swagger-apis/channels/1.0.0.yml) | [YAML](diffs/channels/1.0.0-rc5_1.0.0.yml) |
|  | [1.0.0](swagger-apis/channels/1.0.0.yml) | [1.0.1-rc1.0](swagger-apis/channels/1.0.1-rc1.0.yml) | [YAML](diffs/channels/1.0.0_1.0.1-rc1.0.yml) |
|  | [1.0.1-rc1.0](swagger-apis/channels/1.0.1-rc1.0.yml) | [1.0.1](swagger-apis/channels/1.0.1.yml) | [YAML](diffs/channels/1.0.1-rc1.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/channels/1.0.1.yml) | [1.0.2](swagger-apis/channels/1.0.2.yml) | [YAML](diffs/channels/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/channels/1.0.2.yml) | [2.0.0](swagger-apis/channels/2.0.0.yml) | [YAML](diffs/channels/1.0.2_2.0.0.yml) |
|  | [2.0.0](swagger-apis/channels/2.0.0.yml) | [3.0.0](swagger-apis/channels/3.0.0.yml) | [YAML](diffs/channels/2.0.0_3.0.0.yml) |
| common | [1.0.0-rc5.1](swagger-apis/common/1.0.0-rc5.1.yml) | [1.0.0-rc5.2](swagger-apis/common/1.0.0-rc5.2.yml) | [YAML](diffs/common/1.0.0-rc5.1_1.0.0-rc5.2.yml) |
|  | [1.0.0-rc5.2](swagger-apis/common/1.0.0-rc5.2.yml) | [1.0.0-rc5](swagger-apis/common/1.0.0-rc5.yml) | [YAML](diffs/common/1.0.0-rc5.2_1.0.0-rc5.yml) |
|  | [1.0.0-rc5](swagger-apis/common/1.0.0-rc5.yml) | [1.0.0](swagger-apis/common/1.0.0.yml) | [YAML](diffs/common/1.0.0-rc5_1.0.0.yml) |
|  | [1.0.0](swagger-apis/common/1.0.0.yml) | [1.0.1-rc1.0](swagger-apis/common/1.0.1-rc1.0.yml) | [YAML](diffs/common/1.0.0_1.0.1-rc1.0.yml) |
|  | [1.0.1-rc1.0](swagger-apis/common/1.0.1-rc1.0.yml) | [1.0.1](swagger-apis/common/1.0.1.yml) | [YAML](diffs/common/1.0.1-rc1.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/common/1.0.1.yml) | [1.0.2](swagger-apis/common/1.0.2.yml) | [YAML](diffs/common/1.0.1_1.0.2.yml) |
| consents | [1.0.0-rc6.5](swagger-apis/consents/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/consents/1.0.0-rc6.6.yml) | [YAML](diffs/consents/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/consents/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/consents/1.0.0-rc6.7.yml) | [YAML](diffs/consents/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/consents/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/consents/1.0.0.yml) | [YAML](diffs/consents/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/consents/1.0.0.yml) | [1.0.1](swagger-apis/consents/1.0.1.yml) | [YAML](diffs/consents/1.0.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/consents/1.0.1.yml) | [1.0.2](swagger-apis/consents/1.0.2.yml) | [YAML](diffs/consents/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/consents/1.0.2.yml) | [1.0.3](swagger-apis/consents/1.0.3.yml) | [YAML](diffs/consents/1.0.2_1.0.3.yml) |
| credit-cards | [1.0.0-rc6.5](swagger-apis/credit-cards/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/credit-cards/1.0.0-rc6.6.yml) | [YAML](diffs/credit-cards/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/credit-cards/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/credit-cards/1.0.0-rc6.7.yml) | [YAML](diffs/credit-cards/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/credit-cards/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/credit-cards/1.0.0.yml) | [YAML](diffs/credit-cards/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/credit-cards/1.0.0.yml) | [1.0.2](swagger-apis/credit-cards/1.0.2.yml) | [YAML](diffs/credit-cards/1.0.0_1.0.2.yml) |
|  | [1.0.2](swagger-apis/credit-cards/1.0.2.yml) | [1.0.3](swagger-apis/credit-cards/1.0.3.yml) | [YAML](diffs/credit-cards/1.0.2_1.0.3.yml) |
|  | [1.0.3](swagger-apis/credit-cards/1.0.3.yml) | [1.0.4](swagger-apis/credit-cards/1.0.4.yml) | [YAML](diffs/credit-cards/1.0.3_1.0.4.yml) |
| customers | [1.0.0-rc6.5](swagger-apis/customers/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/customers/1.0.0-rc6.6.yml) | [YAML](diffs/customers/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/customers/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/customers/1.0.0-rc6.7.yml) | [YAML](diffs/customers/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/customers/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/customers/1.0.0.yml) | [YAML](diffs/customers/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/customers/1.0.0.yml) | [1.0.1](swagger-apis/customers/1.0.1.yml) | [YAML](diffs/customers/1.0.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/customers/1.0.1.yml) | [1.0.2](swagger-apis/customers/1.0.2.yml) | [YAML](diffs/customers/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/customers/1.0.2.yml) | [1.0.3](swagger-apis/customers/1.0.3.yml) | [YAML](diffs/customers/1.0.2_1.0.3.yml) |
| financings | [1.0.0-rc6.5](swagger-apis/financings/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/financings/1.0.0-rc6.6.yml) | [YAML](diffs/financings/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/financings/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/financings/1.0.0-rc6.7.yml) | [YAML](diffs/financings/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/financings/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/financings/1.0.0.yml) | [YAML](diffs/financings/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/financings/1.0.0.yml) | [1.0.2](swagger-apis/financings/1.0.2.yml) | [YAML](diffs/financings/1.0.0_1.0.2.yml) |
|  | [1.0.2](swagger-apis/financings/1.0.2.yml) | [1.0.3](swagger-apis/financings/1.0.3.yml) | [YAML](diffs/financings/1.0.2_1.0.3.yml) |
|  | [1.0.3](swagger-apis/financings/1.0.3.yml) | [1.0.4](swagger-apis/financings/1.0.4.yml) | [YAML](diffs/financings/1.0.3_1.0.4.yml) |
| insurances | [1.0.0-rc1.0](swagger-apis/insurances/1.0.0-rc1.0.yml) |  |  |
| investments | [1.0.0](swagger-apis/investments/1.0.0.yml) |  |  |
| invoice-financings | [1.0.0-rc6.5](swagger-apis/invoice-financings/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/invoice-financings/1.0.0-rc6.6.yml) | [YAML](diffs/invoice-financings/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/invoice-financings/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/invoice-financings/1.0.0-rc6.7.yml) | [YAML](diffs/invoice-financings/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/invoice-financings/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/invoice-financings/1.0.0.yml) | [YAML](diffs/invoice-financings/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/invoice-financings/1.0.0.yml) | [1.0.2](swagger-apis/invoice-financings/1.0.2.yml) | [YAML](diffs/invoice-financings/1.0.0_1.0.2.yml) |
|  | [1.0.2](swagger-apis/invoice-financings/1.0.2.yml) | [1.0.3](swagger-apis/invoice-financings/1.0.3.yml) | [YAML](diffs/invoice-financings/1.0.2_1.0.3.yml) |
|  | [1.0.3](swagger-apis/invoice-financings/1.0.3.yml) | [1.0.4](swagger-apis/invoice-financings/1.0.4.yml) | [YAML](diffs/invoice-financings/1.0.3_1.0.4.yml) |
| loans | [1.0.0-rc6.5](swagger-apis/loans/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/loans/1.0.0-rc6.6.yml) | [YAML](diffs/loans/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/loans/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/loans/1.0.0-rc6.7.yml) | [YAML](diffs/loans/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/loans/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/loans/1.0.0.yml) | [YAML](diffs/loans/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/loans/1.0.0.yml) | [1.0.2](swagger-apis/loans/1.0.2.yml) | [YAML](diffs/loans/1.0.0_1.0.2.yml) |
|  | [1.0.2](swagger-apis/loans/1.0.2.yml) | [1.0.3](swagger-apis/loans/1.0.3.yml) | [YAML](diffs/loans/1.0.2_1.0.3.yml) |
|  | [1.0.3](swagger-apis/loans/1.0.3.yml) | [1.0.4](swagger-apis/loans/1.0.4.yml) | [YAML](diffs/loans/1.0.3_1.0.4.yml) |
| participants | [1.0.0](swagger-apis/participants/1.0.0.yml) |  |  |
| payments | [1.0.0-rc1.0](swagger-apis/payments/1.0.0-rc1.0.yml) | [1.0.0-rc2.0](swagger-apis/payments/1.0.0-rc2.0.yml) | [YAML](diffs/payments/1.0.0-rc1.0_1.0.0-rc2.0.yml) |
|  | [1.0.0-rc2.0](swagger-apis/payments/1.0.0-rc2.0.yml) | [1.0.0-rc3.0](swagger-apis/payments/1.0.0-rc3.0.yml) | [YAML](diffs/payments/1.0.0-rc2.0_1.0.0-rc3.0.yml) |
|  | [1.0.0-rc3.0](swagger-apis/payments/1.0.0-rc3.0.yml) | [1.0.0-rc4.0](swagger-apis/payments/1.0.0-rc4.0.yml) | [YAML](diffs/payments/1.0.0-rc3.0_1.0.0-rc4.0.yml) |
|  | [1.0.0-rc4.0](swagger-apis/payments/1.0.0-rc4.0.yml) | [1.0.0-rc5.0](swagger-apis/payments/1.0.0-rc5.0.yml) | [YAML](diffs/payments/1.0.0-rc4.0_1.0.0-rc5.0.yml) |
|  | [1.0.0-rc5.0](swagger-apis/payments/1.0.0-rc5.0.yml) | [1.0.0-rc5.1](swagger-apis/payments/1.0.0-rc5.1.yml) | [YAML](diffs/payments/1.0.0-rc5.0_1.0.0-rc5.1.yml) |
|  | [1.0.0-rc5.1](swagger-apis/payments/1.0.0-rc5.1.yml) | [1.0.0-rc5.2](swagger-apis/payments/1.0.0-rc5.2.yml) | [YAML](diffs/payments/1.0.0-rc5.1_1.0.0-rc5.2.yml) |
|  | [1.0.0-rc5.2](swagger-apis/payments/1.0.0-rc5.2.yml) | [1.0.0-rc5.3](swagger-apis/payments/1.0.0-rc5.3.yml) | [YAML](diffs/payments/1.0.0-rc5.2_1.0.0-rc5.3.yml) |
|  | [1.0.0-rc5.3](swagger-apis/payments/1.0.0-rc5.3.yml) | [1.0.0-rc5.4](swagger-apis/payments/1.0.0-rc5.4.yml) | [YAML](diffs/payments/1.0.0-rc5.3_1.0.0-rc5.4.yml) |
|  | [1.0.0-rc5.4](swagger-apis/payments/1.0.0-rc5.4.yml) | [1.0.0-rc5.5](swagger-apis/payments/1.0.0-rc5.5.yml) | [YAML](diffs/payments/1.0.0-rc5.4_1.0.0-rc5.5.yml) |
|  | [1.0.0-rc5.5](swagger-apis/payments/1.0.0-rc5.5.yml) | [1.0.0](swagger-apis/payments/1.0.0.yml) | [YAML](diffs/payments/1.0.0-rc5.5_1.0.0.yml) |
|  | [1.0.0](swagger-apis/payments/1.0.0.yml) | [1.0.1-rc1.0](swagger-apis/payments/1.0.1-rc1.0.yml) | [YAML](diffs/payments/1.0.0_1.0.1-rc1.0.yml) |
|  | [1.0.1-rc1.0](swagger-apis/payments/1.0.1-rc1.0.yml) | [1.0.1-rc1.1](swagger-apis/payments/1.0.1-rc1.1.yml) | [YAML](diffs/payments/1.0.1-rc1.0_1.0.1-rc1.1.yml) |
|  | [1.0.1-rc1.1](swagger-apis/payments/1.0.1-rc1.1.yml) | [1.0.1-rc1.2](swagger-apis/payments/1.0.1-rc1.2.yml) | [YAML](diffs/payments/1.0.1-rc1.1_1.0.1-rc1.2.yml) |
|  | [1.0.1-rc1.2](swagger-apis/payments/1.0.1-rc1.2.yml) | [1.0.1](swagger-apis/payments/1.0.1.yml) | [YAML](diffs/payments/1.0.1-rc1.2_1.0.1.yml) |
| products-services | [1.0.0-rc5.1](swagger-apis/products-services/1.0.0-rc5.1.yml) | [1.0.0-rc5.2](swagger-apis/products-services/1.0.0-rc5.2.yml) | [YAML](diffs/products-services/1.0.0-rc5.1_1.0.0-rc5.2.yml) |
|  | [1.0.0-rc5.2](swagger-apis/products-services/1.0.0-rc5.2.yml) | [1.0.0-rc5](swagger-apis/products-services/1.0.0-rc5.yml) | [YAML](diffs/products-services/1.0.0-rc5.2_1.0.0-rc5.yml) |
|  | [1.0.0-rc5](swagger-apis/products-services/1.0.0-rc5.yml) | [1.0.0](swagger-apis/products-services/1.0.0.yml) | [YAML](diffs/products-services/1.0.0-rc5_1.0.0.yml) |
|  | [1.0.0](swagger-apis/products-services/1.0.0.yml) | [1.0.1](swagger-apis/products-services/1.0.1.yml) | [YAML](diffs/products-services/1.0.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/products-services/1.0.1.yml) | [1.0.2](swagger-apis/products-services/1.0.2.yml) | [YAML](diffs/products-services/1.0.1_1.0.2.yml) |
|  | [1.0.2](swagger-apis/products-services/1.0.2.yml) | [2.0.0](swagger-apis/products-services/2.0.0.yml) | [YAML](diffs/products-services/1.0.2_2.0.0.yml) |
|  | [2.0.0](swagger-apis/products-services/2.0.0.yml) | [3.0.0](swagger-apis/products-services/3.0.0.yml) | [YAML](diffs/products-services/2.0.0_3.0.0.yml) |
| resources | [1.0.0-rc6.5](swagger-apis/resources/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/resources/1.0.0-rc6.6.yml) | [YAML](diffs/resources/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/resources/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/resources/1.0.0-rc6.7.yml) | [YAML](diffs/resources/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/resources/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/resources/1.0.0.yml) | [YAML](diffs/resources/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/resources/1.0.0.yml) | [1.0.1](swagger-apis/resources/1.0.1.yml) | [YAML](diffs/resources/1.0.0_1.0.1.yml) |
|  | [1.0.1](swagger-apis/resources/1.0.1.yml) | [1.0.2](swagger-apis/resources/1.0.2.yml) | [YAML](diffs/resources/1.0.1_1.0.2.yml) |
| unarranged-accounts-overdraft | [1.0.0-rc6.5](swagger-apis/unarranged-accounts-overdraft/1.0.0-rc6.5.yml) | [1.0.0-rc6.6](swagger-apis/unarranged-accounts-overdraft/1.0.0-rc6.6.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.0-rc6.5_1.0.0-rc6.6.yml) |
|  | [1.0.0-rc6.6](swagger-apis/unarranged-accounts-overdraft/1.0.0-rc6.6.yml) | [1.0.0-rc6.7](swagger-apis/unarranged-accounts-overdraft/1.0.0-rc6.7.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.0-rc6.6_1.0.0-rc6.7.yml) |
|  | [1.0.0-rc6.7](swagger-apis/unarranged-accounts-overdraft/1.0.0-rc6.7.yml) | [1.0.0](swagger-apis/unarranged-accounts-overdraft/1.0.0.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.0-rc6.7_1.0.0.yml) |
|  | [1.0.0](swagger-apis/unarranged-accounts-overdraft/1.0.0.yml) | [1.0.2](swagger-apis/unarranged-accounts-overdraft/1.0.2.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.0_1.0.2.yml) |
|  | [1.0.2](swagger-apis/unarranged-accounts-overdraft/1.0.2.yml) | [1.0.3](swagger-apis/unarranged-accounts-overdraft/1.0.3.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.2_1.0.3.yml) |
|  | [1.0.3](swagger-apis/unarranged-accounts-overdraft/1.0.3.yml) | [1.0.4](swagger-apis/unarranged-accounts-overdraft/1.0.4.yml) | [YAML](diffs/unarranged-accounts-overdraft/1.0.3_1.0.4.yml) |
