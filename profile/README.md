FormaUI builds Forma, a Blazor component library for .NET, and Nexo, an embeddable language for computing and shaping data. DOMQL uses Nexo to query and observe the DOM. Locali checks Forma’s localization, and Versioning defines how we release our projects.

| Project | What it does | Get it |
| --- | --- | --- |
| [Forma](https://github.com/FormaUI/Forma) | Provides .NET 11 Blazor components for input, navigation, layout, dialogs, and working with files. Every component supports localization and both left-to-right and right-to-left layouts. The host application can theme components through design tokens. | [`formaui-net.Blazor.Server`](https://www.nuget.org/packages/formaui-net.Blazor.Server) on NuGet |
| [Nexo](https://github.com/FormaUI/Nexo) | The host application declares a typed vocabulary. Scripts use that vocabulary to compute and shape data. Nexo checks each script before it runs and returns plain, immutable data. | [`formaui-net.Nexo`](https://www.nuget.org/packages/formaui-net.Nexo) on NuGet and [`@formaui-net/nexo`](https://www.npmjs.com/package/@formaui-net/nexo) on npm |
| [DOMQL](https://github.com/FormaUI/DOMQL) | A JavaScript library that runs queries written in Nexo against the DOM. Run a query once to read the document, or observe its result as the document changes. | [`formaui-net.DOMQL`](https://www.nuget.org/packages/formaui-net.DOMQL) on NuGet |
| [Locali](https://github.com/FormaUI/Locali) | Checks Forma locale files and the C#, Visual Basic, and Razor code that reads them. It applies the same lookup rules as the runtime so you can catch localization errors before the application runs. | [`formaui-net.Locali`](https://www.nuget.org/packages/formaui-net.Locali), a .NET tool |
| [Versioning](https://github.com/FormaUI/Versioning) | Defines the versioning, branching, commit, release, and packaging rules for every FormaUI project. Its GitHub Actions enforce those rules. | Pin its GitHub Actions to a release. |

All projects are in preview. Releases use `1.0.0-preview.N`. A project’s contract can change between previews, and breaking changes come with migration notes.

To install a preview from NuGet, pass `--prerelease` to `dotnet`. On npm, install `@formaui-net/nexo@preview`.
