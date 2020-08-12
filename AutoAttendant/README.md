# Custom Call Routing/Auto Attendant

The eMG System incorporates Auto Attendant capabilities called CCR (Custom Call Routing).

After or during a Voice Store & Forward (VSF) Auto Attendant (AA) Announcement, a caller may dial a digit to select a destination or route for the call.

The Custom Call Routing/Voice Store & Forward (VSF) Auto Attendant (AA) Routing Audio Text Table defines the destination associated with digits dialed by the caller in response to the VSF AA Announcement (01-70).

Up to 70 single-level Audio Text menus may be assigned or, multi-level menu structures.

A maximum 70 levels can be established using one menu as a destination for the previous level.

## Program the Incoming Call to be answered by the Auto Attendant.

__CO Line Data__ -> __CO/IP Ring Assignment__

1. Select the VSF (Voice Store & Forward) Radio Button
2. Select the Announcement Number

## Program the Key Actions for the Auto Attendant menu using the Custom Call Routing (CCR) Table

__Tables Data__ -> __CCR Table__

## Select the Type

The type can be a Station, Station Group, System Speed, PABX Transfer With System Speed, Voice Store & Forward Announcement, a Voice Store & Forward Announcement and Disconnect, Conference Room, etc. 

## Select the Value

This will be the Station Value, Station Group, System Speed extension, etc.

