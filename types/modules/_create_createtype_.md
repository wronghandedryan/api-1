[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["create/createType"](_create_createtype_.md)

# External module: "create/createType"

## Index

### Functions

* [createType](_create_createtype_.md#createtype)
* [createTypeUnsafe](_create_createtype_.md#createtypeunsafe)

## Functions

###  createType

▸ **createType**<**K**>(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `type`: K, ...`params`: any[]): *InterfaceTypes[K]*

*Defined in [packages/types/src/create/createType.ts:76](https://github.com/polkadot-js/api/blob/859800280/packages/types/src/create/createType.ts#L76)*

Create an instance of a `type` with a given `params`.

**Type parameters:**

▪ **K**: *keyof InterfaceTypes*

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) | - |
`type` | K | A recognizable string representing the type to create an instance from |
`...params` | any[] | The value to instantiate the type with  |

**Returns:** *InterfaceTypes[K]*

___

###  createTypeUnsafe

▸ **createTypeUnsafe**<**T**, **K**>(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `type`: K, `params`: any[], `isPedantic?`: undefined | false | true): *T*

*Defined in [packages/types/src/create/createType.ts:60](https://github.com/polkadot-js/api/blob/859800280/packages/types/src/create/createType.ts#L60)*

**Type parameters:**

▪ **T**: *[Codec](../interfaces/_types_codec_.codec.md)*

▪ **K**: *string*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) | - |
`type` | K | - |
`params` | any[] | [] |
`isPedantic?` | undefined &#124; false &#124; true | - |

**Returns:** *T*