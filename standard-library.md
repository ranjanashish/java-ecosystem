# Standard Library

## Static Methods

###### Arrays

* `Arrays.asList()`
* `Arrays.binarySearch()`
* `Arrays.copyOf()`
* `Arrays.fill()`
* `Arrays.stream()` - (overloaded)
  * returns `IntStream` for int array
  * returns `LongStream` for long array
  * returns `DoubleStream` for double array
  * returns `Stream<T>` for generic type array
* `Arrays.sort()`

###### Collections

* `Collections.emptyList()` - returns **immutable** empty list; `List.of()` can also be used
* `Collections.emptyMap()` - returns **immutable** empty map; `Map.of()` can also be used
* `Collections.emptySet()` - returns **immutable** empty set; `Set.of()` can also be used
* `Collections.singletonList()` - returns **immutable** list; `List.of()` can also be used
* `Collections.singletonMap()` - returns **immutable** map; `Map.of()` can also be used
* `Collections.singleton()` - returns **immutable** set; `Set.of()` can also be used
* `Collections.unmodifiableList()` - returns **immutable** list
* `Collections.unmodifiableMap()` - returns **immutable** map
* `Collections.unmodifiableSet()` - returns **immutable** set
* `Collections.addAll()`
* `Collections.binarySearch()`
* `Collections.frequency()`
* `Collections.max()`
* `Collections.min()`
* `Collections.nCopies()`
* `Collections.shuffle()`
* `Collections.sort()`
* `Collections.swap()`

###### Collectors

* `Collectors.joining()`
* `Collectors.toList()`
* `Collectors.toMap()`
* `Collectors.toSet()`
* `Collectors.toUnmodifiableList()`
* `Collectors.toUnmodifiableMap()`
* `Collectors.toUnmodifiableSet()`

###### IntStream

* `IntStream.of()`
* `IntStream.range()`
* `IntStream.empty()`
* `IntStream.concat()`

###### List

* `List.of()` - returns **immutable** list
* `List.copyOf()` - returns **immutable** list

###### Map

* `Map.of()` - returns **immutable** map
* `Map.copyOf()` - returns **immutable** map
* `Map.entry()` - returns **immutable** entry
* `Map.ofEntries()` - returns **immutable** map

###### Math

* `Math.addExact()`
* `Math.abs()`
* `Math.ceil()`
* `Math.floor()`
* `Math.max()`
* `Math.min()`
* `Math.pow()`
* `Math.exp()`
* `Math.round()`
* `Math.random()`

###### Misc

* `Boolean.parseBoolean()`
* `Integer.parseInt()`
* `Long.parseLong()`
* `Float.parseFloat()`
* `Double.parseDouble()`
* `Boolean.valueOf()`
* `Integer.valueOf()`
* `Long.valueOf()`
* `Float.valueOf()`
* `Double.valueOf()`
* `Optional.empty()`
* `Optional.of()`
* `Optional.ofNullable()`

###### Set

* `Set.of()` - returns **immutable** set
* `Set.copyOf()` - return **immutable** set

## Interfaces

* `AutoCloseable`
* `Supplier<T>`

## Exceptions

* `AssertionError`

## Annotations

* `FunctionalInterface`
