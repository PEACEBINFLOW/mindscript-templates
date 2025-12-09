# 3.4-node-network.ms.md
# MindScript Template — Node Network Diagram

<MIND_SCRIPT>
    <TARGET>diagram</TARGET>

    <TASK>
        Build a node–edge network diagram.
    </TASK>

    <DATA>
        nodes: {{node_list}}
        edges: {{edge_list}}
    </DATA>

    <STRUCTURE>
        nodes:
            - id
            - label
            - type
        edges:
            - from
            - to
            - relation
    </STRUCTURE>

    <RULES>
        - No cycles unless specified.
        - Output must be deterministic.
    </RULES>

    <OUTPUT>
        Node list + edge list representation.
    </OUTPUT>
</MIND_SCRIPT>
