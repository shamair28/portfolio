# Portfolio Site Map & Content Inventory

Source: shamair28.wixsite.com/portfolio — captured June 30, 2026, for migration reference.
This covers structure and text only (you've already got the media handled).

---

## Part 1 — Navigation Structure

### Main menu (as it appears in the site header on every page)

```
HOME                      /
PROJECTS                  /projects
PHOTOGRAPHY               /photography
 └─ HEADSHOTS             /headshots
INSTAGRAM                 → external, instagram.com/6.lenz
CONTACT ME                /blank
Other Projects            /projects-2
 ├─ Commercial Design Assets    /copy-of-projects
 ├─ Old Graphics Assignment     /graphics
 ├─ Old Video Assignment        /video
 └─ Old Video Assignment #2     /single-project
More                       (Wix's generic overflow-menu trigger — not an actual page)
```

Two items — Photography and Other Projects — are themselves clickable pages *and* dropdown parents. Everything else is a single destination.

### Pages that exist but aren't in the main menu

These are only reachable by clicking through from another page, not from the header:

| Page | URL | How you get there |
|---|---|---|
| Short-Form Content | `/projects/short-form` | "Read More" on the Projects page |
| Commercial and Product Design | `/projects/commercial-design` | "Read More" on the Projects page |
| Content Examples | `/content` | "Additional Content Showcase" link — appears on the Projects page *and* on both of the pages above |

So **Projects** functions as a hub: it's a menu item, but most of the substantial writing on your site actually lives one click deeper, on these three pages.

### One thing worth a decision before you rebuild

**Other Projects** (`/projects-2`) and **Commercial Design Assets** (`/copy-of-projects`, its own dropdown child) currently render identical content — same "EZ 2 SHOP" text, same Google Drive link, word for word. The `copy-of-projects` slug is a strong hint this was a Wix-duplicated page that never got differentiated. Right now your nav has two separate labeled entries pointing to what's effectively one page. Worth either merging them into a single nav item or writing distinct content for each when you rebuild.

---

## Part 2 — Page-by-Page Content

### Home
`/` — main menu

No body copy — it's a single image carousel (4 photos) on an otherwise empty homepage. Nothing to migrate here text-wise; this is purely a design/layout decision on the new site.

---

### Projects
`/projects` — main menu

> **Projects**

Two entries, each with a "Read More" linking to its own page (covered below):

- **Short-Form Content** — *Short-form content posted across various social media platforms*
- **Commercial and Product Design** — *Branded content and product designs from concept to market*

Plus a link to **Additional Content Showcase** (`/content`).

---

### Short-Form Content
`/projects/short-form` — reached via "Read More" from Projects

> **Short-Form Content**
> Short-form content posted across various social media platforms

**Collaboration with GLOCAL Foundation**
My experience includes a significant collaboration with the GLOCAL Foundation of Canada, a reputable non-profit organization dedicated to community engagement and social impact. In this role, I was entrusted with the comprehensive process of content creation, which involved extensive planning, filming, editing, and ultimately publishing impactful content aimed at raising awareness about pressing social issues and engaging the community in meaningful dialogue.

**Content Creation and Impact**
During my time with the GLOCAL Foundation of Canada, I developed a series of informative and visually captivating videos that highlighted various initiatives and programs designed to uplift and support marginalized communities. This experience not only enhanced my technical skills but also deepened my understanding of how to convey messages that resonate emotionally with viewers.

**Collaborative Projects and Achievements**
Additionally, I have worked with influencers and other creators, to produce compelling videos that have successfully resonated with audiences, achieving impressive milestones of over 1 million views. This collaborative work has been instrumental in honing my skills in crafting engaging narratives that captivate viewers from the first few seconds, utilizing trending formats that align with current social media trends, and optimizing content for maximum reach and impact across different social media channels.

**Creative Strategy and Audience Engagement**
Through my work, I strive to blend creativity with strategic thinking, ensuring that each piece of content not only entertains but also informs and inspires viewers. I pay careful attention to the analytics and feedback received from each project, allowing me to continuously improve my approach and adapt my content to better meet the needs and interests of my audience.

**Goals and Vision**
My goal is to create content that not only stands out in a crowded digital landscape but also fosters a sense of community and encourages positive action among viewers. By leveraging storytelling techniques and visual aesthetics, I aim to produce content that leaves a lasting impression, ultimately contributing to a more informed and engaged society.

**Performance stat:** 10,000,000+ views across social media platforms

**Project Gallery note:** *(due to privacy concerns, additional reference work done with content creators only available upon request)*

**Links on this page:** "Additional Content Showcase" → `/content` · "< Back" → `/projects`

---

### Commercial and Product Design
`/projects/commercial-design` — reached via "Read More" from Projects

> **Commercial and Product Design**
> Branded content and product designs from concept to market

At EZ 2 Shop, I have played a key role in creating a complete range of artwork and branding materials that authentically reflect our lifestyle and fashion offerings. My focus has been on delivering innovative solutions, exemplified by our two flagship products, EZ 2-Curl and EZ 2-Print, which capture the essence of our mission.

**Product Overview**
- **EZ 2-Curl:** A heatless hair curler designed for effortless styling, allowing users to achieve curls without the use of heat.
- **EZ 2-Print:** Sublimation tumblers that come prepped for users to print their own designs, making customization simple and accessible.

**Branding Approach**
Our branding strategy focuses on creating a cohesive identity that resonates with our target audience. This includes:
- **Visual Identity:** Development of logos, color palettes, and typography that reflect the modern, stylish essence of our products.
- **Packaging Design:** Eye-catching packaging that not only protects our products but also enhances the unboxing experience for customers.
- **Marketing Materials:** Creation of promotional graphics, social media assets, and advertisements that effectively communicate the benefits of our products.

**Market Presence**
EZ 2 Shop products are available on Amazon, where we leverage our branding to stand out in a competitive marketplace. Our focus on quality, innovation, and customer satisfaction drives our marketing efforts and enhances our brand visibility. In summary, the artwork and branding for EZ 2 Shop have been meticulously crafted to ensure that our products, EZ 2-Curl and EZ 2-Print, not only meet consumer needs but also create a lasting impression in the lifestyle and fashion market.

**Performance stat:** CAD $200,000+ in annual sales revenue

**Project Gallery note:** *(due to privacy concerns, additional reference work done with content creators only available upon request)*

**Links on this page:** "Additional Content Showcase" → `/content` · "< Back" → `/projects`

---

### Content Examples
`/content` — reached via "Additional Content Showcase" (appears on Projects, Short-Form Content, and Commercial and Product Design)

> **Content Examples**
> Additional videos to showcase and highlight varied content. Everything below was shot, produced, and edited by myself.
###### Embedded YouTube videos are shown on page in a gallery section
---

### Photography
`/photography` — main menu

No body copy at all — pure image gallery, zero text in the page itself.

---

### Headshots
`/headshots` — dropdown child of Photography

Just the page heading, "HEADSHOTS" — otherwise gallery-only, no body copy.

---

### Contact Me
`/blank` — main menu

> **Get a Quote**

A form with four fields: **First Name**, **Phone**, **Email**, **Address**. Submit button reads "Submit Request"; the post-submit confirmation message is "Thanks for submitting!"

(Note the URL slug is the Wix-default `/blank` — it was never renamed, worth giving it a real path like `/contact` on the new site.)

---

### Other Projects
`/projects-2` — main menu

> **Projects**
> **EZ 2 SHOP**
> Digital and Print assets used for E-Commerce Business on Amazon

**Links on this page:** "Google Drive Projects Folder" → `https://drive.google.com/drive/folders/1qqZp6fBGw3rA6pcCWIa86Nf-BnoEWXZn?usp=sharing`

*(Identical to Commercial Design Assets below — see the note in Part 1.)*

---

### Commercial Design Assets
`/copy-of-projects` — dropdown child of Other Projects

Same content as Other Projects, above, word for word — same Google Drive link too.

---

### Old Graphics Assignment
`/graphics` — dropdown child of Other Projects

> **Welcome to Cafe Oakville**
> Oakville's Premiere coffee shop and bakery
> **Mission Statement**

That's the entirety of the extracted text — the "Mission Statement" heading has no body copy following it on the live page (the rest of the page is graphic/image content rather than text).

---

### Old Video Assignment
`/video` — dropdown child of Other Projects

> **Behind the Scenes**
>
> **Dislikes**
> - Bad Masking
> - Bad Tracking

Minimal text — this page is built around the embedded video and a couple of animated GIFs rather than written copy.

---

### Old Video Assignment #2
`/single-project` — dropdown child of Other Projects

> **Updated HS Project**
> Showcase of camera work, colour correction, After Effects, as well as Premiere Pro abilities. This entire video was planned, filmed, edited, and submitted in under 90 minutes.

---

### Instagram
`instagram.com/6.lenz` — main menu, external link

Not a page on the Wix site — the nav just opens your Instagram profile in a new destination. Nothing to migrate; just decide whether the new site links out the same way.

---

## Quick reference: pages with little or no real copy

Home, Photography, Headshots, Old Graphics Assignment, and Old Video Assignment are all light-to-empty on text — they lean on images/video instead. If the new site's design also leans visual for these sections, you may not need new copy at all; if you want a more text-driven layout, these are the five pages that will need new writing rather than migrated writing.
