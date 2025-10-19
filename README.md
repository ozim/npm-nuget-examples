# Komendy

### npm utwórz nową bibliotekę
```
npm init
```
### instalowanie
```
npm i --ignore-scripts
npm ci --ignore-scripts
npm uninstall 
npm pack <PACKAGE_NAME>: pobieranie paczki tgz
npm run postinstall
```
### publikowanie
 - npm publish

# NuGet
### dotnet/nuget nowa biblioteka
```
dotnet new classlib
```
```
dotnet build --configuration Release    
dotnet pack --configuration Release
dotnet nuget push MorseNuget.1.0.3.nupkg --source https://api.nuget.org/v3/index.json --api-key <KEY-HERE>
```
# Bibliografia

## Generyczne supply chain
https://ntsc.org/wp-content/uploads/2025/03/The-2025-Software-Supply-Chain-Security-Report-RL-compressed.pdf
https://deepstrike.io/blog/supply-chain-attack-statistics-2025

## npm
### npm Shai Hulud
https://dev.to/andyrichardsonn/how-i-exploited-npm-downloads-and-why-you-shouldn-t-trust-them-4bme  
https://sekurak.pl/kolejny-atak-na-lancuch-dostaw-w-srodowisku-npm-kampania-shai-hulud/
https://www.blackduck.com/blog/npm-malware-attack-shai-hulud-threat.html
https://www.truesec.com/hub/blog/500-npm-packages-compromised-in-ongoing-supply-chain-attack-shai-hulud
https://www.wiz.io/blog/shai-hulud-npm-supply-chain-attack

### npm dokumentacja
https://docs.npmjs.com/cli/v8/commands/npm-ci
https://dev.to/scooperdev/use-npm-pack-to-test-your-packages-locally-486e

### npm ogólne
https://www.cookielab.io/blog/package-managers-comparison-yarn-npm-pnpm  
https://en.wikipedia.org/wiki/Npm_left-pad_incident  
https://npms.io/search?q=%40angular%2Fcli  
https://en.wikipedia.org/wiki/Npm 

## NuGet
https://www.reversinglabs.com/blog/iamreboot-malicious-nuget-packages-exploit-msbuild-loophole  
https://www.nuget.org/  
https://tedspence.com/publishing-a-dotnet-tool-on-nuget-e1df7909ec5a  
https://medium.com/azlamps/moq-scandal-or-why-caring-about-licenses-is-a-good-idea-9c5086024435
https://thehackernews.com/2024/07/60-new-malicious-packages-uncovered-in.html
https://aaronstannard.com/microsoft-delete-nuget-packages/
https://trailheadtechnology.com/securing-the-nuget-supply-chain-a-case-study/
https://gunaui.com/ - Gսոa.UI3.Wіnfօrms

### package deletion
https://github.com/NuGet/Home/discussions/14429 - 
https://aaronstannard.com/microsoft-delete-nuget-packages/

### NuGet init.ps1
https://github.com/NuGet/Home/issues/4318  
https://forums.powershell.org/t/install-package-run-install-ps1/15402
https://haacked.com/archive/2011/04/19/writing-a-nuget-package-that-adds-a-command-to-the.aspx/

### wprowadzenie 2FA w NuGet 
https://devblogs.microsoft.com/dotnet/requiring-two-factor-authentication-on-nuget-org/

## Ruby
https://www.ruby-lang.org/en/news/2025/10/17/rubygems-repository-transition/  
https://rubygems.org/stats  
https://rubygems.org/
