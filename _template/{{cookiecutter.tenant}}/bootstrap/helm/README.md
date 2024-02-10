# {{cookiecutter.tenant}}
## ArgoCD apps status

| ENVIRONMENT | App status |
| ----------- | ---------- |
| DEV         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=dev-{{cookiecutter.tenant}}-tenant&revision=true)](https://dmaganto.argocd.infra/applications/argocd/dev-{{cookiecutter.tenant}}-tenant&revision=true) |
| TEST         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=test-{{cookiecutter.tenant}}-tenant&revision=true)](https://dmaganto.argocd.infra/applications/argocd/test-{{cookiecutter.tenant}}-tenant&revision=true) |
| PREPROD         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=preprod-{{cookiecutter.tenant}}-tenant&revision=true)](https://dmaganto.argocd.infra/applications/argocd/preprod-{{cookiecutter.tenant}}-tenant&revision=true) |
| PROD         | [![App Status](https://dmaganto.argocd.infra/api/badge?name=prod-{{cookiecutter.tenant}}-tenant&revision=true)](https://dmaganto.argocd.infra/applications/argocd/prod-{{cookiecutter.tenant}}-tenant&revision=true) |
