# 2.4-research-explainer.ms.md
# MindScript Template — Research Explainer

<MIND_SCRIPT>
    <TARGET>text</TARGET>

    <TASK>
        Explain a research topic using structured, academic-style formatting.
    </TASK>

    <DATA>
        topic: {{research_topic}}
        domain: {{field_of_study}}
    </DATA>

    <STRUCTURE>
        1. Introduction  
        2. Background  
        3. Core Principles  
        4. Applications  
        5. Limitations  
        6. Future Directions  
        7. Summary  
    </STRUCTURE>

    <RULES>
        - Tone must be formal and academic.
        - Citations should be conceptual, not fabricated.
        - No hallucinated research papers.
    </RULES>

    <OUTPUT>
        A structured research explainer with clear section headers.
    </OUTPUT>
</MIND_SCRIPT>
