# Evidence-grounded product case studies

A polished case study is not useful if the evidence underneath it is ambiguous. This is the lightweight method I use to make a narrative compelling without turning assumptions or repeated drafts into facts.

## 1. Separate evidence classes

| Class | Meaning | Publication rule |
| --- | --- | --- |
| Confirmed fact | Supported by a reliable source or direct artifact | Publish after confidentiality review |
| Derived calculation | Reproducible arithmetic based on confirmed inputs | Publish with the method and units |
| Assumption | Necessary for analysis but not yet validated | Label explicitly |
| Directional outcome | Signal is credible but definition or baseline is incomplete | Describe direction; withhold false precision |
| Product judgment | A decision, prioritization, or trade-off | Explain the rationale and alternatives |

## 2. Build a metric record

Before placing a number in a headline, record:

1. The exact definition, unit, and baseline.
2. The population and measurement window.
3. Whether the value was measured, estimated, projected, or directional.
4. Personal contribution versus the broader team's result.
5. Whether the organization permits even a rounded public version.

If two sources disagree, the number leaves the public draft until the discrepancy is resolved.

## 3. Tell the decision story

Use a consistent narrative:

```text
Context -> evidence -> product question -> options -> decision
        -> rollout -> observed outcome -> remaining uncertainty
```

This structure makes product judgment visible. A feature list does not.

## 4. Add one decision artifact

Choose the artifact that makes the central decision easier to inspect:

- A before/after workflow for process redesign.
- A state machine for lifecycle products.
- A prioritization matrix for roadmap trade-offs.
- A metric tree for outcome strategy.
- A system diagram for platform boundaries.
- An experiment table for a proof of concept.

Recreate the artifact with fictional or generalized inputs. Do not publish internal screenshots merely because names have been blurred.

## 5. Run the confidentiality test

Remove customer names, employee details, internal identifiers, screenshots, message text, account configuration, credentials, source documents, and implementation details that create security or ownership risk. When the public value comes from the method, publish the method and keep the underlying data private.

## Final review questions

- Can a reader distinguish what shipped from what was proposed?
- Are projected opportunities clearly separated from realized outcomes?
- Does every metric have one stable definition?
- Is personal ownership clear without claiming the whole team's work?
- Can the case stand on its reasoning without confidential detail?
