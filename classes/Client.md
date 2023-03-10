[@farcaster/js](../README.md) / [Exports](../modules.md) / Client

# Class: Client

## Table of contents

### Constructors

- [constructor](Client.md#constructor)

### Properties

- [\_grpcClient](Client.md#_grpcclient)

### Methods

- [getAllAmpMessagesByFid](Client.md#getallampmessagesbyfid)
- [getAllCastMessagesByFid](Client.md#getallcastmessagesbyfid)
- [getAllReactionMessagesByFid](Client.md#getallreactionmessagesbyfid)
- [getAllSignerMessagesByFid](Client.md#getallsignermessagesbyfid)
- [getAllUserDataMessagesByFid](Client.md#getalluserdatamessagesbyfid)
- [getAllVerificationMessagesByFid](Client.md#getallverificationmessagesbyfid)
- [getAmp](Client.md#getamp)
- [getAmpsByFid](Client.md#getampsbyfid)
- [getAmpsByUser](Client.md#getampsbyuser)
- [getCast](Client.md#getcast)
- [getCastsByFid](Client.md#getcastsbyfid)
- [getCastsByMention](Client.md#getcastsbymention)
- [getCastsByParent](Client.md#getcastsbyparent)
- [getIdRegistryEvent](Client.md#getidregistryevent)
- [getNameRegistryEvent](Client.md#getnameregistryevent)
- [getReaction](Client.md#getreaction)
- [getReactionsByCast](Client.md#getreactionsbycast)
- [getReactionsByFid](Client.md#getreactionsbyfid)
- [getSigner](Client.md#getsigner)
- [getSignersByFid](Client.md#getsignersbyfid)
- [getUserData](Client.md#getuserdata)
- [getUserDataByFid](Client.md#getuserdatabyfid)
- [getVerification](Client.md#getverification)
- [getVerificationsByFid](Client.md#getverificationsbyfid)
- [submitMessage](Client.md#submitmessage)
- [subscribe](Client.md#subscribe)

## Constructors

### constructor

• **new Client**(`address`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Defined in

[src/client.ts:42](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L42)

## Properties

### \_grpcClient

• **\_grpcClient**: `HubRpcClient`

#### Defined in

[src/client.ts:40](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L40)

## Methods

### getAllAmpMessagesByFid

▸ **getAllAmpMessagesByFid**(`fid`): `HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpRemoveData`](../modules/types.md#ampremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpRemoveData`](../modules/types.md#ampremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Defined in

[src/client.ts:221](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L221)

___

### getAllCastMessagesByFid

▸ **getAllCastMessagesByFid**(`fid`): `HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastRemoveData`](../modules/types.md#castremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastRemoveData`](../modules/types.md#castremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Defined in

[src/client.ts:216](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L216)

___

### getAllReactionMessagesByFid

▸ **getAllReactionMessagesByFid**(`fid`): `HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionRemoveData`](../modules/types.md#reactionremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionRemoveData`](../modules/types.md#reactionremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Defined in

[src/client.ts:226](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L226)

___

### getAllSignerMessagesByFid

▸ **getAllSignerMessagesByFid**(`fid`): `HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerRemoveData`](../modules/types.md#signerremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerRemoveData`](../modules/types.md#signerremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Defined in

[src/client.ts:240](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L240)

___

### getAllUserDataMessagesByFid

▸ **getAllUserDataMessagesByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:245](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L245)

___

### getAllVerificationMessagesByFid

▸ **getAllVerificationMessagesByFid**(`fid`): `HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationRemoveData`](../modules/types.md#verificationremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<(`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> \| `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationRemoveData`](../modules/types.md#verificationremovedata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>)[]\>

#### Defined in

[src/client.ts:233](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L233)

___

### getAmp

▸ **getAmp**(`fid`, `targetFid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `targetFid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:90](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L90)

___

### getAmpsByFid

▸ **getAmpsByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:95](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L95)

___

### getAmpsByUser

▸ **getAmpsByUser**(`targetFid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `targetFid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`AmpAddData`](../modules/types.md#ampadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:100](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L100)

___

### getCast

▸ **getCast**(`fid`, `hash`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `hash` | `string` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:58](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L58)

___

### getCastsByFid

▸ **getCastsByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:67](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L67)

___

### getCastsByMention

▸ **getCastsByMention**(`mentionFid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `mentionFid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:81](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L81)

___

### getCastsByParent

▸ **getCastsByParent**(`parent`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `parent` | [`CastId`](../modules/types.md#castid) |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`CastAddData`](../modules/types.md#castadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:72](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L72)

___

### getIdRegistryEvent

▸ **getIdRegistryEvent**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `fid`: `number` ; `from`: `undefined` \| `string` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`IdRegistryEventType`](../enums/protobufs.IdRegistryEventType.md)  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `fid`: `number` ; `from`: `undefined` \| `string` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`IdRegistryEventType`](../enums/protobufs.IdRegistryEventType.md)  }\>\>

#### Defined in

[src/client.ts:183](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L183)

___

### getNameRegistryEvent

▸ **getNameRegistryEvent**(`fname`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `expiry`: `undefined` \| `number` ; `fname`: `string` ; `from`: `string` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`NameRegistryEventType`](../enums/protobufs.NameRegistryEventType.md)  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fname` | `string` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `expiry`: `undefined` \| `number` ; `fname`: `string` ; `from`: `string` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`NameRegistryEventType`](../enums/protobufs.NameRegistryEventType.md)  }\>\>

#### Defined in

[src/client.ts:202](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L202)

___

### getReaction

▸ **getReaction**(`fid`, `type`, `cast`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `type` | [`ReactionType`](../enums/protobufs.ReactionType.md) |
| `cast` | [`CastId`](../modules/types.md#castid) |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:109](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L109)

___

### getReactionsByCast

▸ **getReactionsByCast**(`cast`, `type?`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `cast` | [`CastId`](../modules/types.md#castid) |
| `type?` | [`ReactionType`](../enums/protobufs.ReactionType.md) |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:135](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L135)

___

### getReactionsByFid

▸ **getReactionsByFid**(`fid`, `type?`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `type?` | [`ReactionType`](../enums/protobufs.ReactionType.md) |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`ReactionAddData`](../modules/types.md#reactionadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:127](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L127)

___

### getSigner

▸ **getSigner**(`fid`, `signer`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `signer` | `string` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:169](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L169)

___

### getSignersByFid

▸ **getSignersByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`SignerAddData`](../modules/types.md#signeradddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:178](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L178)

___

### getUserData

▸ **getUserData**(`fid`, `type`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `type` | [`UserDataType`](../enums/protobufs.UserDataType.md) |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:192](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L192)

___

### getUserDataByFid

▸ **getUserDataByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`UserDataAddData`](../modules/types.md#userdataadddata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:197](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L197)

___

### getVerification

▸ **getVerification**(`fid`, `address`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `address` | `string` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:151](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L151)

___

### getVerificationsByFid

▸ **getVerificationsByFid**(`fid`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `fid` | `number` |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`VerificationAddEthAddressData`](../modules/types.md#verificationaddethaddressdata) ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>[]\>

#### Defined in

[src/client.ts:160](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L160)

___

### submitMessage

▸ **submitMessage**(`message`): `HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`MessageData`](../modules/types.md#messagedata)<[`MessageBody`](../modules/types.md#messagebody), [`MessageType`](../enums/protobufs.MessageType.md)\> ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `message` | `Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`MessageData`](../modules/types.md#messagedata)<[`MessageBody`](../modules/types.md#messagebody), [`MessageType`](../enums/protobufs.MessageType.md)\> ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\> |

#### Returns

`HubAsyncResult`<`Readonly`<{ `_protobuf`: [`Message`](../modules/protobufs.md#message) ; `data`: [`MessageData`](../modules/types.md#messagedata)<[`MessageBody`](../modules/types.md#messagebody), [`MessageType`](../enums/protobufs.MessageType.md)\> ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>\>

#### Defined in

[src/client.ts:50](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L50)

___

### subscribe

▸ **subscribe**(`filters?`): `Promise`<`HubResult`<[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>\>\>

Data from this stream can be parsed using `deserializeEventResponse`.

#### Parameters

| Name | Type |
| :------ | :------ |
| `filters` | [`EventFilters`](../modules.md#eventfilters) |

#### Returns

`Promise`<`HubResult`<[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>\>\>

#### Defined in

[src/client.ts:257](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/client.ts#L257)
