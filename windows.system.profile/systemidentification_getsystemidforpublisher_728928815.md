---
-api-id: M:Windows.System.Profile.SystemIdentification.GetSystemIdForPublisher
-api-type: winrt method
---

<!-- Method syntax
public Windows.System.Profile.SystemIdentificationInfo GetSystemIdForPublisher()
-->

# Windows.System.Profile.SystemIdentification.GetSystemIdForPublisher

## -description
Gets an identifier value for the system based on the app publisher ID.

## -returns
A [SystemIdentificationInfo](systemidentificationinfo.md) object for this system, based on the app publisher ID.

## -remarks
The identifier returned by this method is specific to the app publisher on the current device.


The ID has the following characteristics:

+ Unique for every system
+ Can be created offline
+ Persists across rebooting, OS upgrades/reinstalls, and so on
+ Persists across hardware modifications
+ Available in OneCore
+ Available on the factory floor for licensing purposes
This method requires either a Unified Extensible Firmware Interface (UEFI) or a Trusted Platform Module (TPM) to generate the system ID. It will fail if neither is present.

## -examples

## -see-also
