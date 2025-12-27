# php2go


You know PHP functions well.   
However, you don't have a good understanding of the functions in the Go standard library.   
Then this extension is for you.

Use PHP function names as snippets in Golang.

## Usage



## Common

|Snippet           |Description                                                                         |
|------------------|------------------------------------------------------------------------------------|
|`php2go: do-while`|The loop the truth expression is checked at the end of each iteration.              |
|`php2go: for`     |The for loop.                                                                       |
|`php2go: foreach` |The foreach construct provides an easy way to iterate over arrays.                  |
|`php2go: switch`  |The switch statement is similar to a series of IF statements on the same expression.|
|`php2go: while`   |The loop the truth expression is checked at the beginning of each iteration.        |




## Strings

|Snippet                     |Description                                                               |
|----------------------------|--------------------------------------------------------------------------|
|`php2go: base64_decode`     |Decodes data encoded with MIME base64.                                    |
|`php2go: base64_encode`     |Encodes data with MIME base64.                                            |
|`php2go: chr`               |Generate a single-byte string from a number.                              |
|`php2go: explode`           |Split a string by a string.                                               |
|`php2go: html_entity_decode`|Convert HTML entities to their corresponding characters.                  |
|`php2go: htmlentities`      |Convert all applicable characters to HTML entities.                       |
|`php2go: implode`           |Join array elements with a string.                                        |
|`php2go: json_decode`       |Decodes a JSON string.                                                    |
|`php2go: json_encode`       |Returns the JSON representation of a value.                               |
|`php2go: md5`               |Calculate the md5 hash of a string.                                       |
|`php2go: md5_file`          |Calculates the md5 hash of a given file.                                  |
|`php2go: ord`               |Convert the first byte of a string to a value between 0 and 255.          |
|`php2go: rawurldecode`      |Decode URL-encoded strings from RFC 3986.                                 |
|`php2go: rawurlencode`      |URL-encode according to RFC 3986.                                         |
|`php2go: sha1`              |Calculate the sha1 hash of a string.                                      |
|`php2go: sha1_file`         |Calculates the sha1 hash of a given file.                                 |
|`php2go: strlen`            |Get string length of bytes.                                               |
|`php2go: str_repeat`        |Repeat a string.                                                          |
|`php2go: str_replace`       |Replace all occurrences of the search string with the replacement string. |
|`php2go: str_word_count`    |Return information about words used in a string.                          |
|`php2go: strtolower`        |Make a string lowercase.                                                  |
|`php2go: strtoupper`        |Make a string uppercase.                                                  |
|`php2go: substr`            |Return part of a string.                                                  |
|`php2go: trim`              |Strip whitespace from the beginning and end of a string.                  |
|`php2go: urldecode`         |Decodes URL-encoded string.                                               |
|`php2go: urlencode`         |URL-encodes string.                                                       |



## Arrays

|Snippet                |Description                                                                    |
|-----------------------|-------------------------------------------------------------------------------|
|`php2go: array`        |Create a slice.                                                                |
|`php2go: array_chunk`  |Split an array into chunks.                                                    |
|`php2go: array_merge`  |Merge one or more arrays.                                                      |
|`php2go: array_push`   |Push one or more elements onto the end of array.                               |
|`php2go: array_pop`    |Push one or more elements onto the end of array.                               |
|`php2go: array_reverse`|Return an array with elements in reverse order.                                |
|`php2go: array_shift`  |Shift an element off the beginning of array.                                   |
|`php2go: array_unshift`|Prepend one or more elements to the beginning of an array.                     |
|`php2go: count`        |Counts all elements in an array.                                               |
|`php2go: in_array`     |Checks if a value exists in an array.                                          |
|`php2go: max`          |Find highest value.                                                            |
|`php2go: min`          |Find lowest value.                                                             |
|`php2go: sort`         |Sort an array in ascending order.                                              |
|`php2go: usort`        |Sort an array by values using a user-defined comparison function.              |



## Numbers

|Snippet               |Description                                                                     |
|----------------------|--------------------------------------------------------------------------------|
|`php2go: abs`         |Absolute value.                                                                 |
|`php2go: ceil`        |Round fractions up.                                                             |
|`php2go: floor`       |Round fractions down.                                                           |
|`php2go: is_nan`      |Checks whether a float is NAN.                                                  |
|`php2go: round`       |Rounds a float with precision.                                                  |
|`php2go: pi`          |Get value of pi.                                                                |


## Time

|Snippet              |Description                                                                      |
|---------------------|---------------------------------------------------------------------------------|
|`php2go: date`       |Format a Unix timestamp.                                                         |
|`php2go: date('t')`  |Number of days in the given month.                                               |
|`php2go: date('w')`  |Numeric representation of the day of the week.                                   |
|`php2go: time`       |Returns current Unix timestamp.                                                  |
|`php2go: strtotime`  |Parse some textual datetime description into a Unix timestamp.                   |
|`php2go: sleep`      |Delay execution.                                                                 |
|`php2go: usleep`     |Delay execution in microseconds.                                                 |



## Time formats

|Snippet              |Description                                                                      |
|---------------------|---------------------------------------------------------------------------------|
|`php2go: d.m.Y`      |Date format `d.m.Y`.                                                             |
|`php2go: d.m.Y H:i:s`|Date format `d.m.Y H:i:s`.                                                       |
|`php2go: Y-m-d`      |Date format `Y-m-d`.                                                             |
|`php2go: Y-m-d H:i:s`|Date format `Y-m-d H:i:s`.                                                       |



