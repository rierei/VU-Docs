---
title: UIComponentData
---

Inherits from [Asset](/vext/ref/fb/asset)

## Summary

### Constructors

|  |
| --- |
| **[UIComponentData](#constructor-0)**() |
| **[UIComponentData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[UIComponentData](#constructor-2)**(other: [Asset](/vext/ref/fb/asset)) |
| **[UIComponentData](#constructor-3)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "shortName" >}} | string |
| {{< prop "dataSources" >}} | string[] |
| {{< prop "updateType" >}} | [UIUpdateType](/vext/ref/fb/uiupdatetype) |
| {{< prop "updatesPerSecond" >}} | int |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "UIComponentData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### UIComponentData {#constructor-0}

> **UIComponentData**()

Creates a new [UIComponentData](/vext/ref/fb/uicomponentdata) frostbite instance.

### UIComponentData {#constructor-1}

> **UIComponentData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [UIComponentData](/vext/ref/fb/uicomponentdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### UIComponentData {#constructor-2}

> **UIComponentData**(other: [Asset](/vext/ref/fb/asset))

Casts an instance of type [Asset](/vext/ref/fb/asset) to [UIComponentData](/vext/ref/fb/uicomponentdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [Asset](/vext/ref/fb/asset) | The instance to cast to [UIComponentData](/vext/ref/fb/uicomponentdata). |

### UIComponentData {#constructor-3}

> **UIComponentData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [UIComponentData](/vext/ref/fb/uicomponentdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [UIComponentData](/vext/ref/fb/uicomponentdata). |

## Properties

### {{% prop-heading "shortName" %}}

> **string**

### {{% prop-heading "dataSources" %}}

> **string**[]

### {{% prop-heading "updateType" %}}

> **[UIUpdateType](/vext/ref/fb/uiupdatetype)**

### {{% prop-heading "updatesPerSecond" %}}

> **int**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [UIComponentData](/vext/ref/fb/uicomponentdata) type.

