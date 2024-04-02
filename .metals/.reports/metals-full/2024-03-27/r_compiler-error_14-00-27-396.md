file:///C:/Users/dreammeaker/ft_userdata/freqtrade/Untitled-2.java
### java.util.NoSuchElementException: next on empty iterator

occurred in the presentation compiler.

presentation compiler configuration:
Scala version: 3.3.1
Classpath:
<HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala3-library_3\3.3.1\scala3-library_3-3.3.1.jar [exists ], <HOME>\AppData\Local\Coursier\cache\v1\https\repo1.maven.org\maven2\org\scala-lang\scala-library\2.13.10\scala-library-2.13.10.jar [exists ]
Options:



action parameters:
uri: file:///C:/Users/dreammeaker/ft_userdata/freqtrade/Untitled-2.java
text:
```scala
/* We've started Quokka for you automatically on this file.
 *
 * To open a new Quokka file:
 *   - Press `Ctrl K, J` to create a new JavaScript File
 *   - Press `Ctrl K, T` to create a new TypeScript File
 *   - Press `Ctrl K, L` to open an interactive sample from:
 *     https://github.com/wallabyjs/interactive-examples
 *
 * To start/restart Quokka on an existing file:
 *   - Press `Ctrl K, Q`
*/

// See the output of console.log right next to your code
const quokka = { isAwesome: true };

console.log(quokka);

// See the value of a variable simply by typing its name
quokka;

// Use sequence expression to compare objects
const wallaby = { "is Quokka's BigBrother": true };

(quokka, wallaby)

// Gutter indicators show what code was executed (code coverage)

// Orange indicators means only part of the line was executed
// because JavaScript stops processing after first false value
console.log('partialCoverage', false && true);

// Green indicators means that Quokka executed all statements
// on a line of code
if (false) {
  // White indicators means that a line of code was never
  // executed by Quokka
  console.log('noCoverage', true);
}

// Red indicators show where an error occurred. The error message
// is also shown beside the error
throw new Error('Something went wrong');

// There's a lot more Quokka can do! Visit our docs to learn more:
// - https://quokkajs.com/docs/

```



#### Error stacktrace:

```
scala.collection.Iterator$$anon$19.next(Iterator.scala:973)
	scala.collection.Iterator$$anon$19.next(Iterator.scala:971)
	scala.collection.mutable.MutationTracker$CheckedIterator.next(MutationTracker.scala:76)
	scala.collection.IterableOps.head(Iterable.scala:222)
	scala.collection.IterableOps.head$(Iterable.scala:222)
	scala.collection.AbstractIterable.head(Iterable.scala:933)
	dotty.tools.dotc.interactive.InteractiveDriver.run(InteractiveDriver.scala:168)
	scala.meta.internal.pc.MetalsDriver.run(MetalsDriver.scala:45)
	scala.meta.internal.pc.PcCollector.<init>(PcCollector.scala:44)
	scala.meta.internal.pc.PcSemanticTokensProvider$Collector$.<init>(PcSemanticTokensProvider.scala:61)
	scala.meta.internal.pc.PcSemanticTokensProvider.Collector$lzyINIT1(PcSemanticTokensProvider.scala:61)
	scala.meta.internal.pc.PcSemanticTokensProvider.Collector(PcSemanticTokensProvider.scala:61)
	scala.meta.internal.pc.PcSemanticTokensProvider.provide(PcSemanticTokensProvider.scala:90)
	scala.meta.internal.pc.ScalaPresentationCompiler.semanticTokens$$anonfun$1(ScalaPresentationCompiler.scala:109)
```
#### Short summary: 

java.util.NoSuchElementException: next on empty iterator