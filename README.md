# Opinionated template for new .Net-Core solutions

This repository acts as a starting point for new .Net-Core applications.

## Features

- Generic [.editorconfig](https://docs.microsoft.com/en-us/visualstudio/ide/create-portable-custom-editor-options) with naming rules
- [Global.json](https://docs.microsoft.com/en-us/aspnet/core/?view=aspnetcore-3.0) to lock .Net-Core SDK
- [.vsconfig](https://devblogs.microsoft.com/setup/configure-visual-studio-across-your-organization-with-vsconfig/) to discover required Visual Studio components
-  [Default Roslyn analyzers](https://github.com/BrunoZell/blank-dotnet-solution-template/blob/master/analyzers.props) with a [solid ruleset](https://docs.microsoft.com/en-us/visualstudio/code-quality/using-rule-sets-to-group-code-analysis-rules?view=vs-2019)

## Todo

- [ ] Publish as NuGet package
- [ ] Parameterize hardcoded versions
