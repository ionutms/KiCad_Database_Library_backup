# KiCad Database Library

A comprehensive collection of custom KiCad symbols, footprints, and 3D models for electronic components.

## Contents:
- Schematic symbols (.lib)
- PCB footprints (.kicad_mod)
- 3D models (.step, .wrl)

Designed to enhance your KiCad projects with additional components and improve visualization.

## Usage:
1. Clone or download the repository
2. Add the library to your KiCad project
3. Enjoy an expanded selection of components for your designs!

## Adding KiCad Database Library as a Submodule

To add the KiCad Database Library as a submodule, follow these steps:

1. Open a terminal in your project's root directory.
2. Run the following command to add the submodule:

   ```
   git submodule add https://github.com/ionutms/KiCad_Database_Library_backup.git
   ```

3. Commit the changes:

   ```
   git commit -m "Add KiCad Database Library as submodule"
   ```

4. Push the changes to your remote repository:

   ```
   git push origin main
   ```

Now the KiCad Database Library is added as a submodule to your project.

## Removing the KiCad Database Library Submodule

To remove the KiCad Database Library submodule, follow these steps:

1. Deinitialize the submodule:

   ```
   git submodule deinit KiCad_Database_Library_backup
   ```

2. Remove the submodule from the working tree and .gitmodules:

   ```
   git rm KiCad_Database_Library_backup
   ```

3. Commit the changes:

   ```
   git commit -m "Remove KiCad Database Library submodule"
   ```

4. Push the changes to your remote repository:

   ```
   git push origin main
   ```

These steps work on both Linux and Windows systems. They assume the submodule is in a directory named 'KiCad_Database_Library_backup' at the root of your repository. Adjust the path if your submodule is located elsewhere.

Note: This process will remove the submodule from your repository, but some remnants might still exist in your local .git directory. If you need to completely clean up all traces of the submodule, you may need to manually remove any remaining files or folders related to the submodule in your .git directory.
