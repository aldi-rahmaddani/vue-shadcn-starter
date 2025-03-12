# 🎨 Theme configuration guide

Follow this guide to change your project's theme and color scheme.

## 📂 Where is the theme configuration file?

1. The configuration file is located in @/assets/css/index.css
2. Change the value of the css variable to change the color scheme
3. Use the hsl color format for consistency

## 📄 Variables with the same value

### @root

| Color             | Variable                                                                                   |
| :---------------- | :----------------------------------------------------------------------------------------- |
| 0 0% 100%         | background, card, popover                                                                  |
| 0 0% 3.9%         | foreground, card-foreground, popover-foreground, ring                                      |
| 0 0% 9%           | primary, secondary-foreground, accent-foreground                                           |
| 0 0% 98%          | primary-foreground, destructive-foreground, sidebar-background, sidebar-primary-foreground |
| 0 0% 89.8%        | border, input                                                                              |
| 240 5.3% 26.1%    | sidebar-foreground                                                                         |
| 240 5.9% 10%      | sidebar-primary, sidebar-accent-foreground                                                 |
| 240 4.8% 95.9%    | sidebar-accent                                                                             |
| 220 13% 91%       | sidebar-border                                                                             |
| 217.2 91.2% 59.8% | sidebar-ring                                                                               |

### @.dark

| Color             | Variable                                                                                                                  |
| :---------------- | :------------------------------------------------------------------------------------------------------------------------ |
| 0 0% 3.9%         | background, card, popover                                                                                                 |
| 0 0% 3.9%         | foreground, card-foreground, popover-foreground, primary, secondary-foreground, accent-foreground, destructive-foreground |
| 0 0% 9%           | primary-foreground                                                                                                        |
| 0 0% 14.9%        | secondary, muted, accent, border, input                                                                                   |
| 0 0% 63.9%        | mute-foreground                                                                                                           |
| 0 62.8% 30.6%     | destructive                                                                                                               |
| 0 0% 83.1%        | ring                                                                                                                      |
| 240 5.9% 10%      | sidebar-background                                                                                                        |
| 240 4.8% 95.9%    | sidebar-foreground, sidebar-accent-foreground                                                                             |
| 224.3 76.3% 48%   | sidebar-primary                                                                                                           |
| 0 0% 100%         | sidebar-primary-foreground                                                                                                |
| 240 3.7% 15.9%    | sidebar-accent, sidebar-border                                                                                            |
| 217.2 91.2% 59.8% | sidebar-ring                                                                                                              |

## ⚙️ Other Config

- radius: 0.5rem;

## 📦 Customize component styles

Customizing the component style can be done by editing directly in the component file located in @components/ui/\*
