# WebBreaker Configuration Repository for WebInspect Scanning
WebBreaker administers WebInspect scanning from a mutually exclussive remote GIT repo.  The three directories `policies`, `settings`, and `webmacros`, contain desired configurations that are optional for WebInspect scanning.

### Policies
> Grouping of proprietary WebInspect vulnerabiltiy tests to perform.  The policy file(s) is an format `xml` with a `.policy` file extension.

### Settings
> Scan configurations that are grouped into an `xml` file, bootstrapping a WebInspect scan.  Setting files determine which `webmacro`, `policy`, `hosts`, and other relevant scan configurations will be used in the scan.

### Webmacros
> Proprietary functional recordings of either a login or workflow for a website.  If a website requires authentication the login webmacro may be used for authentication, maintaining scan-state.  The workflow macro is a recording with authentication of a base case usage of the website.  Alernatively, a scan can be performed without a workflow webmacro, and a simple target url or a listing of urls can be provided.
