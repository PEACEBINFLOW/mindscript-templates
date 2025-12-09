# 4.4-character-sheet-builder.ms.md
# MindScript Template — Character Sheet Builder

<MIND_SCRIPT>
    <TARGET>image</TARGET>

    <TASK>
        Build a character sheet prompt with defined visual attributes.
    </TASK>

    <DATA>
        name: {{character_name}}
        traits: {{character_traits}}
        outfit: {{outfit_description}}
    </DATA>

    <STRUCTURE>
        - Full-body description
        - Headshot description
        - Clothing breakdown
        - Color palette
        - Key accessories
        - Poses
    </STRUCTURE>

    <RULES>
        - Maintain consistency across poses.
        - No contradictory attributes.
    </RULES>

    <OUTPUT>
        Character sheet generation prompt.
    </OUTPUT>
</MIND_SCRIPT>
