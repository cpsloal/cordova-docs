---
license: >
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
---

File
====

This object contains attributes of a single file.

Properties
----------

- __name:__ The name of the file. _(DOMString)_
- __fullPath:__ The full path of the file including the file name. _(DOMString)_
- __type:__ The mime type of the file. _(DOMString)_
- __lastModifiedDate:__ The last time the file was modified. _(Date)_
- __size:__ The size of the file in bytes. _(long)_

Methods
-------

- __slice__: Select only a portion of the file to be read.

Details
-------

The `File` object contains attributes of a single file.  You can get an instance of a File object by calling the __file__ method of a `FileEntry` object.

Supported Platforms
-------------------

- Android
- BlackBerry WebWorks (OS 5.0 and higher)
- iOS
- Windows Phone 7 and 8
- Windows 8


slice
--------------

Return a new File object, for which FileReader will return only the specified portion of the file.
Negative values for __start__ or __end__ are measured from the end of the file.
The indexes are always relative to the current slice (see the full example).

__Parameters:__

- __start__ - The index of the first byte to read, inclusive.
- __end__ - The index of the byte after the last one to read.

__Quick Example__

    var slicedFile = file.slice(10, 30);

__Full Example__

    var slice1 = file.slice(100, 400);
    var slice2 = slice1.slice(20, 35);
    
    var slice3 = file.slice(120, 135);
    // slice2 and slice3 are equivalent.

__Supported Platforms:__

- Android
- iOS
