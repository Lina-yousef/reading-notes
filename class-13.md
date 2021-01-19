**Local Storage**

**HISTORY OF LOCAL STORAGE BEFORE HTML5**

* Cookies were invented early in the web’s history, and indeed they can be used for persistent local storage of small amounts of data.

* In the beginning, there was only Internet Explorer.

* serData allows web pages to store up to 64 KB of data per domain.

* In 2002, Adobe introduced a feature in Flash 6 that gained the unfortunate and misleading name of **“Flash cookies.”**

* In 2007, Google launched Gears, an open source browser plugin aimed at providing additional capabilities in browsers.

* By 2009, dojox.storage could auto-detect (and provide a unified interface on top of) Adobe Flash, Gears, Adobe AIR, and an early prototype of HTML5 storage that was only implemented in older versions of Firefox.

* **all of them are either specific to a single browser, or reliant on a third-party plugin.**

* **HTML5 STORAGE**

* Based on named : key (string) / value (any type supported by JS).
* You store data based on a named key.
* then you can retrieve that data with the same key.

**parseInt() or parseFloat()** : to coerce your retrieved data into the expected JavaScript datatype.

**Calling setItem()** : with a named key that already exists will silently overwrite the previous value.

**Calling getItem()** : with a non-existent key will return null rather than throw an exception.

**removeItem()** :  removing the value for a given named key, and clearing the entire storage area.

**key()**: property to get the total number of values in the storage area, and to iterate through all of the keys by index.

* **TRACKING CHANGES TO THE HTML5 STORAGE AREA**

* The storage event is fired on the window object whenever **setItem()**, **removeItem()**, or **clear()** is called and actually changes something.

* The storage event is supported everywhere the localStorage object is supported.

* In 2007, Google launched Gears, an open source cross-browser plugin which included an embedded database based on SQLite.

* This early prototype later influenced the creation of the Web SQL Database specification.

* most of the action resides in the string you pass to the executeSql method.

* This string can be any supported SQL statement, including **SELECT**, **UPDATE**, **INSERT**, **DELETE** statements.

* **The primary difference is that the object store has no structured query language.**
* You don’t construct a statement like **"SELECT * from USERS where ACTIVE = 'Y'"**. Instead, you use methods provided by the object store to open a cursor on the database named **“USERS”.**


[Previous](class-12.md)  | [Home](README.md) | [Next](class-14a.md)
