# Resource Type

Resource Type describes the kind of resource the charge applies to.  A Resource Type is commonly used for scenarios like identifying cost changes in groups of similar resources and may include values like Virtual Machine, Data Warehouse, and Load Balancer.

The ResourceType column MUST be present within billing data.  This column MUST be of type String and MUST NOT be null when a corresponding [ResourceId](#resourceid) is not null.  When a corresponding ResourceId value is null, the ResourceType column value MUST also be null.  Providers MUST use a consistent value-format and a set of values for ResourceType values within their billing datasets.

## Column ID

ResourceType

## Display Name

Resource Type

## Description

The kind of resource the charge applies to.

## Content Constraints

|    Constraint   |      Value      |
|:----------------|:----------------|
| Column type     | Dimension       |
| Column required | True            |
| Allows nulls    | True            |
| Data type       | String          |
| Value format    | \<not specified> |

## Introduced (version)

1.0
