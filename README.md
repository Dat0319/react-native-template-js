# react-native-template-js

# RN_Core

---

## this is a core of a app and syntax to render a app auto all thing you want.

### auto create a project React Native with the same structure components:

<br>
run init project from local computer:

```
sh create_RN_project_custom.sh

```

run init project from git hub repo full components:

```
sh rn_init.sh

```

run init project from server company use curl:

```
sh rn_core.sh

```

### Fix flipper with high ios version

((!defined(TARGET*OS_OSX) || TARGET_OS_OSX)
&& (MAC_OS_X_VERSION_MIN_REQUIRED MAC_OS_X_VERSION_10_15)) ||
(TARGET_OS_IPHONE & (**IPHONE_OS_VERSION_MIN_REQUIRED < **IPHONE_12*)

follow [link](https://github.com/facebook/flipper/issues/834#issuecomment-605403957)

```
https://github.com/facebook/flipper/issues/834#issuecomment-605403957
```
