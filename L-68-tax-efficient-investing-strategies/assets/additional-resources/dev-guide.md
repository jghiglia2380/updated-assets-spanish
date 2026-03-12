# Developer Guide - L-68: Tax Efficient Investing Strategies

## Purpose
This folder contains curated external resource links for the Spanish version of this chapter. These resources will be displayed to Spanish-speaking users on the website.

## Files
- `content.md` - Spanish user-facing content with translated titles, descriptions, and URLs
- `dev-guide.md` - This file (English documentation for dev team)

## Content Structure
The Spanish content.md contains:
- **Resource titles** - In Spanish (user-facing)
- **Resource types** - Guía, Herramienta, Calculadora, Artículo, Video
- **Descriptions** - In Spanish (user-facing)
- **URLs** - Mix of Spanish-language US government sites and English educational sites

## Common Spanish-Language URL Patterns
- `irs.gov/es` - IRS Spanish portal
- `consumerfinance.gov/es` - CFPB Spanish portal
- `consumidor.ftc.gov` - FTC consumer Spanish
- `studentaid.gov/es` - Federal Student Aid Spanish
- `cuidadodesalud.gov/es` - Healthcare.gov Spanish
- `ssa.gov/espanol` - Social Security Spanish
- `usa.gov/es` - USA.gov Spanish
- `robodeidentidad.gov` - Identity theft Spanish
- `es.khanacademy.org` - Khan Academy Spanish

## Integration Notes
1. Parse content.md and render as HTML
2. Each resource should display:
   - Clickable title (links to URL)
   - Type badge (e.g., "Guía", "Calculadora")
   - Description paragraph
3. Group resources by section headers
4. All external links should open in new tabs (`target="_blank"`)
5. Consider adding `rel="noopener noreferrer"` for security

## Component Structure Suggestion
```jsx
<ResourceSection title="Section Name">
  <ResourceCard
    title="Resource Title"
    type="Guía"
    url="https://..."
    description="Description text..."
  />
</ResourceSection>
```
