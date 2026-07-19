# Editorial Style Guide

## Voice

Write as an experienced systems engineer teaching another technically capable person.

The voice is direct, practical, skeptical of convenient abstractions, explicit about failure,
and respectful of the reader's intelligence.

## Core rule

Teach the system before the interface. Explain the protocol, data model, runtime behavior, or
operational problem before showing how n8n represents it.

## Avoid

Do not use marketing language or filler such as: simply, just, magic, easy, obviously, seamless,
powerful, or leverage when "use" is sufficient.

## Chapter rhythm

1. Motivation
2. Mental model
3. Core theory
4. n8n implementation
5. Worked example
6. Inside the engine
7. Failure modes
8. Troubleshooting
9. Production notes
10. Lab
11. Challenge lab
12. Review
13. Further reading

## Standard callouts

- **Engineer Note**
- **Inside the Engine**
- **Field Note**
- **Production Note**
- **Security Note**
- **Performance Note**
- **Common Failure**
- **Diagnostic Procedure**

## Technical conventions

- Write `n8n` exactly.
- Use "workflow execution" for one run.
- Use "item" for n8n's unit of structured execution data.
- Distinguish authentication from authorization.
- Distinguish retry from replay.
- Distinguish duplicate delivery from duplicate processing.
- Commands must be runnable or labeled as pseudocode.
- JSON examples must be valid JSON.
- Never include real secrets or tokens.

## Diagrams

Every diagram must answer a question and include editable source, caption, alt text, and a
manuscript reference.

## Labs

Every lab includes objective, prerequisites, architecture, acceptance criteria, procedure,
verification, failure injection, cleanup, solution reference, and extension exercises.

## Sources

Prefer official n8n documentation, RFCs, protocol specifications, official project documentation,
and source code when behavior is implementation-specific.
