# JIST – JSON Intermediate Structure & Translator

JIST is a universal, language-independent code structure written in JSON.  
It can be transformed into Python, C#, JavaScript, DOCX, PDF or anything else  
via interpreters or generators.

This repository contains the specification, examples, and generators.

## Example

```json
{
  "type": "function",
  "name": "add",
  "params": ["a", "b"],
  "returns": "number",
  "body": [
    {
      "type": "return",
      "value": {
        "type": "binary",
        "operator": "+",
        "left": "a",
        "right": "b"
      }
    }
  ]
}
