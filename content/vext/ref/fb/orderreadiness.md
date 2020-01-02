---
title: OrderReadiness
---
### Base Classes

[UrgencyUserData](UrgencyUserData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                               | Description                                                                                                         |
| ------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| OrderReadiness()                                                          | Create a new instance of this container type.                                                                       |
| OrderReadiness(OrderReadiness other)                                      | Create a reference copy of an instance of the same type.                                                            |
| OrderReadiness([UrgencyUserData](UrgencyUserData) other)                  | Upcast an instance of type [UrgencyUserData](UrgencyUserData) to [OrderReadiness](OrderReadiness).                  |
| OrderReadiness([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [OrderReadiness](OrderReadiness). |

## Properties

| Name             | Type                             | Description |
| ---------------- | -------------------------------- | ----------- |
| orderType        | string                           |             |
| minimumReadiness | [ReadinessState](ReadinessState) |             |

## Methods

| Type                             | Name            | Parameters                                     |
| -------------------------------- | --------------- | ---------------------------------------------- |
| [OrderReadiness](OrderReadiness) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [OrderReadiness](OrderReadiness) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |