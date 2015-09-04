# tarbomb Disposal

Extract a tar file into the current working directory. If the contents
of the tar file are namespaced into their own directory, then this is
the same as `tar x`. However, if the contents extract all over the
working directory (i.e., a tarbomb), then a directory is first created
for them (with the same name as the archive, with `.tar` removed).

## Usage

Extract the tar `FILE` into the current working directory:

    tbd FILE

## License

[MIT License](LICENSE)

Copyright (c) 2015 Genome Research Limited
