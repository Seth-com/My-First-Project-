# Week 1 Bio Page Project

My first website built from scratch using HTML + CSS. I'm learning web dev one day at a time.

### 🚀 Live Demo
[View Live Site](https://seth-com.github.io/My-First-Project-/)

### 🛠️ Built With
- HTML5
- CSS3 - Box Model, Flexbox

### 📅 Learning Timeline

#### **Week 1: HTML + CSS Basics** ✅
- [x] HTML structure: headings, paragraphs, lists, forms
- [x] CSS fundamentals: selectors, colors, fonts
- [x] Set up GitHub repo + GitHub Pages deployment
- [x] Used GitHub Desktop for commits and pushes

#### **Week 2: Layout & Styling** 🔥 In Progress
**Day 1-2: Box Model** ✅
- [x] Learned `padding` vs `margin` vs `border`
- [x] Fixed button spacing issue using `padding` on form container
- [x] Understood why `margin` leaks outside containers

**Day 3: Flexbox** ✅
- [x] Used `display: flex` to create 2-column layout
- [x] Grouped Name + Email inputs side-by-side
- [x] Learned `flex: 1`, `gap`, and `flex-direction: column`
- [x] Made form responsive-ready

**Day 4: Button U  X** ⏳
- [x] Added `:hover` and `active` pseudo-classes
- [x] Used `transition` for smooth animations 
- [x] Aplied `transform: translateY()` for lift effect
- [x] Added `box-shadow` for depth and `border-radius` for modern look 

### 🎯 Key Concepts Learned
1. **Box Model:** `padding` = inside space. Use it on containers to create breathing room for children.
2. **Flexbox:** `display: flex` on parent puts children in a row. `flex: 1` makes them share space equally.
3. **Git Workflow:** Save → Commit → Push → Live site updates

# Day 5: Contact Form with CSS Validation ✅

### Project: Interactive Contact Form
**Date:** May 3, 2026  
**Status:** Complete 💯  

---

### 🚀 What I Built
A fully responsive contact form using **pure HTML & CSS** with real-time validation. No JavaScript used.

**Live Features:**
1. **Smart Validation** - Error messages only show after user interacts
2. **Visual Feedback** - Blue glow on focus, red border when invalid  
3. **Responsive Layout** - Name/Email side-by-side using Flexbox
4. **UX Polish** - Hover effects, no layout shift, clean error handling
5. **Browser Native** - Uses HTML5 `required` + `type="email"` validation

---

### 🛠️ Tech Stack / Concepts Used
| **Technology** | **What I learned** |
| --- | --- |
| **HTML5** | `required`, `type="email"`, `placeholder`, semantic `<form>` |
| **CSS3** | `:invalid`, `:focus`, `:not()`, `:placeholder-shown` pseudo-classes |
| **Flexbox** | `display: flex`, `align-items: flex-start`, `gap` for layout |
| **UX Design** | Hide errors by default, `box-shadow` for focus glow |
| **Debugging** | CSS specificity conflicts, layout shift fixes |

---

### 🐛 Bugs I Killed Today
1. **Error showing on page load** → Fixed with `:not(:placeholder-shown)`
2. **Email input stretching** → Fixed with `align-items: flex-start` on `.input-row`
3. **Ugly default focus outline** → Replaced with custom blue `box-shadow`
4. **Border conflicts** → Removed `border: none;` and set proper colors
5. **CSS can't detect submit** → Learned browser handles empty submit natively

---

### 📸 Screenshot
> screenshot will be added later

**Before:** Errors showing always, layout jumping, red borders everywhere  
**After:** Clean form, errors only on interaction, smooth UX

---

### 💡 Key Lesson Learned
> "Pure CSS validation has limits. CSS controls style, not behavior. 
> For submit events and complex logic, JavaScript is needed. 
> But for Day 5, HTML5 + CSS validation is perfect." - Me, after 2 hours debugging 😅

---

### 🔜 Next Steps - Day 6 Preview
1. Add JavaScript to show custom error on submit click
2. Display "Message Sent!" success state
3. Add character counter for message box

---

### 🎯 How to Run
1. Clone repo
2. Open `index.html` in browser
3. Try submitting empty → Browser blocks it
4. Click input, leave empty → Custom error shows
5. Fill all fields → Form ready to submit

**Built with 💪 and plenty debugging by Dzansi** 



---
Built with 💙 while learning. Day by day.
