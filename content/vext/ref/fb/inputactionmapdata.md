---
title: InputActionMapData
---

Inherits from [DataContainer](/vext/ref/shared/type/datacontainer)

## Summary

### Constructors

|  |
| --- |
| **[InputActionMapData](#constructor-0)**() |
| **[InputActionMapData](#constructor-1)**(guid: [Guid](/vext/ref/shared/type/guid)) |
| **[InputActionMapData](#constructor-2)**(other: [DataContainer](/vext/ref/shared/type/datacontainer)) |

### Properties

| Name | Type |
| ---- | ---- |
| {{< prop "actions" >}} | [InputActionsData](/vext/ref/fb/inputactionsdata)[] |
| {{< prop "platformSpecific" >}} | [InputActionMapPlatform](/vext/ref/fb/inputactionmapplatform) |
| {{< prop "slot" >}} | [InputActionMapSlot](/vext/ref/fb/inputactionmapslot) |
| {{< prop "copyKeyBindingsFrom" >}} | string |

### Static members

| Name | Type |
| ---- | ---- |
| {{< static "InputActionMapData" "typeInfo" >}} | [TypeInformation](/vext/ref/shared/type/typeinformation) |

## Constructors

### InputActionMapData {#constructor-0}

> **InputActionMapData**()

Creates a new [InputActionMapData](/vext/ref/fb/inputactionmapdata) frostbite instance.

### InputActionMapData {#constructor-1}

> **InputActionMapData**(guid: [Guid](/vext/ref/shared/type/guid))

Creates a new [InputActionMapData](/vext/ref/fb/inputactionmapdata) frostbite instance and assigns it the provided [Guid](/vext/ref/shared/type/guid).

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **guid** | [Guid](/vext/ref/shared/type/guid) | The [Guid](/vext/ref/shared/type/guid) to assign to the newly created instance. |

### InputActionMapData {#constructor-2}

> **InputActionMapData**(other: [DataContainer](/vext/ref/shared/type/datacontainer))

Casts an instance of type [DataContainer](/vext/ref/shared/type/datacontainer) to [InputActionMapData](/vext/ref/fb/inputactionmapdata). Will throw an error when trying to cast from an unsupported type.

#### Parameters

| Name | Type | Description |
| ---- | ---- | ----------- |
| **other** | [DataContainer](/vext/ref/shared/type/datacontainer) | The instance to cast to [InputActionMapData](/vext/ref/fb/inputactionmapdata). |

## Properties

### {{% prop-heading "actions" %}}

> **[InputActionsData](/vext/ref/fb/inputactionsdata)**[]

### {{% prop-heading "platformSpecific" %}}

> **[InputActionMapPlatform](/vext/ref/fb/inputactionmapplatform)**

### {{% prop-heading "slot" %}}

> **[InputActionMapSlot](/vext/ref/fb/inputactionmapslot)**

### {{% prop-heading "copyKeyBindingsFrom" %}}

> **string**

## Static members

### {{% static-heading "typeInfo" %}}

> **[TypeInformation](/vext/ref/shared/type/typeinformation)**

The type information for the [InputActionMapData](/vext/ref/fb/inputactionmapdata) type.

