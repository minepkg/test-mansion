<h1 align="center">test-mansion</h1>
<p align="center">
  <img src="https://media.cdn.minepkg.io/5d27a7019208ad000953e85b/6068fe5709dadefdce1e3907.1080.webp" width="650" alt="artistic rendering of the map">
</p>

---

This is a minepkg modpack that i used when you try mods with `minepkg try <modname>`.
It also is installed as a dev dependency by default for new mod packages (`minepkg init`).

test-mansion only includes a few mods that help in testing in order to keep stability high.

### Test your package with `test-mansion`

You can include test-mansion for testing in your own package (can be a mod or modpack).

To do this simply type `minepkg install --dev test-mansion` in the directory of your package.
Your published package will **not** include test-mansion as a dependency if you install it like this.
You can read more about [dev dependencies here](https://preview.minepkg.io/docs/manifest#devdependencies).

### License

Everything in this repository is MIT licensed.

The packages that get installed if you use this modpack can be licensed differently.