# 0.1.1
* Exclude hiccup and garden as transitive dependencies for Glow since they're large dependencies and Pyro doesn't rely on any of Glow's HTML/CSS features.

# 0.1.0
 * Source code reader that highlights the relevant line in question
 * Ability to drop all stacktrace frames once we hit `clojure.main/repl/read-eval-print`.
 * Ability to filter `clojure.core`, `clojure.lang`, `clojure.test` stacktrace frames. After all, your bug probably isn't in the language or the compiler.
 * Ability to filter `leiningen.core.*` and `leiningen.test` stacktrace frames. Again, your bug probably isn't in the build system.
