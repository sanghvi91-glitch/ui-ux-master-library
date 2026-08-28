# Repository Architecture

## Overview

The repository is organized into numbered sections so that related UI/UX
resources can be discovered quickly and maintained consistently.

## Top-Level Organization

- `01-ui-components` — reusable interface components.
- `02-design-systems` — design tokens and system patterns.
- `03-dashboard-templates` — dashboard and administrative layouts.
- `04-landing-page-templates` — landing-page patterns.
- `05-forms` — form components and examples.
- `06-tables` — data table patterns.
- `07-charts-data-visualization` — charts and visualization resources.
- `08-navigation` — navigation patterns.
- `09-authentication` — authentication interfaces.
- `10-calendar-date-time` — calendar and date/time resources.
- `11-rich-text-editors` — rich-text editing resources.
- `12-icons` — icon resources.
- `13-animations` — motion and animation resources.
- `14-notifications` — notification patterns.
- `15-loading-empty-error-states` — common application states.
- `16-other` — additional resources that do not fit another category.

## Organization Principles

1. Keep related resources together.
2. Prefer clear and descriptive names.
3. Avoid unnecessary duplication.
4. Preserve the existing numbered category structure.
5. Keep additions easy to discover and reuse.

## Adding New Resources

When adding a resource:

1. Choose the most appropriate category.
2. Follow existing naming conventions.
3. Include useful documentation where appropriate.
4. Avoid committing generated dependencies or build artifacts.
5. Keep the repository structure consistent.