## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_AppCenter
package-version: 2019-05-12
azure-arm: true
```

### Tag: package-2019-05-12 and ruby

These settings apply only when `--tag=package-2019-05-12 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2019-05-12' && $(ruby)
namespace: Microsoft.AppCenter
output-folder: $(ruby-sdks-folder)/AppCenter
```