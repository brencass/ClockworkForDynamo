﻿![Image](clockwork-logo.png)

#Clockwork for Dynamo#

Clockwork is a collection of custom nodes for the [Dynamo](http://www.dynamobim.org) visual programming environment which can be downloaded from Dynamo's [package manager](http://www.dynamopackages.com). Currently it consists of some 200+ nodes that were previously published in a number of separate packages. My reasoning is that keeping all nodes in a single package will make updates easier and reduce package dependencies. I had never set out to build so many custom nodes – somehow it just happened.

If you use Clockwork remember to uninstall all of my previous packages (see [list below](#packages-to-uninstall)).

#State of migration#

At least for some time, I will maintain two versions this package (one for Dynamo 0.6.3 and one for Dynamo 0.7.x). As soon as 0.7.x supports all my 0.6.3 workflows, I will abandon the 0.6.3 branch. Migrating from 0.6.3, I also recategorized and renamed most of the nodes. These changes are documented in an excel sheet [here](NodeList.xls) that contains a list of all nodes within the package. This list also includes information as to which nodes were deprecated during migration and which ones are still buggy or haven't been migrated yet. Note that nodes known to be buggy in the latest offical Dynamo release have not been included in the package.

I am currently using the offical 0.6.3 and 0.7.2 Dynamo builds to test nodes, so some buggy nodes might very well be running under more recent daily builds.

#Material on this repository#

This repository contains the following:

Directory [package_samples](package_samples) contains simple examples for most of the nodes in Clockwork. I use them for occasional testing, but they should also help explain how to use each node. The samples are currently still sorted according to their previous package and limited to 0.6.3 files. I plan to correct that in the future and also add 0.7.x versions of the sample files.

Directory [workflow_samples](workflow_samples) contains some sample workflows that I have published online somewhere before. I have also started to include some of the examples that I use for teaching Dynamo. All of these are currently still 0.6.3 files and will be migrated as 0.7.x stability improves.

Directory [nodes](nodes) is the actual repository of the custom nodes.

Directory [issues](issues) contains sample files for issues raised on the [Dynamo GitHub site](https://github.com/DynamoDS/Dynamo).

#Packages to uninstall#
If you have installed Clockwork or are planning to do so, you should uninstall all of the following packages (that is if you had those installed, of course):
- Accumulate List
- Almost Zero
- Alphabetical Sequence
- Altitude And Azimuth From Vector
- Angle Between Vectors
- Angle Bisector
- Angle By Angle Sum
- Binary To Decimal
- Buckyball
- Central Projection On Face
- Central Projection On Plane
- Convex Hull 2D
- Correct Normal Orientation
- Count Sequences Of True Or False
- Count True And False
- Create Placeholder Sheets
- CSV To List
- Curve Array
- Custom Rounding
- Dispatch
- Drop Last Row And Column From UV Field
- Elements From And To IDs
- Equal List Lengths
- Evaluate Divided Surface Grid Nodes
- Exterior Angle
- Family To Type And Back
- Foundation Stuff
- Get And Set Family Type
- Get And Set Name
- Get Bounding Box
- Get Current Revit Document Path
- Get Directory From File Path
- Get Element By Face
- Get Element Location
- Get Faces From Solid
- Get Highest And Lowest From List
- Get Third XYZ Axis
- Group List Of Lists By Key
- Has Out-Of-Plane XYZs
- Hosted Object Stuff
- Increment Or Decrement By 1
- Intersects For Divided Surfaces
- Invert And Mirror Normalized values
- Is Empty
- Is Multiple
- Is Odd Number
- Is Point Inside Polygon
- Is Related To Mass
- Law Of Cosines
- Law Of Sines
- LibG Vector Components
- Lines Through Points (Closed Loop)
- List Not Empty
- Mappable Conditions
- Match List With Key Values
- Material Stuff
- Mesh Stuff
- Move XYZs from Plane To Plane
- Normalization
- Parameter Exists
- Parse Solar Radiation CSV
- Phasing Stuff
- Plane By Reference Or Sketch Plane
- Plane From First 3 XYZs
- Plane From Planar Face
- Plane Properties
- Plane-Vector Intersection
- Project Stuff
- Pythagorean Theorem
- Recursive Boolean Difference
- Regular Expressions
- Remove Duplicates From List
- Replace Substring
- Return List Or Single Value
- Revit API Helpers
- Revit App Version Info
- Roof And Floor Stuff
- Room Stuff
- Select By Category
- Sequence With Leading Zeros
- Similar
- Simple Patterning
- Solve Triangle By XYZs
- Sort List Of Lists
- Standard Colours
- Standard Normals
- Subcategory Stuff
- Sublist Helpers
- Swap UV
- Switch
- Topo Stuff
- Transform Curve Loop
- True And False For Any And All
- Turn Into List
- Unit Conversion
- UV Components
- Vector And Plane Are Parallel
- Vector Is In Plane
- Vector-Vector Intersection
- Vectors Are Orthogonal
- Vectors Are Parallel
- View Stuff
- Wall Stuff
- XYZ Axis From Vector
- XYZ Grid From Face