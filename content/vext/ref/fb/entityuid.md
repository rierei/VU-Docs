---
title: EntityUid
---

## Summary

### Constructors

|  |
| --- |
| **[EntityUid](#constructor-0)**() |
| **[EntityUid](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "id" >}} | int |

### Methods

| Method | Returns |
| ------ | ------- |
| **[Clone](#clone)**() | [EntityUid](/vext/ref/fb/entityuid) |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "EntityUid" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### EntityUid {#constructor-0}

> **EntityUid**()

Creates a new [EntityUid](/vext/ref/fb/entityuid) frostbite instance.

### EntityUid {#constructor-1}

> **EntityUid**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [EntityUid](/vext/ref/fb/entityuid) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

## Properties

### {{% prop-heading "id" %}}

> **int**

## Methods

### Clone {#clone}

> **Clone**(): [EntityUid](/vext/ref/fb/entityuid)

Creates a shallow-copy clone of this structure, which is essentially the equivalent of creating a new structure of the same type and assigning the values of this structure to all of its properties. Any properties that contain structure types (eg. [Vec3](/vext/ref/shared/type/vec3)) will be cloned when assigning, while properties that contain instance types (eg. [DataContainer](/vext/ref/shared/type/datacontainer)) will be referencing the same instance.

#### Returns

| Type | Description |
| ---- | ----------- |
| **[EntityUid](/vext/ref/fb/entityuid)** | The newly created structure. |

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [EntityUid](/vext/ref/fb/entityuid) type.

