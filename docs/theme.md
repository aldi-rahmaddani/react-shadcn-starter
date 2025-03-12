# 🎨 Theme configuration guide

Follow this guide to change your project's theme and color scheme.

## 📂 Where is the theme configuration file?

1. The configuration file is located in @/assets/css/index.css
2. Change the value of the css variable to change the color scheme
3. Use the oklch() color format for consistency

## 📄 Variables with the same value

### @root

| Color                     | Variable                                                                                     |
| :------------------------ | :------------------------------------------------------------------------------------------- |
| oklch(1 0 0)              | background, card, popover                                                                    |
| oklch(0.145 0 0)          | foreground, card-foreground, popover-foreground, sidebar-foreground                          |
| oklch(0.205 0 0)          | primary, secondary-foreground, accent-foreground, sidebar-primary, sidebar-accent-foreground |
| oklch(0.985 0 0)          | primary-foreground, sidebar, sidebar-primary-foreground                                      |
| oklch(0.97 0 0)           | secondary, muted, accent, sidebar-accent                                                     |
| oklch(0.556 0 0)          | muted-foreground                                                                             |
| oklch(0.577 0.245 27.325) | destructive, destructive-foreground                                                          |
| oklch(0.922 0 0)          | border, input, sidebar-border                                                                |
| oklch(0.708 0 0)          | ring, sidebar-ring                                                                           |
| oklch(0.708 0 0)          | ring, sidebar-ring                                                                           |

### @.dark

| Color                     | Variable                                                                                                                                                                     |
| :------------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| oklch(0.145 0 0)          | background, card, popover                                                                                                                                                    |
| oklch(0.985 0 0)          | foreground, card-foreground, popover-foreground, primary, secondary-foreground, accent-foreground, sidebar-foreground, sidebar-primary-foreground, sidebar-accent-foreground |
| oklch(0.205 0 0)          | primary-foreground, sidebar                                                                                                                                                  |
| oklch(0.269 0 0)          | secondary, muted, accent, border, input, sidebar-accent, sidebar-border                                                                                                      |
| oklch(0.708 0 0)          | muted-foreground                                                                                                                                                             |
| oklch(0.396 0.141 25.723) | destructive                                                                                                                                                                  |
| oklch(0.637 0.237 25.331) | destructive-foreground                                                                                                                                                       |
| oklch(0.439 0 0)          | ring, sidebar-ring                                                                                                                                                           |

## ⚙️ Other Config

- radius: 0.625rem;

## 📦 Customize component styles

Customizing the component style can be done by editing directly in the component file located in @components/ui/\*
