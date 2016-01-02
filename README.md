This formats member photos for the member photo wall. It generates a PDF for printing.

The application runs entirely in the browser, but needs to be served via http protocol.

Serving locally can be be accomplished in many ways, but most distributions have Python (and the SimpleHTTPServer example) installed, which can be invoked as such:
`pushd <directory>; python -m SimpleHTTPServer; popd`

The application can then be accessed via browser at http://localhost:8000

