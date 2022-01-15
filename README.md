# blocklists

Adblock Plus-compatible blocklists of various spammy websites plaguing search
results. These typically contain scraped or machine-translated pages from
github or stack-overflow.

After applying the blocklist, these pages will be removed from DuckDuckGo and
Google search results.


## Usage

In uBlock Origin, paste the link to the raw version of
[blocklist.txt](blocklist.txt) into the `Custom` field in the `Filter lists`
tab.


## Adding websites

Select a file inside the [src](src) directory and add the website URL. Then,
run the [compile](compile) script to generate the
[blocklist.txt](blocklist.txt) file. Each URL is automatically surrounded by
suitable search engine selectors.

Contents of the [src/verbatim.txt](src/verbatim.txt) file are appended to
[blocklist.txt](blocklist.txt) as they are, without surrounding them by any
selectors.
