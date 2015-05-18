# Less Space Utility
Inspired by Purple UI Kit

# Usage
Spacing utilities allow you to insert generic spacing to elements and components.
The classes take the following form: .u-{{type}}-{{direction}}{{size}}

# Default values

| Directions     | Sizes     |
|----------------|-----------|
| A- all         | n - none  |
| T - top        | xxs - 6px |
| R - right      | xs - 9px  |
| B - bottom     | s - 12px  |
| L - left       | m - 20px  |
| H - horizontal | l - 27px  |
| V - vertical   | xl - 33px |

# Build


 1. Install gulp, gulp-less and gulp watch: `npm install`
 2. Customize `src/spacer.less`
 3. Use `gulp less` or `gulp watch` to build
 4. Use the generated css file from `dist/spacer.css`
