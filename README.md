javautils
=============

The Schuberg Philis Java Utilities library is meant to decouple other Java projects from the underlying utility libraries (e.g. apache commons or guava). In addition, some more specific utility methods not provided by other libraries are also implemented here.

The APIs should be kept as simple as possible to maximize reusability by making it simpler to use.

The test suite that comes with this library should be representative of every use-case in which the library takes part. That means, if you use this library for a specific purpose for which there aren't any tests yet, pelase do add them to the library's test suite. This will help others notice if a change will have unexpected side-effects.

Utility libraries should not depend on application code, and application code will eventually depend heavily on utility libraries. Therefore, it is very important to keep a high standard for technical code quality: small and simple methods, with few dependencies, and very high test coverage, to say the least.
