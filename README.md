# JSweet Swing example

Sample project for J4TS & JSweet & Swing

Many of the Swing classes and methods are missing, at the moment,
so most Swing applications would need major surgery to work this way.
I intend to continue to submit PRs for the [`j4ts-awt-swing`](https://github.com/j4ts/j4ts-awt-swing)
project that supports this one.

I have included three sample apps from the Swing Tutorial.  Two of the `main()`
methods are replaced with `mainDisabled()` at the moment.

## Usage

```
git clone https://github.com/vorth/j4ts-swing-example.git
cd j4ts-swing-example
mvn clean compile && python3 -m http.server 9000
```

There are many other ways to run a sample webserver, of course; any will do.

