# cfn-template

Snapshot-only repository for scanning vulnerable-by-design CloudFormation templates sourced from Cfngoat.

## Source
- Source repository local path: "/Users/bottens/git/cfngoat"
- Source commit SHA: "0c09b69cfc3dbc6cb3ef01883415c35c588ced48"
- Snapshot date: "2026-05-15"

## Scan Targets
- "/cfngoat.yaml"
- "/eks.yaml"

## Update Procedure
```bash
cd /Users/bottens/git/cfngoat
# pull latest as needed

cp cfngoat.yaml /Users/bottens/git/cfn-template/cfngoat.yaml
cp eks.yaml /Users/bottens/git/cfn-template/eks.yaml

# update README source commit SHA
cd /Users/bottens/git/cfn-template
git add cfngoat.yaml eks.yaml README.md
git commit -m "Update Cfngoat template snapshot"
git push
```

## Notes
- This repo is intentionally snapshot-only for scanning.
- Keep source provenance (commit SHA) updated on each refresh.
