# clr.tools.gitlibs

A port of [clojure/tools.gitlibs](https://github.com/clojure/tools.gitlibs) library to ClojureCLR.

> An API for retrieving, caching, and programatically accessing git libraries.

> To access git dependencies (for example, via tools.deps), one must download git directories and working trees as indicated by git shas. This library provides this functionality and also keeps a cache of git dirs and working trees that can be reused.

## Usage

See the ClojureJVM library repo linked to above.

For configuration, the environment variables referenced are the same.  
Instead of Java system properties, this version will look at the `app.config` data.
The equivalent of `~/.gitlibs` on Windows is the the `.gitlibs` directory in the user's home directory, typically `C:/Users/<username>`.

# Releases

deps.edn reference:

```
    {io.github.clojure/clr.tools.gitlibs {:sha "TO_BE_DETERMINED"}}
```

Nuget reference:

```
    PM> Install-Package clojure.tools.gitlibs -Version 2.5.190 
```
	
Leiningen/Clojars reference:

```
   [org.clojure.clr/tools.gitlibs "2.5.197"]
```

## Contributing 

[Contributing to Clojure projects](https://clojure.org/community/contributing) requires a signed Contributor Agreement. 


# Copyright and License

Per the ClojureJVM version:


> Copyright © 2018-2023 Rich Hickey, Alex Miller, and contributors
>
> All rights reserved. The use and
> distribution terms for this software are covered by the
> [Eclipse Public License 1.0] which can be found in the file
> epl-v10.html at the root of this distribution. By using this software
> in any fashion, you are agreeing to be bound by the terms of this
> license. You must not remove this notice, or any other, from this
> software.
>
> [Eclipse Public License 1.0]: http://opensource.org/licenses/eclipse-1.0.php