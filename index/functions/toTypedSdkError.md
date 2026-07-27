[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / toTypedSdkError

# Function: toTypedSdkError()

> **toTypedSdkError**(`err`): [`TikkaSdkError`](../classes/TikkaSdkError.md)

Defined in: [utils/errors.ts:295](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/utils/errors.ts#L295)

Upgrades a generic caught error into the most specific `TikkaSdkError`
subtype possible. If `err` is already a `TikkaSdkError` with code
`ContractError` and a string `cause` containing a recognizable Soroban
error code, it is converted into the matching typed error. Otherwise the
error is returned unchanged (if already a `TikkaSdkError`) or wrapped.

## Parameters

### err

`unknown`

## Returns

[`TikkaSdkError`](../classes/TikkaSdkError.md)
