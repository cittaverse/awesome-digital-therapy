# Narrative Quality Scoring — Research Landscape (March 2026 Update)

> GEO #61 — Research scan for latest automated narrative assessment tools

## Key Findings

### 1. Van Genugten et al. — Automated AI Scoring (Springer, 2025)
- **Paper**: "Modeling memories, predicting prospections: Automated scoring of autobiographical detail narration using large language models"
- **Journal**: Behavior Research Methods (Springer)
- **Approach**: Fine-tuned distilBERT for internal/external detail classification
- **Language**: English only
- **Dimensions**: 2 (internal details, external details)
- **Method**: Sentence-level classification → aggregation
- **Code**: [GitHub](https://github.com/rubenvangenugten/autobiographical_interview_scoring)
- **CittaVerse differential**: 
  - Our scorer: 6 dimensions (vs 2)
  - Chinese language support (vs English only)
  - Neuro-symbolic (no LLM dependency vs distilBERT required)
  - Clinical context (MCI screening vs general research)

### 2. Pan et al. — LLM-based Memory Scoring (UChicago, 2026)
- **Paper**: "LLM-based scoring of narrative memories reveals that emotional arousal..."
- **Source**: UChicago working paper (2026-03)
- **Approach**: LLMs for quantifying emotional arousal + memory fidelity
- **Relevance**: Validates LLM-based scoring approach → supports our v0.6 hybrid roadmap
- **CittaVerse differential**: We focus on Chinese elderly population + clinical deployment

### 3. Rememo — AI-in-the-loop Therapy Tool (NUS, 2026)
- **Paper**: arXiv:2602.17083 — "Rememo: A Research-through-Design Inquiry Towards an AI-in-the-loop Therapist's Tool for Dementia Reminiscence"
- **Team**: Celeste Seah et al., National University of Singapore
- **Focus**: AI-generated imagery for therapist-guided reminiscence
- **CittaVerse differential**: We focus on post-session assessment (scoring), they focus on in-session content generation → complementary

### 4. Remi — LLM Chatbot for Reminiscence (UChicago, 2025)
- **Paper**: Biological Psychiatry Journal, 2025
- **Approach**: LLM chatbot delivering structured Simple Reminiscence Therapy
- **Target**: Socially isolated older adults
- **CittaVerse differential**: We provide structured quality assessment, not just conversation

### 5. Noa — AI Agent for Long-Term Care (2025)
- **Paper**: "Exploring AI Agents for Reminiscence Therapy in Long-Term Care"
- **Approach**: Embodied conversational agent (ECA) with avatar
- **CittaVerse differential**: We focus on narrative quality measurement, not avatar interaction

### 6. Frontiers VR-RT Review (2025)
- **Paper**: "Developing assistive technology to support reminiscence therapy: a user..." (Frontiers in Medicine)
- **Scope**: Technology landscape from static digital aids to immersive AI systems
- **Relevance**: Positions CittaVerse in the "adaptive AI" tier of the landscape

## Competitive Positioning Summary

| Tool | Language | Dimensions | Method | Clinical | Open Source |
|------|----------|-----------|--------|----------|-------------|
| **CittaVerse Scorer** | Chinese | 6 | Neuro-symbolic | MCI screening | ✅ MIT |
| Van Genugten | English | 2 | distilBERT | General research | ✅ |
| Pan et al. | English | 2 (arousal + fidelity) | LLM | General research | ❌ |
| Rememo | English | N/A (generation) | GenAI | Dementia care | ❌ |
| Remi | English | N/A (chatbot) | LLM | Social isolation | ❌ |

## Implications for CittaVerse

1. **Market validation**: Multiple groups independently pursuing automated narrative assessment → confirms demand
2. **Differentiation strong**: No Chinese-language tool exists; 6-dimension framework is unique
3. **v0.6 hybrid approach validated**: Both van Genugten and Pan use LLMs → supports our hybrid roadmap
4. **Collaboration opportunity**: Rememo (complementary, not competitive) → email outreach planned
5. **Academic community growing**: 5+ active research groups → good timing for arXiv submission

---

*Research scan completed 2026-03-23 22:00 UTC by Hulk 🟢*
