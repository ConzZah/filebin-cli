# filebin-cli
minimal filebin.net cli in bash

![filebin-cli_v0 2](https://github.com/user-attachments/assets/4760591d-0535-445e-8bd3-72f2740e56b3)

( self hosted filebins "should" also work, change the $fb variable and try )


#### FEATURES ####

- every basic filebin action: (up/downloading of files, creating, locking, deleting of bins) including downloading whole bins as .zip or .tar files.
- supports automatic sha256 diffing, (for both uploads and downloads)
- ls implementation, allowing you to view filenames, total bin size, and expiration date (and even individual files) at a glance.
- qr-code generation for bin urls (even shows them right in your terminal, if you have qrencode installed).
- basic autocompletion for (remote) filenames

Keep in mind, this is at a very early stage, so expect the occasional bug.

if you are able to spot one, please open an issue / let me know.

Sincerely, ConzZah.

<p align="center">
  <a href="https://github.com/ConzZah/filebin-cli/raw/main/filebin-cli">
    <img alt="filebin-cli_v0.1" src="https://img.shields.io/badge/filebin cli-v0.2-0688CB.svg">
  </a>
</p>
