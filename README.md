Rapicoin Core Integration Tree
==============================

Rapicoin is a decentralized peer-to-peer cryptocurrency, forked from Bitcoin Core, with faster block times and independent networking.

🔗 Website: *(Coming Soon)*  
📦 Download binaries: *(Coming Soon)*

What is Rapicoin Core?
----------------------

Rapicoin Core connects to the Rapicoin peer-to-peer network to download and fully
validate blocks and transactions. It also includes a wallet and graphical user
interface (GUI), which can be optionally built.

Rapicoin is designed for faster transactions — a new block is created every **1 minute**,
enabling quicker confirmations compared to Bitcoin's 10-minute block time.

Further information about Rapicoin Core is available in the [doc folder](/doc).

License
-------

Rapicoin Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or visit https://opensource.org/license/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested (see `doc/build-*.md` for instructions).  
New stable releases will be tagged accordingly.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md),  
and useful developer notes are available in [doc/developer-notes.md](doc/developer-notes.md).

Testing
-------

Testing and code review is essential to maintain the security of the Rapicoin network.  
We welcome help in reviewing pull requests and testing new code.

### Automated Testing

Developers are encouraged to write [unit tests](src/test/README.md) for new code.  
Unit tests can be compiled and run with: `ctest`  
More details in [/src/test/README.md](/src/test/README.md)

Integration and regression tests (Python-based) can be run with:  
`build/test/functional/test_runner.py`

### Manual QA Testing

Every change should ideally be tested by someone other than the author.  
Please include a test plan in pull requests when possible.

Translations
------------

Translations for Rapicoin Core will be managed via Transifex (coming soon).  
We do not accept translation changes via GitHub pull requests.

---

*This software is under active development and is not affiliated with Bitcoin Core.*
