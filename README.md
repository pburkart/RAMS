# RAMS – Refugee Aid Management System

# Introduction

Local city council with help from 2 charities manages refugee aid efforts. Those efforts include management of:
-	collection/distribution of item donated by the public
-	sourcing volunteer drivers (for items delivery and transport of people)
-	allocation of accommodation spaces across different sites (hotels, fire-stations, ...)




**Item donations:**

There are about 14 donation points across the city where donation can be made and about 40 distribution points where items are delivered to be handed to refugees. On a high-level the current process is as follow.

1.	The need for certain items is advertised (online, facebook?)
2.	The public responds by donations of items to one of the 14 collection points
3.	City council officer sources a volunteer delivery drivers 
4.	Drivers collect items and deliveries are made to a drop off point



**Accommodation:**

There are about 24 accommodation locations including hotels, fire stations and others. Each has a certain capacity.
1.	Need for accommodation is identified
2.	City council / charity member calls all locations to check for spaces available until:
3.	Accommodation is found
4.	Transport is organized and fulfilled


# Problem

The key identified issues with current processes are issues with slow communication/updates on inventory/accommodation levels and involve:

1. Slow manual process of searching for available accommodation spaces which involves calling all hotels/places and asking each for availability.


2. Slow feedback loop on advertising the need for donation of items needed/no longer needed - resulting in overstock (too many donations of certain items).

E.g. it is often the case that from when announcement is made to the public (asking for donations of certain items) to the time when second “we have enough” announcement is made too many items arrive within certain category. 

3. Transportation requests currently results in too many drivers showing up (or none).


# Aims
The main aims of this project are to organise and automate current processes in a clear and systematic fashion to save time and maximise the refugee aid efforts.
This can be achieved by the design and development of computerized system (web-app) for the city council to operate. The proposed system could address the main issues by allowing stakeholders access and real time inventory update capabilities for item donations and accommodation spaces.  
In addition, the system should have the capability to store and manage a database of volunteer drivers and their availability.  



# Initial conceptual structure
4 parts of the system:

1.	Identity (accounts and roles)
3.	Inventory (who has what, and how much)
4.	Accommodation (number of spaces available and where)
5.	Transport (drivers) database (availability and contact details)


Roles:

**Admin** – a system wide administrator (all access across all areas)
**Org** – City council / charity employee (read access across all areas, write access at own organisation?)

**Point** (donations) – endpoint (donation collection/distribution point)

**Point** (accommodation) – endpoint (accommodation location)

**Driver** – volunteer delivery/transport driver


# Requirements

Definitions:

| Term | Description |
| ---- | ----------- |
| Admin | a system wide administrator (all access across all areas) |
| Org | City council/charity employee (read access across all areas, write access at own organisation?) |
| Point (donations) | endpoint (donation collection/distribution point) | 
| Point (accommodation) | endpoint (accommodation location) |
| Driver | volunteer delivery/transport driver |
| CRUD | Create, Read, Update, Delete |


  - Draft Functional Requirements (FR)

| No    | Description |
| ----- | ----------- |
| FR000 |	Online-capable account/role-based web application for internal use |
| FR001 |	Admin user able to create accounts and assign roles for accounts (Org/Points/Driver) CRUD |
| FR002 |	Log-in functionality – admin / organisation / point / driver |
| FR003 |	Admin/Org/Point able to view donated items inventory across all sites |
| FR004 |	Admin/Org can CRUD item in inventory system |
| FR005 |	Point (donations) - can update their own quantities – which is propagated across the system |
| FR006 |	Point (accommodation) – can update available spaces |
| FR007 |	Admin/Org/Point able to view a live dashboard (overview of all points) – with option for detailed view for point to see quantities and spaces |
| FR008 |	Driver can update own availability (days/times) |
| FR009 |	Admin/Org can view driver database, availability, and contact details |
| FR010 |	Inventory levels viewable by public? (without login) |



  - Non-Functional Requirements (NF)
  - Design diagrams

# Contributing guidelines
  - Setting up the development environment

  ...
  
  - Installing VS Code Extensions
        
      Angular:
       - ...

      .NET/C#
       - ...
  - Document the code as you write it
      - ...
