# Data Template

This document defines the standard format for all linguistic data in the Tarifit-Dialects repository.

---

## Vocabulary Entry

Each vocabulary entry should include the following fields:

| Field | Required | Description |
|-------|:--------:|-------------|
| ID | ✅ | Unique identifier |
| Tarifit | ✅ | Word in Tarifit (Latin script) |
| Arabic | ✅ | Arabic translation |
| English | ✅ | English translation |
| Dialect | ✅ | Dialect group |
| Part of Speech | ✅ | Noun, Verb, Adjective... |
| Category | ✅ | Food, Nature, Family... |
| Example | ⭕ | Example sentence |
| IPA | ⭕ | Pronunciation (optional) |
| Notes | ⭕ | Additional information |

---

## Example

| ID | Tarifit | Arabic | English | Dialect | POS | Category | Example |
|----|----------|---------|----------|----------|-----|----------|----------|
| 000001 | aman | ماء | water | Central Rif | Noun | Nature | Aman d azedgan. |
| 000002 | tafucht | شمس | sun | Central Rif | Noun | Nature | Tafucht tfeɣ. |

---

## Sentence Entry

Each sentence should include:

| Field | Required |
|-------|:--------:|
| ID | ✅ |
| Tarifit | ✅ |
| Arabic | ✅ |
| English | ✅ |
| Dialect | ✅ |
| Topic | ⭕ |
| Notes | ⭕ |

---

## Categories

Suggested categories:

- Nature
- Family
- Food
- Animals
- Body
- Colors
- Numbers
- Clothing
- Education
- Health
- Transportation
- Technology
- Culture
- Religion
- Daily Life
- Agriculture
- Weather
- Emotions
- Work
- Geography

---

## Naming Rules

- Use lowercase for Latin words.
- Use one standard spelling for each word.
- Avoid duplicate entries.
- Follow the orthography guide.
