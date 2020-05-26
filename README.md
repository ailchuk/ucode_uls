# uls

## Synopsys

    ./uls [-AFRSldmortu1] [file ...]

## Description

Implementation of the famous Unix command ```ls```, using the C programming
language.

## How to use

### Compilation:

    make

### Reinstalliation

    make reinstall

### Uninstalliation

    make uninstall

## Supported flags
 
|Flag|Description|
|----|------------------------------------------------------------------------|
|```1```|The numeric digit ```one```. Force output to be one entry per line. This is the default when output is not to a terminal.|
|```A```|List all entries except for ```.``` and ```..```.|
|```F```|Display a slash (```/```) immediately after each pathname that is a directory, an asterisk (```*```) after each that is executable, an at sign(```@```) after each symbolic link, an equals sign (```=```) after each socket, a percent sign (```%```) after each whiteout, and a vertical bar after each that is a FIFO.|
|```l```|The lowercase letter ```ell```. List in long format. If the output is to a terminal, a total sum for all the file sizes is output on a line before  the long listing.|
|```m```|Stream output format; list files across the page, separated by   commas.|
|```o```|List in long format, but omit the group id.|
|```R```|Recursively list subdirectories encountered.|
|```r```|Reverse the order of the sort to get reverse lexicographical order or the oldest entries first (or largest files last, if combined with sort by size.|
|```S```|Sort files by size.|
|```t```|Sort by time modified (most recently modified first) before sorting  the operands by lexicographical order.|
|```u```|Use time of last access, instead of last modification of the file for sorting (```-t```) or long printing (```-l```).|

## Developers: 
- Andrii Ilchuk [@ailchuk](https://github.com/ailchuk)
- Oleksiy Nechaiev [@onechaiev](https://github.com/jacomogrelli)

## License

Collision is an open-sourced software licensed under the
[MIT license](LICENSE.md).
