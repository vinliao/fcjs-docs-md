[@farcaster/js](../README.md) / [Exports](../modules.md) / [protobufs](../modules/protobufs.md) / ServerCredentials

# Class: ServerCredentials

[protobufs](../modules/protobufs.md).ServerCredentials

## Table of contents

### Constructors

- [constructor](protobufs.ServerCredentials.md#constructor)

### Methods

- [\_getSettings](protobufs.ServerCredentials.md#_getsettings)
- [\_isSecure](protobufs.ServerCredentials.md#_issecure)
- [createInsecure](protobufs.ServerCredentials.md#createinsecure)
- [createSsl](protobufs.ServerCredentials.md#createssl)

## Constructors

### constructor

• **new ServerCredentials**()

## Methods

### \_getSettings

▸ `Abstract` **_getSettings**(): ``null`` \| `SecureServerOptions`

#### Returns

``null`` \| `SecureServerOptions`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server-credentials.d.ts:10

___

### \_isSecure

▸ `Abstract` **_isSecure**(): `boolean`

#### Returns

`boolean`

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server-credentials.d.ts:9

___

### createInsecure

▸ `Static` **createInsecure**(): [`ServerCredentials`](protobufs.ServerCredentials.md)

#### Returns

[`ServerCredentials`](protobufs.ServerCredentials.md)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server-credentials.d.ts:11

___

### createSsl

▸ `Static` **createSsl**(`rootCerts`, `keyCertPairs`, `checkClientCertificate?`): [`ServerCredentials`](protobufs.ServerCredentials.md)

#### Parameters

| Name | Type |
| :------ | :------ |
| `rootCerts` | ``null`` \| `Buffer` |
| `keyCertPairs` | `KeyCertPair`[] |
| `checkClientCertificate?` | `boolean` |

#### Returns

[`ServerCredentials`](protobufs.ServerCredentials.md)

#### Defined in

node_modules/.pnpm/@grpc+grpc-js@1.8.9/node_modules/@grpc/grpc-js/build/src/server-credentials.d.ts:12
