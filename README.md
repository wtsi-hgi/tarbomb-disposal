# tarbomb Disposal

Extract a tar file into the current working directory. If the contents
of the tar file are namespaced into their own directory, then this is
the same as `tar x`. However, if the contents extract all over the
working directory (i.e., a tarbomb), then a directory is first created
for them (with the same name as the archive, with the extension
removed).

## Usage

Extract the tar `FILE` into a subdirectory of the current working
directory:

    tbd [options] FILE

The following tar options can be passed through:

Flag | Option
:--: | --------------------------------
`m`  | Do not extract modification time
`o`  | Set owner to yourself
`p`  | Preserve file permissions
`v`  | Verbose output

These may be specified with or without a preceding dash.

## License

[MIT License](LICENSE)

Copyright (c) 2015 Genome Research Limited
