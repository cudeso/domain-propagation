## Domain Propagation Test

This is a test to research how quickly indicators of compromise (IOC) propagate between different blocklists. The approach is

- Register a fresh domain;
- Add it to a known block list, for example botvrij.eu;
- Query other blocklists, via URLHaus, VT and MISP and check if the domain is included or not;
- Build a timeline.
