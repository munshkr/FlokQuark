# FlokQuark

SuperCollider Quark for connecting [Flok](https://github.com/munshkr/flok) with
SuperCollider.

You will need this to use the `remote_sclang` target in Flok.


## Install

Open a new document on your SuperCollider IDE and type:

```supercollider
Quarks.install("https://github.com/munshkr/FlokQuark");
```

After a few seconds, if everything went OK, you should see something like this
in your Post window:

```
Installing Flok
Flok installed
-> Quark: Flok[0.1.0]
```

Finally recompile your class library.  Go to `Language` menu, `Recompile class
library`, or hit <kbd>Ctrl</kbd>+<kbd>Shift</kbd>+<kbd>L</kbd>.


## Usage


Whenever you need to use it, start your `flok-repl` with `-t remote_sclang`,
and on SuperCollider IDE, run this:

```supercollider
s.waitForBoot { Flok.start };
```

If you see `Flok started. Listening for messages on port 57200...` on your Post
window, you are ready!


## Contributing

Bug reports and pull requests are welcome on GitHub at the [issues
page](https://github.com/munshkr/FlokQuark). This project is intended to be a
safe, welcoming space for collaboration, and contributors are expected to
adhere to the [Contributor Covenant](http://contributor-covenant.org) code of
conduct.


## License

This project is licensed under GPL 3+. Refer to [LICENSE.txt](LICENSE.txt)
