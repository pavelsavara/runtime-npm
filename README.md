## Unofficial npm package for WASM dotnet runtime

```
npm install --save @pavelsavara/dotnet-runtime
```

See [@pavelsavara/dotnet-runtime](https://www.npmjs.com/package/@pavelsavara/dotnet-runtime)

### Build
- `powershell c:\Dev\runtime\.dotnet\dotnet-install.ps1 -AzureFeed https://dotnetbuilds.azureedge.net/public -InstallDir c:\Users\pavelsavara\.dotnet -v 7.0.100-preview.7.22327.3`
- `dotnet build /t:PackNpmPackage src\dotnet-runtime\`
- `npm publish --access public src\dotnet-runtime\pavelsavara-dotnet-runtime-7.0.100-preview.7.22327.3.tgz`