# Test of how github includes SVGs in markdown

## SVG Graphics

SVG through markdown:

![alt text](picture.svg "svg image")

PNG through markdown:

![alt text](picture.png "png image")

SVG through relative html:

<object type="image/svg+xml" data="picture.svg" border="0"></object>

## Tables

Pretty in code:

| Feature | Status |
| :---    | :---:  |
| a       | ✓      |
| b       |        |

Ugly in code:

| Feature | Status |
| :--- | :---: |
| a | ✓ |
| b | |

