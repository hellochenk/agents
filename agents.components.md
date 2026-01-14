# agents.md (component)

## Component intent
- here is some reusable business component
- It should remain stateless where possible

## Props rules
- Prefer explicit props over config objects
- Avoid boolean explosion

## Styling
- Follow existing className / variant pattern
- Do not introduce new styling systems

## Reuse rule
- If a new use case cannot be expressed via props,
  consider extracting a new component instead of bloating this one
