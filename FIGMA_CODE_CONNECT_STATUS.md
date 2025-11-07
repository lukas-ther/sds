# Figma Code Connect Status Report

**Generated:** November 6, 2025  
**Status:** ✅ Successfully Published

## Summary

- **Total Code Connect Files:** 30 `.figma.tsx` files
- **Unique Components Connected:** 74 components
- **Total Connections:** 99 connections (some components have multiple variants)
- **Last Published:** Successfully published to Figma

## Recent Fixes

### Button Component - Size Mapping Fixed ✅

The Button component now properly maps the `Medium` size variant:

**Fixed in:** `src/figma/primitives/Button.figma.tsx`

```typescript
size: figma.enum("Size", {
  Small: "small",
  Medium: "medium",  // ✅ Added
}),
```

**Button Connections:**
- Primary Button: `node-id=9762:426`
- Danger Button: `node-id=185-852`

## Connected Components

### Primitives (21/28 components)

✅ **Connected:**
- Accordion (2 components: Accordion, AccordionItem)
- Avatar (3 components: Avatar, AvatarBlock, AvatarGroup)
- Button (2 components: Button, ButtonDanger, ButtonGroup)
- Checkbox (2 components: CheckboxField, CheckboxGroup)
- Dialog (1 component)
- IconButton (1 component)
- Input (1 component: Input/InputField)
- Menu (6 components: Menu, MenuHeader, MenuHeading, MenuItem, MenuSeparator, MenuShortcut)
- Navigation (3 components: Navigation, NavigationButton, NavigationPill)
- Notification (1 component)
- Pagination (6 components: Pagination, PaginationGap, PaginationList, PaginationNext, PaginationPage, PaginationPrevious)
- Radio (2 components: RadioField, RadioGroup)
- Search (1 component)
- Select (1 component: Select/SelectField)
- Slider (1 component: SliderField)
- Switch (1 component: SwitchField)
- Tab (2 components: Tab, Tabs)
- Tag (3 components: Tag, TagToggle, TagToggleGroup)
- Text (20 components: Text, TextCode, TextContentHeading, TextContentTitle, TextEmphasis, TextHeading, TextLink, TextLinkList, TextList, TextListItem, TextPrice, TextSmall, TextStrong, TextSubheading, TextSubtitle, TextTitleHero, TextTitlePage)
- Textarea (1 component: Textarea/TextareaField)
- Tooltip (1 component)

❌ **Missing Connections:**
- Fieldset - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- Icon - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- Image - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- Link - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- ListBox - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- Logo - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists
- Table - Exported from `src/ui/primitives/index.ts` but no `.figma.tsx` file exists

### Compositions (6/6 components)

✅ **Connected:**
- Cards (6 components: Card, PricingCard, ProductInfoCard, ReviewCard, StatsCard, TestimonialCard)
- Footers (1 component: Footer)
- Forms (1 component: FormBox with 6 variants)
- Headers (2 components: Header, HeaderAuth)
- Heroes (1 component: Hero with 5 variants)
- Panels (1 component: Panel with 4 variants)

❌ **Missing Connections:**
- None - All composition exports have Figma connections

### Additional Sections

✅ **Connected:**
- Section component with 10 different variants for card grids and page layouts

## Connection Details by Node ID

All connections point to the Figma file: `https://figma.com/design/DkDhtPbv3hB7Fg0ZEXdCaY`

### Key Node IDs
- Button (Primary): `9762:426`
- Button (Danger): `185-852`
- ButtonGroup: `2072-9432`
- Dialog: `9762-696`, `192-31534`
- Input: `2136-2263`
- Select: `2136-2336`
- Textarea: `9762-3088`

## Recommendations

### 1. Missing Component Connections

If the following components exist in your Figma design system, create corresponding `.figma.tsx` files:

- `src/figma/primitives/Fieldset.figma.tsx`
- `src/figma/primitives/Icon.figma.tsx`
- `src/figma/primitives/Image.figma.tsx`
- `src/figma/primitives/Link.figma.tsx`
- `src/figma/primitives/ListBox.figma.tsx`
- `src/figma/primitives/Logo.figma.tsx`
- `src/figma/primitives/Table.figma.tsx`

### 2. Verify Node IDs in Figma

If a component doesn't show the Code Connect connection in Figma:
1. Right-click the component in Figma
2. Select "Copy link"
3. Verify the `node-id` parameter matches the value in `figma.config.json`

### 3. Publishing Workflow

To publish Code Connect updates:

```bash
# Parse connections to validate
npx figma connect parse --config figma.config.json

# Publish to Figma
npx figma connect publish --config figma.config.json
```

## Configuration Files

- **Config:** `figma.config.json`
- **Connection Files:** `src/figma/**/*.figma.tsx` (30 files)
- **Component Source:** `src/ui/**/*` (as configured in importPaths)

## Notes

- Icon components are excluded from Code Connect via `exclude: ["src/figma/icons/*"]` in config
- Import paths are aliased for cleaner imports (e.g., `from "primitives"`)
- GitHub source links point to: `https://github.com/lukas-ther/sds`

