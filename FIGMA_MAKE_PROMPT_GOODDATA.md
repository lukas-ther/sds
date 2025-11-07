# Figma Make Prompt: GoodData Getting Started Page

## Design Overview
Create a modern, dark-themed "Getting Started" onboarding page for GoodData's AI data intelligence platform. The page should feature tutorial cards organized in two sections, with a clean card-based layout.

## Page Structure

### Background
- Dark background (near black, #1a1a1a or similar)
- Full-page modal/overlay appearance
- Centered content with maximum width container

### Main Header Section
**Section Title:** "Getting Started"  
**Subtitle:** "Learn the basics with starter tutorials from the GoodData team"

- Use a graduation cap icon (🎓) or similar educational icon
- White text for title (large heading)
- Gray text for subtitle (smaller, muted)
- Top padding: 48px

---

## Section 1: Getting Started (4 Cards)

Display 4 horizontally arranged cards in a responsive grid (4 columns on desktop, 2 on tablet, 1 on mobile).

### Card Design Specifications
- Card style: Subtle stroke/border variant (1px border, rgba(255,255,255,0.1))
- Border radius: 12px
- Padding: 24px (use design token: padding-600)
- Background: Slightly lighter than page background (rgba(255,255,255,0.03))
- Hover state: Subtle elevation/glow effect

### Card Content Structure
Each card contains:
1. **Image/Asset Area** (top)
   - Aspect ratio: 16:9
   - Height: ~180px
   - Gradient overlay with blur effect
   - Text overlay centered: Card title in white
   - Background: Subtle gradient (blue/purple/orange tones)

2. **Card Title** (below image)
   - Font: Medium weight, 18px
   - Color: White
   - Margin top: 16px

3. **Description Text**
   - Font: Regular weight, 14px
   - Color: Gray (#a0a0a0)
   - Margin top: 8px

4. **Duration Badge** (at bottom)
   - Clock icon + text
   - Font: 13px
   - Color: Muted gray (#888)
   - Margin top: 12px

### Card 1: Intro to AI Agents
- **Image overlay text:** "Intro to AI Agents"
- **Image background:** Blue-purple gradient with abstract data visualization blur
- **Title:** "Intro to GoodData AI Agents"
- **Description:** "Learn how to build intelligent agents that act on data"
- **Duration:** "⏱ 3m watch"

### Card 2: Intro to Analytics Lake
- **Image overlay text:** "Analytics Lake Intro"
- **Image background:** Teal-blue gradient with geometric patterns blur
- **Title:** "Intro to the Analytics Lake"
- **Description:** "Discover the composable data service layer"
- **Duration:** "⏱ 5m watch"

### Card 3: Intro to Embedded Analytics
- **Image overlay text:** "Embedded Analytics"
- **Image background:** Purple-pink gradient with dashboard elements blur
- **Title:** "Intro to Embedded Analytics"
- **Description:** "Integrate analytics directly into your applications"
- **Duration:** "⏱ 4m watch"

### Card 4: Intro to Business Intelligence
- **Image overlay text:** "Business Intelligence"
- **Image background:** Orange-amber gradient with chart visualization blur
- **Title:** "Intro to Business Intelligence"
- **Description:** "Explore AI-enabled analytics capabilities"
- **Duration:** "⏱ 6m watch"

**Spacing:** Gap between cards: 24px (use design token: gap-600)

---

## Section 2: Project Tutorials (3 Cards)

**Section Title:** "Project Tutorials"  
**Subtitle:** "See what's possible through guided projects"

- Same styling as Section 1 header
- Use a layers/stack icon (📚) or project icon
- Top margin: 64px from Section 1

Display 3 horizontally arranged cards with the same design specifications as Section 1.

### Card 1: AI Assistant Workflow
- **Image overlay text:** "AI Assistant Flow"
- **Image background:** Green-teal gradient with chat bubbles blur
- **Title:** "AI Assistant Workflow"
- **Description:** "Build conversational analytics with AI assistants"
- **Duration:** "⏱ 7m watch"

### Card 2: Data Visualization Flow
- **Image overlay text:** "Data Visualization"
- **Image background:** Blue-indigo gradient with dashboard mockup blur
- **Title:** "Data Visualization Flow"
- **Description:** "Create self-service dashboards and visualizations"
- **Duration:** "⏱ 8m watch"

### Card 3: Headless BI Workflow
- **Image overlay text:** "Headless BI Setup"
- **Image background:** Purple-violet gradient with API/code elements blur
- **Title:** "Headless BI Workflow"
- **Description:** "Implement the open semantic layer integration"
- **Duration:** "⏱ 6m watch"

**Spacing:** Gap between cards: 24px (use design token: gap-600)

---

## Navigation Footer

**Layout:** Horizontal flex container, space-between alignment
- Top margin: 48px from Section 2
- Bottom margin: 32px

### Back Button (Left)
- Style: Secondary/Ghost button
- Text: "Back"
- Color: Gray text (#888)
- No background, just text
- Font size: 15px

### Start Building Button (Right)
- Style: Primary button
- Text: "Start Building"
- Background: Brand gradient or solid color (e.g., #0066ff or purple-blue gradient)
- Text color: White
- Padding: 12px 32px
- Border radius: 8px
- Font weight: Medium
- Font size: 15px
- Hover: Slightly brighter/elevated

---

## Help Section (Bottom)

**Layout:** Centered text with button on right
- Background: Subtle border-top (1px, rgba(255,255,255,0.08))
- Padding: 24px 0
- Margin top: 32px

### Text (Left side)
- **Title:** "Not sure where to start?"
- **Subtitle:** "Get in touch and we'll build you a custom workflow to get you going."
- Font size: 14px title, 13px subtitle
- Color: Gray (#888)

### Schedule Button (Right side)
- Text: "Schedule a call →"
- Style: Text button with arrow
- Color: Brand blue (#0066ff)
- Font size: 14px
- No background, just colored text with hover underline

---

## Design Tokens to Use

### Spacing
- `gap-600`: 24px (card gaps)
- `gap-400`: 16px (internal card spacing)
- `gap-200`: 8px (small spacing)
- `padding-600`: 24px (card padding)
- `padding-800`: 32px (section padding)

### Colors (Dark Theme)
- Background: #1a1a1a
- Card background: rgba(255, 255, 255, 0.03)
- Border: rgba(255, 255, 255, 0.1)
- Text primary: #ffffff
- Text secondary: #a0a0a0
- Text muted: #888888
- Brand primary: #0066ff (or GoodData brand color)
- Accent gradients: Blue-purple, teal, orange, pink variants

### Typography
- Heading large: 28px, weight 600
- Heading medium: 18px, weight 500
- Body: 14-15px, weight 400
- Small: 13px, weight 400

### Effects
- Card border radius: 12px
- Button border radius: 8px
- Hover glow: 0 4px 20px rgba(0, 102, 255, 0.15)
- Card elevation: 0 2px 8px rgba(0, 0, 0, 0.3)

---

## Responsive Behavior

### Desktop (>1024px)
- Section 1: 4 columns
- Section 2: 3 columns
- Container max-width: 1200px
- All cards equal width

### Tablet (768px - 1024px)
- Section 1: 2 columns (2 rows of 2)
- Section 2: 2 columns (1 card spans or 3rd card below)
- Container max-width: 768px

### Mobile (<768px)
- All sections: 1 column
- Cards stack vertically
- Full width with side margins (20px)
- Navigation buttons stack vertically

---

## Component Library References

Use these design system components from the SDS library:

- **Card**: Stroke variant with vertical direction
- **Grid**: Responsive column layout with gap-600
- **TextHeading**: For section titles
- **Text**: For descriptions and subtitles
- **TextSmall**: For duration badges
- **Button**: Primary variant for "Start Building", ghost for "Back"
- **Flex**: For layout containers and spacing

---

## Additional Notes

1. All images should have a subtle gradient overlay to ensure text readability
2. Cards should have a subtle hover state (slight scale transform or glow)
3. The entire layout should feel premium and modern, matching GoodData's enterprise positioning
4. Icons should be consistent - use simple line icons or the SDS icon library
5. Maintain consistent visual hierarchy with proper spacing and typography scales
6. Ensure sufficient contrast ratios for accessibility (WCAG AA minimum)

---

## Figma Make Instructions

When creating this design in Figma Make:

1. Start with a dark frame (1440 x 1024 or auto-layout)
2. Create the two section headers with their icons and text
3. Build one card component first with all the elements
4. Duplicate and modify the card for each variation
5. Use auto-layout for the grid sections to enable responsive behavior
6. Group cards into section containers
7. Add the footer navigation with proper spacing
8. Include the help section at the bottom
9. Apply consistent spacing using 8px grid system
10. Test hover states and ensure all text is readable

This design represents a modern onboarding experience for GoodData's AI data intelligence platform, helping users get started with key platform features through guided tutorials.



