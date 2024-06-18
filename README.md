# las-decomp
Decompilation of Link's Awakening Switch (2019 remake) for Nintendo Switch using Ghidra

**Note**: You must provide your own `main` file

# Importing

Instructions:
1. Goto `File` -> `Import File...` and import your unaltered copy of the `main` file
2. Open `main` in the CodeBrowser
3. Goto `File` -> `Add to Program...`
4. Select the `main.xml` from this [repository](https://github.com/Owen-Splat/las-decomp/releases/latest) and click `Add to Program`


# Exporting

Instructions:
1. Right-click `main` and choose `Export` from the Active Project window
2. Choose `XML` as the format
3. Click `Options`:
   - Deselect `Memory Contents` so that the code binaries are **NOT** included
4. Click `OK`
