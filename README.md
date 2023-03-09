# OWASP CVE suppression of false positives

- To suppress a CVE add the XML snippet to [src/main/resources/owasp-suppressions.xml](src/main/resources/owasp-suppressions.xml).
- The XML snippet can be found by clicking the `suppress` button next to the CVE in this report within your project: `target/dependency-check-report.html`
- Only do this if you are sure it's a false positive!
- The [pom.xml](pom.xml) file should only need its version number changing with each suppression file release.
