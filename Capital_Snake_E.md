# Capital_Snake Naming Rules

## Introduction

**Capital_Snake** is a naming convention designed to address the shortcomings of other styles  
such as snake_case, UpperCamelCase, and lowerCamelCase, specifically their handling of abbreviations,  
which often appear unnatural and difficult to read.

| **Naming Style** | **Example**       |
| ---------------- | ----------------- |
| snake_case       | uml_defined_model |
| UpperCamelCase   | UMLDefinedModel   |
| UpperCamelCase   | UmlDefinedModel   |
| lowerCamelCase   | umlDefinedModel   |
| Capital_Snake    | UML_Defined_Model |

**Capital_Snake** emphasizes consistency and readability, making it suitable for file names, variable names, and system configurations.  
**Capital_Snake** does not seek to replace existing naming conventions or coding rules;  
rather, it aims to complement them by addressing their shortcomings.  
When existing rules prove inadequate, **Capital_Snake** can be utilized to achieve clear and effective naming,  
serving as a useful tool for better project practices.

---

## Basic Rules

1. **Word Delimiters**:

   - Separate words using underscores (`_`).

2. **Capitalized First Letters**:

   - Capitalize the first letter of each word.
   - Articles, prepositions, and conjunctions should also have their first letters capitalized.

3. **Abbreviations**:

   - Abbreviations must be written entirely in uppercase.
   - Add an underscore (`_`) after the abbreviation for clear separation from other words.

4. **Allowed Characters**:

   - Use uppercase and lowercase alphabet letters (A–Z, a–z), digits (0–9), and symbols (`_`, `-`, `.`).
   - Non-ASCII characters (e.g., Japanese or other special characters) are generally allowed.

5. **Forbidden Characters**:

   - The following characters are prohibited:
     - Spaces (` `)
     - Reserved characters (`*`, `?`, `<`, `>`, `|`, `"`, `:`, `/`, `\`)
     - Special symbols (`$`, `%`, `&`, `^`, `,`, `(`, `)`)

6. **Exceptional Rules**:
   - When specific tools or environments restrict certain characters, additional forbidden characters should be defined individually.

---

## Examples of Application

| **Structure**                  | **Example**              |
| ------------------------------ | ------------------------ |
| Technical document name        | `UML_Class_Diagram.xlsx` |
| Naming compatible with English | `This_Is_A_Table`        |
| System configuration file name | `Server_Config_File.ini` |
| Directory name                 | `User_Data_Backup`       |
| Code function name             | `Create_JSON_Parser`     |

---

## List of Forbidden Characters

## ASCII Code Table

|         | 0     | 1     | 2     | 3     | 4     | 5     | 6     | 7     |
| ------- | ----- | ----- | ----- | ----- | ----- | ----- | ----- | ----- |
| **0x0** | ✖ NUL | ✖ SOH | ✖ STX | ✖ ETX | ✖ EOT | ✖ ENQ | ✖ ACK | ✖ BEL |
| **0x1** | ✖ BS  | ✖ HT  | ✖ LF  | ✖ VT  | ✖ FF  | ✖ CR  | ✖ SO  | ✖ SI  |
| **0x2** | ✖ DLE | ✖ DC1 | ✖ DC2 | ✖ DC3 | ✖ DC4 | ✖ NAK | ✖ SYN | ✖ ETB |
| **0x3** | ✖ CAN | ✖ EM  | ✖ SUB | ✖ ESC | ✖ FS  | ✖ GS  | ✖ RS  | ✖ US  |
| **0x4** | ✔ SPC | ✔ !   | ✖ "   | ✔ #   | ✖ $   | ✖ %   | ✖ &   | ✔ '   |
| **0x5** | ✖ (   | ✖ )   | ✖ \*  | ✔ +   | ✖ ,   | ✔ -   | ✔ .   | ✖ /   |
| **0x6** | ✔ 0   | ✔ 1   | ✔ 2   | ✔ 3   | ✔ 4   | ✔ 5   | ✔ 6   | ✔ 7   |
| **0x7** | ✔ 8   | ✔ 9   | ✖ :   | ✖ ;   | ✖ <   | ✔ =   | ✖ >   | ✖ ?   |
| **0x8** | ✔ @   | ✔ A   | ✔ B   | ✔ C   | ✔ D   | ✔ E   | ✔ F   | ✔ G   |
| **0x9** | ✔ H   | ✔ I   | ✔ J   | ✔ K   | ✔ L   | ✔ M   | ✔ N   | ✔ O   |
| **0xA** | ✔ P   | ✔ Q   | ✔ R   | ✔ S   | ✔ T   | ✔ U   | ✔ V   | ✔ W   |
| **0xB** | ✔ X   | ✔ Y   | ✔ Z   | ✔ [   | ✖ \\  | ✔ ]   | ✖ ^   | ✔ \_  |
| **0xC** | ✖ `   | ✔ a   | ✔ b   | ✔ c   | ✔ d   | ✔ e   | ✔ f   | ✔ g   |
| **0xD** | ✔ h   | ✔ i   | ✔ j   | ✔ k   | ✔ l   | ✔ m   | ✔ n   | ✔ o   |
| **0xE** | ✔ p   | ✔ q   | ✔ r   | ✔ s   | ✔ t   | ✔ u   | ✔ v   | ✔ w   |
| **0xF** | ✔ x   | ✔ y   | ✔ z   | ✖ {   | ✖ \|  | ✖ }   | ✔ ~   | ✖ DEL |
