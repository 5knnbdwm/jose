# Interface: FlattenedDecryptGetKey

## Callable

### FlattenedDecryptGetKey

▸ **FlattenedDecryptGetKey**(`protectedHeader`, `token`): [`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array` \| `Promise`<[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array`\>

Interface for Flattened JWE Decryption dynamic key resolution.
No token components have been verified at the time of this function call.

#### Parameters

| Name | Type |
| :------ | :------ |
| `protectedHeader` | `undefined` \| [`JWEHeaderParameters`](types.JWEHeaderParameters.md) |
| `token` | [`FlattenedJWE`](types.FlattenedJWE.md) |

#### Returns

[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array` \| `Promise`<[`KeyLike`](../types/types.KeyLike.md) \| `Uint8Array`\>
