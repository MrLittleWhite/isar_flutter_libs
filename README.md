### Flutter binaries for the [Isar Database](https://github.com/isar/isar) please go there for documentation.
Fix isar_flutter_libs build errors, on 3.1.0+1.
See: https://github.com/isar/isar/issues/1470

Change pubspec.yaml file in your poject: 

use:
```yaml
isar_flutter_libs:
    git: 
      url: https://github.com/MrLittleWhite/isar_flutter_libs.git
```

instead:
```yaml
isar_flutter_libs: ^3.1.0+1
```
