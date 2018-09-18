# duck-template-package

This is a template repository, designed to speed up starting a new pacakge in duck.

This will be kept up to date, with the correct standards for directory structure, naming, documentation format etc.

## How to use it

Edit this readme to the needs of your project, but keep the bottom section explaining DUCK

In the repo there are 3 directories. Scripts, Docs, Tests.

In most situations there should be contents in all 3 directories. 
If the package is small enough the documentation can be in this readme.
If you use the Docs directory, please provide links from the readme for easy navigation and between the pages of documentation if possible.

Rename the following files & their change their content, so the assembly name matches the file name
`Scripts/Duck.MyPackage.asmdef`
`Tests/Duck.MyPackage.Tests.asmdef`

The following files are for example purposes and can be reused or removed.

`Scripts/ExampleScript.cs` & `Tests/ExampleScript.Tests.cs`

_The following section should be kept in the readme of any duck package, to aid discoverability, navigability and provide context_

## DUCK

This repo is part of DUCK (dubit unity component kit). <INSERT LINK TO MAIN DUCK PAGE>
DUCK is a series of repos containing reusable component, utils systems & tools that can be submoduled into a unity project. 

DUCK packages can be added to a project normally as git submodules or by using the [Duck Pacakge Manager](https://github.com/dubit/duck-package-manager). 
