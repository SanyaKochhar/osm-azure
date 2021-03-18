<!--

Use the checklist below to ensure your release PR is complete before marking it ready for review.

-->

- [ ] I have ensured all PRs [labelled `hold: upstream release`](https://github.com/Azure/osm-azure/labels/hold%3A%20upstream%20release) have been tested and merged by their authors
- [ ] I have updated the Helm chart:
    1. Made applicable updates to the osm-arc values.yaml if any were made in the upstream OSM chart
    <!--
    How: in upstream, compare between the latest release and the previous release to check if anything has changed in the OSS values.yaml e.g: https://github.com/openservicemesh/osm/compare/v0.6.1...v0.7.0-rc.1
    Check for variable name changes, removed variables, variables that need to be overridden, etc. and make applicable changes in the osm-arc chart.    
    -->   
    2. Updated the chart version, app version and depedency version in charts/osm-arc/Chart.yaml

Is this a release candidate?