# C# Code Region Snippets (vs2013, vs2015)

[![Build status](https://ci.appveyor.com/api/projects/status/4p5c0dy577mrmevf?svg=true)](https://ci.appveyor.com/project/yuri-s100/coderegionssnippets-vsextension)

<!-- Update the VS Gallery link after you upload the VSIX-->
Download this extension from the [VS Gallery](https://marketplace.visualstudio.com/vsgallery/54ad0509-6b3a-4223-b88e-af425c8928f0)
or get the [CI build](http://vsixgallery.com/extension/BE701C9A-FDDD-44C9-AAA9-69B441577417/).

---------------------------------------
This lightweight extension allows to add Code Regions with same name at region start and region end marks for `C#` code in vs2013, vs2015.

See the [change log](CHANGELOG.md) for changes and road map.

## Features

- **Code region snippet with custom name**
- **Code region snippet with fixed name**
- **Fixed set of code regions snippet** 

**Code regions snippets invoking options:**

1. By shortcut `Ctrl+k, Ctrl+s`.

    1.1. Select code that should be surrounded with region (or just put the cursor in some place) and type `Ctrl+k, Ctrl+s`.
    
    [![Shortcut Ctrl+k, Ctrl+s](Art/snippets_01.png)](Art/snippets_01.png)

	1.2. Click on *Regions* folder.

	[![Regions folder](Art/snippets_02.png)](Art/snippets_02.png)

2. By snippet hotkey.
	
	2.1. By typing a `#r` on an empty line, a list of snippets appears. Hit `Tab` twice on the snippet you want and it will be inserted.

	[![Regions folder](Art/snippets_03.png)](Art/snippets_03.png)

### Code region snippet with custom name
Surrounds the code with regions marks when the same region name appeares in both marks

[![Region with custom name](Art/snippet_custom_01.gif)](Art/snippet_custom_01.gif)

### Code region snippet with fixed name
Surrounds code with regions marks when the region name is predefined for:
  - `Events`
  - `Fields`
  - `Properties`
  - `Constructors`
  - `Methods`

### Fixed set of code regions snippet
Adds predefined set of regions for:
  - `Class`

    [![Regions set 4 class](Art/snippets_set_class_01.png)](Art/snippets_set_class_01.png)
  - `Interface`

    [![Regions set 4 interface](Art/snippets_set_interface_01.png)](Art/snippets_set_interface_01.png)


## Contribute
Check out the [contribution guidelines](CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure
to install the
[Extensibility Tools 2015](https://marketplace.visualstudio.com/vsgallery/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE)