---
id: daf-identity-manager.abstractidentityprovider.addkey
title: AbstractIdentityProvider.addKey() method
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Packages](./index.md) &gt; [daf-identity-manager](./daf-identity-manager.md) &gt; [AbstractIdentityProvider](./daf-identity-manager.abstractidentityprovider.md) &gt; [addKey](./daf-identity-manager.abstractidentityprovider.addkey.md)

## AbstractIdentityProvider.addKey() method

<b>Signature:</b>

```typescript
abstract addKey(args: {
        identity: IIdentity;
        key: IKey;
        options?: any;
    }, context: IAgentContext<IKeyManager>): Promise<any>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  args | { identity: [IIdentity](./daf-core.iidentity.md) ; key: [IKey](./daf-core.ikey.md)<!-- -->; options?: any; } |  |
|  context | [IAgentContext](./daf-core.iagentcontext.md) &lt;[IKeyManager](./daf-core.ikeymanager.md)<!-- -->&gt; |  |

<b>Returns:</b>

Promise&lt;any&gt;