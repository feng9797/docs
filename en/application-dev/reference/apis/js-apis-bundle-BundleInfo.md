# BundleInfo



> **NOTE**<br>
> The initial APIs of this module are supported since API version 7. Newly added APIs will be marked with a superscript to indicate their earliest API version.



Provides the application bundle information.



 **System capability**: SystemCapability.BundleManager.BundleFramework

| Name                             | Type                                                        | Readable| Writable| Description                                      |
| --------------------------------- | ------------------------------------------------------------ | ---- | ---- | ------------------------------------------ |
| name                              | string                                                       | Yes  | No  | Bundle name.                              |
| type                              | string                                                       | Yes  | No  | Bundle type.                                |
| appId                             | string                                                       | Yes  | No  | ID of the application to which the bundle belongs.                      |
| uid                               | number                                                       | Yes  | No  | UID of the application to which the bundle belongs.                     |
| installTime                       | number                                                       | Yes  | No  | Time when the HAP file was installed.                             |
| updateTime                        | number                                                       | Yes  | No  | Time when the HAP file was updated.                             |
| appInfo                           | [ApplicationInfo](js-apis-bundle-ApplicationInfo.md)         | Yes  | No  | Application configuration information.                        |
| abilityInfos                      | Array\<[AbilityInfo](js-apis-bundle-AbilityInfo.md)>         | Yes  | No  | Ability configuration information.                         |
| reqPermissions                    | Array\<string>                                               | Yes  | No  | Permissions to request from the system for running the application.          |
| reqPermissionDetails              | Array\<[ReqPermissionDetail](#ReqPermissionDetail)>          | Yes  | No  | Detailed information of the permissions to request from the system.|
| vendor                            | string                                                       | Yes  | No  | Vendor of the bundle.                            |
| versionCode                       | number                                                       | Yes  | No  | Version number of the bundle.                            |
| versionName                       | string                                                       | Yes  | No  | Version description of the bundle.                  |
| compatibleVersion                 | number                                                       | Yes  | No  | Earliest SDK version required for running the bundle.           |
| targetVersion                     | number                                                       | Yes  | No  | Latest SDK version required for running the bundle.             |
| isCompressNativeLibs              | boolean                                                      | Yes  | No  | Whether to compress the native library of the bundle. The default value is **true**.        |
| hapModuleInfos                    | Array\<[HapModuleInfo](js-apis-bundle-HapModuleInfo.md)>     | Yes  | No  | Module configuration information.                            |
| entryModuleName                   | string                                                       | Yes  | No  | Name of the entry module.                           |
| cpuAbi                            | string                                                       | Yes  | No  | cpuAbi information of the bundle.                        |
| isSilentInstallation              | string                                                       | Yes  | No  | Whether the application can be installed in silent mode.                          |
| minCompatibleVersionCode          | number                                                       | Yes  | No  | Earliest version compatible with the bundle in the distributed scenario.        |
| entryInstallationFree             | boolean                                                      | Yes  | No  | Whether installation-free is supported for the entry module.                       |
| reqPermissionStates<sup>8+</sup>  | Array\<number>                                               | Yes  | No  | Permission grant state.                        |
| extensionAbilityInfo<sup>9+</sup> | Array\<[ExtensionAbilityInfo](js-apis-bundle-ExtensionAbilityInfo.md)> | Yes  | No  | Extension ability information.                       |



## ReqPermissionDetail

Provides the detailed information of the permissions to request from the system.

 **System capability**: SystemCapability.BundleManager.BundleFramework

| Name                 | Type                   | Readable| Writable| Description                |
| --------------------- | ----------------------- | ---- | ---- | -------------------- |
| name                  | string                  | Yes  | Yes  | Name of the permission to request.  |
| reason                | string                  | Yes  | Yes  | Reason for requesting the permission.  |
| reasonId<sup>9+</sup> | number                  | Yes  | Yes  | ID of the reason for requesting the permission.|
| usedScene             | [UsedScene](#UsedScene) | Yes  | Yes  | Application scenario and timing for using the permission.|



## UsedScene

Describes the application scenario and timing for using the permission.

 **System capability**: SystemCapability.BundleManager.BundleFramework

| Name     | Type          | Readable| Writable| Description                     |
| --------- | -------------- | ---- | ---- | ------------------------- |
| abilities | Array\<string> | Yes  | Yes  | Abilities that use the permission.|
| when      | string         | Yes  | Yes  | Time when the permission is used.         |