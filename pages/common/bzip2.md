# bzip2

> A block-sorting file compressor.
> More information: <https://manned.org/bzip2>.

- Compress a file:

`bzip2 {{path/to/file_to_compress}}`

- Decompress a file:

`bzip2 -d {{path/to/compressed_file.bz2}}`

- Decompress a file to standard output:

`bzip2 -dc {{path/to/compressed_file.bz2}}`

- Test the integrity of each file inside the archive file:

`bzip2 -t {{path/to/compressed_file.bz2}}`

- Show the compression ratio for each file processed with detailed information:

`bzip2 -v {{path/to/compressed_files.bz2}}`

- Decompress a file overwriting existing files:

`bzip2 -f {{path/to/compressed_file.bz2}}`

- Display help:

`bzip2 -h`
