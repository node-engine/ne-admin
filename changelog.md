# ne-admin changelog

## Change Tags

- [FN] New Feature: Added a new feature
- [BF] Bug fix: Fixed a bug
- [OO] Optimisation: The internal workings of the module is improved 
- [OR] Refactor: The internal code is refactored
- [CI] Input change: What is required as input for the module is changed
- [CO] Output change: What is output by the module is changed
- [DN] New Dependency: A new dependency is added to the package
- [DR] Remove Dependency: A  dependency is removed from the package
- [DU] Update Dependency: A dependency is updated in the package


# 1.4.8

Release date: 20151028

[BF]
- delete button fixed

# 1.4.7

Release date: 20151027

[BF]
- change from 1 per line to 2 edit item per line
- Improced the styling 


# 1.4.6

Release date: 20151026

[BF]
- Input fields in Edit and Add forms to 80% width 
- change from 3 per line to 1 edit item per line



# 1.4.5

Release date: 20151025

[FN]
Added support for dataRef.editType: "select" to the add new

[FN]
Added support for dataRef.editType: "textarea" to the add new



# 1.4.4

Release date: 20151025

[FN]
support for dataRef.editType: "select"

[FN]
support for dataRef.editType: "textarea"

[CO]
Use dataRef.label for the field labels



# 1.4.3

Release date: 20151024

[BF]
Fixed the getWithPermissions bug


# 1.4.2

Release date: 20151021

Removed 1.4.0
- Caused too many bugs


# 1.4.1

Release date: 20151021

Fixes bugs cuase by 1.4.0


# 1.4.0

Release date: 20151020

All require statements (BF DN)
- When using ne-auto the require statements did not find the module
- Are now conditional to be compatible with ne-auto
- If there is a process.env.NE_AUTO then the require statements use the ne-auto if not then they require from root
- Now this module will work with ne-auto and without ne-auto
- DN tag because this is connected to dependencies 


## 1.3.0

Release date: 20151019

ne-css (CO DU)
- ne-gulp 1.4.0 compiles the css to the root ot the /app folder
- Example in there is a file in the ne-css folder named negulpstyle.styl it will build to /app/css/negulpstyle.css
- need to give the css from each module a unique name so that they down overwrite one another.

readme 
- updated


