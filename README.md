# fossa-zero-day-demo
Demo repo to simulate zero-day dependency xyz-lib
Formal definition

A zero-day is a vulnerability that is:

Unknown to the public (or not yet formally cataloged)

Has no CVE assigned yet

May already be exploited or considered dangerous

“Zero-day” means defenders have had zero days to prepare.
What this means in real life

Security teams cannot wait for CVE feeds

Traditional vulnerability scanners won’t catch it yet

Action must be taken based on:

Threat intelligence

Vendor advisories

Internal research

Suspicious behavior

✅ This is exactly where SBOMs + policy enforcement shine.

&&&&&&&&&&

Here:

xyz-lib is the “package”

0.0.1 is the version

It doesn’t need to exist in npm

FOSSA only needs to see the declaration to:

Track it

Include it in the SBOM

Apply policies

&&&&&&&&&&&&&&&&&

GitHub stores:

package.json

Commit history

Branches

FOSSA:

Connects to GitHub

Clones the repo

Reads package.json

Extracts dependency data

Builds an SBOM
