# problem statement
gets a secret file from azure keyvault

# example usage

> note: in examples, VERSION represents a version of the azure.keyvault.secret-file.get pkg

## install

```shell
opctl pkg install github.com/opspec-pkgs/azure.keyvault.secret-file.get#VERSION
```

## run

```
opctl run github.com/opspec-pkgs/azure.keyvault.secret-file.get#VERSION
```

## compose

```yaml
run:
  op:
    pkg: { ref: github.com/opspec-pkgs/azure.keyvault.secret-file.get#VERSION }
    inputs:
      subscriptionId:
      loginId:
      loginSecret:
      name:
      vault:
      # end optional args
      encoding:
      loginTenantId:
      loginType:
      # end optional args
    outputs:
      value:
```
