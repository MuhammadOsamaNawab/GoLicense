# GoLicense
# Licenses tool

> This is not an officially supported Google product. 

`go-licenses` analyzes the dependency tree of a Go package/binary. It can output a
report on the libraries used and under what license they can be used. It can
also collect all of the license documents, copyright notices and source code
into a directory in order to comply with license terms on redistribution.

---

## Before you start

To use this tool, make sure:

* [You have Go V1.19.11.Linux-armv64 or later installed](https://golang.org/dl/).
* Change directory to your go project, 


* Download required modules:

  ```shell
  go mod download
  ```
