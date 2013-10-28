# rbenv-rbx is DEPRECATED thanks to [sstephenson/ruby-build@dbd8c71](https://github.com/sstephenson/ruby-build/commit/dbd8c71d17c4110b1e6bfcf0e2f0ee9ef7fdb100)

---

# rbenv-rbx

This is a plugin for [rbenv](https://github.com/sstephenson/rbenv) that fixes
up your shims and sets your `RBENV_COMMAND_PATH` properly for use with
[Rubinius](http://rubini.us/).

## Installation

To install rbenv-rbx, clone this repository into your `~/.rbenv/plugins`
directory. (You'll need a recent version of rbenv that supports plugin
bundles.)

    $ mkdir -p ~/.rbenv/plugins
    $ cd ~/.rbenv/plugins
    $ git clone git://github.com/rmm5t/rbenv-rbx.git

## Attribution and Genesis

This project was originally a fork of the
[`rbenv-rbx_2.0.0-dev_fix`](https://github.com/collinschaafsma/rbenv-rbx_2.0.0-dev_fix/)
rbenv plugin, but aims to automatically support all versions of Rubinius under
rbenv instead of just 2.0.0-dev in 1.9 mode.

For more information, please review this
[thread](https://github.com/sstephenson/rbenv/issues/178) on the underlying
problem.

## License

&copy; 2012-2013 Collin Schaafsma, Ryan McGeary. Released under the MIT license. See
`LICENSE` for details.
