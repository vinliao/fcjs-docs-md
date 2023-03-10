[@farcaster/js](../README.md) / [Exports](../modules.md) / types

# Namespace: types

## Table of contents

### References

- [FarcasterNetwork](types.md#farcasternetwork)
- [HashScheme](types.md#hashscheme)
- [MessageType](types.md#messagetype)
- [ReactionType](types.md#reactiontype)
- [SignatureScheme](types.md#signaturescheme)
- [UserDataType](types.md#userdatatype)

### Type Aliases

- [AmpAddData](types.md#ampadddata)
- [AmpAddMessage](types.md#ampaddmessage)
- [AmpBody](types.md#ampbody)
- [AmpRemoveData](types.md#ampremovedata)
- [AmpRemoveMessage](types.md#ampremovemessage)
- [CastAddBody](types.md#castaddbody)
- [CastAddData](types.md#castadddata)
- [CastAddMessage](types.md#castaddmessage)
- [CastId](types.md#castid)
- [CastRemoveBody](types.md#castremovebody)
- [CastRemoveData](types.md#castremovedata)
- [CastRemoveMessage](types.md#castremovemessage)
- [EventResponse](types.md#eventresponse)
- [IdRegistryEvent](types.md#idregistryevent)
- [IdRegistryEventResponse](types.md#idregistryeventresponse)
- [Message](types.md#message)
- [MessageBody](types.md#messagebody)
- [MessageData](types.md#messagedata)
- [MessageEventResponse](types.md#messageeventresponse)
- [NameRegistryEvent](types.md#nameregistryevent)
- [NameRegistryEventResponse](types.md#nameregistryeventresponse)
- [ReactionAddData](types.md#reactionadddata)
- [ReactionAddMessage](types.md#reactionaddmessage)
- [ReactionBody](types.md#reactionbody)
- [ReactionRemoveData](types.md#reactionremovedata)
- [ReactionRemoveMessage](types.md#reactionremovemessage)
- [SignerAddData](types.md#signeradddata)
- [SignerAddMessage](types.md#signeraddmessage)
- [SignerBody](types.md#signerbody)
- [SignerRemoveData](types.md#signerremovedata)
- [SignerRemoveMessage](types.md#signerremovemessage)
- [UserDataAddData](types.md#userdataadddata)
- [UserDataAddMessage](types.md#userdataaddmessage)
- [UserDataBody](types.md#userdatabody)
- [VerificationAddEthAddressBody](types.md#verificationaddethaddressbody)
- [VerificationAddEthAddressData](types.md#verificationaddethaddressdata)
- [VerificationAddEthAddressMessage](types.md#verificationaddethaddressmessage)
- [VerificationEthAddressClaim](types.md#verificationethaddressclaim)
- [VerificationRemoveBody](types.md#verificationremovebody)
- [VerificationRemoveData](types.md#verificationremovedata)
- [VerificationRemoveMessage](types.md#verificationremovemessage)

## References

### FarcasterNetwork

Re-exports [FarcasterNetwork](../enums/protobufs.FarcasterNetwork.md)

___

### HashScheme

Re-exports [HashScheme](../enums/protobufs.HashScheme.md)

___

### MessageType

Re-exports [MessageType](../enums/protobufs.MessageType.md)

___

### ReactionType

Re-exports [ReactionType](../enums/protobufs.ReactionType.md)

___

### SignatureScheme

Re-exports [SignatureScheme](../enums/protobufs.SignatureScheme.md)

___

### UserDataType

Re-exports [UserDataType](../enums/protobufs.UserDataType.md)

## Type Aliases

### AmpAddData

?? **AmpAddData**: [`MessageData`](types.md#messagedata)<[`AmpBody`](types.md#ampbody), [`MESSAGE_TYPE_AMP_ADD`](../enums/protobufs.MessageType.md#message_type_amp_add)\>

#### Defined in

[src/types.ts:37](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L37)

___

### AmpAddMessage

?? **AmpAddMessage**: [`Message`](types.md#message)<[`AmpAddData`](types.md#ampadddata)\>

#### Defined in

[src/types.ts:54](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L54)

___

### AmpBody

?? **AmpBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `targetFid` | `number` |

#### Defined in

[src/types.ts:94](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L94)

___

### AmpRemoveData

?? **AmpRemoveData**: [`MessageData`](types.md#messagedata)<[`AmpBody`](types.md#ampbody), [`MESSAGE_TYPE_AMP_REMOVE`](../enums/protobufs.MessageType.md#message_type_amp_remove)\>

#### Defined in

[src/types.ts:38](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L38)

___

### AmpRemoveMessage

?? **AmpRemoveMessage**: [`Message`](types.md#message)<[`AmpRemoveData`](types.md#ampremovedata)\>

#### Defined in

[src/types.ts:55](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L55)

___

### CastAddBody

?? **CastAddBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `embeds?` | `string`[] |
| `mentions?` | `number`[] |
| `mentionsPositions?` | `number`[] |
| `parent?` | [`CastId`](types.md#castid) |
| `text` | `string` |

#### Defined in

[src/types.ts:77](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L77)

___

### CastAddData

?? **CastAddData**: [`MessageData`](types.md#messagedata)<[`CastAddBody`](types.md#castaddbody), [`MESSAGE_TYPE_CAST_ADD`](../enums/protobufs.MessageType.md#message_type_cast_add)\>

#### Defined in

[src/types.ts:32](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L32)

___

### CastAddMessage

?? **CastAddMessage**: [`Message`](types.md#message)<[`CastAddData`](types.md#castadddata)\>

#### Defined in

[src/types.ts:33](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L33)

___

### CastId

?? **CastId**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `fid` | `number` |
| `hash` | `string` |

#### Defined in

[src/types.ts:62](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L62)

___

### CastRemoveBody

?? **CastRemoveBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `targetHash` | `string` |

#### Defined in

[src/types.ts:85](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L85)

___

### CastRemoveData

?? **CastRemoveData**: [`MessageData`](types.md#messagedata)<[`CastRemoveBody`](types.md#castremovebody), [`MESSAGE_TYPE_CAST_REMOVE`](../enums/protobufs.MessageType.md#message_type_cast_remove)\>

#### Defined in

[src/types.ts:34](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L34)

___

### CastRemoveMessage

?? **CastRemoveMessage**: [`Message`](types.md#message)<[`CastRemoveData`](types.md#castremovedata)\>

#### Defined in

[src/types.ts:51](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L51)

___

### EventResponse

?? **EventResponse**: [`NameRegistryEventResponse`](types.md#nameregistryeventresponse) \| [`IdRegistryEventResponse`](types.md#idregistryeventresponse) \| [`MessageEventResponse`](types.md#messageeventresponse)

#### Defined in

[src/types.ts:166](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L166)

___

### IdRegistryEvent

?? **IdRegistryEvent**: `Readonly`<{ `_protobuf`: [`IdRegistryEvent`](protobufs.md#idregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `fid`: `number` ; `from`: `string` \| `undefined` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`IdRegistryEventType`](../enums/protobufs.IdRegistryEventType.md)  }\>

#### Defined in

[src/types.ts:117](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L117)

___

### IdRegistryEventResponse

?? **IdRegistryEventResponse**: `GenericEventResponse` & { `idRegistryEvent`: [`IdRegistryEvent`](types.md#idregistryevent) ; `type`: [`EVENT_TYPE_MERGE_ID_REGISTRY_EVENT`](../enums/protobufs.EventType.md#event_type_merge_id_registry_event)  }

#### Defined in

[src/types.ts:156](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L156)

___

### Message

?? **Message**<`TData`\>: `Readonly`<{ `_protobuf`: [`Message`](protobufs.md#message) ; `data`: `TData` ; `hash`: `string` ; `hashScheme`: [`HashScheme`](../enums/protobufs.HashScheme.md) ; `signature`: `string` ; `signatureScheme`: [`SignatureScheme`](../enums/protobufs.SignatureScheme.md) ; `signer`: `string`  }\>

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TData` | [`MessageData`](types.md#messagedata) |

#### Defined in

[src/types.ts:13](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L13)

___

### MessageBody

?? **MessageBody**: [`CastAddBody`](types.md#castaddbody) \| [`CastRemoveBody`](types.md#castremovebody) \| [`ReactionBody`](types.md#reactionbody) \| [`AmpBody`](types.md#ampbody) \| [`VerificationAddEthAddressBody`](types.md#verificationaddethaddressbody) \| [`VerificationRemoveBody`](types.md#verificationremovebody) \| [`SignerBody`](types.md#signerbody) \| [`UserDataBody`](types.md#userdatabody)

#### Defined in

[src/types.ts:67](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L67)

___

### MessageData

?? **MessageData**<`TBody`, `TType`\>: `Object`

#### Type parameters

| Name | Type |
| :------ | :------ |
| `TBody` | [`MessageBody`](types.md#messagebody) |
| `TType` | [`MessageType`](../enums/protobufs.MessageType.md) |

#### Type declaration

| Name | Type |
| :------ | :------ |
| `_protobuf` | [`MessageData`](protobufs.md#messagedata) |
| `body` | `TBody` |
| `fid` | `number` |
| `network` | [`FarcasterNetwork`](../enums/protobufs.FarcasterNetwork.md) |
| `timestamp` | `number` |
| `type` | `TType` |

#### Defined in

[src/types.ts:23](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L23)

___

### MessageEventResponse

?? **MessageEventResponse**: `GenericEventResponse` & { `deleted_messages?`: [`Message`](types.md#message)[] ; `message`: [`Message`](types.md#message) ; `type`: [`EVENT_TYPE_MERGE_MESSAGE`](../enums/protobufs.EventType.md#event_type_merge_message) \| [`EVENT_TYPE_PRUNE_MESSAGE`](../enums/protobufs.EventType.md#event_type_prune_message) \| [`EVENT_TYPE_REVOKE_MESSAGE`](../enums/protobufs.EventType.md#event_type_revoke_message)  }

#### Defined in

[src/types.ts:147](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L147)

___

### NameRegistryEvent

?? **NameRegistryEvent**: `Readonly`<{ `_protobuf`: [`NameRegistryEvent`](protobufs.md#nameregistryevent) ; `blockHash`: `string` ; `blockNumber`: `number` ; `expiry`: `number` \| `undefined` ; `fname`: `string` ; `from`: `string` ; `logIndex`: `number` ; `to`: `string` ; `transactionHash`: `string` ; `type`: [`NameRegistryEventType`](../enums/protobufs.NameRegistryEventType.md)  }\>

#### Defined in

[src/types.ts:129](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L129)

___

### NameRegistryEventResponse

?? **NameRegistryEventResponse**: `GenericEventResponse` & { `nameRegistryEvent`: [`NameRegistryEvent`](types.md#nameregistryevent) ; `type`: [`EVENT_TYPE_MERGE_NAME_REGISTRY_EVENT`](../enums/protobufs.EventType.md#event_type_merge_name_registry_event)  }

#### Defined in

[src/types.ts:161](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L161)

___

### ReactionAddData

?? **ReactionAddData**: [`MessageData`](types.md#messagedata)<[`ReactionBody`](types.md#reactionbody), [`MESSAGE_TYPE_REACTION_ADD`](../enums/protobufs.MessageType.md#message_type_reaction_add)\>

#### Defined in

[src/types.ts:35](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L35)

___

### ReactionAddMessage

?? **ReactionAddMessage**: [`Message`](types.md#message)<[`ReactionAddData`](types.md#reactionadddata)\>

#### Defined in

[src/types.ts:52](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L52)

___

### ReactionBody

?? **ReactionBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `target` | [`CastId`](types.md#castid) |
| `type` | [`ReactionType`](../enums/protobufs.ReactionType.md) |

#### Defined in

[src/types.ts:89](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L89)

___

### ReactionRemoveData

?? **ReactionRemoveData**: [`MessageData`](types.md#messagedata)<[`ReactionBody`](types.md#reactionbody), [`MESSAGE_TYPE_REACTION_REMOVE`](../enums/protobufs.MessageType.md#message_type_reaction_remove)\>

#### Defined in

[src/types.ts:36](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L36)

___

### ReactionRemoveMessage

?? **ReactionRemoveMessage**: [`Message`](types.md#message)<[`ReactionRemoveData`](types.md#reactionremovedata)\>

#### Defined in

[src/types.ts:53](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L53)

___

### SignerAddData

?? **SignerAddData**: [`MessageData`](types.md#messagedata)<[`SignerBody`](types.md#signerbody), [`MESSAGE_TYPE_SIGNER_ADD`](../enums/protobufs.MessageType.md#message_type_signer_add)\>

#### Defined in

[src/types.ts:47](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L47)

___

### SignerAddMessage

?? **SignerAddMessage**: [`Message`](types.md#message)<[`SignerAddData`](types.md#signeradddata)\>

#### Defined in

[src/types.ts:58](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L58)

___

### SignerBody

?? **SignerBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `signer` | `string` |

#### Defined in

[src/types.ts:108](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L108)

___

### SignerRemoveData

?? **SignerRemoveData**: [`MessageData`](types.md#messagedata)<[`SignerBody`](types.md#signerbody), [`MESSAGE_TYPE_SIGNER_REMOVE`](../enums/protobufs.MessageType.md#message_type_signer_remove)\>

#### Defined in

[src/types.ts:48](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L48)

___

### SignerRemoveMessage

?? **SignerRemoveMessage**: [`Message`](types.md#message)<[`SignerRemoveData`](types.md#signerremovedata)\>

#### Defined in

[src/types.ts:59](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L59)

___

### UserDataAddData

?? **UserDataAddData**: [`MessageData`](types.md#messagedata)<[`UserDataBody`](types.md#userdatabody), [`MESSAGE_TYPE_USER_DATA_ADD`](../enums/protobufs.MessageType.md#message_type_user_data_add)\>

#### Defined in

[src/types.ts:49](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L49)

___

### UserDataAddMessage

?? **UserDataAddMessage**: [`Message`](types.md#message)<[`UserDataAddData`](types.md#userdataadddata)\>

#### Defined in

[src/types.ts:60](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L60)

___

### UserDataBody

?? **UserDataBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `type` | [`UserDataType`](../enums/protobufs.UserDataType.md) |
| `value` | `string` |

#### Defined in

[src/types.ts:112](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L112)

___

### VerificationAddEthAddressBody

?? **VerificationAddEthAddressBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `blockHash` | `string` |
| `ethSignature` | `string` |

#### Defined in

[src/types.ts:98](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L98)

___

### VerificationAddEthAddressData

?? **VerificationAddEthAddressData**: [`MessageData`](types.md#messagedata)<[`VerificationAddEthAddressBody`](types.md#verificationaddethaddressbody), [`MESSAGE_TYPE_VERIFICATION_ADD_ETH_ADDRESS`](../enums/protobufs.MessageType.md#message_type_verification_add_eth_address)\>

#### Defined in

[src/types.ts:39](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L39)

___

### VerificationAddEthAddressMessage

?? **VerificationAddEthAddressMessage**: [`Message`](types.md#message)<[`VerificationAddEthAddressData`](types.md#verificationaddethaddressdata)\>

#### Defined in

[src/types.ts:56](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L56)

___

### VerificationEthAddressClaim

?? **VerificationEthAddressClaim**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `address` | `string` |
| `blockHash` | `string` |
| `fid` | `BigNumber` |
| `network` | [`FarcasterNetwork`](../enums/protobufs.FarcasterNetwork.md) |

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:81

___

### VerificationRemoveBody

?? **VerificationRemoveBody**: `Object`

#### Type declaration

| Name | Type |
| :------ | :------ |
| `address` | `string` |

#### Defined in

[src/types.ts:104](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L104)

___

### VerificationRemoveData

?? **VerificationRemoveData**: [`MessageData`](types.md#messagedata)<[`VerificationRemoveBody`](types.md#verificationremovebody), [`MESSAGE_TYPE_VERIFICATION_REMOVE`](../enums/protobufs.MessageType.md#message_type_verification_remove)\>

#### Defined in

[src/types.ts:43](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L43)

___

### VerificationRemoveMessage

?? **VerificationRemoveMessage**: [`Message`](types.md#message)<[`VerificationRemoveData`](types.md#verificationremovedata)\>

#### Defined in

[src/types.ts:57](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/types.ts#L57)
