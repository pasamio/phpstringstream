The PHP "String" Stream Wrapper is a simple stream wrapper for PHP that is
designed to handle simple strings within PHP. There are two classes included:
one to "control" the virtual streams and another to translate the string into
the stream interface for use with functions that accept file pointers (e.g.
fgetcsv, fread, etc).