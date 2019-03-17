# typed-gson
Type information encoding in Json

The [JSON](https://www.json.org/) does not support object types, this library implements TypeAdapterFactory for [GSON](https://github.com/google/gson) that adds type meta-information to JSON object during encoding and uses it during decoding.
The library is aimed for use with [Scala](https://www.scala-lang.org/) so there is also support for Scala Option and object types.