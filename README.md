# minecraft-zarf

To create this package:

```shell
zarf package create --max-package-size=0 --confirm
```

To deploy:

```shell
zarf package deploy zarf-package-minecraft-<arch>-<version>.tar.zst --confirm
```
