# Web Extension Pack

[![Build status](https://ci.appveyor.com/api/projects/status/7yqisx9nepdo5auu?svg=true)](https://ci.appveyor.com/project/madskristensen/webextensionpack)

Download the extension at the
[VS Gallery](https://visualstudiogallery.msdn.microsoft.com/f3b504c6-0095-42f1-a989-51d5fc2a8459)
or get the
[nightly build](http://vsixgallery.com/extension/92e3e73b-510f-45bb-8aee-c637e83778b3/)

------------------------------------

A Visual Studio extension that installs a short list of
highly valuable extensions targeted web development.

See the [change log](CHANGELOG.md) for changes and road map.

## Extensions
After installing the Web Extension Pack and restarting
Visual Studio, the following extensions will be installed:

- [Add New File](https://visualstudiogallery.msdn.microsoft.com/3f820e99-6c0d-41db-aa74-a18d9623b1f3)
- [Browser Reload on Save](https://visualstudiogallery.msdn.microsoft.com/46eef4d9-045b-4596-bd7f-eee980bb5450)
- [Browser Sync](https://visualstudiogallery.msdn.microsoft.com/5741a548-5179-4a77-ad96-fca71535774d)
- [Bundler & Minifier](https://visualstudiogallery.msdn.microsoft.com/9ec27da7-e24b-4d56-8064-fd7e88ac1c40)
- [Editor Enhancements](https://visualstudiogallery.msdn.microsoft.com/4f64e542-3772-4136-8f87-0113441c7aa1)
- [File Icons](https://visualstudiogallery.msdn.microsoft.com/5e1762e8-a88b-417c-8467-6a65d771cc4e)
- [File Nesting](https://visualstudiogallery.msdn.microsoft.com/3ebde8fb-26d8-4374-a0eb-1e4e2665070c)
- [Glyphfriend](https://visualstudiogallery.msdn.microsoft.com/5fd24afb-b3b2-4cec-9b03-1cfcec6123aa)
- [HTML Snippet Pack](https://visualstudiogallery.msdn.microsoft.com/57a8ac31-775a-428c-ade9-6837d183a4dc)
- [Image Sprites](https://visualstudiogallery.msdn.microsoft.com/8bb845e9-5717-4eae-aed3-1fdf6fe5819a)
- [Image Optimizer](https://visualstudiogallery.msdn.microsoft.com/a56eddd3-d79b-48ac-8c8f-2db06ade77c3)
- [JavaScript Snippet Pack](https://visualstudiogallery.msdn.microsoft.com/423eb4a3-215f-4a8f-9287-1512618ffda3)
- [Markdown Editor](https://visualstudiogallery.msdn.microsoft.com/eaab33c3-437b-4918-8354-872dfe5d1bfe)
- [Open Command Line](https://visualstudiogallery.msdn.microsoft.com/4e84e2cf-2d6b-472a-b1e2-b84932511379)
- [Package Installer](https://visualstudiogallery.msdn.microsoft.com/753b9720-1638-4f9a-ad8d-2c45a410fd74)
- [Suggested Extensions](https://visualstudiogallery.msdn.microsoft.com/3be88243-8bf1-407a-a7ca-a968d0de2d59)
- [Web Accessibility Checker](https://visualstudiogallery.msdn.microsoft.com/3aabefab-1681-4fea-8f95-6a62e2f0f1ec)
- [Web Compiler](https://visualstudiogallery.msdn.microsoft.com/3b329021-cd7a-4a01-86fc-714c2d05bb6c)
- [Web Essentials 2015](https://visualstudiogallery.msdn.microsoft.com/ee6e6d8c-c837-41fb-886a-6b50ae2d06a2)

If you already have one or more of these extensions installed,
Web Extension Pack will not re-install them. It will simply
just skip them.

### Honorable mentions
These extensions are not included, but they are likely to be of
interest.

- [.ignore](https://visualstudiogallery.msdn.microsoft.com/d0eba56d-603b-45ab-a680-edfda585f7f3)
- [NPM Task Runner](https://visualstudiogallery.msdn.microsoft.com/8f2f2cbc-4da5-43ba-9de2-c9d08ade4941)
- [Client-Side Library Installer](https://visualstudiogallery.msdn.microsoft.com/4cd5e0e0-2c38-426b-9f43-1d3688cc8be1)
- [Open in VS Code](https://visualstudiogallery.msdn.microsoft.com/33f6f3fd-68e8-4783-b934-ece91a08d265)
- [SideWaffle Template Pack](https://visualstudiogallery.msdn.microsoft.com/a16c2d07-b2e1-4a25-87d9-194f04e7a698)
- [Text Generator](https://visualstudiogallery.msdn.microsoft.com/4d809607-87dd-445c-8cd4-585da67c6beb)
- [Trailing Whitespace Visualizer](https://visualstudiogallery.msdn.microsoft.com/a204e29b-1778-4dae-affd-209bea658a59)

## Installing
It doesn't take long to install the extensions. Probably less
than a minute.

![Installing progress](art/progress.png)

When installation is done you will be prompted to restart
Visual Studio. After the restart, all the extensions are
fully functional and ready to use.

## Reset Web Extension Pack
If you've uninstalled any of the extensions installed by Web Extension
Pack, then those extensions won't be installed again automatically.

To reset this behavior go to _Tools -> Reset Web Extension Pack..._

## Suggest new extensions
If you know of any good extensions that you think would benefit web
developers, then log an issue with the suggestion on the 
[GitHub issue tracker](https://github.com/madskristensen/WebExtensionPack/issues).

## Contribute
Check out the [contribution guidelines](.github/CONTRIBUTING.md)
if you want to contribute to this project.

For cloning and building this project yourself, make sure 
to install the
[Extensibility Tools 2015](https://visualstudiogallery.msdn.microsoft.com/ab39a092-1343-46e2-b0f1-6a3f91155aa6)
extension for Visual Studio which enables some features
used by this project.

## License
[Apache 2.0](LICENSE) 