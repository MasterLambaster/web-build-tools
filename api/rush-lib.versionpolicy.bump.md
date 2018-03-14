[Home](./index) &gt; [@microsoft/rush-lib](./rush-lib.md) &gt; [VersionPolicy](./rush-lib.versionpolicy.md) &gt; [bump](./rush-lib.versionpolicy.bump.md)

# VersionPolicy.bump method

> This API is provided as a preview for developers and may change based on feedback that we receive. Do not use this API in a production environment.

Bumps version based on the policy

**Signature:**
```javascript
abstract bump(bumpType?: BumpType, identifier?: string): void;
```
**Returns:** `void`

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  `bumpType` | `BumpType` | (optional) override bump type |
|  `identifier` | `string` | (optional) override prerelease Id |
