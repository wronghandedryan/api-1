[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["rx/RxBlueprint"](../modules/_rx_rxblueprint_.md) › [RxBlueprint](_rx_rxblueprint_.rxblueprint.md)

# Class: RxBlueprint

## Hierarchy

  ↳ [Blueprint](_base_blueprint_.blueprint.md)‹"rxjs"›

  ↳ **RxBlueprint**

## Implements

* ContractBase‹"rxjs"›

## Index

### Constructors

* [constructor](_rx_rxblueprint_.rxblueprint.md#constructor)

### Properties

* [abi](_rx_rxblueprint_.rxblueprint.md#abi)
* [api](_rx_rxblueprint_.rxblueprint.md#api)
* [codeHash](_rx_rxblueprint_.rxblueprint.md#codehash)
* [decorateMethod](_rx_rxblueprint_.rxblueprint.md#decoratemethod)
* [registry](_rx_rxblueprint_.rxblueprint.md#registry)

### Accessors

* [messages](_rx_rxblueprint_.rxblueprint.md#messages)

### Methods

* [deployContract](_rx_rxblueprint_.rxblueprint.md#deploycontract)
* [getMessage](_rx_rxblueprint_.rxblueprint.md#getmessage)

## Constructors

###  constructor

\+ **new RxBlueprint**(`api`: ApiRx, `abi`: ContractABIPre | Abi, `codeHash`: string | Hash): *[RxBlueprint](_rx_rxblueprint_.rxblueprint.md)*

*Overrides [Blueprint](_base_blueprint_.blueprint.md).[constructor](_base_blueprint_.blueprint.md#constructor)*

*Defined in [rx/RxBlueprint.ts:14](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/rx/RxBlueprint.ts#L14)*

**Parameters:**

Name | Type |
------ | ------ |
`api` | ApiRx |
`abi` | ContractABIPre &#124; Abi |
`codeHash` | string &#124; Hash |

**Returns:** *[RxBlueprint](_rx_rxblueprint_.rxblueprint.md)*

## Properties

###  abi

• **abi**: *Abi*

*Inherited from [Base](_base_util_.base.md).[abi](_base_util_.base.md#abi)*

*Defined in [base/util.ts:14](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L14)*

___

###  api

• **api**: *ApiObject‹"rxjs"›*

*Inherited from [Base](_base_util_.base.md).[api](_base_util_.base.md#api)*

*Defined in [base/util.ts:16](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L16)*

___

###  codeHash

• **codeHash**: *Hash*

*Inherited from [Blueprint](_base_blueprint_.blueprint.md).[codeHash](_base_blueprint_.blueprint.md#codehash)*

*Defined in [base/Blueprint.ts:38](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/Blueprint.ts#L38)*

___

###  decorateMethod

• **decorateMethod**: *DecorateMethod‹"rxjs"›*

*Inherited from [Base](_base_util_.base.md).[decorateMethod](_base_util_.base.md#decoratemethod)*

*Defined in [base/util.ts:18](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L18)*

___

###  registry

• **registry**: *Registry*

*Inherited from [Base](_base_util_.base.md).[registry](_base_util_.base.md#registry)*

*Defined in [base/util.ts:20](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L20)*

## Accessors

###  messages

• **get messages**(): *ContractMessage[]*

*Inherited from [Base](_base_util_.base.md).[messages](_base_util_.base.md#messages)*

*Defined in [base/util.ts:31](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L31)*

**Returns:** *ContractMessage[]*

## Methods

###  deployContract

▸ **deployContract**(`constructorIndex`: number, `endowment`: number | BN, `maxGas`: number | BN, ...`params`: any[]): *[BlueprintCreate](../interfaces/_base_blueprint_.blueprintcreate.md)‹"rxjs"›*

*Inherited from [Blueprint](_base_blueprint_.blueprint.md).[deployContract](_base_blueprint_.blueprint.md#deploycontract)*

*Defined in [base/Blueprint.ts:46](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/Blueprint.ts#L46)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`constructorIndex` | number | 0 |
`endowment` | number &#124; BN | - |
`maxGas` | number &#124; BN | - |
`...params` | any[] | - |

**Returns:** *[BlueprintCreate](../interfaces/_base_blueprint_.blueprintcreate.md)‹"rxjs"›*

___

###  getMessage

▸ **getMessage**(`nameOrIndex?`: string | number): *ContractMessage*

*Inherited from [Base](_base_util_.base.md).[getMessage](_base_util_.base.md#getmessage)*

*Defined in [base/util.ts:42](https://github.com/polkadot-js/api/blob/859800280/packages/api-contract/src/base/util.ts#L42)*

**Parameters:**

Name | Type |
------ | ------ |
`nameOrIndex?` | string &#124; number |

**Returns:** *ContractMessage*