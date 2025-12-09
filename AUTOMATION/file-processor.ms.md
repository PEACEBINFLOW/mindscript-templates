# 6.3-file-processor.ms.md
# MindScript Template — File Processor

<MIND_SCRIPT>
    <TARGET>automation</TARGET>

    <TASK>Define a multi-step file processing workflow.</TASK>

    <DATA>
        file_type: {{file_type}}
        operations: {{operation_list}}
    </DATA>

    <STRUCTURE>
        - Load File
        - Validate Format
        - Apply Transformations
        - Export
        - Verification
    </STRUCTURE>

    <OUTPUT>
        Deterministic file processing sequence.
    </OUTPUT>
</MIND_SCRIPT>
