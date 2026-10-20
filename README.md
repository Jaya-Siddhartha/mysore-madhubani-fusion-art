# Fusion of Indian Art: Mysore Meets Madhubani

**Assignment:** Regional Painting Fusion Project (Indian Art History, 10 marks)

**Objective:** To create and present an original artwork that combines elements of two Indian regional painting traditions: **Mysore painting** (Karnataka) and **Madhubani painting** (Bihar).

**Live site:** https://mysore-madhubani-fusion-art.vercel.app  
**GitHub:** https://github.com/Jaya-Siddhartha/mysore-madhubani-fusion-art

### Team

| Name | Register number |
|---|---|
| Addanki Jaya Siddhartha | RA2411003010774 |
| Nallana Saahithi | RA2411003010772 |
| Aryan Sagar Patike | RA2411003010722 |
| Yogesh Reddy Pelluru | RA2411003010742 |
| Gopalchetty Goutam | RA2411003010767 |

> **About the artwork:** the fusion artwork shown on the website (`assets/fusion-artwork.svg`) is an original **digital illustration** (SVG). It is not hand-painted, and the website says so. If the team also paints the design by hand, its photo can be shown instead (see below).

---

## Folder structure

```
Project 3/
├── index.html                          the whole website (7 sections)
├── style.css                           colours, layout, mobile styles
├── README.md                           this file
└── assets/
    ├── mysore-reference.jpg            reference image (from Mysore_images_2_pages.pdf)
    ├── madhubani-reference.jpg         reference image (from madhubani paintings.pdf)
    └── fusion-artwork.svg              our fusion artwork (digital illustration)
```

No JavaScript is needed. The site uses only HTML and CSS (plus Google Fonts).

## Website sections

1. **Introduction:** title, short introduction, assignment, objective, team
2. **Understanding the Two Art Styles:** a Mysore card and a Madhubani card, each with a reference image
3. **Our Fusion Artwork:** the centrepiece, a large framed image with an explanation
4. **How We Combined the Styles:** comparison table and a short explanation
5. **Materials and Method:** materials list and a 6-step process
6. **Conclusion**
7. **References**

---

## The fusion artwork

**File:** `assets/fusion-artwork.svg` (800 × 1000 vector image; it stays sharp at any size)

| Part of the artwork | Inspired by |
|---|---|
| Saraswati: calm face, tall crown (kirita), necklaces, earrings, bangles, waist belt | Mysore painting |
| Veena, prayer beads and palm-leaf book in her four hands; lotus seat; swan (her vehicle) | Mysore painting (traditional Saraswati iconography) |
| Ornate gold arch with pearls and gems; deep red background | Mysore painting |
| Peacocks, sun and moon, two patterned fish, lotus flowers, leafy vines | Madhubani painting |
| Dotted background, triangle and leaf borders, bold double outlines, bright flat colours | Madhubani painting |
| Flower garland in Madhubani colours on the Mysore figure; lotuses and water inside and outside the arch | Links that join the two styles |

### Showing a hand-painted version instead (optional)

1. Photograph or scan the painting straight-on, cropped to the paper edges.
2. Save it as **`assets/fusion-artwork.jpg`**.
3. In `index.html` (Section 3), change `src="assets/fusion-artwork.svg"` to `src="assets/fusion-artwork.jpg"`, and remove `width="800" height="1000"` if the photo has a different shape.
4. Change the caption line *"Digital illustration created for this project."* to describe the painting (e.g. *"Watercolour and gold paint on paper."*), and update the alt text and Section 7B.

### Remaining checks for the team

- [ ] **Reference images:** the two PDFs don't record where their images came from. If you know the original source of the two images used (website, book, artist), add it to Section 7A.
- [ ] If you paint the design by hand, update the caption, the Materials note and Section 7B (steps above).

---

## Run locally

Double-click **`index.html`**. It opens in your browser and works without a server.

Or, in VS Code: right-click `index.html` and choose **Open with Live Server**.

## Deploy on Vercel

The site is plain static HTML, so it needs no build settings.

**With the Vercel CLI** (from inside the `Project 3` folder):

```bash
vercel --prod
```

**Or with GitHub:** push the folder to a GitHub repository. On vercel.com, choose **Add New → Project**, import the repository, leave **Framework Preset = Other**, and click **Deploy**.

---

## Explanation for your faculty presentation (about 1–2 minutes)

> "Our project is *Fusion of Indian Art: Mysore Meets Madhubani*. We chose two regional painting traditions that look very different.
>
> **Mysore painting** from Karnataka developed from Vijayanagara painting and was supported by the Wodeyar kings of Mysore. It's known for delicate lines, graceful figures, rich jewellery, decorative arches and gold leaf over raised gesso work. Its subjects are mostly gods, goddesses and mythology.
>
> **Madhubani painting** comes from the Mithila region of Bihar, where women traditionally painted walls and floors for festivals and weddings. It uses bold double outlines, bright colours and patterns that fill every space, with fish, lotuses, birds and decorative borders.
>
> In our artwork, **Saraswati**, the goddess of knowledge and the arts, sits at the centre in the **Mysore style**, with her veena, crown, jewellery and a gold arch. Around her, we used **Madhubani** elements: fish, lotus flowers, birds, geometric patterns and a colourful border.
>
> The comparison table shows what we took from each style. Mysore gives the painting its focus and refinement; Madhubani gives it energy and colour. Both traditions are devotional and decorative, so they come together naturally in one design. This is our example of creative synthesis between two Indian art traditions."

Then show: Section 2 (the two cards) → Section 3 (the artwork) → Section 4 (the table) → Section 5 (the process).

---

## References

**A. Sources used to study the traditional styles**

- “Mysore painting”, Wikipedia: https://en.wikipedia.org/wiki/Mysore_painting (history, Vijayanagara origins, Wodeyar patronage, gesso and gold technique, subjects)
- “Madhubani art”, Wikipedia: https://en.wikipedia.org/wiki/Madhubani_art (Mithila region, women painters, styles and motifs)
- Reference images: from the team's own reference documents `Mysore_images_2_pages.pdf` and `madhubani paintings.pdf`. The original artists and sources were not recorded in those documents.

**B. Original fusion artwork**

- "Saraswati: Mysore Meets Madhubani" (`assets/fusion-artwork.svg`): an original digital illustration (SVG) created for this project. It is not copied from either reference document.
