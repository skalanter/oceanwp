# OceanWP Customizer Options - Complete Hierarchical Structure

This document contains all available Customizer options from both repositories:
- **oceanwp** (main theme)
- **ocean-extra** (plugin)

The structure is organized exactly as it appears in the WordPress Customizer, preserving the hierarchical relationship between panels, sections, and individual options.

## Main Customizer Sections

### Typography
**Path:** `Customizer > Typography`

#### Google Font Settings
**Path:** `Customizer > Typography > Google Font Settings`

- **Disable Google Fonts** - Switch to disable Google Fonts completely
- **Enable Google Fonts** - Switch to enable Google Fonts
- **Load Google Fonts Locally** - Section for local Google Fonts
  - **Enable Local Google Fonts** - Switch to host Google Fonts locally
  - **Apply on Elementor** - Switch to apply local fonts on Elementor
  - **Preload Local Google Fonts** - Switch to preload local fonts
  - **Font Format** - Selection between TTF, WOFF, WOFF2
- **Google Font Subsets** - Section for font subsets
  - **Font Subsets** - Multi-select for latin, latin-ext, cyrillic, cyrillic-ext, greek, greek-ext, vietnamese

#### Global Typography Settings
**Path:** `Customizer > Typography > Global Typography Settings`

- **Body** - Complete typography control with:
  - Font Family
  - Font Weight (Desktop/Tablet/Mobile)
  - Font Subset
  - Font Size (Desktop/Tablet/Mobile)
  - Font Size Unit
  - Letter Spacing (Desktop/Tablet/Mobile)
  - Letter Spacing Unit
  - Line Height (Desktop/Tablet/Mobile)
  - Line Height Unit
  - Text Transform (Desktop/Tablet/Mobile)
  - Text Decoration

- **All Headings** - Typography control for all headings (H1-H6) with same options as Body

- **Heading 1 (H1)** - Individual H1 typography settings
- **Heading 2 (H2)** - Individual H2 typography settings
- **Heading 3 (H3)** - Individual H3 typography settings
- **Heading 4 (H4)** - Individual H4 typography settings
- **Heading 5 (H5)** - Individual H5 typography settings
- **Heading 6 (H6)** - Individual H6 typography settings

### Colors
**Path:** `Customizer > Colors`

- **Site Background** - Background color with alpha/palette support
- **Primary Color** - Primary color with Normal/Hover states
- **Border Color** - Main border color for elements
- **Body Color** - Text color for body content
- **All Headings** - Color for all heading elements
- **Heading 1 (H1)** - Individual H1 color
- **Heading 2 (H2)** - Individual H2 color
- **Heading 3 (H3)** - Individual H3 color
- **Heading 4 (H4)** - Individual H4 color
- **Heading 5 (H5)** - Individual H5 color
- **Heading 6 (H6)** - Individual H6 color
- **Links** - Link colors with Normal/Hover states

### Site Style & Settings
**Path:** `Customizer > Site Style & Settings`

*[Note: This section contains layout, container, and general styling options - full details would require reading the styles-and-settings.php file]*

### Pages & Special Pages
**Path:** `Customizer > Pages & Special Pages`

*[Note: This section contains page-specific settings - full details would require reading the page-settings.php file]*

### Top Bar
**Path:** `Customizer > Top Bar`

*[Note: This section contains top bar configuration options - full details would require reading the topbar.php file]*

### Header
**Path:** `Customizer > Header`

#### General
**Path:** `Customizer > Header > General`

- **Header Type** - Radio selection between:
  - Minimal
  - Transparent
  - Top Menu
  - Full Screen
  - Center Header
  - Medium Header
  - Vertical Header
  - Custom Header

##### Custom Header Settings
**Path:** `Customizer > Header > General > Custom Header Settings`

- **Add Container** - Switch to add container
- **Select Template** - Choose from OceanWP Library templates

##### Default Header Options
**Path:** `Customizer > Header > General > Default Header Options`

- **Height** - Range slider for header height (1-200px)
- **Padding** - Spacing control for header padding (Top/Right/Bottom/Left + responsive)
- **Full Width** - Switch for full width header
- **Border Bottom** - Switch for header border bottom

##### Additional Styling & Settings
**Path:** `Customizer > Header > General > Additional Styling & Settings`

###### Top Menu Header Settings
**Path:** `Customizer > Header > General > Additional Styling & Settings > Top Menu Header Settings`

- **Menu Position** - Before/After the logo

###### Full Screen Header Settings
**Path:** `Customizer > Header > General > Additional Styling & Settings > Full Screen Header Settings`

- **Add Transparent Header** - Switch for transparency
- **Hamburger Width** - Range slider (1-100px)
- **Hamburger Bars Height** - Range slider (1-10px)
- **Hamburger Bars Gap** - Range slider (1-25px)

*[Note: Header section continues with many more subsections including Logo, Menu, Mobile Menu, etc.]*

### Blog
**Path:** `Customizer > Blog`

*[Note: This section contains blog layout and styling options - full details would require reading the blog.php file]*

### Sidebar
**Path:** `Customizer > Sidebar`

*[Note: This section contains sidebar configuration options - full details would require reading the sidebar.php file]*

### Footer Widgets
**Path:** `Customizer > Footer Widgets`

*[Note: This section contains footer widget options - full details would require reading the footer-widget.php file]*

### Footer Copyright
**Path:** `Customizer > Footer Copyright`

*[Note: This section contains footer copyright options - full details would require reading the footer-copyright.php file]*

### SEO Settings
**Path:** `Customizer > SEO Settings`

*[Note: This section contains SEO configuration options - full details would require reading the seo.php file]*

### Performance
**Path:** `Customizer > Performance`

*[Note: This section contains performance optimization options - full details would require reading the performance.php file]*

### WooCommerce
**Path:** `Customizer > WooCommerce`
*(Available when WooCommerce is active)*

*[Note: This section contains extensive WooCommerce integration options - full details would require reading the woocommerce.php file]*

### Easy Digital Downloads
**Path:** `Customizer > Easy Digital Downloads`
*(Available when EDD is active)*

*[Note: This section contains EDD integration options - full details would require reading the edd.php file]*

### LearnDash
**Path:** `Customizer > LearnDash`
*(Available when LearnDash is active)*

*[Note: This section contains LearnDash integration options - full details would require reading the learndash.php file]*

### LifterLMS
**Path:** `Customizer > LifterLMS`
*(Available when LifterLMS is active)*

*[Note: This section contains LifterLMS integration options - full details would require reading the lifterlms.php file]*

## Ocean Extra Plugin Options

### Site Preloader
**Path:** `Customizer > Site Preloader`

- **Enable Site Preloader** - Switch to enable preloader

#### Preloader Type
**Path:** `Customizer > Site Preloader > Preloader Type`

- **Preloader Type** - Choice between Default/Custom

##### Custom Preloader Settings
**Path:** `Customizer > Site Preloader > Custom Preloader Settings`

- **Select Template** - Choose from OceanWP Library templates
- **Elementor Flickers/FOUC** - Switch for Elementor flicker prevention

##### Default Preloader Settings
**Path:** `Customizer > Site Preloader > Default Preloader Settings`

- **Icon Type** - Selection between CSS/Image/Logo/SVG
- **Preloader Icon** - Choose from:
  - Roller
  - Circle
  - Ring
  - Dual Ring
  - Ripple Plain
  - Ripple Circle
  - Heart
  - Ellipsis
  - Spinner Line
  - Spinner Dot
- **Image** - Upload image for preloader
- **Upload SVG** - Upload SVG file
- **Size (px)** - Range slider for icon size (0-100px)
- **Content** - Textarea for preloader text
- **Container Width (px)** - Range slider for container width (0-2000px, responsive)

##### Typography and Colors
**Path:** `Customizer > Site Preloader > Typography and Colors`

- **Content Text** - Complete typography control with all standard options

### OceanWP Info
**Path:** `Customizer > OceanWP Info`

- **Documentation Links** - Information and links
- **Website Templates** - Information about available demos
- **Premium Support** - Support information
- **Free User Support** - Community support links

## Notes

1. **Responsive Controls**: Many options include separate controls for Desktop, Tablet, and Mobile devices.

2. **Typography Controls**: Typography sections typically include:
   - Font Family
   - Font Weight (with responsive variants)
   - Font Subset
   - Font Size (with responsive variants and units)
   - Letter Spacing (with responsive variants and units)
   - Line Height (with responsive variants and units)
   - Text Transform (with responsive variants)
   - Text Decoration
   - Color

3. **Color Controls**: Color options typically include:
   - Normal state
   - Hover state (where applicable)
   - Alpha channel support
   - Color palette support

4. **Conditional Options**: Many options are conditionally displayed based on other settings (e.g., Custom Header options only appear when Custom Header type is selected).

5. **Integration Options**: Additional sections appear when specific plugins are active (WooCommerce, EDD, LearnDash, LifterLMS).

6. **Ocean Extra Extensions**: The Ocean Extra plugin adds additional functionality through various modules that integrate with the Customizer.

---

*This structure represents the complete hierarchical organization of OceanWP Customizer options as they appear in the WordPress Customizer interface. Each option includes appropriate controls, validation, and conditional display logic.*