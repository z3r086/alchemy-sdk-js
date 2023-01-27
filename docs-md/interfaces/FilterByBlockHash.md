[alchemy-sdk](../README.md) / [Exports](../modules.md) / FilterByBlockHash

# Interface: FilterByBlockHash

Filter object used to filter logs by a specific block hash when using
[CoreNamespace.getLogs](../classes/CoreNamespace.md#getlogs).

## Hierarchy

- [`EventFilter`](EventFilter.md)

  ↳ **`FilterByBlockHash`**

## Table of contents

### Properties

- [address](FilterByBlockHash.md#address)
- [blockHash](FilterByBlockHash.md#blockhash)
- [topics](FilterByBlockHash.md#topics)

## Properties

### address

• `Optional` **address**: `string` \| `string`[]

The address to filter by. If omitted, filters for all addresses.

#### Inherited from

[EventFilter](EventFilter.md).[address](EventFilter.md#address)

#### Defined in

[src/types/types.ts:2293](https://github.com/alchemyplatform/alchemy-sdk-js/blob/bed7d71/src/types/types.ts#L2293)

___

### blockHash

• `Optional` **blockHash**: `string`

The specific block hash to search for logs matching the filter.

#### Defined in

[src/types/types.ts:2274](https://github.com/alchemyplatform/alchemy-sdk-js/blob/bed7d71/src/types/types.ts#L2274)

___

### topics

• `Optional` **topics**: (``null`` \| `string` \| `string`[])[]

The topics to filter by, or null to match any topics.

#### Inherited from

[EventFilter](EventFilter.md).[topics](EventFilter.md#topics)

#### Defined in

[src/types/types.ts:2295](https://github.com/alchemyplatform/alchemy-sdk-js/blob/bed7d71/src/types/types.ts#L2295)