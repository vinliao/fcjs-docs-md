[@farcaster/js](../README.md) / [Exports](../modules.md) / [protobufs](../modules/protobufs.md) / Server

# Class: Server

[protobufs](../modules/protobufs.md).Server

## Table of contents

### Constructors

- [constructor](protobufs.Server.md#constructor)

### Properties

- [\_channelzHandler](protobufs.Server.md#_channelzhandler)
- [\_respondWithError](protobufs.Server.md#_respondwitherror)
- [\_retrieveHandler](protobufs.Server.md#_retrievehandler)
- [\_runHandlerForCall](protobufs.Server.md#_runhandlerforcall)
- [\_setupHandlers](protobufs.Server.md#_setuphandlers)
- [\_streamHandler](protobufs.Server.md#_streamhandler)
- [\_verifyContentType](protobufs.Server.md#_verifycontenttype)
- [callTracker](protobufs.Server.md#calltracker)
- [channelzEnabled](protobufs.Server.md#channelzenabled)
- [channelzRef](protobufs.Server.md#channelzref)
- [channelzTrace](protobufs.Server.md#channelztrace)
- [getChannelzInfo](protobufs.Server.md#getchannelzinfo)
- [getChannelzSessionInfoGetter](protobufs.Server.md#getchannelzsessioninfogetter)
- [handlers](protobufs.Server.md#handlers)
- [http2ServerList](protobufs.Server.md#http2serverlist)
- [keepaliveTimeMs](protobufs.Server.md#keepalivetimems)
- [keepaliveTimeoutMs](protobufs.Server.md#keepalivetimeoutms)
- [listenerChildrenTracker](protobufs.Server.md#listenerchildrentracker)
- [maxConnectionAgeGraceMs](protobufs.Server.md#maxconnectionagegracems)
- [maxConnectionAgeMs](protobufs.Server.md#maxconnectionagems)
- [options](protobufs.Server.md#options)
- [serverAddressString](protobufs.Server.md#serveraddressstring)
- [sessionChildrenTracker](protobufs.Server.md#sessionchildrentracker)
- [sessions](protobufs.Server.md#sessions)
- [started](protobufs.Server.md#started)
- [trace](protobufs.Server.md#trace)

### Methods

- [addHttp2Port](protobufs.Server.md#addhttp2port)
- [addProtoService](protobufs.Server.md#addprotoservice)
- [addService](protobufs.Server.md#addservice)
- [bind](protobufs.Server.md#bind)
- [bindAsync](protobufs.Server.md#bindasync)
- [forceShutdown](protobufs.Server.md#forceshutdown)
- [getChannelzRef](protobufs.Server.md#getchannelzref)
- [register](protobufs.Server.md#register)
- [removeService](protobufs.Server.md#removeservice)
- [start](protobufs.Server.md#start)
- [tryShutdown](protobufs.Server.md#tryshutdown)
- [unregister](protobufs.Server.md#unregister)

## Constructors

### constructor

• **new Server**(`options?`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `options?` | `ChannelOptions` |

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:27

## Properties

### \_channelzHandler

• `Private` **\_channelzHandler**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:51

___

### \_respondWithError

• `Private` **\_respondWithError**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:50

___

### \_retrieveHandler

• `Private` **\_retrieveHandler**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:49

___

### \_runHandlerForCall

• `Private` **\_runHandlerForCall**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:53

___

### \_setupHandlers

• `Private` **\_setupHandlers**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:54

___

### \_streamHandler

• `Private` **\_streamHandler**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:52

___

### \_verifyContentType

• `Private` **\_verifyContentType**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:48

___

### callTracker

• `Private` **callTracker**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:20

___

### channelzEnabled

• `Private` `Readonly` **channelzEnabled**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:17

___

### channelzRef

• `Private` **channelzRef**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:18

___

### channelzTrace

• `Private` **channelzTrace**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:19

___

### getChannelzInfo

• `Private` **getChannelzInfo**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:28

___

### getChannelzSessionInfoGetter

• `Private` **getChannelzSessionInfoGetter**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:29

___

### handlers

• `Private` **handlers**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:12

___

### http2ServerList

• `Private` **http2ServerList**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:11

___

### keepaliveTimeMs

• `Private` `Readonly` **keepaliveTimeMs**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:25

___

### keepaliveTimeoutMs

• `Private` `Readonly` **keepaliveTimeoutMs**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:26

___

### listenerChildrenTracker

• `Private` **listenerChildrenTracker**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:21

___

### maxConnectionAgeGraceMs

• `Private` `Readonly` **maxConnectionAgeGraceMs**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:24

___

### maxConnectionAgeMs

• `Private` `Readonly` **maxConnectionAgeMs**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:23

___

### options

• `Private` **options**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:15

___

### serverAddressString

• `Private` **serverAddressString**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:16

___

### sessionChildrenTracker

• `Private` **sessionChildrenTracker**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:22

___

### sessions

• `Private` **sessions**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:13

___

### started

• `Private` **started**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:14

___

### trace

• `Private` **trace**: `any`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:30

## Methods

### addHttp2Port

▸ **addHttp2Port**(): `never`

#### Returns

`never`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:41

___

### addProtoService

▸ **addProtoService**(): `never`

#### Returns

`never`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:31

___

### addService

▸ **addService**(`service`, `implementation`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `service` | `ServiceDefinition`<`UntypedServiceImplementation`\> |
| `implementation` | `UntypedServiceImplementation` |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:32

___

### bind

▸ **bind**(`port`, `creds`): `never`

#### Parameters

| Name | Type |
| :------ | :------ |
| `port` | `string` |
| `creds` | [`ServerCredentials`](protobufs.ServerCredentials.md) |

#### Returns

`never`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:34

___

### bindAsync

▸ **bindAsync**(`port`, `creds`, `callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `port` | `string` |
| `creds` | [`ServerCredentials`](protobufs.ServerCredentials.md) |
| `callback` | (`error`: ``null`` \| `Error`, `port`: `number`) => `void` |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:35

___

### forceShutdown

▸ **forceShutdown**(): `void`

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:36

___

### getChannelzRef

▸ **getChannelzRef**(): `ServerRef`

Get the channelz reference object for this server. The returned value is
garbage if channelz is disabled for this server.

#### Returns

`ServerRef`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:47

___

### register

▸ **register**<`RequestType`, `ResponseType`\>(`name`, `handler`, `serialize`, `deserialize`, `type`): `boolean`

#### Type parameters

| Name |
| :------ |
| `RequestType` |
| `ResponseType` |

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |
| `handler` | `HandleCall`<`RequestType`, `ResponseType`\> |
| `serialize` | `Serialize`<`ResponseType`\> |
| `deserialize` | `Deserialize`<`RequestType`\> |
| `type` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:37

___

### removeService

▸ **removeService**(`service`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `service` | `ServiceDefinition`<`UntypedServiceImplementation`\> |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:33

___

### start

▸ **start**(): `void`

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:39

___

### tryShutdown

▸ **tryShutdown**(`callback`): `void`

#### Parameters

| Name | Type |
| :------ | :------ |
| `callback` | (`error?`: `Error`) => `void` |

#### Returns

`void`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:40

___

### unregister

▸ **unregister**(`name`): `boolean`

#### Parameters

| Name | Type |
| :------ | :------ |
| `name` | `string` |

#### Returns

`boolean`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server.d.ts:38
