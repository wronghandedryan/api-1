[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["primitive/Bytes"](../modules/_primitive_bytes_.md) › [Bytes](_primitive_bytes_.bytes.md)

# Class: Bytes

**`name`** Bytes

**`description`** 
A Bytes wrapper for Vec<u8>. The significant difference between this and a normal Uint8Array
is that this version allows for length-encoding. (i.e. it is a variable-item codec, the same
as what is found in [Text](_primitive_text_.text.md) and [Vec](_codec_vec_.vec.md))

## Hierarchy

  ↳ [Raw](_codec_raw_.raw.md)

  ↳ **Bytes**

  ↳ [StorageKey](_primitive_storagekey_.storagekey.md)

## Implements

* [IU8a](../interfaces/_types_interfaces_.iu8a.md)

## Indexable

* \[ **index**: *number*\]: number

## Index

### Constructors

* [constructor](_primitive_bytes_.bytes.md#constructor)

### Properties

* [registry](_primitive_bytes_.bytes.md#registry)

### Accessors

* [encodedLength](_primitive_bytes_.bytes.md#encodedlength)
* [hash](_primitive_bytes_.bytes.md#hash)
* [isEmpty](_primitive_bytes_.bytes.md#isempty)
* [length](_primitive_bytes_.bytes.md#length)

### Methods

* [bitLength](_primitive_bytes_.bytes.md#bitlength)
* [eq](_primitive_bytes_.bytes.md#eq)
* [subarray](_primitive_bytes_.bytes.md#subarray)
* [toHex](_primitive_bytes_.bytes.md#tohex)
* [toHuman](_primitive_bytes_.bytes.md#tohuman)
* [toJSON](_primitive_bytes_.bytes.md#tojson)
* [toRawType](_primitive_bytes_.bytes.md#torawtype)
* [toString](_primitive_bytes_.bytes.md#tostring)
* [toU8a](_primitive_bytes_.bytes.md#tou8a)

## Constructors

###  constructor

\+ **new Bytes**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `value?`: [AnyU8a](../modules/_types_helpers_.md#anyu8a)): *[Bytes](_primitive_bytes_.bytes.md)*

*Overrides [Raw](_codec_raw_.raw.md).[constructor](_codec_raw_.raw.md#constructor)*

*Defined in [packages/types/src/primitive/Bytes.ts:47](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/primitive/Bytes.ts#L47)*

**Parameters:**

Name | Type |
------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) |
`value?` | [AnyU8a](../modules/_types_helpers_.md#anyu8a) |

**Returns:** *[Bytes](_primitive_bytes_.bytes.md)*

## Properties

###  registry

• **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md).[registry](../interfaces/_types_interfaces_.iu8a.md#registry)*

*Inherited from [Raw](_codec_raw_.raw.md).[registry](_codec_raw_.raw.md#registry)*

*Defined in [packages/types/src/codec/Raw.ts:30](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L30)*

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Overrides [Raw](_codec_raw_.raw.md).[encodedLength](_codec_raw_.raw.md#encodedlength)*

*Defined in [packages/types/src/primitive/Bytes.ts:55](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/primitive/Bytes.ts#L55)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Inherited from [Raw](_codec_raw_.raw.md).[hash](_codec_raw_.raw.md#hash)*

*Defined in [packages/types/src/codec/Raw.ts:48](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L48)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Inherited from [Raw](_codec_raw_.raw.md).[isEmpty](_codec_raw_.raw.md#isempty)*

*Defined in [packages/types/src/codec/Raw.ts:55](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L55)*

**`description`** Returns true if the type wraps an empty/default all-0 value

**Returns:** *boolean*

___

###  length

• **get length**(): *number*

*Inherited from [Raw](_codec_raw_.raw.md).[length](_codec_raw_.raw.md#length)*

*Overrides [IU8a](../interfaces/_types_interfaces_.iu8a.md).[length](../interfaces/_types_interfaces_.iu8a.md#length)*

*Defined in [packages/types/src/codec/Raw.ts:62](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L62)*

**`description`** The length of the value

**Returns:** *number*

## Methods

###  bitLength

▸ **bitLength**(): *number*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md)*

*Inherited from [Raw](_codec_raw_.raw.md).[bitLength](_codec_raw_.raw.md#bitlength)*

*Defined in [packages/types/src/codec/Raw.ts:70](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L70)*

**`description`** Returns the number of bits in the value

**Returns:** *number*

___

###  eq

▸ **eq**(`other?`: any): *boolean*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md)*

*Inherited from [Raw](_codec_raw_.raw.md).[eq](_codec_raw_.raw.md#eq)*

*Defined in [packages/types/src/codec/Raw.ts:77](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L77)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | any |

**Returns:** *boolean*

___

###  subarray

▸ **subarray**(`begin`: number, `end?`: undefined | number): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Inherited from [Raw](_codec_raw_.raw.md).[subarray](_codec_raw_.raw.md#subarray)*

*Overrides [IU8a](../interfaces/_types_interfaces_.iu8a.md).[subarray](../interfaces/_types_interfaces_.iu8a.md#subarray)*

*Defined in [packages/types/src/codec/Raw.ts:91](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L91)*

**`description`** Create a new subarray from the actual buffer. This is needed for compat reasons since a new Uint8Array gets returned here

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`begin` | number | The position to start at |
`end?` | undefined &#124; number | The position to end at  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

___

###  toHex

▸ **toHex**(): *string*

*Inherited from [Raw](_codec_raw_.raw.md).[toHex](_codec_raw_.raw.md#tohex)*

*Defined in [packages/types/src/codec/Raw.ts:98](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L98)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(): *[AnyJson](../modules/_types_helpers_.md#anyjson)*

*Inherited from [Raw](_codec_raw_.raw.md).[toHuman](_codec_raw_.raw.md#tohuman)*

*Defined in [packages/types/src/codec/Raw.ts:105](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L105)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Returns:** *[AnyJson](../modules/_types_helpers_.md#anyjson)*

___

###  toJSON

▸ **toJSON**(): *string*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md)*

*Inherited from [Raw](_codec_raw_.raw.md).[toJSON](_codec_raw_.raw.md#tojson)*

*Defined in [packages/types/src/codec/Raw.ts:112](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L112)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *string*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md)*

*Overrides [Raw](_codec_raw_.raw.md).[toRawType](_codec_raw_.raw.md#torawtype)*

*Defined in [packages/types/src/primitive/Bytes.ts:62](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/primitive/Bytes.ts#L62)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [IU8a](../interfaces/_types_interfaces_.iu8a.md)*

*Inherited from [Raw](_codec_raw_.raw.md).[toString](_codec_raw_.raw.md#tostring)*

*Overrides [IU8a](../interfaces/_types_interfaces_.iu8a.md).[toString](../interfaces/_types_interfaces_.iu8a.md#tostring)*

*Defined in [packages/types/src/codec/Raw.ts:126](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/codec/Raw.ts#L126)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Overrides [Raw](_codec_raw_.raw.md).[toU8a](_codec_raw_.raw.md#tou8a)*

*Defined in [packages/types/src/primitive/Bytes.ts:70](https://github.com/polkadot-js/api/blob/370dc8681/packages/types/src/primitive/Bytes.ts#L70)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*