# Hypermedia-project-part-1-CV-BruPostigo
Hypermedia project that consist on creating a CV that's a web

Project Analysis: Information Architecture

The website employs a simple, linear, single-page scrolling structure, which is ideal for a resume or personal portfolio where the user's primary goal is rapid consumption of information. The content is divided into four main chronological and semantic blocks, each filling the viewport (100vh) to provide focus.

Header/Hero Section: This is the initial impression. Instead of static content, it immediately presents a prominent navigation bar. This architecture provides the user with an instant, high-level map of the entire page and allows them to jump directly to the most relevant section (e.g., Work Experience) without scrolling. This design choice prioritizes user control and efficiency.

About Me (dark-bg): This is the discovery section, pairing a personal photo with a brief introduction. The two-column layout visually balances the soft (personal statement) and the hard (image identity) information.

Work Experience (primary-bg): This block contains the core professional data. By isolating this content with a striking primary color (#8b0000), it signals to the user that this is the most critical data set. The content is structured with clear, digestible blocks (job-entry), ensuring quick scannability.

Contact (dark-bg): The final step in the funnel. This section is purely functional, using large, distinct Font Awesome icons to provide immediate, actionable links (Email, Instagram, Phone). By placing this section at the bottom, the architecture follows the natural progression of a successful user journey: Discovery $\rightarrow$ Vetting $\rightarrow$ Action.

This vertical, sectional layout guarantees the target user (Maria, the recruiter) can find any piece of information with minimal effort, eliminating the potential confusion of subpages or complex hierarchies. The architecture ensures that key information is segmented clearly for maximum cognitive processing efficiency.

Project Analysis: Visual Design

The visual design is built on a high-contrast, bold, and modern aesthetic, primarily drawing inspiration from a "dark theme with strong accents" philosophy.

Color Palette: The primary palette is defined by three main variables:

--color-dark (#2c2c2c): Used as the main background, providing a sophisticated, low-glare reading environment.

--color-primary (#8b0000, a deep maroon/red): Used to isolate and highlight the most important professional content (Work Experience). This color choice conveys strength and passion.

--color-accent (#e74c3c, a bright red/orange): Used for headings (<h2>), icons, and button hover states. It acts as the visual anchor, drawing the user's eye to interactive elements and structural titles.

Contrast and Readability: The text is white (--color-light) against the dark and primary backgrounds, ensuring AAA accessibility contrast and excellent readability, which is crucial for a time-constrained user like the Proactive Recruiter.

Typography: Two Google Fonts are used to create a clear visual hierarchy:

Montserrat (--font-header): A geometric sans-serif used for all major headings and navigation links. Its bold, clean lines convey modernity and professionalism.

Roboto (--font-main): Used for body text, providing high readability and a neutral foundation for long-form content.

Layout and Responsiveness: The design enforces a fixed maximum width for content containers (1100px) and uses padding to keep content centered. Crucially, the full-screen height for each section (height: 100vh;) forces the user to interact with the site section-by-section, mimicking a slide presentation and ensuring focus. The navigation links are bold, rounded, and use a clear, professional hover effect (color change and slight lift) to reinforce interactivity. The use of large Font Awesome icons in the contact section further reinforces the site's modern, accessible, and functional visual identity.


LINKS:

Figma project: https://www.figma.com/design/J6VnldC2VJNKAFbCXUGBzj/cv-bru-postigo?node-id=0-1&t=itpEpaZ3IOl5iEff-1

CV: https://brupostigo.github.io/Hypermedia-project-part-1-CV-BruPostigo/
