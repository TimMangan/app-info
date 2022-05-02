# App-Info Document Template (replace this with your application name)

(Logo here) This application is used for ...

This is the high level file that describes the application summary.  Additional documentation files may also be present to cover specific scenarios, such as repackaging into a specific format.  Make a copy of this template saved into an appropriate subfolder and name it **ReadMe.md**.

## Documentation for

| Category | Value |
|-----|-------------------------------------------------------|
| Vendor Name | |
| Application Name| |
| Application Version | Leave blank if version specific doc files exist. |
| Vendor/App Website|  |



## Vendor Installer Types

This is where we can define the forms of installers available from the vendor.
<table >
<tr>
<td>

| Type | Available |
|----|----|
| Setup Exe | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| MSI | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| AppX/Bundle | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| MSIX/Bundle | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| .appinstaller | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |

</td>
<td width=100></td>
<td>

| Architecture | Available |
|----|----|
| 32-bit | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| 64-bit | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| AnyCPU | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| Arm | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |
| Arm-64 | [<img src="/media/Unknown.png" alt="Unknown" />](/media/Unknown.png) |

</td>
</tr>
</table>

## App Configuration Type

This is where to place a summary of how application configuration is stored.  Items of configuration of common interest should be documented in a separate file.

| Type | Used |
|----|----|
| Registry | [<img src="/media/Unknown.png" alt="Yes" />](/media/Unknown.png) |
| File | [<img src="/media/Unknown.png" alt="Yes" />](/media/Unknown.png) |
| AD/GPO | [<img src="/media/Unknown.png" alt="Yes" />](/media/Unknown.png) |
| AAD/GPO | [<img src="/media/Unknown.png" alt="Yes" />](/media/Unknown.png) |


## Repackaging Summary

This is where to list a summary of known success (or not) in repackaging info certain formats.  If repackaging the application is not straightforward, a specific documentation file covering the details for that repackaging format is suggested. Values in the Success field are somewhat subjective, but we recommend that the summary use the following value:

* [<img src="/media/CatFullFidelity.png" alt="Full Fidelity" />](/media/CatFullFidelity.png) - App appears to be completly functional.
* [<img src="/media/CatHighConfidence.png" alt="High Confidence" />](/media/CatHighConfidence.png) - There may be a small loss in functionality, but most companies will be OK with deploying this form.
* [<img src="/media/CatMostlyWorks.png" alt="Mostly Works" />](/media/CatMostlyWorks.png) - A loss in functionality that likely makes this a bad way to deploy.
* [<img src="/media/CatIssues.png" alt="Has Issues" />](/media/CatIssues.png) - Application is known to not work in this form (so far).
* [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) - No information is available.


| Type | Success |
|----|----|
| MSI | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| App-V | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| ThinApp | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| Citrix App Layers | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| Cloud Volumes | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| FlexApp | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| Numecent | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |
| MSIX | [<img src="/media/CatUnknown.png" alt="Unknown/Untested" />](/media/CatUnknown.png) |

## Useful links
This is a place to put useful links to appropriate existing external sources, either those of the vendor or elsewhere.