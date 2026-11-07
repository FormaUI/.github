FormaUI is an umbrella project for open-source software. We believe people should be able to use applications in their own language, on the devices they use, and in the ways that work for them. Our tools make it easier for developers to build software that gives people those choices. Everything is free to use, with no gotchas.

**Eyal Alon** — I’m the programmer behind FormaUI. I designed the architecture and made every technical decision, down to the smallest detail. I wrote and refined the code with Claude Code as my pair programmer.

## [Forma](https://github.com/FormaUI/Forma)

Forma is a .NET 11 Blazor component library for input, navigation, layout, dialogs, and working with files. The same components run in Blazor Web Apps, standalone WebAssembly apps, and Blazor Hybrid apps built with WPF, Windows Forms, or .NET MAUI. Every component supports localization, left-to-right and right-to-left layouts, and theming through design tokens.

**Get it**

- [Interactive Server](https://github.com/FormaUI/Forma#set-up-a-server-host)
- [WebAssembly and Auto](https://github.com/FormaUI/Forma#webassembly-components)
- [Blazor Hybrid](https://github.com/FormaUI/Forma#blazor-hybrid)

## [Nexo](https://github.com/FormaUI/Nexo)

Nexo is an embeddable language with no domain of its own. The host declares a typed vocabulary, and scripts use it to compute and shape data. Nexo checks each script against that vocabulary before it runs and returns plain, immutable data.

**Get it**

- [NuGet](https://www.nuget.org/packages/formaui-net.Nexo)
- [npm](https://www.npmjs.com/package/@formaui-net/nexo)

## [DOMQL](https://github.com/FormaUI/DOMQL)

DOMQL is a JavaScript library for working with the DOM through queries written in Nexo. A query can read the document once or keep its result current as the document changes. Scripts can also subscribe to events and perform actions such as focusing an element, scrolling it into view, or opening a popover.

**Get it**

- [NuGet](https://www.nuget.org/packages/formaui-net.DOMQL)
- [npm](https://www.npmjs.com/package/@formaui-net/domql)

## [Locali](https://github.com/FormaUI/Locali)

Locali is a .NET tool that checks Forma locale files and the C#, Visual Basic, and Razor code that reads them. It applies the same lookup rules as the runtime so you can catch localization errors before the application runs.

**Get it**

- [NuGet](https://www.nuget.org/packages/formaui-net.Locali)

## [Versioning](https://github.com/FormaUI/Versioning)

Versioning defines the versioning, branching, commit, release, and packaging rules for every FormaUI project. Its GitHub Actions enforce those rules.

**Get it**

- [GitHub releases](https://github.com/FormaUI/Versioning/releases)

## Preview releases

All projects are in preview. Releases use `1.0.0-preview.N`. A project’s contract can change between previews, and breaking changes come with migration notes.

To install a preview from NuGet, pass `--prerelease` to `dotnet`. On npm, use `npm install @formaui-net/nexo@preview` or `npm install @formaui-net/domql@preview`.
