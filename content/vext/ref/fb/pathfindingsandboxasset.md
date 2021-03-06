---
title: PathfindingSandboxAsset
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[PathfindingSandboxAsset](#constructor-0)**() |
| **[PathfindingSandboxAsset](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[PathfindingSandboxAsset](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[PathfindingSandboxAsset](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "system" >}} | [PathfindingSystemEntityData](/vext/ref/fb/pathfindingsystementitydata) \| nil |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "PathfindingSandboxAsset" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### PathfindingSandboxAsset {#constructor-0}

> **PathfindingSandboxAsset**()

Creates a new [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset) frostbite instance.

### PathfindingSandboxAsset {#constructor-1}

> **PathfindingSandboxAsset**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### PathfindingSandboxAsset {#constructor-2}

> **PathfindingSandboxAsset**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset). |

### PathfindingSandboxAsset {#constructor-3}

> **PathfindingSandboxAsset**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset). |

## Properties

### {{% prop-heading "system" %}}

> **[PathfindingSystemEntityData](/vext/ref/fb/pathfindingsystementitydata)** \| **nil**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [PathfindingSandboxAsset](/vext/ref/fb/pathfindingsandboxasset) type.

