# Windows Application Packaging Project

This project packages WinFormsApp1 and WinFormsApp2 into an MSIX installer.

## Structure
- Both WinFormTest1 and WinFormTest2 are Git submodules
- PackagingProject creates an MSIX package containing both applications

## Building
1. Open InstallerTestV2.sln in Visual Studio
2. Set PackagingProject as the startup project
3. Build the solution
4. Right-click PackagingProject and select "Publish" ? "Create App Packages"

## Notes
- Replace the placeholder images in `Images/` folder with proper application icons
- Update the Publisher certificate information in Package.appxmanifest
- Both applications will be packaged together in a single MSIX installer
