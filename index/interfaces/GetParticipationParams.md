[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / GetParticipationParams

# Interface: GetParticipationParams

Defined in: [modules/user/user.types.ts:36](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/user/user.types.ts#L36)

Parameters for querying user participation statistics.

## Example

```ts
const params: GetParticipationParams = {
  address: userAddress
};
const result = await userService.getParticipation(params);
```

## Properties

### address

> **address**: `string`

Defined in: [modules/user/user.types.ts:38](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/user/user.types.ts#L38)

User's Stellar public key address to query
