---
Title: Dnd
---

Interact with dnd5eapi.co
​
## Commands
- {{% commandref classes "List character classes" %}}
- {{% commandref condition "Get info about a condition" %}}
- {{% commandref conditions "List conditions" %}}
- {{% commandref healing "Get info about Potions of Healing" %}}
- {{% commandref school "Get info about a magic school" %}}
- {{% commandref schools "List magic schools" %}}
- {{% commandref spell "Get info about a spell" %}}
- {{% commandref spells "List spells by level and optionally class" %}}

{{% command classes "List character classes" %}}
- Do gary `spells <level> [character_class]` to list spells for a class
{{% command condition "Get info about a condition" "<condition>" %}}
- `condition` is the name of the condition
- Do `gary conditions` to list possible conditions
{{% command conditions "List conditions" %}}
- Do `gary condition <condition>` to get info about a condition
{{% command healing "Get info about Potions of Healing" "" "heal" %}}
{{% command school "Get info about a magic school" "<magic_school>" "magic" %}}
- `magic_school` is the name of the magic school
- Do `gary schools` to list possible magic schools
{{% command schools "List magic schools" "" "magics" %}}
- Do `gary school <magic_school>` to get info about magic school
{{% command spell "Get info about a spell" "<spell_name>" %}}
- `spell_name` is the name of the spell
- Do `gary spells <level> [character_class]` to list possible spells
{{% command spells "List spells by level and optionally class" "<level> [character_class]" %}}
- `level` is the level of the spell (required)
- `character_class` is the class to list spells for (optional)
- Do `gary classes` to list possible character classes
- Do `gary spell <spell_name>` to get info about a spell