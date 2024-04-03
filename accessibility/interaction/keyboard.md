---
layout: page
title: Make your visualizations keyboard-accessible
parent: Interaction
grand_parent: Accessibility
nav_order: 21
---

# Make interactive visualizations keyboard-accessible.

Many users who encounter an interactive data visualization will navigate it using a mouse, but many users will use a keyboard or other assistive technologies instead of a mouse. When designing an interactive data visualization, we must ensure that they are keyboard accessible. 

Test your data visualization or dashboard with a keyboard to make sure it behaves as expected. The table below from WebAIM’s article Keyboard Accessibility outlines the most common online interactions and the corresponding keystrokes. Use these keystrokes to test your visualization with a keyboard.

| Interaction                     | Keystrokes                                                                           | 
| ------------------------------- | ------------------------------------------------------------------------------------ | 
| Navigate to interactive elements | {::nomarkdown}<ul><li><code>Tab</code> - navigate forward</li><li><code>Shift</code> + <code>Tab</code> - navigate backward</li></ul>{:/}|
| Link | {::nomarkdown}<ul><li><code>Enter</code> - activate the link</li></ul>{:/}|
| Button | {::nomarkdown}<ul><li><code>Enter</code> or <code>Spacebar</code> - activate the button</li></ul>{:/}|
| Checkbox | {::nomarkdown}<ul><li><code>Spacebar</code> - check/uncheck a checkbox</li></ul>{:/}|
| Radio buttons | {::nomarkdown}<ul><li><code>Spacebar</code> - select the focused option (if not selected)</li><li><code>↑</code>/<code>↓</code> or <code>←</code>/<code>→</code> - navigate between options</li><li><code>Tab</code> - leave the group of radio buttons</li></ul>{:/}|
| Select (dropdown) menu | {::nomarkdown}<ul><li><code>↑</code>/<code>↓</code> - navigate between options</li><li><code>Spacebar</code> - expand</li><li><code>Enter</code>/<code>Esc</code> - select option and collapse</li></ul>{:/}|
| Autocomplete | {::nomarkdown}<ul><li>Type to begin filtering</li><li><code>↑</code>/<code>↓</code> - navigate to an option</li><li><code>Enter</code> - select an option</li></ul>{:/}|
| Dialog | {::nomarkdown}<ul><li><code>Esc</code> - close</li></ul>{:/}|
| Slider | {::nomarkdown}<ul><li><code>↑</code>/<code>↓</code> or <code>←</code>/<code>→</code> - increase or decrease slider value</li><li><code>Home</code>/<code>End</code>  - beginning or end</li></ul>{:/}|
| Menu bar | {::nomarkdown}<ul><li><code>↑</code>/<code>↓</code> - previous/next menu option</li><li><code>Enter</code>/<code>End</code>  - expand the menu (optional) and select an option.</li><li><code>←</code>/<code>→</code> - expand/collapse submenu</li></ul>{:/}|
| Tab panel | {::nomarkdown}<ul><li><code>Tab</code> - once to navigate into the group of tabs and once to navigate out of the group of tabs</li><li><code>↑</code>/<code>↓</code> or <code>←</code>/<code>→</code> - choose and activate previous/next tab.</li></ul>{:/}|
| 'Tree' menu | {::nomarkdown}<ul><li><code>↑</code>/<code>↓</code> - navigate previous/next menu option</li><li><li><code>←</code>/<code>→</code> - expand/collapse submenu, move up/down one level.</li></ul>{:/}|
| Scroll | {::nomarkdown}<ul><li><code>↑</code>/<code>↓</code> - scroll vertically</li><li><code>←</code>/<code>→</code> - scroll horizontally</li><li><code>Spacebar</code>/<code>Shift</code> + <code>Spacebar</code> - scroll by page</li></ul>{:/}|

For more detailed guidance on keyboard accessibility, see WebAIM’s article [Keyboard Accessibility](https://webaim.org/techniques/keyboard/){:target="_blank"}.