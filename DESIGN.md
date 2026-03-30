# Design System: High-End Editorial Athlete Registration

## 1. Overview & Creative North Star: "The Kinetic Editorial"
Most registration apps feel like a digital tax return. This design system rejects the "form-filler" aesthetic in favor of **The Kinetic Editorial**. We treat the student-athlete journey with the prestige of a high-end sports magazine combined with the fluidity of modern motion design.

Instead of a rigid grid of input boxes, we utilize **intentional asymmetry** and **tonal layering**. We break the "template" look by using a massive typographic scale (Plus Jakarta Sans) for headlines that occasionally overlap container boundaries, creating a sense of forward momentum and athleticism. The layout breathes through generous white space, using the `20` (5rem) and `24` (6rem) spacing tokens to create "moments of focus" rather than cluttered screens.

---

## 2. Colors & Surface Philosophy
The palette is rooted in a high-performance "Championship Blue," but its application is sophisticated and layered.

### The "No-Line" Rule
**Explicit Instruction:** You are prohibited from using 1px solid borders (`#CCCCCC` or similar) to section content. Boundaries must be defined solely through background shifts.
*   **Secondary Sectioning:** Place a `surface-container-low` (#f2f3fd) element directly onto a `surface` (#f9f9ff) background.
*   **Depth through Tonal Transition:** Use the natural shift from `surface-container` (#ecedf7) to `surface-container-highest` (#e0e2ec) to indicate nested importance.

### The "Glass & Gradient" Rule
To elevate the "Cadastro Atletas" brand beyond a standard utility app:
*   **Floating UI:** Use Glassmorphism for the Bottom Navigation and Floating Action Buttons. Apply `surface-container-lowest` (#ffffff) at 80% opacity with a `20px` backdrop-blur.
*   **Signature Textures:** Main CTAs and Progress Headers must use a linear gradient: `primary` (#005bbf) to `primary_container` (#1a73e8) at a 135-degree angle. This adds "visual soul" and three-dimensional depth.

---

## 3. Typography: The Editorial Voice
We use a dual-font strategy to balance athletic energy with administrative clarity.

*   **Display & Headlines (Plus Jakarta Sans):** Used for "Hero" moments (e.g., "Bem-vindo, Atleta"). Use `display-lg` for impactful entry screens. These should have a tight letter-spacing (-0.02em) to feel authoritative.
*   **Body & Labels (Inter):** Used for all functional data entry. Inter provides maximum legibility at small scales. 
*   **Hierarchy as Brand:** Use `headline-sm` (1.5rem) for form section titles (e.g., "Dados Pessoais") to give the app an editorial, magazine-like structure.

---

## 4. Elevation & Depth: Tonal Layering
We move away from the "shadow-on-everything" approach. Depth is achieved through the **Layering Principle**.

*   **The Layering Principle:** Place a `surface-container-lowest` (#ffffff) card on top of a `surface-container-low` (#f2f3fd) background. The 2-step shift in luminance creates a perceived lift without visual noise.
*   **Ambient Shadows:** For the Floating Action Button (FAB), use a "tinted" shadow. Instead of black, use `on-surface` (#191c23) at 6% opacity with a `24px` blur and `8px` Y-offset.
*   **The Ghost Border Fallback:** If a form field requires a container, use `outline-variant` (#c1c6d6) at **15% opacity**. It should be felt, not seen.

---

## 5. Components & Primitive Styling

### Input Fields (The "Athlete Profile" Input)
*   **Style:** No background fill. Use a bottom-only "Ghost Border" (15% opacity `outline-variant`). 
*   **State:** When active, the border transforms into a 2px `primary` (#005bbf) line.
*   **Label:** Use `label-md` in `on-surface-variant` (#414754) floating above the input.

### Cards & Lists (The "Anti-Divider" Approach)
*   **Forbid:** Do not use horizontal line dividers.
*   **Alternative:** Separate list items using `spacing-4` (1rem) and subtle background shifts. For athlete stats or records, use `surface-container-high` cards with `rounded-lg` (1rem) corners.

### Floating Action Button (FAB)
*   **Shape:** Use `rounded-xl` (1.5rem) rather than a circle for a more modern, "squircle" look.
*   **Color:** Gradient fill (`primary` to `primary_container`).
*   **Placement:** Offset from the bottom-right using `spacing-6` (1.5rem) to allow the background to "wrap" around it.

### Multi-Step Form Indicators
*   **Style:** Do not use numbers (1, 2, 3). Use expansive horizontal bars.
*   **Active:** `primary` (#005bbf) bar, 4px height.
*   **Inactive:** `surface-container-highest` (#e0e2ec), 4px height.
*   **Logic:** The bars should span the full width of the screen with `spacing-1` between segments to create a sleek, "high-speed" progress feel.

---

## 6. Do’s and Don’ts

### Do:
*   **Do** use `display-md` for empty states. A large, bold "Sem Atletas" is more premium than a small icon.
*   **Do** embrace asymmetry. Align your headline to the left but your "Next" button to the far right.
*   **Do** use `surface-bright` for the main background to ensure the app feels "fresh" and "clean."

### Don’t:
*   **Don’t** use pure black (#000000) for text. Always use `on-surface` (#191c23) to maintain the soft editorial feel.
*   **Don’t** use `rounded-none`. Everything in this system has a minimum of `rounded-sm` to maintain a friendly, approachable student-athlete vibe.
*   **Don’t** use "Drop Shadows" on cards. Use tonal background shifts unless the element is literally floating over scrolling content.

---

## 7. Signature Interaction: The "Fluid Transition"
When moving between registration steps, elements should not "slide" in a standard way. Use a **Staggered Fade-In**:
1.  Headline fades in first (0ms delay).
2.  Form inputs fade in with a slight upward slide (50ms delay).
3.  The "Proceed" FAB scales up from the bottom (100ms delay).

This creates a sense of "orchestration" that feels bespoke and high-end.