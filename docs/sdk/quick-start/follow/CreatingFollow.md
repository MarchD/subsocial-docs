---
id: following
title: Following and unfollowing
---
## Methods for profile

### Follow Account

Start following an account.

```
substrateApi.tx.profileFollows.followAccount(AccountId: AnyAccountId)
```

Example: 

```typescript
...
const tx = substrateApi.tx.profileFollows.followAccount('3osmnRNnrcScHsgkTJH1xyBF5kGjpbWHsGrqM31BJpy4vwn8')

...
```

### Unfollow Account

Stop following an account.

```
substrateApi.tx.profileFollows.unfollowAccount(AccountId: AnyAccountId)
```

Example: 

```typescript
...
const tx = substrateApi.tx.profileFollows.unfollowAccount('3osmnRNnrcScHsgkTJH1xyBF5kGjpbWHsGrqM31BJpy4vwn8')

...
```

> 🆃 [AnyAccountId](https://docs.subsocial.network/js-docs/js-sdk/modules.html#anyaccountid): *AccountId* | *string*

## Methods for space

### Follow Space

Start following a space.

```
substrateApi.tx.spaceFollows.followSpace(SpaceId: AnySpaceId)
```

Example:

```typescript
...
const tx = substrateApi.tx.spaceFollows.followSpace('1')

...
```

### Unfollow Space

Stop following a space.

```
substrateApi.tx.spaceFollows.unfollowSpace(SpaceId: AnySpaceId)
```

Example:

```typescript
...
const tx = substrateApi.tx.spaceFollows.unfollowSpace('1')

...
```

> 🆃 [AnySpaceId](https://docs.subsocial.network/js-docs/js-sdk/modules.html#anyspaceid): [*SpaceId*](https://docs.subsocial.network/js-docs/js-sdk/interfaces/interfaces.spaceid.html) | *BN*
