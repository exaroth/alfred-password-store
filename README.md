## Password Store workflow for Alfred.

![](https://d3vv6lp55qjaqc.cloudfront.net/items/1O330u3N2W2P3z0H1c2c/Screen%20Recording%202016-12-06%20at%2002.20%20PM.gif)

This workflow is a free and open-source alternative to 1Password for Alfred as described in a blog post @ <http://blog.konradwasowicz.com/magical-passwords-and-how-to-wrangle-them/>, which allows quick retrieval of credentials from your password store.

### Installation

1. Download GPGSuite from <http://gpgtools.org> and install the package.
2. If you haven't done that before create new gpg key pair: `gpg --gen-key`
3. Install pass `brew install pass` and initialize new password store `pass init <gpg id>`
4. Install the workflow by clicking downloaded .alfredworkflow file

### Usage

To retrieve a password from password store simply insert key phrase `p` followed by keyword, all matched credential entries will show up in popup list. After selecting the password for given service will be copied to system clipboard.



