# Explicit Buildpack

Force your CF app developers to specify their buildpack.

## Steps to install

1. `git clone https://github.com/ecsteam/explicit-buildpack.git`
1. `cd explicit-buildpack`
1. `zip -r explicit-buildpack.zip *`
1. `cf create-buildpack explicit-buildpack explicit-buildpack.zip 1`
