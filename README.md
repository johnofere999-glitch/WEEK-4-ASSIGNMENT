# SpendWise Dashboard Shell

A responsive, modern dashboard interface built for the SpendWise capstone project using HTML5, CSS Grid, Flexbox, and CSS Custom Properties.

## Key Features

1. **CSS Grid Layout**:
   - Primary page layout uses a 2-column Grid (`260px 1fr`) separating the sidebar from the main content.
   - Dashboard category cards are organized using `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`.

2. **Flexbox Alignment**:
   - Flexbox manages internal alignment for header elements, sidebar items, and card content.

3. **CSS Custom Properties (Variables)**:
   - Configured `:root` variables for `--brand-color`, `--accent-color`, `--surface-bg`, `--text-primary`, and `--text-secondary`.

4. **Card Micro-interactions**:
   - Smooth 200ms hover and focus state transitions utilizing `transform: translateY(-6px)` and tailored `box-shadow` effects. Accessible via keyboard (`tabindex="0"`).

5. **Responsive Design (< 768px)**:
   - Media queries collapse the 2-column layout into a single-column view for mobile devices.

6. **Dark Theme (Stretch Goal)**:
   - Automatic dark theme styling via `@media (prefers-color-scheme: dark)` overriding CSS variables.
