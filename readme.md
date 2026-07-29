


# sampleRBAC

RBAC sample project


For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [DeleteAllData](#deletealldata)
        - [Page](#page)
        - [ReadAllData](#readalldata)
    - [Shared Actions](#shared-actions)
        - [GetPermissions](#getpermissions)
    - [Shared Components](#shared-components)
        - [CardItem](#carditem)


## Installation

1. In your Convertigo Studio click on ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/icons/studio/project_import.gif?raw=true "Import a project in treeview") to import a project in the treeview
2. In the import wizard

   ![](https://github.com/convertigo/convertigo/blob/develop/eclipse-plugin-studio/tomcat/webapps/convertigo/templates/ftl/project_import_wzd.png?raw=true "Import Project")
   
   paste the text below into the `Project remote URL` field:
   <table>
     <tr><td>Usage</td><td>Click the copy button at the end of the line</td></tr>
     <tr><td>To contribute</td><td>

     ```
     sampleRBAC=git@github.com:convertigo/c8oprj-sample-rbac.git:branch=8.4.0.0
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     sampleRBAC=git@github.com:convertigo/c8oprj-sample-rbac/archive/8.4.0.0.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __sampleRBAC__ project


## Mobile Application

Describes the mobile application global properties

### Pages

#### DeleteAllData

Demonstrates page access granted by the samplerbac.data.delete:all permission

#### Page

Default home page

#### ReadAllData

Demonstrates page access granted by the samplerbac.data.read:all permission

### Shared Actions

#### GetPermissions

### Shared Components

#### CardItem

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>item</td><td></td>
</tr>
</table>

**events**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>onDelete</td><td></td>
</tr>
</table>



