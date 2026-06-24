# Prompt Comparison

## Objective

The objective of this exercise was to analyze and optimize a prompt with regard to efficiency, clarity, sustainability and token consumption.

---

## Original Prompt

Kannst du mir bitte detaillierte Informationen zu dem Produkt SmartHome Air Quality Sensor geben? Ich möchte wissen, welche Funktionen es hat, für wen es geeignet ist und was es besonders macht. Falls es Alternativen gibt, kannst du diese auch nennen. Außerdem interessiert mich der Preis und ob es aktuell Rabatte gibt.

### Identified Weaknesses

- Multiple questions are combined into a single request.
- No limitation on answer length.
- No predefined response structure.
- Broad wording encourages long responses.
- Price and discount information may not be available and can increase hallucination risk.
- Higher token consumption due to unrestricted output.

---

## Optimized Prompt

Beschreibe den SmartHome Air Quality Sensor in maximal 150 Wörtern.

Gib die Antwort in folgender Struktur aus:

1. Hauptfunktionen
2. Zielgruppe
3. Besondere Merkmale

Falls keine verlässlichen Preisinformationen verfügbar sind, weise darauf hin.

### Implemented Improvements

- Defined maximum answer length.
- Introduced a fixed response structure.
- Removed unnecessary wording.
- Focused on relevant information.
- Reduced risk of unsupported price information.
- Improved readability and consistency.

---

## Comparison of Results

| Criterion | Original Prompt | Optimized Prompt |
|------------|------------|------------|
| Clarity | Medium | High |
| Structure | Unstructured | Clearly structured |
| Response Length | Long | Compact |
| Token Consumption | Higher | Lower |
| Hallucination Risk | Higher | Lower |
| Readability | Medium | High |

---

## Conclusion

The optimized prompt produced a shorter, more focused and better structured response. By limiting the answer length and defining a clear output structure, the response became more efficient and easier to read.

The optimization demonstrates how sustainable prompting can reduce token consumption and computational effort while maintaining answer quality.