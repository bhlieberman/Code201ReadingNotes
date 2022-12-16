# Asynchrony

1. Asynchrony is the occurence of multiple distinct actions without the one interrupting or blocking the progress of the other. Different programming languages have their own way of expressing this model, like thread pools, futures, and async/await (which I think uses thread pools internally, but whatever).
2. Asynchrony is chiefly beneficial because expensive and time-consuming operations like network IO can be performed in the background without blocking the program's main thread, and without introducing the complexity implicit in concurrent programming with threads, locks, and other problems.
