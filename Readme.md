This repository is a copy of public available `external-secrets` Helm Chart.
Flux can not use official Helm Repository https://external-secrets.io/ due to following issue https://github.com/fluxcd/flux2/issues/2019 .
Flux can not use official Helm Source from Git repository https://github.com/external-secrets/external-secrets/tree/main/deploy/charts/external-secrets due to CRD s are not commited to the repository. They are generated during Helm release process


Browse: https://external-secrets.io/index.yaml
Download tar and extract