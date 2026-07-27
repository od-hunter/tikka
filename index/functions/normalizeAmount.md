[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / normalizeAmount

# Function: normalizeAmount()

> **normalizeAmount**(`amount`, `decimals?`): `string`

Defined in: [utils/formatting.ts:232](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/utils/formatting.ts#L232)

Normalizes an amount to a fixed-decimal string without converting to stroops.
Useful for logging, display, or metadata.

## Parameters

### amount

`string` \| `number`

Amount string or safe integer.

### decimals?

`number` = `7`

Number of decimal places (default: 7 for XLM).

## Returns

`string`
