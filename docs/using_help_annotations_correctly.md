## Using help annotations

Whenever using help annotations, please see these 3 steps below.

1. Make sure you first write `github:`, so MakeCode knows to fetch a repository on GitHub
2. Write the repository's name **without any spaces after writing the colon**
3. Add a slash command to tell the compiler to read a specific file in the repository
4. If it is a folder in a repository, write the folder's name and then another slash command
5. Finally, add the file's name (**the file's path must be right or it will not be load**)
6. Also, make sure to **not** add .md in the end of the file path because MakeCode already reads doc files as markdown files.
7. 

Here is a snippet showing how to use the helper annotation correctly.
``` ts 
//% help=github:pxt-hardware-programming-docs/docs/_getFactoryInstance
function _getFactoryInstance() {
    // No code for now, do not worry about the code right here, only the doc rendering error
}
_getFactoryInstance() 

//% help=github:pxt-hardware-programming-docs/docs/allocate
function allocate() {} 
allocate()

//% help=github:pxt-hardware-programming-docs/docs/binRange
function binRange() {}
binRange()

//% help=github:pxt-hardware-programming-docs/docs/analyzing_code
function analyzing_code() {}
analyzing_code()

//% help=github:pxt-hardware-programming-docs/docs/bpp
function bpp() {}
bpp()

//% help=github:pxt-hardware-programming-docs/docs/fixed-size
function fixedSize() {}
fixedSize()

//% help=github:pxt-hardware-programming-docs/docs/exportModifier
function exportModifier() {}
exportModifier()

//% help=github:pxt-hardware-programming-docs/docs/decoder 
function decoder() {}
decoder()
```
