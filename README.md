# WebBreaker Configuration Repository for WebInspect Scanning
WebBreaker administers WebInspect scanning from a mutually exclussive remote GIT repo.  The three directories `policies`, `settings`, and `webmacros`, contain desired configurations that are optional for WebInspect scanning.

### Policies
> Grouping of proprietary WebInspect vulnerabiltiy tests to perform.  Tests represented in an `xml` scheme with a `.policy` file extension.

### Settings
> Scan configurations that are grouped into an `xml` file, bootstrapping a WebInspect scan.  Setting files determine which `webmacro`, `policy`, `hosts`, and other relevant scan configurations will be used in the scan.

### Webmacros
> Proprietary functional recordings of either a login or workflow for a website, both file contents are encoded.  If a website requires authentication the login webmacro can be used for authentication and maintain the state of the scan.  The workflow macro is a recording with authentication of base case usage of the website.  Alernatively, a website can be scanned by providing a list of URLs in-scope to scan, without a `webmacro`.
