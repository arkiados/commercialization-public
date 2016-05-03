---
author: joshbax-msft
title: Project Class
description: Project Class
MSHAttr:
- 'PreferredSiteName:MSDN'
- 'PreferredLib:/library/windows/hardware'
ms.assetid: 27b3e1a7-ba2c-4fc9-82a2-686bb8d97149
---

# Project Class


This class represents a **Project** object which is created in the database for each project the user initiates. It is effectively handles a set of product instances that users will be running logo tests for. In addition to that, there is metadata stored along with each **Project** object.

**Namespace:** Microsoft.Windows.Kits.Hardware.ObjectModel **Assembly:** Microsoft.Windows.Kits.Hardware.ObjectModel (in Microsoft.Windows.Kits.Hardware.ObjectModel)

## Usage


**Visual Basic**`Dim instance As Project`

## Syntax


**Visual Basic**`<DataContractAttribute> _``Public MustInherit Class Project`           `Implements IRunTests`

**C#**`[DataContractAttribute]``public abstract class Project : IRunTests`

## Inheritance Hierarchy


**System.Object**      **Microsoft.Windows.Kits.Hardware.ObjectModel.NotificationBase**           **Microsoft.Windows.Kits.Hardware.ObjectModel.Project**

## Remarks


Projects are the highest level objects in the hierarchy of data and objects used to represent certification. There are a number of layers of objects between the project and the test results and logs.

## Thread Safety


Any public static (**Shared** in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

 

 

[Send comments about this topic to Microsoft](mailto:wsddocfb@microsoft.com?subject=Documentation%20feedback%20%5Bp_hck\p_hck%5D:%20Project%20Class%20%20RELEASE:%20%284/27/2016%29&body=%0A%0APRIVACY%20STATEMENT%0A%0AWe%20use%20your%20feedback%20to%20improve%20the%20documentation.%20We%20don't%20use%20your%20email%20address%20for%20any%20other%20purpose,%20and%20we'll%20remove%20your%20email%20address%20from%20our%20system%20after%20the%20issue%20that%20you're%20reporting%20is%20fixed.%20While%20we're%20working%20to%20fix%20this%20issue,%20we%20might%20send%20you%20an%20email%20message%20to%20ask%20for%20more%20info.%20Later,%20we%20might%20also%20send%20you%20an%20email%20message%20to%20let%20you%20know%20that%20we've%20addressed%20your%20feedback.%0A%0AFor%20more%20info%20about%20Microsoft's%20privacy%20policy,%20see%20http://privacy.microsoft.com/default.aspx. "Send comments about this topic to Microsoft")



