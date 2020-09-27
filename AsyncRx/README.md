# FSharp.Control.AsyncRx

> FSharp.Control.AsyncRx is a lightweight Async Reactive (AsyncRx) library for F#.

FSharp.Control.AsyncRx is a library for asynchronous reactive programming, and is the implementation of Async Observables ([ReactiveX](http://reactivex.io/)) for F#. FSharp.Control.AsyncRx makes it easy to compose and combine streams of asynchronous event based data such as timers, mouse-moves, keyboard input, web requests and enables you to do operations such as:

- Filtering
- Transforming
- Aggregating
- Combining
- Time-shifting

FSharp.Control.AsyncRx was designed specifically for targeting [Fable](http://fable.io/) which means that the code may be [transpiled](https://en.wikipedia.org/wiki/Source-to-source_compiler) to JavaScript, and thus the same F# code may be used both client and server side for full stack software development.

## Documentation

Please check out the [documentation](https://fablereaction.readthedocs.io/en/latest/asyncrx/)

## Install

```cmd
paket add FSharp.Control.AsyncRx --project <project>
```
