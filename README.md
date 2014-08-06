[<img src="img/logo.png" align="right" height="80"/ alt="dmpr logo">]()

Data Package Manager for R
====

**Under Development. Check below for current capabilities.**

## Description

An R package for creating and installing data packages that follow the
[Open Knowledge Foundation](https://okfn.org/)'s
[Data Package Protocol](http://dataprotocols.org/data-packages/).
The package largely mirrors functionality in the Node.js package
[Data Package Manager (dpm)](https://github.com/okfn/dpm).

The package will eventually have two core functions:

- `datapackage_init`: Initialise a data package from a data frame,
metadata list, and the source code file used to create the data set.

    + To-do for v0.1
    
    - [ ] Everything

- `datapackage_install`: Load a data package into R.

    + To-do for v0.1
    
    - [x] Load data from locally stored data package and return metadata
    
    - [ ] Load data from a zip file at http.
    
    - [ ] Load data from a GitHub repo.
    
## Install development build

```{S}
devtools::install_github('christophergandrud/dpmr')
```

---

[<img src="http://media.tumblr.com/023c285c14ef01953d3b67ffe789004d/tumblr_inline_mor1uu2OOZ1qz4rgp.png" height = "100" align="right" />](http://nadrosia.tumblr.com/post/53520500877/made-in-berlin-badge-update)

Licensed under
[GPL-3](https://github.com/christophergandrud/simPH/blob/master/LICENSE.md)
