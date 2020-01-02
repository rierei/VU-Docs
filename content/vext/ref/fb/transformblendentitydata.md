---
title: TransformBlendEntityData
---
### Base Classes

[EntityData](EntityData)

## Description

A container type representing a Frostbite instance entry.

## Constructors

| Constructor                                                                         | Description                                                                                                                             |
| ----------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------- |
| TransformBlendEntityData()                                                          | Create a new instance of this container type.                                                                                           |
| TransformBlendEntityData(TransformBlendEntityData other)                            | Create a reference copy of an instance of the same type.                                                                                |
| TransformBlendEntityData([EntityData](EntityData) other)                            | Upcast an instance of type [EntityData](EntityData) to [TransformBlendEntityData](TransformBlendEntityData).                            |
| TransformBlendEntityData([GameObjectData](GameObjectData) other)                    | Upcast an instance of type [GameObjectData](GameObjectData) to [TransformBlendEntityData](TransformBlendEntityData).                    |
| TransformBlendEntityData([GameDataContainer](GameDataContainer) other)              | Upcast an instance of type [GameDataContainer](GameDataContainer) to [TransformBlendEntityData](TransformBlendEntityData).              |
| TransformBlendEntityData([DataContainer](/vext/ref/shared/class/datacontainer) other) | Upcast an instance of type [DataContainer](/vext/ref/shared/class/datacontainer) to [TransformBlendEntityData](TransformBlendEntityData). |

## Properties

| Name        | Type                                                    | Description |
| ----------- | ------------------------------------------------------- | ----------- |
| in2         | [LinearTransform](/vext/ref/shared/class/LinearTransform) |             |
| in1         | [LinearTransform](/vext/ref/shared/class/LinearTransform) |             |
| blendValue  | number                                                  |             |
| blendValue2 | number                                                  |             |
| realm       | [Realm](Realm)                                          |             |

## Methods

| Type                                                 | Name            | Parameters                                     |
| ---------------------------------------------------- | --------------- | ---------------------------------------------- |
| [TransformBlendEntityData](TransformBlendEntityData) | [Clone](#clone) | \[[Guid](/vext/ref/shared/class/guid) **guid**\] |

### Clone

> [TransformBlendEntityData](TransformBlendEntityData) **Clone**(\[[Guid](/vext/ref/shared/class/guid) **guid**\])

Creates a shallow-copy clone of the instance. Look at [DataContainer::Clone](/vext/ref/shared/class/datacontainer#clone) for more details.

#### Parameters

| Name | Type         | Description                                 |
| ---- | ------------ | ------------------------------------------- |
| guid | [Guid](Guid) | An optional GUID to assign to the instance. |