# Example Vocabulary

## Vocabulary Name [`vocabulary_machine_name`]

### Vocabulary Settings

| Property           | Value                                                        |
| ------------------ | ------------------------------------------------------------ |
| Name               | Vocabulary Name                                              |
| Machine Name       | `vocabulary_machine_name`                                    |
| Description        | A short explanation of the usage of the Vocabulary and its terms. |
| Languages Settings | *Default language :*  <br />*Show language selector on create and edit pages :* Yes / No<br />*Enable translation :* Yes / No |

### Fields

| Field Name | Field Machine Name | Field Type             | N    | R    | T    | Values                          |
| ---------- | ------------------ | ---------------------- | ---- | ---- | ---- | ------------------------------- |
| Title      | `label`            | Property               | 1    | Yes  | Yes  | *Max Length :* 255              |
| Body       | `field_body`       | Text (Long, Formatted) | 1    | No   | No   | *Allowed Formats :* Simple HTML |

### Forms

#### Form Mode 1

| Field Name  | Widget                    | Options                |
| :---------- | ------------------------- | ---------------------- |
| Name        | Textfield                 | *Textfield Size :* 60  |
| Description | Text Area (multiple rows) | *Rows :* 5             |
| Language    | Language Select           |                        |
| Translation | Datetime Timestamp        |                        |
| Published   | Single on/off checkbox    | *Use field label:* Yes |

### Displays

#### Default

Template : `taxonomy-term--vocabulary-machine-name.html.twig`

| Field       | Label      | Format     | Options |
| ----------- | ---------- | ---------- | ------- |
| Description | - Hidden - | Default    |         |
| Language    | - Hidden - | - Hidden - |         |

#### Display Mode 1

Template : `taxonomy-term--vocabulary-machine-name--display-mode-1.html.twig`

| Field       | Label      | Format     | Options |
| ----------- | ---------- | ---------- | ------- |
| Description | - Hidden - | Default    |         |
| Language    | - Hidden - | - Hidden - |         |

### Permissions

| Permission                                | Roles                                                        |
| ----------------------------------------- | ------------------------------------------------------------ |
| Translate *Vocabulary Name* taxonomy term | Anonymous user : Yes / No<br />*Authenticated user :*  Yes / No |
| *Vocabulary Name*: Create terms           | Anonymous user : Yes / No<br />*Authenticated user :*  Yes / No |
| *Vocabulary Name*: Delete terms           | Anonymous user : Yes / No<br />*Authenticated user :*  Yes / No |
| *Vocabulary Name*: Edit terms             | Anonymous user : Yes / No<br />*Authenticated user :*  Yes / No |

