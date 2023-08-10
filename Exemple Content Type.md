# Example Content Type

## Content Type Name [`content_type_machine_name`]

### Content Type Settings

| Property                 | Value                                                        |
| ------------------------ | ------------------------------------------------------------ |
| Label                    | Content Type Name                                            |
| Machine Name             | content_type_machine_name                                    |
| Description              | A short explanation of the usage of the Content Type.        |
| Submission form settings | Title field label : Title<br />Preview before submitting : Required/Optional/Disabled<br />Explanation or submission guidelines : |
| Publishing options       | Published : Yes/No<br />Promoted to front page : Yes/No<br />Sticky at top of lists : Yes/No<br />Create new revision : Yes/No |
| Languages Settings       | Default language :  <br />Show language selector on create and edit pages : Yes / No<br />Enable translation : Yes / No |
| Display settings         | Display author and date information : Yes/No                 |

### Fields

| Field Name | Field Machine Name | Field Type             | N    | R    | T    | Values                        |
| ---------- | ------------------ | ---------------------- | ---- | ---- | ---- | ----------------------------- |
| Title      | `label`            | Property               | 1    | Yes  | Yes  | Max Length : 255              |
| Body       | `field_body`       | Text (Long, Formatted) | 1    | No   | No   | Allowed Formats : Simple HTML |

### Forms

#### Form Mode 1

| Field Name             | Widget                    | Options                                                      |
| :--------------------- | ------------------------- | ------------------------------------------------------------ |
| Title                  | Textfield                 | Size : 60                                                    |
| Body                   | Text Area (multiple rows) | Rows : 5                                                     |
| Authored by            | Autocomplete              | Autocomplete matching: Contains<br />Autocomplete suggestion list size: 10<br />Textfield size: 60<br />No placeholder |
| Authored on            | Datetime Timestamp        |                                                              |
| Promoted to front page | Single on/off checkbox    | Use field label: Yes                                         |
| Sticky at top of lists | Single on/off checkbox    | Use field label: Yes                                         |
| Published              | Single on/off checkbox    | Use field label: Yes                                         |

### Displays

#### Default

Template : `node--content-type-machine-name.html.twig`

| Field | Label      | Format     | Options |
| ----- | ---------- | ---------- | ------- |
| Title | - Hidden - | Plain Text |         |
| Text  | - Hidden - | Default    |         |

#### Display Mode 1

Template : `node--content-type-machine-name--display-mode-1.html.twig`

| Field | Label      | Format     | Options |
| ----- | ---------- | ---------- | ------- |
| Title | - Hidden - | Plain Text |         |
| Text  | - Hidden - | Default    |         |

### Permissions

| Permission                              | Roles                                                        |
| --------------------------------------- | ------------------------------------------------------------ |
| *Content Type Name*: Create new content | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Delete any content | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Delete own content | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Delete revisions   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Edit any content   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Edit own content   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: Revert revisions   | Anonymous user : Yes / No<br />Authenticated user : Yes / No |
| *Content Type Name*: View revisions     | Anonymous user : Yes / No<br />Authenticated user : Yes / No |

