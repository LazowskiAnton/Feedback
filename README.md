# Feedback

Bug reports and ideas for my free Visual Studio extensions. The extensions are closed source; this repository only collects feedback.

| Extension | What it does | Links |
|---|---|---|
| **ColorSmith** | Color swatches in the editor and a real color picker. A swatch appears only where the code really defines a color. | [Documentation](https://lazowskianton.github.io/VSExtensions/colorsmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.ColorSmith) |
| **OutputSmith** | A readable Output window: errors stand out, build and test results at a glance, noise dimmed. | [Documentation](https://lazowskianton.github.io/VSExtensions/outputsmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.OutputSmith) |
| **LensSmith** | Errors, warnings and messages at the end of their line, the line tinted by the problem — in C#, C++, TypeScript, XAML and more. | [Documentation](https://lazowskianton.github.io/VSExtensions/lenssmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.LensSmith) |
| **LocaleSmith** | The text behind every .resx key, right where the key is used in C#, XAML and Razor: every translation on hover, missing ones flagged. | [Documentation](https://lazowskianton.github.io/VSExtensions/localesmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.LocaleSmith) |
| **NoteSmith** | Comments that stand out: TODO, FIXME and your own tags in color, every TODO of the solution in one window, anchors in long files. | [Documentation](https://lazowskianton.github.io/VSExtensions/notesmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.NoteSmith) |
| **PackageSmith** | NuGet package versions right in .csproj and Directory.Packages.props: the newest version after every package, vulnerable and deprecated ones flagged, update with Ctrl+. | [Documentation](https://lazowskianton.github.io/VSExtensions/packagesmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.PackageSmith) |
| **RulerSmith** | Sizes and distances of controls while you debug: hold Ctrl+Shift over the app — the control under the pointer, its size and the gaps to its neighbours, in WPF, WinForms, Win32 and web pages. | [Documentation](https://lazowskianton.github.io/VSExtensions/rulersmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.RulerSmith) |
| **TidySmith** | C# code in the order your team wants: members sorted with a preview and one Undo, regions by your rules, comments wrapped — and hints where something can be tidied. | [Documentation](https://lazowskianton.github.io/VSExtensions/tidysmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.TidySmith) |
| **SnapSmith** | Beautiful pictures of code straight from Visual Studio: your editor colors or 12 themes, window frames, 16 backgrounds and four of your own — PNG or SVG, nothing uploaded. | [Documentation](https://lazowskianton.github.io/VSExtensions/snapsmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.SnapSmith) |
| **BuildSmith** | What your build did and why it took that long: the time and the change in the status bar, every project on a timeline with the critical path, projects that are never up to date, a history of builds with labels, and a comparison of up to ten builds. | [Documentation](https://lazowskianton.github.io/VSExtensions/buildsmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.BuildSmith) |
| **RegexSmith** | Regular expressions explained and tested right in the C# editor: a plain-language breakdown on hover with groups in color and sample strings, patterns that can hang underlined with fixes, and a tester that writes the pattern back to the code. | [Documentation](https://lazowskianton.github.io/VSExtensions/regexsmith/) · [Marketplace](https://marketplace.visualstudio.com/items?itemName=LazowskiAnton.RegexSmith) |

All extensions are free, have no telemetry and support Visual Studio 2022 and 2026. The [extensions site](https://lazowskianton.github.io/VSExtensions/) has them all in 14 languages.

## How to give feedback

Open [**Issues → New issue**](https://github.com/LazowskiAnton/Feedback/issues/new/choose) and pick a form:

- **Bug report** — something does not work or looks wrong.
- **Idea** — a feature you would like to have.
- **OutputSmith: line not recognized** — a line of the Output window that should be colored differently.

Before you write, please search the [existing issues](https://github.com/LazowskiAnton/Feedback/issues?q=is%3Aissue): if your problem or idea is already there, add a 👍 to it instead of a new issue — the 👍 count helps to decide what comes first.

### Please keep private things private

Issues here are public. Before you paste output, code or screenshots, replace company, product, project and person names, paths and keys with neutral ones (for example `Contoso`). The structure of a line is what matters, not the names.

### Language

English is preferred, but you can write in any language the extensions support.

## What happens next

Each issue gets labels: the extension it is about, its type and its status.

| Label | Meaning |
|---|---|
| `planned` | Accepted, will be done in one of the next versions. |
| `done` | Done; the issue mentions the version. |
| `needs info` | More details are needed — please check the questions in the issue. |
| `won't do` | Out of scope for the extension; the reason is in the issue. |

There is no promised response time, but every issue is read.

## Releases

What changed in each version: in the changelog of the extension's documentation ([ColorSmith](https://lazowskianton.github.io/VSExtensions/colorsmith/#changelog), [OutputSmith](https://lazowskianton.github.io/VSExtensions/outputsmith/#changelog), [LensSmith](https://lazowskianton.github.io/VSExtensions/lenssmith/#changelog), [LocaleSmith](https://lazowskianton.github.io/VSExtensions/localesmith/#changelog), [NoteSmith](https://lazowskianton.github.io/VSExtensions/notesmith/#changelog), [PackageSmith](https://lazowskianton.github.io/VSExtensions/packagesmith/#changelog), [RulerSmith](https://lazowskianton.github.io/VSExtensions/rulersmith/#changelog), [TidySmith](https://lazowskianton.github.io/VSExtensions/tidysmith/#changelog), [SnapSmith](https://lazowskianton.github.io/VSExtensions/snapsmith/#changelog), [BuildSmith](https://lazowskianton.github.io/VSExtensions/buildsmith/#changelog), [RegexSmith](https://lazowskianton.github.io/VSExtensions/regexsmith/#changelog)).
