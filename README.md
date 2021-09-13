# Store.Cli

Store.Cli is a kind of command-line "Store appx fetcher" (for Win 10/11 Desktop). 
It's CLI console app that makes use of [StoreLib](https://github.com/StoreDev/StoreLib).
Please use it for RnD any "MS Store" entities =)

# Screenshots
![Shot 1](https://github.com/mediaexplorer74/Store.Cli/blob/main/shot.png)

## Usage

Clone the repo and build StoreWeb using either Visual Studio 2019, VS Code or dotnet CLI.


### "CMD Build" 

```sh
dotnet build
```

### Run

Run Store.Cli.exe to start this console app from Command line interface (please start cmd.exe as Administrator)



#### Dependencies
[StoreLib](https://github.com/StoreDev/StoreLib)
.NET 4.8 FrameWork installed


# Solution Layout
Projects have a README.MD which expands on the internal functionality and layout of that project. 


A brief summary of each project is as follows:
- **[Store.Cli](./Store.Cli/)** - The main part (frontend) with store "CLI" commands realization
  - All components are integrated into this project
  - This has StoreLib reference
- **[StoreLib](./StoreLib/)** - Library for MS Store connection
  - search packages
  - make package urls for direct downloading
  - some cool helpers (i.e., app screnshots' url getter)
- **[StoreLib.Tests](./StoreLib.Tests/)** - "Background" (tests)
  - FE3 tests (contains some useful things to research!)
  - DisplayCatalog tests


With best wishes,

  [m][e] 2021


# Thanks!
I wanted to put down some thank you's here for folks/projects/websites that were invaluable for helping me get this project into a functional state:
- [TitleOS](https://github.com/TitleOS) - StoreLib and StoreWeb creator/author
- [StoreLib](https://github.com/StoreDev/StoreLib) - DotNet library that provides APIs to interact with the various Microsoft Store endpoints.
- [StoreWeb](https://github.com/StoreDev/StoreWeb) - An interface for StoreLib created in ASP.NET

# License & Copyright

Store.Cli is RnD project. AS-IS. No support. Distributed under the MIT License. 
