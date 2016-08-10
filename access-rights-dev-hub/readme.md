---
title: "Access Rights for Dev Hub"
sub-title: "This article covers how to secure access to Dev Hub in general and in particular to tools like the Widget editor, the Extension editor and the Engine API explorer."
draft: true
meta:
  page-image: "images/page-image.png"
---

Introduced with Qlik Sense 3.0 you now also have granular control to define access rights for Dev Hub. This article covers some of the most common scenarios. But due to the feature-richness of the Security Rules concept in Qlik Sense there is by far more possible as described in this article.

## Default settings

The default settings - starting with Qlik Sense 3.0 - for Dev Hub are:

- The RootAdmin has full access rights to Dev-Hub and all its tools (Single configurator, Extension editor, Mashup editor, Engine API explorer, Widget editor).
- All other users (if they don't have RootAdmin or ContentAdmin rights) will be able to access Dev-Hub, but Extension editor, Mashup editor and the Engine API explorer are deactivated (grayed out).
- It is important to mention though, that these users can use existing Visualization extensions or Widgets by default.

### Default security rules on QMC

There are some default security rules with come with every installation of Qlik Sense that enable the above described behavior:

- `Extension` - Everyone can view extensions
- `ContentAdmin` - Definition

Note: From a QMC perspective Mashups & Widget libraries are treated as extensions.

## Scenario 1: Allow everyone to create extensions, widget libraries and widgets



## See also
- [Access rights and Dev Hub](http://rd-docloc.rdlund.qliktech.com/en-US/sense-developer/3.0-ld/Subsystems/Dev-Hub/Content/Overview/dev-hub-access-rights.htm) on help.qlik.com
- [QMC Help: Default administration roles](http://help.qlik.com/en-US/sense/3.0/Subsystems/ManagementConsole/Content/default-administration-roles.htm) 
- [QMC Help: Property-based access control](http://help.qlik.com/en-US/sense/3.0/Subsystems/ManagementConsole/Content/property-based-access-control.htm) 
- [QMC Help: Security rules overview](http://help.qlik.com/en-US/sense/3.0/Subsystems/ManagementConsole/Content/security-rules-overview.htm) 
- [QMC Help: Creating security rules](http://help.qlik.com/en-US/sense/3.0/Subsystems/ManagementConsole/Content/create-security-rules.htm) 


## FAQ

**Q**: Can I disable the button for "Dev Hub" in Qlik Sense's Hub?
**A**: No, this is currently (af Qlik Sense 2.2 and higher) not possible and supported.

## Further Questions?

If there are any uncovered questions or scenarios in this article, please feel free to add a comment at the bottom of this page.
