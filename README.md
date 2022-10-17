# toybox.py's toystore

**toystore** is a repository of available **toyboxes** for [**toybox.py**](https://toyboxpy.io).

This list is by no mean meant to be exhaustive or exclusive, **toybox.py** users can easily use any git repo as a **toybox**, but it is meant as a convenient way to use, for example:

```console
toybox add Aspen
```

instead of:

```console
toybox add https://github.com/DidierMalenfant/Aspen
```

### Supported fields

- `url` : Full url to the git repo.
- `description` : One sentence description of the **toybox** (optional).
- `author` : Name and/or email of the **toybox**'s author or maintainer (optional).
- `license` : License used for the toybox **toybox** as a [spdx identifier](https://spdx.org/licenses/) (optional).
- `site` : Url of the website for the **toybox** (optional).

### Adding your own toybox

Please open a pull-request to add your **toybox** to the list, making sure it is added in alphabetical order in the file `toystore.toml`.

### License

**toystore** is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.
