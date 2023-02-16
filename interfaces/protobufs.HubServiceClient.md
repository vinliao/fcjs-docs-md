[@farcaster/js](../README.md) / [Exports](../modules.md) / [protobufs](../modules/protobufs.md) / HubServiceClient

# Interface: HubServiceClient

[protobufs](../modules/protobufs.md).HubServiceClient

A generic gRPC client. Primarily useful as a base class for all generated
clients.

## Hierarchy

- [`Client`](../classes/protobufs.Client.md)

  ↳ **`HubServiceClient`**

## Table of contents

### Methods

- [close](protobufs.HubServiceClient.md#close)
- [getAllAmpMessagesByFid](protobufs.HubServiceClient.md#getallampmessagesbyfid)
- [getAllCastMessagesByFid](protobufs.HubServiceClient.md#getallcastmessagesbyfid)
- [getAllMessagesBySyncIds](protobufs.HubServiceClient.md#getallmessagesbysyncids)
- [getAllReactionMessagesByFid](protobufs.HubServiceClient.md#getallreactionmessagesbyfid)
- [getAllSignerMessagesByFid](protobufs.HubServiceClient.md#getallsignermessagesbyfid)
- [getAllSyncIdsByPrefix](protobufs.HubServiceClient.md#getallsyncidsbyprefix)
- [getAllUserDataMessagesByFid](protobufs.HubServiceClient.md#getalluserdatamessagesbyfid)
- [getAllVerificationMessagesByFid](protobufs.HubServiceClient.md#getallverificationmessagesbyfid)
- [getAmp](protobufs.HubServiceClient.md#getamp)
- [getAmpsByFid](protobufs.HubServiceClient.md#getampsbyfid)
- [getAmpsByUser](protobufs.HubServiceClient.md#getampsbyuser)
- [getCast](protobufs.HubServiceClient.md#getcast)
- [getCastsByFid](protobufs.HubServiceClient.md#getcastsbyfid)
- [getCastsByMention](protobufs.HubServiceClient.md#getcastsbymention)
- [getCastsByParent](protobufs.HubServiceClient.md#getcastsbyparent)
- [getChannel](protobufs.HubServiceClient.md#getchannel)
- [getFids](protobufs.HubServiceClient.md#getfids)
- [getIdRegistryEvent](protobufs.HubServiceClient.md#getidregistryevent)
- [getInfo](protobufs.HubServiceClient.md#getinfo)
- [getNameRegistryEvent](protobufs.HubServiceClient.md#getnameregistryevent)
- [getReaction](protobufs.HubServiceClient.md#getreaction)
- [getReactionsByCast](protobufs.HubServiceClient.md#getreactionsbycast)
- [getReactionsByFid](protobufs.HubServiceClient.md#getreactionsbyfid)
- [getSigner](protobufs.HubServiceClient.md#getsigner)
- [getSignersByFid](protobufs.HubServiceClient.md#getsignersbyfid)
- [getSyncMetadataByPrefix](protobufs.HubServiceClient.md#getsyncmetadatabyprefix)
- [getSyncSnapshotByPrefix](protobufs.HubServiceClient.md#getsyncsnapshotbyprefix)
- [getUserData](protobufs.HubServiceClient.md#getuserdata)
- [getUserDataByFid](protobufs.HubServiceClient.md#getuserdatabyfid)
- [getVerification](protobufs.HubServiceClient.md#getverification)
- [getVerificationsByFid](protobufs.HubServiceClient.md#getverificationsbyfid)
- [makeBidiStreamRequest](protobufs.HubServiceClient.md#makebidistreamrequest)
- [makeClientStreamRequest](protobufs.HubServiceClient.md#makeclientstreamrequest)
- [makeServerStreamRequest](protobufs.HubServiceClient.md#makeserverstreamrequest)
- [makeUnaryRequest](protobufs.HubServiceClient.md#makeunaryrequest)
- [submitIdRegistryEvent](protobufs.HubServiceClient.md#submitidregistryevent)
- [submitMessage](protobufs.HubServiceClient.md#submitmessage)
- [submitNameRegistryEvent](protobufs.HubServiceClient.md#submitnameregistryevent)
- [subscribe](protobufs.HubServiceClient.md#subscribe)
- [waitForReady](protobufs.HubServiceClient.md#waitforready)

## Methods

### close

▸ **close**(): `void`

#### Returns

`void`

#### Inherited from

[Client](../classes/protobufs.Client.md).[close](../classes/protobufs.Client.md#close)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:57

___

### getAllAmpMessagesByFid

▸ **getAllAmpMessagesByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4143

▸ **getAllAmpMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4144

▸ **getAllAmpMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4145

___

### getAllCastMessagesByFid

▸ **getAllCastMessagesByFid**(`request`, `callback`): `SurfaceCall`

Bulk Methods

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4137

▸ **getAllCastMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4138

▸ **getAllCastMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4139

___

### getAllMessagesBySyncIds

▸ **getAllMessagesBySyncIds**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SyncIds`](../modules/protobufs.md#syncids) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4162

▸ **getAllMessagesBySyncIds**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SyncIds`](../modules/protobufs.md#syncids) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4163

▸ **getAllMessagesBySyncIds**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SyncIds`](../modules/protobufs.md#syncids) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4164

___

### getAllReactionMessagesByFid

▸ **getAllReactionMessagesByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4140

▸ **getAllReactionMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4141

▸ **getAllReactionMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4142

___

### getAllSignerMessagesByFid

▸ **getAllSignerMessagesByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4149

▸ **getAllSignerMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4150

▸ **getAllSignerMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4151

___

### getAllSyncIdsByPrefix

▸ **getAllSyncIdsByPrefix**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`SyncIds`](../modules/protobufs.md#syncids)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4159

▸ **getAllSyncIdsByPrefix**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`SyncIds`](../modules/protobufs.md#syncids)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4160

▸ **getAllSyncIdsByPrefix**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`SyncIds`](../modules/protobufs.md#syncids)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4161

___

### getAllUserDataMessagesByFid

▸ **getAllUserDataMessagesByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4152

▸ **getAllUserDataMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4153

▸ **getAllUserDataMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4154

___

### getAllVerificationMessagesByFid

▸ **getAllVerificationMessagesByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4146

▸ **getAllVerificationMessagesByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4147

▸ **getAllVerificationMessagesByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4148

___

### getAmp

▸ **getAmp**(`request`, `callback`): `SurfaceCall`

Amps

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`AmpRequest`](../modules/protobufs.md#amprequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4097

▸ **getAmp**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`AmpRequest`](../modules/protobufs.md#amprequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4098

▸ **getAmp**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`AmpRequest`](../modules/protobufs.md#amprequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4099

___

### getAmpsByFid

▸ **getAmpsByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4100

▸ **getAmpsByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4101

▸ **getAmpsByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4102

___

### getAmpsByUser

▸ **getAmpsByUser**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4103

▸ **getAmpsByUser**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4104

▸ **getAmpsByUser**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4105

___

### getCast

▸ **getCast**(`request`, `callback`): `SurfaceCall`

Casts

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4074

▸ **getCast**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4075

▸ **getCast**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4076

___

### getCastsByFid

▸ **getCastsByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4077

▸ **getCastsByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4078

▸ **getCastsByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4079

___

### getCastsByMention

▸ **getCastsByMention**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4083

▸ **getCastsByMention**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4084

▸ **getCastsByMention**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4085

___

### getCastsByParent

▸ **getCastsByParent**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4080

▸ **getCastsByParent**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4081

▸ **getCastsByParent**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`CastId`](../modules/protobufs.md#castid) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4082

___

### getChannel

▸ **getChannel**(): `Channel`

#### Returns

`Channel`

#### Inherited from

[Client](../classes/protobufs.Client.md).[getChannel](../classes/protobufs.Client.md#getchannel)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:58

___

### getFids

▸ **getFids**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`FidsResponse`](../modules/protobufs.md#fidsresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4133

▸ **getFids**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`FidsResponse`](../modules/protobufs.md#fidsresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4134

▸ **getFids**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`FidsResponse`](../modules/protobufs.md#fidsresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4135

___

### getIdRegistryEvent

▸ **getIdRegistryEvent**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4130

▸ **getIdRegistryEvent**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4131

▸ **getIdRegistryEvent**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4132

___

### getInfo

▸ **getInfo**(`request`, `callback`): `SurfaceCall`

Sync Methods

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`HubInfoResponse`](../modules/protobufs.md#hubinforesponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4156

▸ **getInfo**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`HubInfoResponse`](../modules/protobufs.md#hubinforesponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4157

▸ **getInfo**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Empty`](../modules/protobufs.md#empty) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`HubInfoResponse`](../modules/protobufs.md#hubinforesponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4158

___

### getNameRegistryEvent

▸ **getNameRegistryEvent**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEventRequest`](../modules/protobufs.md#nameregistryeventrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4113

▸ **getNameRegistryEvent**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEventRequest`](../modules/protobufs.md#nameregistryeventrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4114

▸ **getNameRegistryEvent**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEventRequest`](../modules/protobufs.md#nameregistryeventrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4115

___

### getReaction

▸ **getReaction**(`request`, `callback`): `SurfaceCall`

Reactions

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionRequest`](../modules/protobufs.md#reactionrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4087

▸ **getReaction**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionRequest`](../modules/protobufs.md#reactionrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4088

▸ **getReaction**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionRequest`](../modules/protobufs.md#reactionrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4089

___

### getReactionsByCast

▸ **getReactionsByCast**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByCastRequest`](../modules/protobufs.md#reactionsbycastrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4093

▸ **getReactionsByCast**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByCastRequest`](../modules/protobufs.md#reactionsbycastrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4094

▸ **getReactionsByCast**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByCastRequest`](../modules/protobufs.md#reactionsbycastrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4095

___

### getReactionsByFid

▸ **getReactionsByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByFidRequest`](../modules/protobufs.md#reactionsbyfidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4090

▸ **getReactionsByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByFidRequest`](../modules/protobufs.md#reactionsbyfidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4091

▸ **getReactionsByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`ReactionsByFidRequest`](../modules/protobufs.md#reactionsbyfidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4092

___

### getSigner

▸ **getSigner**(`request`, `callback`): `SurfaceCall`

Signer

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SignerRequest`](../modules/protobufs.md#signerrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4124

▸ **getSigner**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SignerRequest`](../modules/protobufs.md#signerrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4125

▸ **getSigner**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SignerRequest`](../modules/protobufs.md#signerrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4126

___

### getSignersByFid

▸ **getSignersByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4127

▸ **getSignersByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4128

▸ **getSignersByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4129

___

### getSyncMetadataByPrefix

▸ **getSyncMetadataByPrefix**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeMetadataResponse`](../modules/protobufs.md#trienodemetadataresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4165

▸ **getSyncMetadataByPrefix**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeMetadataResponse`](../modules/protobufs.md#trienodemetadataresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4166

▸ **getSyncMetadataByPrefix**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeMetadataResponse`](../modules/protobufs.md#trienodemetadataresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4167

___

### getSyncSnapshotByPrefix

▸ **getSyncSnapshotByPrefix**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeSnapshotResponse`](../modules/protobufs.md#trienodesnapshotresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4168

▸ **getSyncSnapshotByPrefix**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeSnapshotResponse`](../modules/protobufs.md#trienodesnapshotresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4169

▸ **getSyncSnapshotByPrefix**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`TrieNodePrefix`](../modules/protobufs.md#trienodeprefix) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`TrieNodeSnapshotResponse`](../modules/protobufs.md#trienodesnapshotresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4170

___

### getUserData

▸ **getUserData**(`request`, `callback`): `SurfaceCall`

User Data

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`UserDataRequest`](../modules/protobufs.md#userdatarequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4107

▸ **getUserData**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`UserDataRequest`](../modules/protobufs.md#userdatarequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4108

▸ **getUserData**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`UserDataRequest`](../modules/protobufs.md#userdatarequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4109

___

### getUserDataByFid

▸ **getUserDataByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4110

▸ **getUserDataByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4111

▸ **getUserDataByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4112

___

### getVerification

▸ **getVerification**(`request`, `callback`): `SurfaceCall`

Verifications

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`VerificationRequest`](../modules/protobufs.md#verificationrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4117

▸ **getVerification**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`VerificationRequest`](../modules/protobufs.md#verificationrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4118

▸ **getVerification**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`VerificationRequest`](../modules/protobufs.md#verificationrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4119

___

### getVerificationsByFid

▸ **getVerificationsByFid**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4120

▸ **getVerificationsByFid**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4121

▸ **getVerificationsByFid**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`FidRequest`](../modules/protobufs.md#fidrequest) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`MessagesResponse`](../modules/protobufs.md#messagesresponse)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4122

___

### makeBidiStreamRequest

▸ **makeBidiStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `options?`): `ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options?` | [`CallOptions`](protobufs.CallOptions.md) |

#### Returns

`ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeBidiStreamRequest](../classes/protobufs.Client.md#makebidistreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:72

▸ **makeBidiStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `options?`): `ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `options?` | [`CallOptions`](protobufs.CallOptions.md) |

#### Returns

`ClientDuplexStream`<`RequestType`, `ResponseType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeBidiStreamRequest](../classes/protobufs.Client.md#makebidistreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:73

___

### makeClientStreamRequest

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `options`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | [`CallOptions`](protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeClientStreamRequest](../classes/protobufs.Client.md#makeclientstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:65

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `metadata`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeClientStreamRequest](../classes/protobufs.Client.md#makeclientstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:66

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `options`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `options` | [`CallOptions`](protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeClientStreamRequest](../classes/protobufs.Client.md#makeclientstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:67

▸ **makeClientStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `callback`): `ClientWritableStream`<`RequestType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`ClientWritableStream`<`RequestType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeClientStreamRequest](../classes/protobufs.Client.md#makeclientstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:68

___

### makeServerStreamRequest

▸ **makeServerStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options?` | [`CallOptions`](protobufs.CallOptions.md) |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeServerStreamRequest](../classes/protobufs.Client.md#makeserverstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:70

▸ **makeServerStreamRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `options?` | [`CallOptions`](protobufs.CallOptions.md) |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<`ResponseType`\>

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeServerStreamRequest](../classes/protobufs.Client.md#makeserverstreamrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:71

___

### makeUnaryRequest

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | [`CallOptions`](protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeUnaryRequest](../classes/protobufs.Client.md#makeunaryrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:61

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `metadata`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeUnaryRequest](../classes/protobufs.Client.md#makeunaryrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:62

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `options`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `options` | [`CallOptions`](protobufs.CallOptions.md) |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeUnaryRequest](../classes/protobufs.Client.md#makeunaryrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:63

▸ **makeUnaryRequest**<`RequestType`, `ResponseType`\>(`method`, `serialize`, `deserialize`, `argument`, `callback`): `SurfaceCall`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `method` | `string` |
| `serialize` | (`value`: `RequestType`) => `Buffer` |
| `deserialize` | (`value`: `Buffer`) => `ResponseType` |
| `argument` | `RequestType` |
| `callback` | `UnaryCallback`<`ResponseType`\> |

#### Returns

`SurfaceCall`

#### Inherited from

[Client](../classes/protobufs.Client.md).[makeUnaryRequest](../classes/protobufs.Client.md#makeunaryrequest)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:64

___

### submitIdRegistryEvent

▸ **submitIdRegistryEvent**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4064

▸ **submitIdRegistryEvent**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4065

▸ **submitIdRegistryEvent**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`IdRegistryEvent`](../modules/protobufs.md#idregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4066

___

### submitMessage

▸ **submitMessage**(`request`, `callback`): `SurfaceCall`

Submit Methods

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Message`](../modules/protobufs.md#message) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4061

▸ **submitMessage**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Message`](../modules/protobufs.md#message) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4062

▸ **submitMessage**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`Message`](../modules/protobufs.md#message) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`Message`](../modules/protobufs.md#message)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4063

___

### submitNameRegistryEvent

▸ **submitNameRegistryEvent**(`request`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4067

▸ **submitNameRegistryEvent**(`request`, `metadata`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4068

▸ **submitNameRegistryEvent**(`request`, `metadata`, `options`, `callback`): `SurfaceCall`

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent) |
| `metadata` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |
| `callback` | (`error`: ``null`` \| [`ServiceError`](../modules/protobufs.md#serviceerror), `response`: [`NameRegistryEvent`](../modules/protobufs.md#nameregistryevent)) => `void` |

#### Returns

`SurfaceCall`

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4069

___

### subscribe

▸ **subscribe**(`request`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>

Event Methods

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SubscribeRequest`](../modules/protobufs.md#subscriberequest) |
| `options?` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4071

▸ **subscribe**(`request`, `metadata?`, `options?`): [`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `request` | [`SubscribeRequest`](../modules/protobufs.md#subscriberequest) |
| `metadata?` | [`Metadata`](../classes/protobufs.Metadata.md) |
| `options?` | `Partial`<[`CallOptions`](protobufs.CallOptions.md)\> |

#### Returns

[`ClientReadableStream`](../modules/protobufs.md#clientreadablestream)<[`EventResponse`](../modules/protobufs.md#eventresponse)\>

#### Defined in

node_modules/.pnpm/@farcaster+protobufs@0.1.4/node_modules/@farcaster/protobufs/dist/index.d.ts:4072

___

### waitForReady

▸ **waitForReady**(`deadline`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `deadline` | `Deadline` |
| `callback` | (`error?`: `Error`) => `void` |

#### Returns

`void`

#### Inherited from

[Client](../classes/protobufs.Client.md).[waitForReady](../classes/protobufs.Client.md#waitforready)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/client.d.ts:59
