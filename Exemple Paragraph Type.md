# Example Paragraph

## Paragraph Type Name [`paragraph_type_machine_name`]

### Paragraph Settings
| Property         | Value |
|--------------|------|
| Label        | Paragraph Type  Name |
| Machine Name | paragraph_type_machine_name |
| Icon         | [SVG link] |
| Description  | A short explanation of the usage of the Paragraph Type. |
| Languages Settings | *Default language :*  <br />*Show language selector on create and edit pages :* Yes / No<br />*Enable translation :* Yes / No |

### Fields

| Field Name | Field Machine Name | Field Type             | N    | R    | T    | Values                          |
| ---------- | ------------------ | ---------------------- | ---- | ---- | ---- | ------------------------------- |
| Title      | `field_title`      | Text (plain)           | 1    | Yes  | Yes  | *Max Length :* 255              |
| Text       | `field_text`       | Text (Long, Formatted) | 1    | No   | No   | *Allowed Formats :* Simple HTML |

### Forms

#### Form Mode 1

| Field Name  | Widget                    | Options     |
| :---------- | ------------------------- | ----------- |
| Title       | Textfield                 | *Size :* 60 |
| Text        | Text Area (multiple rows) | *Rows :* 5  |
| Published   | Disabled                  |             |
| Authored On | Disabled                  |             |

### Displays

#### Display Mode 1

Template : `paragraph--paragraph-machine-name--display-mode-1.html.twig`

| Field | Label      | Format     | Options |
| ----- | ---------- | ---------- | ------- |
| Title | - Hidden - | Plain Text |         |
| Text  | - Hidden - | Default    |         |

