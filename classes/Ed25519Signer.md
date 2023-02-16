[@farcaster/js](../README.md) / [Exports](../modules.md) / Ed25519Signer

# Class: Ed25519Signer

## Hierarchy

- `Ed25519Signer`

  ↳ **`Ed25519Signer`**

## Table of contents

### Constructors

- [constructor](Ed25519Signer.md#constructor)

### Properties

- [scheme](Ed25519Signer.md#scheme)
- [signerKey](Ed25519Signer.md#signerkey)
- [signerKeyHex](Ed25519Signer.md#signerkeyhex)

### Methods

- [signMessageHash](Ed25519Signer.md#signmessagehash)
- [signMessageHashHex](Ed25519Signer.md#signmessagehashhex)
- [fromPrivateKey](Ed25519Signer.md#fromprivatekey)

## Constructors

### constructor

• **new Ed25519Signer**(`privateKey`, `signerKey`, `signerKeyHex`)

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKey` | `Uint8Array` |
| `signerKey` | `Uint8Array` |
| `signerKeyHex` | `string` |

#### Inherited from

BaseEd25519Signer.constructor

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:140

## Properties

### scheme

• `Readonly` **scheme**: [`SIGNATURE_SCHEME_ED25519`](../enums/protobufs.SignatureScheme.md#signature_scheme_ed25519) = `SignatureScheme.SIGNATURE_SCHEME_ED25519`

#### Inherited from

BaseEd25519Signer.scheme

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:134

___

### signerKey

• `Readonly` **signerKey**: `Uint8Array`

20-byte wallet address

#### Inherited from

BaseEd25519Signer.signerKey

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:136

___

### signerKeyHex

• `Readonly` **signerKeyHex**: `string`

#### Inherited from

BaseEd25519Signer.signerKeyHex

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:137

## Methods

### signMessageHash

▸ **signMessageHash**(`hash`): `HubAsyncResult`<`Uint8Array`\>

generates 256-bit signature from an EdDSA key pair

#### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `Uint8Array` |

#### Returns

`HubAsyncResult`<`Uint8Array`\>

#### Inherited from

BaseEd25519Signer.signMessageHash

#### Defined in

node_modules/.pnpm/@farcaster+utils@0.2.3/node_modules/@farcaster/utils/dist/index.d.ts:142

___

### signMessageHashHex

▸ **signMessageHashHex**(`hash`): `HubAsyncResult`<`string`\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `hash` | `string` |

#### Returns

`HubAsyncResult`<`string`\>

#### Defined in

[src/signers.ts:45](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/signers.ts#L45)

___

### fromPrivateKey

▸ `Static` **fromPrivateKey**(`privateKey`): `HubResult`<[`Ed25519Signer`](Ed25519Signer.md)\>

#### Parameters

| Name | Type |
| :------ | :------ |
| `privateKey` | `Uint8Array` |

#### Returns

`HubResult`<[`Ed25519Signer`](Ed25519Signer.md)\>

#### Overrides

BaseEd25519Signer.fromPrivateKey

#### Defined in

[src/signers.ts:38](https://github.com/farcasterxyz/hubble/blob/57fee6a/packages/js/src/signers.ts#L38)
