# 3.3-er-diagram.ms.md
# MindScript Template — ER Diagram Generator

<MIND_SCRIPT>
    <TARGET>diagram</TARGET>

    <TASK>
        Generate an Entity–Relationship (ER) diagram specification.
    </TASK>

    <DATA>
        entities:
            {{entity_list}}
        relationships:
            {{relationship_list}}
    </DATA>

    <STRUCTURE>
        entities:
            - name
            - attributes
        relationships:
            - entity_a
            - entity_b
            - cardinality
            - description
    </STRUCTURE>

    <RULES>
        - No graphical output, only symbolic structure.
        - Must preserve entity order.
    </RULES>

    <OUTPUT>
        ER diagram specification (entities + relationships block).
    </OUTPUT>
</MIND_SCRIPT>
