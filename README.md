# End-to-End Demo: Compliance as Code CIS Benchmarks Catalog (snippet)
End-to-End Demo: Compliance as Code CIS Benchmarks Catalog (snippet)

This repo comprises OSCAL catalog for the end-to-end demo. The OSCAL catalog is for CIS Controls, but for proprietary reasons only a portion (snippet) of the entire catalog is used for this demo.

The full catalog can be obtained from [CIS Controls OSCAL Repository](https://www.cisecurity.org/insights/blog/introducing-the-cis-controls-oscal-repository).

The [demo overview](https://github.com/oscal-compass/e2e-demo).

What this repo does:

This repo ingests industry standard catalogs and provides a mechanism to generate an opinionated control set which is then leveraged by the profile repo.

1. Input: It was initialized with OSCAL catalog.json, which is a subset of the full CIS controls.

2. Processing: Changes to either the catloag.json or markdown files and creation of PR to merge these changes into develop will result in catalog generate/assemble.

3. Output: Updated catalog.json in catalog repo

4. Next action: Updated catalog.json pushed to profile repo

Demo for this repo:

- Show changes to markdown are incorporated into catloag.json

