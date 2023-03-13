# BitWarden-Unified Helm Chart

Bitwarden Unified Helm Chart

For changes to the configuration refer to: https://bitwarden.com/help/install-and-deploy-unified-beta/

### Install:
<code>git clone https://github.com/giuliolibrando/helm-bitwarden-unified.git</code>

<code>cd helm-bitwarden-unified</code>

<code>kubectl create ns bitwarden-unified</code>

<code>helm install bitwarden-unified . -f values.yaml -n bitwarden-unified</code>
