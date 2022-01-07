# Outward Mod Template

A template for creating a C# Outward Mod.

## How to use

1. Either clone/download the repository with Git or GitHub Desktop, or simply download the code manually.
* **NOTE**: If you download the `.zip` manually, you will need to restore the NuGet packages, either by running the command `dotnet restore` in your project folder, or by opening the NuGet Package Manager and clicking the button to restore packages.
3. Open `src/OutwardModTemplate.sln` with any C# IDE (Visual Studio, Rider, etc)
4. Open the `MyMod.cs` file and follow the instructions
5. When you're ready, build the solution. It will be built to the `Release` folder (next to the `src` folder).
6. Take the DLL from the `Release` folder and put it in the `BepInEx/plugins/` folder. If you use r2modman, this can be found by going into r2modman settings and clicking on `Browse Profile Folder`.

For further help, see the [Outward Modding Wiki](https://outward.fandom.com/wiki/Getting_Started_Developing_Mods), or join the [Outward Modding Discord](https://discord.gg/zKyfGmy7TR).
