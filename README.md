# vault-on-kuberenetes

* Step 1: Create the kubernetes cluster using Kind with the config file: kind-config.yaml
* Step 2: Deploy Vault server and agent-sidecar injector using kustomize yamls
* Step 3: Deploy vault-config-operator  (https://github.com/redhat-cop/vault-config-operator)
* Step 4: Deploy the resources SecretEngineMount and KubernetesSecretEngineConfig
