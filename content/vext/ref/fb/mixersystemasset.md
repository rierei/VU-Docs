---
title: MixerSystemAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[MixerSystemAsset](#constructor-0)**() |
| **[MixerSystemAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[MixerSystemAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[MixerSystemAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "groups" >}} | [MixGroup](/vext/ref/fb/mixgroup)[] |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "MixerSystemAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### MixerSystemAsset {#constructor-0}

> **MixerSystemAsset**()

Creates a new [MixerSystemAsset](/vext/ref/fb/mixersystemasset) frostbite instance.

### MixerSystemAsset {#constructor-1}

> **MixerSystemAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [MixerSystemAsset](/vext/ref/fb/mixersystemasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### MixerSystemAsset {#constructor-2}

> **MixerSystemAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [MixerSystemAsset](/vext/ref/fb/mixersystemasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [MixerSystemAsset](/vext/ref/fb/mixersystemasset). |

### MixerSystemAsset {#constructor-3}

> **MixerSystemAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [MixerSystemAsset](/vext/ref/fb/mixersystemasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [MixerSystemAsset](/vext/ref/fb/mixersystemasset). |

## Properties

### {{% prop-heading "groups" %}}

> **[MixGroup](/vext/ref/fb/mixgroup)**[]

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [MixerSystemAsset](/vext/ref/fb/mixersystemasset) type.

