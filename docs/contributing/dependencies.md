# Dependencies

Here we mention some of the dependencies and what we use them for:

* monaco: the text editor.
* webpack: module loader / bundler.
* react: main ui framework
* free-style: provides css style sheet features using just JavaScript. [See this blog post about it](https://medium.com/@basarat/css-modules-are-not-the-solution-1235696863d6#.ar4ydjv4m).
* marked: markdown parser (markdown -> html)


## Tested

* `mocha`
* `ts-node`

`source-map-support` is needed by `ts-node`. We should not need to have it as a dependency but pinned to fix https://github.com/alm-tools/alm/issues/330
