[**Tikka SDK v0.1.0**](../../README.md)

***

[Tikka SDK](../../modules.md) / [index](../README.md) / RaffleStateError

# Class: RaffleStateError

Defined in: [modules/raffle/raffle.types.ts:114](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/raffle/raffle.types.ts#L114)

Thrown when an operation is attempted in an invalid state.
E.g. calling `triggerDraw` on an already-finalized raffle.

## Extends

- `Error`

## Constructors

### Constructor

> **new RaffleStateError**(`raffleId`, `currentStatus`, `attempted`): `RaffleStateError`

Defined in: [modules/raffle/raffle.types.ts:115](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/raffle/raffle.types.ts#L115)

#### Parameters

##### raffleId

`number`

##### currentStatus

[`RaffleStatus`](../enumerations/RaffleStatus.md)

##### attempted

[`RaffleTransition`](../type-aliases/RaffleTransition.md)

#### Returns

`RaffleStateError`

#### Overrides

`Error.constructor`

## Properties

### attempted

> `readonly` **attempted**: [`RaffleTransition`](../type-aliases/RaffleTransition.md)

Defined in: [modules/raffle/raffle.types.ts:118](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/raffle/raffle.types.ts#L118)

***

### currentStatus

> `readonly` **currentStatus**: [`RaffleStatus`](../enumerations/RaffleStatus.md)

Defined in: [modules/raffle/raffle.types.ts:117](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/raffle/raffle.types.ts#L117)

***

### raffleId

> `readonly` **raffleId**: `number`

Defined in: [modules/raffle/raffle.types.ts:116](https://github.com/od-hunter/tikka/blob/6a6d2a13638807a2f53d6769ec3d617fd17ec2c4/sdk/src/modules/raffle/raffle.types.ts#L116)
