# Interface: UploadMetadata

## Hierarchy

- [*SettableMetadata*](/reference/storage/interfaces/settablemetadata.md)

  ↳ **UploadMetadata**

## Table of contents

### Properties

- [cacheControl](/reference/storage/interfaces/uploadmetadata.md#cachecontrol)
- [contentDisposition](/reference/storage/interfaces/uploadmetadata.md#contentdisposition)
- [contentEncoding](/reference/storage/interfaces/uploadmetadata.md#contentencoding)
- [contentLanguage](/reference/storage/interfaces/uploadmetadata.md#contentlanguage)
- [contentType](/reference/storage/interfaces/uploadmetadata.md#contenttype)
- [customMetadata](/reference/storage/interfaces/uploadmetadata.md#custommetadata)
- [md5Hash](/reference/storage/interfaces/uploadmetadata.md#md5hash)

## Properties

### cacheControl

• `Optional` **cacheControl**: *string*

Served as the 'Cache-Control' header on object download.

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[cacheControl](/reference/storage/interfaces/settablemetadata.md#cachecontrol)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:216

___

### contentDisposition

• `Optional` **contentDisposition**: *string*

Served as the 'Content-Disposition' header on object download.

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[contentDisposition](/reference/storage/interfaces/settablemetadata.md#contentdisposition)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:220

___

### contentEncoding

• `Optional` **contentEncoding**: *string*

Served as the 'Content-Encoding' header on object download.

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[contentEncoding](/reference/storage/interfaces/settablemetadata.md#contentencoding)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:224

___

### contentLanguage

• `Optional` **contentLanguage**: *string*

Served as the 'Content-Language' header on object download.

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[contentLanguage](/reference/storage/interfaces/settablemetadata.md#contentlanguage)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:228

___

### contentType

• `Optional` **contentType**: *string*

Served as the 'Content-Type' header on object download.

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[contentType](/reference/storage/interfaces/settablemetadata.md#contenttype)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:232

___

### customMetadata

• `Optional` **customMetadata**: *object*

Additional user-defined custom metadata.

#### Type declaration

Inherited from: [SettableMetadata](/reference/storage/interfaces/settablemetadata.md).[customMetadata](/reference/storage/interfaces/settablemetadata.md#custommetadata)

Defined in: node_modules/@firebase/storage/exp/dist/storage-public.d.ts:236

___

### md5Hash

• `Optional` **md5Hash**: *string*

A Base64-encoded MD5 hash of the object being uploaded.

Defined in: [packages/storage/modular/src/types.ts:57](https://github.com/invertase/react-native-firebase/blob/e2e22540/packages/storage/modular/src/types.ts#L57)