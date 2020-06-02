[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["augment/tx"](../modules/_augment_tx_.md) › ["api/types/submittable"](../modules/_augment_tx_._api_types_submittable_.md) › [SubmittableExtrinsics](_augment_tx_._api_types_submittable_.submittableextrinsics.md)

# Interface: SubmittableExtrinsics <**ApiType**>

## Type parameters

▪ **ApiType**: *[ApiTypes](../modules/_types_base_.md#apitypes)*

## Hierarchy

* [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md)‹ApiType›

  ↳ **SubmittableExtrinsics**

## Callable

▸ (`extrinsic`: Call | Extrinsic | Uint8Array | string): *SubmittableExtrinsic‹ApiType›*

*Defined in [api/src/augment/tx.ts:3210](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L3210)*

**Parameters:**

Name | Type |
------ | ------ |
`extrinsic` | Call &#124; Extrinsic &#124; Uint8Array &#124; string |

**Returns:** *SubmittableExtrinsic‹ApiType›*

## Indexable

* \[ **index**: *string*\]: [SubmittableModuleExtrinsics](_types_submittable_.submittablemoduleextrinsics.md)‹ApiType›

## Index

### Properties

* [authorship](_augment_tx_._api_types_submittable_.submittableextrinsics.md#authorship)
* [balances](_augment_tx_._api_types_submittable_.submittableextrinsics.md#balances)
* [contracts](_augment_tx_._api_types_submittable_.submittableextrinsics.md#contracts)
* [council](_augment_tx_._api_types_submittable_.submittableextrinsics.md#council)
* [democracy](_augment_tx_._api_types_submittable_.submittableextrinsics.md#democracy)
* [elections](_augment_tx_._api_types_submittable_.submittableextrinsics.md#elections)
* [finalityTracker](_augment_tx_._api_types_submittable_.submittableextrinsics.md#finalitytracker)
* [grandpa](_augment_tx_._api_types_submittable_.submittableextrinsics.md#grandpa)
* [identity](_augment_tx_._api_types_submittable_.submittableextrinsics.md#identity)
* [imOnline](_augment_tx_._api_types_submittable_.submittableextrinsics.md#imonline)
* [indices](_augment_tx_._api_types_submittable_.submittableextrinsics.md#indices)
* [recovery](_augment_tx_._api_types_submittable_.submittableextrinsics.md#recovery)
* [scheduler](_augment_tx_._api_types_submittable_.submittableextrinsics.md#scheduler)
* [session](_augment_tx_._api_types_submittable_.submittableextrinsics.md#session)
* [society](_augment_tx_._api_types_submittable_.submittableextrinsics.md#society)
* [staking](_augment_tx_._api_types_submittable_.submittableextrinsics.md#staking)
* [sudo](_augment_tx_._api_types_submittable_.submittableextrinsics.md#sudo)
* [system](_augment_tx_._api_types_submittable_.submittableextrinsics.md#system)
* [technicalCommittee](_augment_tx_._api_types_submittable_.submittableextrinsics.md#technicalcommittee)
* [technicalMembership](_augment_tx_._api_types_submittable_.submittableextrinsics.md#technicalmembership)
* [timestamp](_augment_tx_._api_types_submittable_.submittableextrinsics.md#timestamp)
* [treasury](_augment_tx_._api_types_submittable_.submittableextrinsics.md#treasury)
* [utility](_augment_tx_._api_types_submittable_.submittableextrinsics.md#utility)
* [vesting](_augment_tx_._api_types_submittable_.submittableextrinsics.md#vesting)

## Properties

###  authorship

• **authorship**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[authorship](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#authorship)*

*Defined in [api/src/augment/tx.ts:27](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L27)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **setUncles**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  balances

• **balances**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[balances](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#balances)*

*Defined in [api/src/augment/tx.ts:34](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L34)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **forceTransfer**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setBalance**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **transfer**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **transferKeepAlive**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  contracts

• **contracts**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[contracts](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#contracts)*

*Defined in [api/src/augment/tx.ts:111](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L111)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **call**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **claimSurcharge**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **instantiate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **putCode**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **updateSchedule**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  council

• **council**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[council](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#council)*

*Defined in [api/src/augment/tx.ts:156](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L156)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **close**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **execute**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **propose**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setMembers**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  democracy

• **democracy**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[democracy](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#democracy)*

*Defined in [api/src/augment/tx.ts:274](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L274)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **activateProxy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelQueued**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelReferendum**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **clearPublicProposals**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **closeProxy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **deactivateProxy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **delegate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **emergencyCancel**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **enactProposal**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **externalPropose**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **externalProposeDefault**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **externalProposeMajority**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **fastTrack**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **noteImminentPreimage**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **noteImminentPreimageOperational**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **notePreimage**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **notePreimageOperational**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **openProxy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **propose**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **proxyDelegate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **proxyRemoveVote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **proxyUndelegate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **proxyVote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **reapPreimage**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **removeOtherVote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **removeVote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **second**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **undelegate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **unlock**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vetoExternal**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  elections

• **elections**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[elections](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#elections)*

*Defined in [api/src/augment/tx.ts:840](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L840)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **removeMember**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **removeVoter**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **renounceCandidacy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **reportDefunctVoter**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **submitCandidacy**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  finalityTracker

• **finalityTracker**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[finalityTracker](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#finalitytracker)*

*Defined in [api/src/augment/tx.ts:1003](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1003)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **finalHint**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  grandpa

• **grandpa**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[grandpa](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#grandpa)*

*Defined in [api/src/augment/tx.ts:1011](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1011)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **reportEquivocation**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  identity

• **identity**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[identity](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#identity)*

*Defined in [api/src/augment/tx.ts:1025](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1025)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **addRegistrar**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelRequest**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **clearIdentity**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **killIdentity**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **provideJudgement**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **requestJudgement**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setAccountId**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setFee**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setFields**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setIdentity**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setSubs**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  imOnline

• **imOnline**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[imOnline](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#imonline)*

*Defined in [api/src/augment/tx.ts:1249](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1249)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **heartbeat**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  indices

• **indices**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[indices](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#indices)*

*Defined in [api/src/augment/tx.ts:1265](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1265)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **claim**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **forceTransfer**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **free**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **transfer**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  recovery

• **recovery**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[recovery](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#recovery)*

*Defined in [api/src/augment/tx.ts:1344](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1344)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **asRecovered**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelRecovered**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **claimRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **closeRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **createRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **initiateRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **removeRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setRecovered**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vouchRecovery**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  scheduler

• **scheduler**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[scheduler](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#scheduler)*

*Defined in [api/src/augment/tx.ts:1546](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1546)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **cancel**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelNamed**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **schedule**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **scheduleNamed**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  session

• **session**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[session](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#session)*

*Defined in [api/src/augment/tx.ts:1601](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1601)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **purgeKeys**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setKeys**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  society

• **society**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[society](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#society)*

*Defined in [api/src/augment/tx.ts:1636](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1636)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **bid**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **defenderVote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **found**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **judgeSuspendedCandidate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **judgeSuspendedMember**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **payout**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setMaxMembers**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **unbid**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **unfound**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **unvouch**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vouch**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  staking

• **staking**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[staking](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#staking)*

*Defined in [api/src/augment/tx.ts:1956](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L1956)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **bond**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **bondExtra**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelDeferredSlash**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **chill**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **forceNewEra**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **forceNewEraAlways**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **forceNoEras**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **forceUnstake**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **nominate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **payoutNominator**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **payoutStakers**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **payoutValidator**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **reapStash**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **rebond**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setController**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setHistoryDepth**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setInvulnerables**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setPayee**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setValidatorCount**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **submitElectionSolution**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **submitElectionSolutionUnsigned**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **unbond**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **validate**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **withdrawUnbonded**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  sudo

• **sudo**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[sudo](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#sudo)*

*Defined in [api/src/augment/tx.ts:2471](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2471)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **setKey**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **sudo**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **sudoAs**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **sudoUncheckedWeight**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  system

• **system**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[system](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#system)*

*Defined in [api/src/augment/tx.ts:2526](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2526)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **fillBlock**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **killPrefix**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **killStorage**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **remark**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setChangesTrieConfig**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setCode**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setCodeWithoutChecks**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setHeapPages**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setStorage**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **suicide**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  technicalCommittee

• **technicalCommittee**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[technicalCommittee](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#technicalcommittee)*

*Defined in [api/src/augment/tx.ts:2640](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2640)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **close**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **execute**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **propose**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setMembers**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vote**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  technicalMembership

• **technicalMembership**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[technicalMembership](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#technicalmembership)*

*Defined in [api/src/augment/tx.ts:2758](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2758)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **addMember**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **changeKey**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **clearPrime**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **removeMember**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **resetMembers**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **setPrime**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **swapMember**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  timestamp

• **timestamp**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[timestamp](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#timestamp)*

*Defined in [api/src/augment/tx.ts:2804](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2804)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **set**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  treasury

• **treasury**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[treasury](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#treasury)*

*Defined in [api/src/augment/tx.ts:2828](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2828)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **approveProposal**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **closeTip**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **proposeSpend**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **rejectProposal**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **reportAwesome**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **retractTip**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **tip**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **tipNew**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  utility

• **utility**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[utility](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#utility)*

*Defined in [api/src/augment/tx.ts:2981](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L2981)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **approveAsMulti**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **asMulti**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **asSub**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **batch**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **cancelAsMulti**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

___

###  vesting

• **vesting**: *object*

*Inherited from [AugmentedSubmittables](_augment_tx_._api_types_submittable_.augmentedsubmittables.md).[vesting](_augment_tx_._api_types_submittable_.augmentedsubmittables.md#vesting)*

*Defined in [api/src/augment/tx.ts:3142](https://github.com/polkadot-js/api/blob/6e83e6aaef/packages/api/src/augment/tx.ts#L3142)*

#### Type declaration:

* \[ **index**: *string*\]: [SubmittableExtrinsicFunction](_types_submittable_.submittableextrinsicfunction.md)‹ApiType›

* **vest**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vestOther**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*

* **vestedTransfer**: *[AugmentedSubmittable](../modules/_types_submittable_.md#augmentedsubmittable)‹function›*