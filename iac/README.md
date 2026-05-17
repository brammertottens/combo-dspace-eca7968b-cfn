# cfn-template

CloudFormation templates used for deployment and infrastructure validation.

## Scan Targets
- "/cfngoat.yaml"
- "/eks.yaml"

## Update Procedure
```bash
cd /Users/bottens/git/cfngoat
# pull latest as needed

cp cfngoat.yaml /Users/bottens/git/cfn-template/cfngoat.yaml
cp eks.yaml /Users/bottens/git/cfn-template/eks.yaml

# Update README metadata as needed
cd /Users/bottens/git/cfn-template
git add cfngoat.yaml eks.yaml README.md
git commit -m "Update CloudFormation templates"
git push
```

## Notes
- This repository is maintained for IaC scanning workflows.
