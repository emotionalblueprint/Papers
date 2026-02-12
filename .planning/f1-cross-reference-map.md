# F1 Cross-Reference Map

Framework 1: The Emotional Gradient — Scientific Foundations

## Status Overview

| Source Theory | .org Status | Priority | Notes |
|--------------|-------------|----------|-------|
| Polyvagal Theory | ✅ exists | — | `/content/theories/polyvagal.json` |
| Attachment Theory | ✅ exists | — | `/content/theories/attachment.json` |
| Affective Neuroscience | ❌ missing | HIGH | Panksepp, Damasio, Barrett, LeDoux |
| Trauma Research | ❌ missing | HIGH | van der Kolk, Levine, Ogden, Herman |
| Emotion Science | ❌ missing | MEDIUM | Gross, Siegel, Fredrickson, Ekman |
| Motivational Science | ❌ missing | LOW | Gray, Carver & Scheier |

## F1 Content That Should Link to .org

### 1. Cross-Theoretical Validation Table (line 19-26)

| Concept | Tradition | Researcher | .org Link Needed |
|---------|-----------|------------|------------------|
| Autonomic States | Polyvagal Theory | Porges | ✅ `/theories/polyvagal` |
| Approach/Avoidance | Motivational Science | Gray, Carver & Scheier | ❌ create theory |
| Broaden-and-Build | Positive Psychology | Fredrickson | ❌ create theory |
| Window of Tolerance | Trauma Theory | Siegel, Ogden | ❌ create theory |
| Safety vs. Threat | Attachment Theory | Bowlby | ✅ `/theories/attachment` |
| Fight-Flight-Freeze-Fawn | Trauma Research | Walker, van der Kolk | ❌ create theory |

### 2. Scientific Foundations Section (line 101-127)

**Domain: Polyvagal Theory & Autonomic Neuroscience**
- Stephen Porges → ✅ linked to polyvagal.json
- Deb Dana → included in polyvagal.json sources

**Domain: Affective Neuroscience** → ❌ CREATE NEW THEORY FILE
- Jaak Panksepp: Primary emotional systems
- Antonio Damasio: Somatic marker hypothesis
- Lisa Feldman Barrett: Constructed Emotion theory
- Joseph LeDoux: Amygdala & threat detection

**Domain: Trauma Research** → ❌ CREATE NEW THEORY FILE
- Bessel van der Kolk: Trauma and the body
- Peter Levine: Somatic Experiencing
- Pat Ogden: Sensorimotor Psychotherapy
- Judith Herman: Complex trauma

**Domain: Attachment Theory**
- John Bowlby → ✅ linked to attachment.json
- Mary Ainsworth → included in attachment.json
- Mary Main → included in attachment.json
- Allan Schore → ❌ could add to attachment.json

**Domain: Emotion Science** → ❌ CREATE NEW THEORY FILE
- James Gross: Process model of emotion regulation
- Daniel Siegel: Window of tolerance, interpersonal neurobiology
- Barbara Fredrickson: Broaden-and-build theory
- Paul Ekman: Basic emotions

### 3. Core Terminology (line 129-140)

Terms that should link to .org glossary:
- Neuroception → ❌ create glossary entry
- Pattern A / Pattern B → ❌ create glossary entry (or use four-mode-gradient)
- State-Dependent Capacity → ❌ create glossary entry
- Calibration → ❌ create glossary entry
- Pattern Hijack → ❌ create glossary entry
- Threat Lock → ❌ create glossary entry

## Proposed .org Content to Create

### Theory Files Needed (Priority Order)

1. **trauma-research.json** — van der Kolk, Levine, Ogden, Herman
2. **affective-neuroscience.json** — Panksepp, Damasio, Barrett, LeDoux
3. **emotion-science.json** — Gross, Siegel, Fredrickson, Ekman
4. **motivational-science.json** — Gray, Carver & Scheier, BIS/BAS

### Glossary Terms Status

| Term | .org Status | Notes |
|------|-------------|-------|
| four-mode-gradient | ✅ exists | ⚠️ Uses "Connect/Protect/Collapse/Restore" — differs from .com "Connection/Protection/Control/Domination" |
| regulatory-state | ✅ exists | |
| neuroception | ❌ missing | Core F1 concept |
| state-dependent-capacity | ❌ missing | |
| calibration | ❌ missing | |
| pattern-hijack | ❌ missing | |
| threat-lock | ❌ missing | |

### ✅ Terminology Inconsistency RESOLVED

**.com uses:** Connection → Protection → Control → Domination
**.org now uses:** Connection → Protection → Control → Domination

Fixed in commit d4af6c3 (2026-02-12)

## Cross-Linking Strategy

### From .com F1 → .org

Add external links in F1 PageContent.js:

```jsx
// In Cross-Theoretical Validation table
{ concept: 'Autonomic States',
  tradition: 'Polyvagal Theory',
  researcher: 'Porges',
  orgLink: 'https://teg-blue.org/theories/polyvagal',  // ADD
  integration: '...'
}
```

### From .org Theory → .com F1

In each theory JSON, add connection:

```json
{
  "connections": [
    {
      "type": "extends",
      "targetUrl": "https://teg-blue.com/mapping-system/following-nervous-system/f1",
      "label": "Applied in Framework 1"
    }
  ]
}
```

## Next Steps

1. [ ] Create trauma-research.json on .org
2. [ ] Create affective-neuroscience.json on .org
3. [ ] Create neuroception.json glossary entry
4. [ ] Update F1 PageContent.js with .org links
5. [ ] Update existing polyvagal.json and attachment.json with F1 connection

---

*Created: 2026-02-12*
