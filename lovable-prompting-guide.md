
# 💡 Lovable Prompting Guide

## 📘 What This Guide Is

This guide is a **compact reference** for using **Lovable** — the AI-powered website builder — more effectively. It covers:

- **How to think about prompting Lovable** — what works and what doesn’t  
- **A curated set of real prompts and formats** shared by actual users — ready to adapt for your own projects  
- **Key tips, caveats, and repeatable patterns** to consistently get better results  

This guide is **generic** and **not brand-specific**, so you can apply its methods to **any website or web-app** you build with Lovable.

---

## 🧠 1. The “First Prompt” Rule

Your **first prompt sets the project’s identity**, structure, and boundaries — almost like a product spec.  
Treat it as a *project brief*, not a casual request.

**✅ Example:**
> “You are building a modern business website with sections for Home, About, Services, and Contact.  
> Use a clean layout with clear CTAs, responsive design, and reusable components.”

**🚫 Avoid:**
> “Make me a website for a cleaning company.”

---

## 📂 2. Use a “Knowledge Base” or Reference Section

Maintain a Knowledge Base (KB) file that holds key details Lovable should reference across prompts:

```text
Goals: attract leads, explain services clearly  
Tech Stack: React + Tailwind  
Pages: Home, About, Contact  
Design Style: modern, easy to read, mobile-first  
Out of Scope: complex backend logic, payments
````

Then begin prompts with:

> “Before writing any code, review the Knowledge Base and confirm understanding.”

---

## ✏️ 3. Three-Layer Prompt Structure

Use the **Intent → Instruction → Style** framework:

```
Intent: Build a small-business website with Home, Services, and Contact pages.  
Instruction: Use responsive design, add navigation, hero section, services grid, and contact form.  
Style: Keep layout simple, consistent spacing, readable fonts, and minimal animation.
```

---

## ⚙️ 4. Work Incrementally

Community consensus: **“Big prompts cause messy results.”**
Give Lovable one clear, focused task at a time.

**Example Flow**

1. Generate layout + navigation + footer
2. Add hero section
3. Create services grid
4. Build contact form

---

## 🧩 5. Be Descriptive About Structure

Avoid vague terms like “modern” or “cool.”
Use functional language:

* “Two-column layout with image left, text right.”
* “Sticky header that shrinks on scroll.”
* “Three call-to-action buttons under hero.”

---

## 🔁 6. Maintain Consistency Across Prompts

Re-use design terms and elements to keep a unified look:

> “Use the same button styles and layout grid as the homepage.”
> “Follow the typography defined in the initial layout.”

---

## 🧱 7. Reference Real Designs

Lovable responds well to visual or structural references:

> “Follow the layout of notion.so’s landing page, simplified.”
> “Use card grids similar to apple.com but lighter.”

If screenshots are available, upload and say:

> “Match this structure and spacing.”

---

## 🪶 8. Iterate and Refine

Use conversational follow-ups instead of restarting:

> “Center the hero text vertically.”
> “Reduce padding by 25%.”
> “Add hover animation on service cards.”

---

## 📏 9. Keep Prompts Manageable (300–700 Characters)

Short prompts lack context; long ones get truncated.
Aim for a concise middle ground and chain them logically.

---

## 🧰 10. Save and Reuse Prompt Templates

Create reusable templates for common layouts:

**Landing Page Template**

```
Hero → Features → Testimonials → CTA → Footer
```

**Service Page Template**

```
Hero → Text/Image Split → FAQs → CTA
```

Store these in a `/prompts/` folder for easy reuse.

---

## ⚠️ Common Mistakes

| Mistake                  | Why It Fails         | Fix                               |
| ------------------------ | -------------------- | --------------------------------- |
| Giant multi-page prompts | AI loses structure   | Split into pages/components       |
| Only adjectives          | Too vague            | Use layout and behavior details   |
| Ignoring mobile          | Desktop-only results | Add “mobile-first and responsive” |
| No backups               | Lost work            | Use GitHub or local versioning    |
| Messy styles             | Unreadable output    | Ask to “clean and simplify code”  |

---

## 🧮 Sample Universal Prompt

```text
Build a responsive business website using clean, semantic HTML and CSS (or React + Tailwind).  
Include a navigation bar, hero section, services section, and contact form.  
Maintain consistent spacing, readable typography, and simple hover animations.  
Focus on usability, accessibility, and modular code structure.  
Avoid filler text like Lorem Ipsum; use generic labels instead.
```

---

## 🧠 Quick Reference Workflow

1. **Write your Knowledge Base** (goals, tech, design, scope)
2. **Craft the first prompt** carefully — treat it like a brief
3. **Generate and review** the layout/code
4. **Iterate** page-by-page or component-by-component
5. **Refine & polish** (alignment, responsiveness, animation)
6. **Save working prompts** as templates
7. **Commit to GitHub** to preserve good versions

---

## 🧩 Community Sources Referenced

* Reddit threads:

  * [Guide to Build with Lovable (r/lovable)](https://www.reddit.com/r/lovable/comments/1mhqfhw/guide_to_build_with_lovable_from_someone_whos_in/)
  * [Prompting Megathread](https://www.reddit.com/r/lovable/comments/1ka2bn9/prompting_megathread/)
  * [Using Lovable — Tips & Tricks](https://www.reddit.com/r/lovable/comments/1jtgb2e/using_lovable_here_are_my_suggestions_to_build/)
* Lovable blog:

  * [Lovable Prompting Handbook](https://lovable.dev/blog/2025-01-16-lovable-prompting-handbook)

---

*File:* `lovable-prompting-guide.md`
*Last Updated:* October 2025

```

--- 
