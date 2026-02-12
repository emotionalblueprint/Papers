# F2 Cross-Reference Map

Framework 2: Identity Formation — Real Self & Role Mask

## Status: ✅ COMPLETE

| Source Theory | .org Status | Notes |
|--------------|-------------|-------|
| Object Relations | ✅ created | Winnicott - True Self / False Self |
| Humanistic Psychology | ✅ created | Rogers - Organismic Self |
| Analytical Psychology | ✅ created | Jung - Persona |
| Developmental Psychology | ✅ created | Chess & Thomas, Kagan - Temperament |
| Self Psychology | ✅ created | Kohut - Compensatory structures |
| Psychoanalysis | ✅ created | Freud - Defensive structures |
| Attachment Theory | ✅ exists | Already linked |
| Affective Neuroscience | ✅ exists | Already linked |
| Trauma Research | ✅ exists | Already linked |

Glossary: real-self.json, role-mask.json ✅ created
Cross-links in F2 PageContent.js ✅ added (commit 802f71f)

## F2 Content That Should Link to .org

### 1. Cross-Theoretical Validation: Real Self (line 86-93)

| Concept | Tradition | Researcher | .org Link Needed |
|---------|-----------|------------|------------------|
| True Self | Object Relations | Winnicott | ❌ create theory |
| Organismic Self | Humanistic Psychology | Rogers | ❌ create theory |
| Temperament | Developmental Psychology | Chess & Thomas, Kagan | ❌ create theory |
| Primary Emotions | Affective Neuroscience | Panksepp | ✅ `/theories/affective-neuroscience` |
| Interoceptive Self | Neuroscience | Craig, Damasio | ✅ `/theories/affective-neuroscience` |
| Somatic Self | Somatic Psychology | Levine, Ogden | ✅ `/theories/trauma-research` |

### 2. Cross-Theoretical Validation: Role Mask (line 95-102)

| Concept | Tradition | Researcher | .org Link Needed |
|---------|-----------|------------|------------------|
| False Self | Object Relations | Winnicott | ❌ create theory |
| Persona | Analytical Psychology | Jung | ❌ create theory |
| Attachment Strategy | Attachment Theory | Ainsworth, Main | ✅ `/theories/attachment` |
| Defensive Structure | Psychoanalysis | Freud, A. Freud | ❌ create theory |
| Survival Self | Trauma Psychology | van der Kolk | ✅ `/theories/trauma-research` |
| Compensatory Structure | Self Psychology | Kohut | ❌ create theory |

## Proposed .org Content to Create

### Theory Files Needed (Priority Order)

1. **object-relations.json** — Winnicott (True Self / False Self)
2. **humanistic-psychology.json** — Rogers (Organismic Self, Actualizing tendency)
3. **analytical-psychology.json** — Jung (Persona, Shadow, Individuation)
4. **developmental-psychology.json** — Chess & Thomas, Kagan (Temperament)
5. **self-psychology.json** — Kohut (Self-object, Compensatory structures)
6. **psychoanalysis.json** — Freud (Defense mechanisms)

### Glossary Terms Needed

1. **real-self.json** — The organism's baseline emotional-somatic configuration
2. **role-mask.json** — Protective identity built to navigate unsafe conditions

## Cross-Linking Strategy

### From .com F2 → .org

Add orgLink to each theory row in the cross-theoretical tables.

### From .org Theory → .com F2

In each theory JSON, add connection:

```json
{
  "connections": [
    {
      "type": "extends",
      "targetUrl": "https://teg-blue.com/mapping-system/following-nervous-system/f2",
      "label": "Applied in Framework 2"
    }
  ]
}
```

---

*Created: 2026-02-12*
