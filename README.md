# ridego_workflows

This is the public GitHub Actions repository for manual RideGo iOS deployments.

It should contain:

- workflow files only
- light documentation related to workflow usage

It should not contain:

- Flutter source code
- signing certificates or provisioning profiles
- Match repository contents

The workflows in this repo check out the private source repo:

- `ehteshamawan1/ridego`

and pull signing assets from the private Match repo:

- `ehteshamawan1/ridego_match`
