# UP ACM Web Portal Documentation

Welcome to the University of the Philippines Diliman, Association for Computing Machinery Student Chapter's web portal documentation.

The repository of the web portal is currently private so this seperate repository is made to host the documentation.

---

## Local Hosting

First, have [Python](https://wiki.python.org/moin/BeginnersGuide/Download) installed in your system. For Window, make sure that it's added to your Path (check this option during installation).



To view the documentation locally, install the mkdocs with `pip`.

```
pip install mkdoc
```

Then use the `serve` command in the root of the project to see the built documentation in localhost. The port link will be provided after it builds.

```
mkdocs serve
```

The documentation can also be built into html with the `build` command. However, make sure not to check this into your remote repository.

```
mkdocs build
```

> For more information on using mkdocs, visit their [site](https://www.mkdocs.org/).