# OceanWP Settings (Metabox) - Complete Hierarchical Structure

This document contains all available OceanWP Settings (also known as Metabox Settings) options from both repositories:
- **oceanwp** (main theme)
- **ocean-extra** (plugin)

The OceanWP Settings are page/post-specific options that allow you to customize individual pages independently from global Customizer settings.

## OceanWP Settings Sections

### General/Main
**Path:** `OceanWP Settings > General` (New Settings) or `OceanWP Settings > Main` (Classic Settings)

- **Content Layout** - Select custom layout for the page
  - Default
  - Right Sidebar
  - Left Sidebar
  - Full Width
  - 100% Full Width
  - Both Sidebars
- **Both Sidebars: Style** - Select both sidebars style
  - Default
  - Sidebar / Sidebar / Content
  - Sidebar / Content / Sidebar
  - Content / Sidebar / Sidebar
- **Both Sidebars: Content Width (%)** - Enter custom content width percentage
- **Both Sidebars: Sidebars Width (%)** - Enter custom sidebars width percentage
- **Sidebar** - Select custom sidebar content
- **Second Sidebar** - Select custom second sidebar content
- **Paddings** - Enable or disable top and bottom padding
  - Enable
  - Disable
- **Custom Body Class** - Add custom CSS classes to body

### Shortcodes
**Path:** `OceanWP Settings > Shortcodes`

- **Shortcode Before Top Bar** - Add shortcode to display before top bar
- **Shortcode After Top Bar** - Add shortcode to display after top bar
- **Shortcode Before Header** - Add shortcode to display before header
- **Shortcode After Header** - Add shortcode to display after header
- **Shortcode Before Title** - Add shortcode to display before page title
- **Shortcode After Title** - Add shortcode to display after page title
- **Shortcode Before Footer Widgets** - Add shortcode to display before footer widgets
- **Shortcode After Footer Widgets** - Add shortcode to display after footer widgets
- **Shortcode Before Footer Bottom** - Add shortcode to display before footer bottom
- **Shortcode After Footer Bottom** - Add shortcode to display after footer bottom

### Header
**Path:** `OceanWP Settings > Header`

- **Display Top Bar** - Enable or disable top bar
  - Default
  - Enable
  - Disable
- **Display Header** - Enable or disable header
  - Default
  - Enable
  - Disable
- **Header Style** - Choose header style for this page
  - Default
  - Minimal
  - Transparent
  - Top Menu
  - Full Screen
  - Center
  - Medium
  - Vertical
  - Custom Header
- **Left Menu** - Choose left menu for center header style
- **Select Template** - Choose custom header template from My Library

### Logo
**Path:** `OceanWP Settings > Logo`

- **Logo** - Select custom logo for this page/post
- **Retina Logo** - Select custom retina logo for this page/post
- **Max Width (px)** - Enter custom max width for logo
- **Tablet: Max Width (px)** - Enter custom max width for tablet view
- **Mobile: Max Width (px)** - Enter custom max width for mobile view
- **Max Height (px)** - Enter custom max height for logo
- **Tablet: Max Height (px)** - Enter custom max height for tablet view
- **Mobile: Max Height (px)** - Enter custom max height for mobile view

### Menu
**Path:** `OceanWP Settings > Menu`

- **Main Navigation Menu** - Choose custom menu for this page/post
- **Typography** - Typography settings for menu
  - Font Family
  - Font Size
  - Font Weight
  - Font Style
  - Text Transform
  - Line Height
  - Letter Spacing
- **Link Color** - Select menu link color
- **Link Color: Hover** - Select menu link hover color
- **Link Color: Current Menu Item** - Select current menu item color
- **Link Background** - Select menu link background color
- **Link Background: Hover** - Select menu link hover background color
- **Link Background: Current Menu Item** - Select current menu item background color
- **Simple Social: Background Color** - Select social links background color
- **Simple Social: Hover Background Color** - Select social links hover background color
- **Simple Social: Color** - Select social links color
- **Simple Social: Hover Color** - Select social links hover color

### Title
**Path:** `OceanWP Settings > Title`

- **Display Page Title** - Enable or disable page title area
  - Default
  - Enable
  - Disable
- **Display Heading** - Enable or disable page title heading
  - Default
  - Enable
  - Disable
- **Custom Title** - Enter custom title text
- **Subheading** - Enter custom subheading text
- **Title Style** - Select custom title style
  - Default
  - Default Style
  - Centered
  - Centered Minimal
  - Background Image
  - Solid Color and White Text
- **Title: Background Color** - Select title background color
- **Title: Background Image** - Select custom background image
- **Position** - Select background image position
  - Default
  - Top Left
  - Top Center
  - Top Right
  - Center Left
  - Center Center
  - Center Right
  - Bottom Left
  - Bottom Center
  - Bottom Right
- **Attachment** - Select background image attachment
  - Default
  - Scroll
  - Fixed
- **Repeat** - Select background image repeat
  - Default
  - No-repeat
  - Repeat
  - Repeat-x
  - Repeat-y
- **Size** - Select background image size
  - Default
  - Auto
  - Cover
  - Contain
- **Title: Background Height** - Enter custom height for title background
- **Title: Background Overlay Opacity** - Enter overlay opacity (0.1 to 1)
- **Title: Background Overlay Color** - Select overlay color

### Breadcrumbs
**Path:** `OceanWP Settings > Breadcrumbs`

- **Display Breadcrumbs** - Enable or disable breadcrumbs
  - Default
  - Enable
  - Disable
- **Color** - Select breadcrumbs color
- **Separator Color** - Select breadcrumbs separator color
- **Links Color** - Select breadcrumbs links color
- **Links Color: Hover** - Select breadcrumbs links hover color

### Footer
**Path:** `OceanWP Settings > Footer`

- **Display Footer Widgets Area** - Enable or disable footer widgets
  - Default
  - Enable
  - Disable
- **Display Copyright Area** - Enable or disable footer bottom/copyright area
  - Default
  - Enable
  - Disable
- **Select Template** - Choose custom footer template from My Library

### Post Settings (For Posts Only)
**Path:** `OceanWP Settings > Post` (Only available for blog posts)

- **Post Style** - Select post layout style
- **Content** - Control post content display
- **Elements** - Control post elements display
- **Media** - Control post media display
- **Social Share** - Control social sharing options
- **Author Box** - Control author box display
- **Next/Prev** - Control next/previous post navigation

## Notes

1. **Availability**: OceanWP Settings require the free Ocean Extra plugin to be installed and active.

2. **Access**: OceanWP Settings are accessed when editing individual pages, posts, or products in WordPress.

3. **New vs Classic Interface**: 
   - **New Settings** (OceanWP 3.5.0+ with Ocean Extra 2.2.0+): Located in Gutenberg sidebar
   - **Classic Settings**: Located below content area in post editor

4. **Post Types**: By default, OceanWP Settings are available for:
   - Pages
   - Posts
   - Products (WooCommerce)
   - OceanWP Library
   - Elementor Library
   - Additional post types based on installed plugins

5. **Extensions**: Additional settings sections may appear based on installed Ocean extensions (both free and premium).

6. **Override Behavior**: All OceanWP Settings override the global Customizer settings for the specific page/post where they are applied.