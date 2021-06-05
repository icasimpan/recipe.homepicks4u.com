```

*** Main ref https://github.com/seanlane/gochowdown

*** Basic setup

1. hugo new site recipe
2. git submodule add https://github.com/seanlane/gochowdown.git themes/gochowdown
3. cp themes/gochowdown/exampleSite/config.yml
4. rm config.toml
5. hugo serve ## to test, which should look like the picture in theme site

---

*** Add recipe:

  hugo new --kind recipe-bundle recipes/bistek-tagalog

NOTE: Do not use ':' in each line as that would break hugo.


*** Add a new recipe with components (an option to above)
  ==> https://github.com/clarklab/chowdown read about component recipe
hugo new --kind recipe-bundle components/corned-beef-omelet
```
