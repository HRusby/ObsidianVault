Tar is a program for handling compressed files. Typically in the tar.gz format but it can handle many other forms of compression

## Listing Contents of an Archive
`tar -tf <ArchiveFile>`
The `-t` option specifies to list the contents

## Decompress an Archive
### Basic Usage
`tar -xf <ArchiveFile>`
In this command 
`-x` specifies to e`x`tract the files
`-f` specifies the archive `f`ile to operate on

We can add `-C` to specify the directory to extract to
`tar -xf <ArchiveFile> -C <ExtractDirectory>`

### Extracting Specific Files / Directories
`tar -xf <ArchiveFile> file1 file2`
In the above example only files of name  `file1` and `file2` will be extracted. Similar behaviour can be performed with directories e.g.
`tar -xf <ArchiveFile> dir1 dir2`
#tar #command-line 