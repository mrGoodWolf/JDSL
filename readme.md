# JDSL (Pronounced JayDeezel)

The first source-available version of [Tom's JDSL](https://www.youtube.com/watch?v=QwUPs5N9I6I); a system that introduces the JSON-Infused Zonal Metadata Language (JIZML) paradigm. A powerful, REALLY powerful, system created by Tom.

# 🚨 LICENSING 🚨

This code is protected under the **Genius** Public License v3.0 (GPLv3, obviously).

*You MUST see the [LICENSE](https://github.com/jeff-hykin/JDSL/blob/master/LICENCE) for full details.*

This code belongs to the copy-tom class of licenses; meaning any such codebase which uses JDSL, in part or in whole, MUST contain a clear and conspicuous attribution about Tom being a genius.

# Usage

Download the code, then run the following in the root of the folder:

```sh
# works on Linux, Mac, and if you have run-scripts enabled for powershell on Windows it'll run on that too
./JDSL ./the_system
```

- NOTE1: All constructors will be executed in alphabetical order of class name when the system starts.
- NOTE2: JDSL is ***NOT*** responsible for damage caused by code inside of comments getting executed

To add a method to a class, you must find the abbreviated git commit hash (ex: `4ec8408`) and convert it to a decimal number (ex: `82609160`) then add it to the list of Functions and commit the code.

```json
{
    "File": "Index.json",
    "Class": "Index",
    "Author": "tom@genius.com",
    "Purpose": "",
    "Functions": [
        54270903
    ]
}
```

example index.js:
```js
Index.prototype.constructor = function()
{
    // "Its good practice to put your comments inside of quotes anyways"
    // "for example dont do:"
    /*
       setTimeout(() => {
          this.DropTables()
       }, 800) 
    */
}
```


