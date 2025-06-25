# IBM Storage 
Meta configuration for IBM Storage Github Org

This repository contains the metadata configuration for the IBM Storage GitHub Organizations. The data here is consumed by the [peribolos](https://docs.prow.k8s.io/docs/components/cli-tools/peribolos/) tool to manage the organization and memberships, as well as team creation and deletion.

# User and Repo Creation

All members must have an IBM w3ID linked with their github profile to be given access. Please complete the steps [here](https://gh-user-map.opensource.dal.dev.cirrus.ibm.com/) 
to complete that process.

After that step is complete make a PR to `config/org.yaml` with your changes or additions. Please keep all entries in alphabetical order.
