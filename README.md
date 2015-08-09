## blp

BLP API as provided by [Bloomberg Labs](http://www.bloomberglabs.com/api/libraries/)

### Why

Packaging the required headers and shared libraries separately appeared as a
good solution in a discussion between the [CRAN](http://cran.r-project.org)
maintainers and the authors of the [Rblpapi](https://github.com/Rblp/Rblpapi)
package which depends on these.  It allows us to keep the
[Rblpapi](https://github.com/Rblp/Rblpapi) free of binary blobs, yet provides
a way for fully automated builds of the package on all supported platforms
(a set which currently consists of both Linux and Windows).

### Usage

The files herein are used chiefly by the respective build scripts for
compiling [Rblpapi](https://github.com/Rblp/Rblpapi).  One can access the
files via the 'raw' URLs, eg for the archive containing the 32-bit Linux
shared library one uses
`https://github.com/Rblp/blp/raw/master/linux32/blpLibrary.tar.gz` 

### License

The BLP API is release under the following license (cf
[License.txt](https://github.com/Rblp/blp/blob/master/License.txt)):

> Copyright 2012. Bloomberg Finance L.P.
> 
> Permission is hereby granted, free of charge, to any person obtaining a copy of
> this proprietary software and associated documentation files (the "Software"),
> to use, publish, or distribute copies of the Software, and to permit persons to
> whom the Software is furnished to do so.
> 
> Any other use, including modifying, adapting, reverse engineering, decompiling,
> or disassembling, is not permitted.
> 
> The above copyright notice and this permission notice shall be included in all
> copies or substantial portions of the Software.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
> IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
> FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
> AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
> LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
> OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
> SOFTWARE.


### Authors

This repo was put together by Dirk Eddelbuettel.
