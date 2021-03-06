# Other single-file public-domain/open source libraries with minimal dependencies

In addition to all of [my libraries](https://github.com/nothings/stb), there are other, similar libraries.

People have told me about quite a few of these. However, I haven't used most of these libraries
and can't comment on their quality. (If you use them and aren't their author, feel
free to tell me about their quality.

**Public domain single-file libraries usable from C and C++ are in bold.** Other libraries are either non-public domain,
or two files, or only usable from C++, or all three.

For the API column, "C" means C only, "C++" means C++ only, and "**C**" means C/C++;
I use this notation to keep the column a little narrower than "C/C++" would be.
(As of this writing, the API is unknown for many libraries, and the benefit of the doubt
is given for boldfacing.)

category          | library                                                               | license              | API |files| description
----------------- | --------------------------------------------------------------------- | -------------------- | --- | --- | -----------
AI                |  [micropather](http://www.grinninglizard.com/MicroPather/)            | zlib                 | C++ |  2  | pathfinding with A*
audio             |  [aw_ima.h](https://github.com/afterwise/aw-ima/blob/master/aw-ima.h) | MIT                  |     |**1**| IMA-ADPCM audio decoder
compression       |  [miniz.c](https://github.com/richgel999/miniz)                       |**public&nbsp;domain**|**C**|  2  | compression,decompression, zip file, png writing
compression       |  [lz4](https://github.com/Cyan4973/lz4)                               | BSD                  |     |  2  | fast but larger LZ compression
compression       |  [fastlz](https://code.google.com/p/fastlz/source/browse/#svn%2Ftrunk)| MIT                  |     |  2  | fast but larger LZ compression
compression       |  [pithy](https://github.com/johnezang/pithy)                          | BSD                  |     |  2  | fast but larger LZ compression
crypto            |  [TweetNaCl](http://tweetnacl.cr.yp.to/software.html)                 | **public domain**    |     |  2  | high-quality tiny cryptography library
data structures   |  [klib](http://attractivechaos.github.io/klib/)                       | MIT                  |     |  2  | many 2-file libs: hash, sort, b-tree, etc
data structures   |  [uthash](https://github.com/troydhanson/uthash)                      | BSD                  |     |  2  | several 1-header, 1-license-file libs: generic hash, list, etc
data structures   |  [PackedArray](https://github.com/gpakosz/PackedArray)                | **WTFPLv2**          |     |  2  | memory-efficient array of elements with non-pow2 bitcount
data structures   |  [minilibs](https://github.com/ccxvii/minilibs)                       | **public domain**    |     |  2  | two-file binary tress (also regex, etc)
files & filenames |**[DG_misc.h](https://github.com/DanielGibson/Snippets/)**             | **public domain**    |     |**1**| Daniel Gibson's stb.h-esque cross-platform helpers: path/file, strings
files & filenames |  [whereami](https://github.com/gpakosz/whereami)                      |**WTFPLv2**           |     |  2  | get path/filename of executable or module
geometry          |**[nv_voronoi.h](http://www.icculus.org/~mordred/nvlib/)**             | **public domain**    |     |**1**| find voronoi regions on lattice w/ integer inputs
geometry          |**[sobol.h](https://github.com/Marc-B-Reynolds/Stand-alone-junk/)**    | **public domain**    |     |**1**| sobol & stratified sampling sequences
geometry          |  [sdf.h](https://github.com/memononen/SDF)                            | MIT                  |     |**1**| compute signed-distance field from antialiased image
geometry          |  [nanoflann](https://github.com/jlblancoc/nanoflann)                  | BSD                  |     |**1**| build KD trees for point clouds
geometry          |  [jc_voronoi](https://github.com/JCash/voronoi)                       | MIT                  |     |**1**| find voronoi regions on float/double data
geometry          |  [par_msquares](https://github.com/prideout/par)                      | MIT                  |     |**1**| convert (binarized) image to triangles
geometry          |  [tk_objfile](https://github.com/joeld42/tk_objfile)                  | MIT                  |     |**1**| OBJ file loader
geometry          |  [par_shapes](http://github.prideout.net/shapes/)                     | MIT                  |     |**1**| generate various 3d geometric shapes
geometry          |  [Tomas Akenine-Moller snippets](http://tinyurl.com/ht79ndj)          | **public domain**    |     |  2  | various 3D intersection calculations, not lib-ified
geometry          |  [Clipper](http://www.angusj.com/delphi/clipper.php)                  | Boost                |     |  2  | line & polygon clipping & offsetting
geometry          |  [PolyPartition](https://github.com/ivanfratric/polypartition)        | MIT                  |     |  2  | polygon triangulation, partitioning
graphics (2d)     |  [blendish](https://bitbucket.org/duangle/oui-blendish/src)           | MIT                  |     |**1**| blender-style widget rendering
graphics (2d)     |  [tigr](https://bitbucket.org/rmitton/tigr/src)                       | **public domain**    |     |  2  | quick-n-dirty window text/graphics for Windows
graphics (2d)     |  [noc_turtle](https://github.com/guillaumechereau/noc)                | **public domain**    |     |  2  | procedural graphics generator
graphics (3-D)    |  [tinyobjloader](https://github.com/syoyo/tinyobjloader)              | BSD                  |     |**1**| wavefront OBJ file loader
graphics (3-D)    |  [mikktspace](http://tinyurl.com/z6xtucm)                             | zlib                 |     |  2  | compute tangent space for normal mapping
hardware          |**[EasyTab](https://github.com/ApoorvaJ/EasyTab)**                     | **public domain**    |**C**|**1**| multi-platform tablet input
images            |**[jo_gif.cpp](http://www.jonolick.com/home/gif-writer)**              | **public domain**    |     |**1**| animated GIF writer
images            |**[gif.h](https://github.com/ginsweater/gif-h)**                       | **public domain**    |     |**1**| animated GIF writer
images            |**[tiny_jpeg.h](https://github.com/serge-rgb/TinyJPEG/)**              | **public domain**    |     |**1**| JPEG encoder
images            |**[miniexr](https://github.com/aras-p/miniexr)**                       | **public domain**    |     |**1**| OpenEXR writer
images            |  [tinyexr](https://github.com/syoyo/tinyexr)                          | BSD                  |     |**1**| EXR image read/write, uses miniz internally  
images            |  [lodepng](http://lodev.org/lodepng/)                                 | zlib                 |     |**1**| PNG encoder/decoder
images            |  [nanoSVG](https://github.com/memononen/nanosvg)                      | zlib                 |     |**1**| 1-file SVG parser; 1-file SVG rasterizer
images            |  [picopng.cpp](http://lodev.org/lodepng/picopng.cpp)                  | zlib                 | C++ |  2  | tiny PNG loader
images            |  [jpeg-compressor](https://github.com/richgel999/jpeg-compressor)     | **public domain**    |     |  2  | 2-file jpeg compress, 2-file jpeg decompress
math              |  [mm_vec.h](https://github.com/vurtun/mmx)                            | BSD                  |     |**1**| SIMD vector math
math              |  [ShaderFastLibs](https://github.com/michaldrobot/ShaderFastLibs)     | MIT                  |     |**1**| approximate transcendental functions optimized for shaders (esp. GCN)
math              |  [TinyExpr](https://github.com/codeplea/tinyexpr)                     | zlib                 |  C  |  2  | evaluation of math expressions from strings
multithreading    |  [mm_sched.h](https://github.com/vurtun/mmx)                          | zlib                 |     |**1**| cross-platform multithreaded task scheduler
network           |**[zed_net](https://github.com/ZedZull/zed_net)**                      | **public domain**    |     |**1**| cross-platform socket wrapper
network           |  [mm_web.h](https://github.com/vurtun/mmx)                            | BSD                  |     |**1**| lightweight webserver, fork of webby
network           |  [par_easycurl.h](https://github.com/prideout/par)                    | MIT                  |     |**1**| curl wrapper
network           |  [yocto](https://github.com/tom-seddon/yhs)                           | **public domain**    |     |  2  | non-production-use http server
network           |  [happyhttp](http://scumways.com/happyhttp/happyhttp.html)            | zlib                 |     |  2  | http client requests
network           |  [mongoose](https://github.com/cesanta/mongoose)                      | GPLv2                |     |  2  | http server
network           |  [LUrlParser](https://github.com/corporateshark/LUrlParser)           | MIT                  |     |  2  | lightweight URL & URI parser RFC 1738, RFC 3986
parsing           |  [SLRE](https://github.com/cesanta/slre)                              | GPLv2                |     |**1**| regular expression matcher
parsing           |  [PicoJSON](https://github.com/kazuho/picojson)                       | BSD                  | C++ |**1**| JSON parse/serializer
parsing           |  [mm_json.h](https://github.com/vurtun/mmx)                           | zlib                 |     |**1**| JSON parser
parsing           |  [mm_lexer.h](https://github.com/vurtun/mmx)                          | zlib                 |     |**1**| C-esque language lexer
parsing           |  [json.h](https://github.com/sheredom/json.h)                         | **public domain**    |     |  2  | JSON parser
parsing           |  [jzon.h](https://github.com/Zguy/Jzon)                               | MIT                  | C++ |  2  | JSON parser
parsing           |  [parson](https://github.com/kgabis/parson)                           | MIT                  |**C**|  2  | JSON parser and serializer
parsing           |  [minilibs](https://github.com/ccxvii/minilibs)                       | **public domain**    |     |  2  | two-file regex (also binary tree, etc)
profiling         |  [Remotery](https://github.com/Celtoys/Remotery)                      | Apache 2.0           |     |  2  | CPU/GPU profiler Win/Mac/Linux, using web browser for viewer
profiling         |  [MicroProfile](https://bitbucket.org/jonasmeyer/microprofile)        | **unlicense**        |     | 2-4 | CPU (and GPU?) profiler, 1-3 header files, uses miniz internally
scripting         |  [lualite](https://github.com/janezz55/lualite/)                      | MIT                  | C++ |**1**| generate lua bindings in C++
strings           |**[DG_misc.h](https://github.com/DanielGibson/Snippets/)**             | **public domain**    |     |**1**| Daniel Gibson's stb.h-esque cross-platform helpers: path/file, strings         
strings           |**[utf8](https://github.com/sheredom/utf8.h)**                         | **public domain**    |     |**1**| utf8 string library
strings           |**[strpool.h](https://github.com/mattiasgustavsson/libs)**             | **public domain**    |     |**1**| string interning
strings           |  [dfa](http://bjoern.hoehrmann.de/utf-8/decoder/dfa/)                 | MIT                  |     |  2  | fast utf8 decoder
strings           |**[gb_string.h](https://github.com/gingerBill/gb)**                    | **public domain**    |**C**|**1**| dynamic strings
tests             |  [utest](https://github.com/evolutional/utest)                        | MIT                  |     |**1**| unit testing
tests             |  [catch](https://github.com/philsquared/Catch)                        | Boost                |     |**1**| unit testing
tests             |  [SPUT](http://www.lingua-systems.com/unit-testing/)                  | BSD                  |     |**1**| unit testing
tests             |  [pempek_assert.cpp](https://github.com/gpakosz/Assert)               | **WTFPLv2**          | C++ |  2  | flexible assertions
tests             |  [minctest](https://github.com/codeplea/minctest)                     | zlib                 |  C  |**1**| unit testing
user interface    |  [dear imgui](https://github.com/ocornut/imgui)                       | MIT                  |     |  9  | an immediate-mode GUI formerly named "ImGui"
_misc_            |**[MakeID.h](http://www.humus.name/3D/MakeID.h)**                      | **public domain**    |     |**1**| allocate/deallocate small integer IDs efficiently
_misc_            |**[loguru](https://github.com/emilk/loguru)**                          | **public domain**    | C++ |**1**| flexible logging
_misc_            |  [tinyformat](https://github.com/c42f/tinyformat)                     | Boost                | C++ |**1**| typesafe printf
_misc_            |  [dbgtools](https://github.com/wc-duck/dbgtools)                      | zlib                 |**C**|  2  | cross-platform debug util libraries
_misc_            |  [stmr](https://github.com/wooorm/stmr.c)                             | MIT                  |  C  |  2  | extract English word stems
_misc_            |  [levenshtein](https://github.com/wooorm/levenshtein.c)               | MIT                  |  C  |  2  | compute edit distance between two strings
                                                                                                                       
There are also these XML libraries, but if you're using XML, shame on you:                                             
                                                                                                                       
- parsing: [tinyxml2](https://github.com/leethomason/tinyxml2): XML                                                    
- parsing: [pugixml](http://pugixml.org/): XML (MIT license)

Also you might be interested in other related, but different lists:

- [clib](https://github.com/clibs/clib/wiki/Packages): list of (mostly) small single C functions (licenses not listed)

## *List FAQ*

### Can I link directly to this list?

Yes, you can just use this page. If you want a shorter, more readable link, you can use [this URL](https://github.com/nothings/stb#other_libs) to link to the FAQ question that links to this page.

### Why isn't library XXX which is made of 3 or more files on this list?

I draw the line arbitrarily at 2 files at most. (Note that some libraries that appear to
be two files require a separate LICENSE file, which made me leave them out). Some of these
libraries are still easy to drop into your project and build, so you might still be ok with them.
But since people come to stb for single-file public domain libraries, I feel that starts
to get too far from what we do here.

### Why isn't library XXX which is at most two files and has minimal other dependencies on this list?

Probably because I don't know about it, feel free to submit a pull request, issue, email, or tweet it at
me (it can be your own library or somebody else's). But I might not include it for various
other reasons, including subtleties of what is 'minimal other dependencies' and subtleties
about what is 'lightweight'.

### Why isn't SQLite's amalgamated build on this list?

Come on.

