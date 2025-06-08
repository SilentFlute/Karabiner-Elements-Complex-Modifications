# 概览

个人[Karabiner-Elements](https://karabiner-elements.pqrs.org/) `Complex Modifications`配置

# VS Code 中的 4 个箭头(4 arrows in VS Code)

```json
{
  "description": "VSCode中四个箭头的快捷键",
  "manipulators": [
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "i",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "up_arrow" }],
      "type": "basic"
    },
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "k",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "down_arrow" }],
      "type": "basic"
    },
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "j",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "left_arrow" }],
      "type": "basic"
    },
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "l",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "right_arrow" }],
      "type": "basic"
    },
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "h",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "home" }],
      "type": "basic"
    },
    {
      "conditions": [
        {
          "bundle_identifiers": ["^com\\.microsoft\\.VSCode$"],
          "type": "frontmost_application_if"
        }
      ],
      "from": {
        "key_code": "semicolon",
        "modifiers": { "mandatory": ["option"] }
      },
      "to": [{ "key_code": "end" }],
      "type": "basic"
    }
  ]
}
```
