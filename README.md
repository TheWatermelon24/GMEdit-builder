# builder (With GMS1.4.9999 Support!)


# About (original)
builder was made to make [GMEdit](https://yellowafterlife.itch.io/gmedit) usable without the need of having GameMaker Studio 2 open in the background to compile projects. builder works by using your pre-existing settings made by GMS 2 to pass arguments into GMAssetCompiler and compile your project. builder was developed with faster development in mind, skipping most file generation and secondary applications being required to compile. builder even supports switching the runtime that you build your project with as well as compiling the project as it's already running! You can download a pre-packaged version of builder from [here!](https://github.com/nommiin/builder/releases)
###### (ORIGINAL README SUPPORT)
If you found the plugin useful, consider donating to help support development on [itch.io!](https://nommiiin.itch.io/builder)

# Usage (GameMaker Studio 2)
1. create a folder named "builder" inside of `%appdata%/AceGM/GMEdit/plugins/` on Windows, `/Users/<username>/Library/Application Support/AceGM/GMEdit/plugins` on macOS
2. clone this repo and copy all files into "builder" folder
3. launch GMEdit and open a project
4. open the main menu and select "Run Project"
5. optional: adjust what runtime to use in the "Preferences" menu

# Usage (GameMaker Studio 1.4.9999)
1. create a folder named "builder" inside of `%appdata%/AceGM/GMEdit/plugins/` on Windows, `/Users/<username>/Library/Application Support/AceGM/GMEdit/plugins` on macOS
2. clone this repo and copy all files into "builder" folder
3. Move the "FreeGMAssetCompiler.exe" file onto your Game Maker installation
4. launch GMEdit and open a project
5. Go to Preferences -> builder-settings and fill "FreeGMAssetCompiler Path"
![[GMAssetCompilerPath.png]]
With this done, it should work when opening a project and hitting F5 or "Run" button in the tools menu.
# Know Issues (Probably never fixing)
* Only Run button works with GMS1.4.9999

# Help
* Please refer to the [Original Plugin Repository](https://github.com/YAL-GMEdit/builder) for help.
* In case you are having the error `Error: FreeGMAssetCompiler Not Found`even when you did move the file onto your Game Maker Installation, try moving the Game Maker Studio 1.4.9999 files to: `C:\ProgramFiles\GameMaker-Studio`

# Thanks
* [nommiin](https://github.com/nommiin/builder/commits?author=nommiin) for making the original plugin.
##### Original Readme Thanks
* [YellowAfterlife](https://twitter.com/YellowAfterlife) for accepting PRs that help the core functionality of this plugin, answering my endless questions, submitting PRs that help improve the plugin, and providing the screenshot used in the readme
* [Sidorakh](https://github.com/sidorakh/) for testing and supporting the plugin
* [Katie](https://twitter.com/347online) for encouraging me to add macOS support to the plugin
