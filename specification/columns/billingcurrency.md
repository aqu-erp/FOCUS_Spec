# Billing Currency

Billing Currency is an identifier that represents the currency that a charge for resources or [*services*](#glossary:service) was billed in. Billing Currency is commonly used in scenarios where costs need to be grouped or aggregated.

The BillingCurrency column MUST be present in the billing data. BillingCurrency MUST match the currency used in the invoice generated by the invoice issuer. This column MUST be of type String and MUST NOT contain null values. BillingCurrency MUST conform to [Currency Code Format](#currencycodeformat) requirements.

## Column ID

BillingCurrency

## Display name

Billing Currency

## Description

Represents the currency that a charge was billed in.

## Content Constraints

| Constraint      | Value                               |
|:----------------|:------------------------------------|
| Column type     | Dimension                           |
| Column required | True                                |
| Allows nulls    | False                               |
| Data type       | String                              |
| Value format    | [Currency Code Format](#currencycodeformat) |

## Introduced (version)

0.5
