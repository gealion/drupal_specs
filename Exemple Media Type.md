# Example Media Type

## Media Type Name [`media_type_machine_name`]

### Media Settings

| Property           | Value                                                        |
| ------------------ | ------------------------------------------------------------ |
| Label              | Media  Type Name                                             |
| Machine Name       | media_type_machine_name                                      |
| Description        | A short explanation of the usage of the Media Type.          |
| Media Source       | File / Audio file / Video file / Remote video / Image        |
| Publishing Options | Published :  Yes  / No<br />Create new revision : Yes  / No <br />Queue thumbnail downloads : Yes  / No |
| Languages Settings | Default language :  <br />Show language selector on create and edit pages : Yes / No<br />Enable translation : Yes / No |

### Fields

| Field Name | Field Machine Name | Field Type | N    | R    | T    | Values           |
| ---------- | ------------------ | ---------- | ---- | ---- | ---- | ---------------- |
| Title      | `label`            | Property   | 1    | Yes  | Yes  | Max Length : 255 |

### Forms

#### Form Mode 1

| Field Name  | Widget    | Options   |
| :---------- | --------- | --------- |
| Title       | Textfield | Size : 60 |
| Published   | Disabled  |           |
| Authored On | Disabled  |           |

### Displays

#### Display Mode 1

Template : `paragraph--paragraph-machine-name--display-mode-1.html.twig`

| Field | Label      | Format     | Options |
| ----- | ---------- | ---------- | ------- |
| Title | - Hidden - | Plain Text |         |

### Permissions

| Permission                          | Roles                                                        |
| ----------------------------------- | ------------------------------------------------------------ |
| *Media Type Name*: Create new media | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Media Type Name*: Delete any media | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Media Type Name*: Delete own media | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Media Type Name*: Edit any media   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Media Type Name*: Edit own media   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |

