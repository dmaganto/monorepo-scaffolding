# {{cookiecutter.service}}
## ArgoCD apps status

| ENVIRONMENT | App status |
| ----------- | ---------- |
| DEV         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=dev-{{cookiecutter.service}}&revision=true)](https://dmaganto.argocd.infra/applications/argocd/dev-{{cookiecutter.service}}) |
| TEST         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=test-{{cookiecutter.service}}&revision=true)](https://dmaganto.argocd.infra/applications/argocd/test-{{cookiecutter.service}}) |
| PREPROD         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=preprod-{{cookiecutter.service}}&revision=true)](https://dmaganto.argocd.infra/applications/argocd/preprod-{{cookiecutter.service}}) |
| PROD         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=prod-{{cookiecutter.service}}&revision=true)](https://dmaganto.argocd.infra/applications/argocd/prod-{{cookiecutter.service}}) |
