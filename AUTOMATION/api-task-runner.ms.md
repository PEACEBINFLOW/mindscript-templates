# 6.2-api-task-runner.ms.md
# MindScript Template — API Task Runner

<MIND_SCRIPT>
    <TARGET>automation</TARGET>

    <TASK>Execute an API-driven workflow.</TASK>

    <DATA>
        endpoint: {{api_endpoint}}
        payload: {{payload_structure}}
        sequence: {{step_list}}
    </DATA>

    <STRUCTURE>
        - Authenticate
        - Send Request
        - Process Response
        - Error Handling
        - Final Output
    </STRUCTURE>

    <OUTPUT>
        Structured API task plan.
    </OUTPUT>
</MIND_SCRIPT>
