\# Component Guidelines



Guidelines for building consistent, reusable, and accessible UI components.



\## Naming



Use clear names based on component responsibility rather than implementation details.



Good:



\- Button

\- Dialog

\- Dropdown

\- DataTable

\- Navigation



Avoid names that describe temporary implementation details.



\## Variants



Components should expose intentional variants.



Examples:



\- Primary

\- Secondary

\- Destructive

\- Ghost

\- Outline



Avoid creating variants for minor visual differences that should instead be handled by design tokens.



\## States



Interactive components should define appropriate states:



\- Default

\- Hover

\- Focus

\- Active

\- Disabled

\- Loading

\- Error

\- Selected



\## Accessibility



Components should:



\- Support keyboard interaction.

\- Provide visible focus indication.

\- Use appropriate semantic HTML.

\- Expose accessible names and descriptions where required.

\- Maintain sufficient color contrast.

\- Respect reduced-motion preferences.

\- Avoid relying on color alone to communicate meaning.



\## Responsive Behavior



Components should define behavior for:



\- Small screens

\- Medium screens

\- Large screens



Avoid unnecessary breakpoint-specific duplication.



\## Composition



Prefer composable components over large components with many unrelated responsibilities.



\## Content



Components should handle realistic content lengths and avoid assumptions about fixed text widths.



\## Interaction



Interactions should be:



\- Predictable

\- Reversible where appropriate

\- Consistent with surrounding components

\- Clear about success, failure, and loading states



\## Visual Consistency



Use shared design tokens for:



\- Color

\- Typography

\- Spacing

\- Radius

\- Borders

\- Elevation

\- Motion



Avoid arbitrary one-off values.



\## Review Checklist



Before adding a reusable component, verify:



\- \[ ] Naming is clear.

\- \[ ] Variants are intentional.

\- \[ ] All important interaction states exist.

\- \[ ] Keyboard behavior works.

\- \[ ] Focus state is visible.

\- \[ ] Accessibility semantics are correct.

\- \[ ] Responsive behavior is defined.

\- \[ ] Shared tokens are used where appropriate.

\- \[ ] Component responsibility is appropriately scoped.

