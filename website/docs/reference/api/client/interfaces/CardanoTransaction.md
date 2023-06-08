---
id: "CardanoTransaction"
title: "Interface: CardanoTransaction"
sidebar_label: "CardanoTransaction"
sidebar_position: 0
custom_edit_url: null
---

Common fields for all cryptocurrency transactions

## Hierarchy

- [`TransactionCommon`](TransactionCommon.md)

  ↳ **`CardanoTransaction`**

## Properties

### amount

• **amount**: `BigNumber`

The amount of token to send in the transaction, denoted in the smallest cryptocurrency's magnitude
For example in BTC, a tx with an 'amount' field of 1 will correspond to a tx corresponding to 0.00000001 BTC

#### Inherited from

[TransactionCommon](TransactionCommon.md).[amount](TransactionCommon.md#amount)

#### Defined in

[packages/core/src/families/types.ts:47](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/types.ts#L47)

___

### family

• `Readonly` **family**: ``"cardano"``

The family of the transaction

#### Overrides

[TransactionCommon](TransactionCommon.md).[family](TransactionCommon.md#family)

#### Defined in

[packages/core/src/families/cardano/types.ts:7](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/cardano/types.ts#L7)

___

### fees

• `Optional` **fees**: `BigNumber`

#### Defined in

[packages/core/src/families/cardano/types.ts:8](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/cardano/types.ts#L8)

___

### memo

• `Optional` **memo**: `string`

#### Defined in

[packages/core/src/families/cardano/types.ts:9](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/cardano/types.ts#L9)

___

### mode

• **mode**: `string`

#### Defined in

[packages/core/src/families/cardano/types.ts:10](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/cardano/types.ts#L10)

___

### recipient

• **recipient**: `string`

The address of the transaction's recipient

#### Inherited from

[TransactionCommon](TransactionCommon.md).[recipient](TransactionCommon.md#recipient)

#### Defined in

[packages/core/src/families/types.ts:51](https://github.com/LedgerHQ/wallet-api/blob/main/packages/core/src/families/types.ts#L51)