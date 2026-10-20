# Fusion of Indian Art: Mysore Meets Madhubani

**Assignment:** Regional Painting Fusion Project (Indian Art History, 10 marks)

**Objective:** To create and present an original artwork that combines elements of two Indian regional painting traditions: **Mysore painting** (Karnataka) and **Madhubani painting** (Bihar).

### Team

| Name | Register number |
|---|---|
| Addanki Jaya Siddhartha | RA2411003010774 |
| Nallana Saahithi | RA2411003010772 |
| Aryan Sagar Patike | RA2411003010722 |
| Yogesh Reddy Pelluru | RA2411003010742 |
| Gopalchetty Goutam | RA2411003010767 |

> **Important:** the main deliverable of this assignment is the **actual fusion artwork** that the team draws or paints. This website only presents that artwork and explains the design. Until the artwork is finished, the website shows a clearly labelled **placeholder** (a plan of the composition).

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
    └── fusion-artwork-placeholder.svg  placeholder: composition plan
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

## How to add your final artwork

1. Take a clear, well-lit photo or scan of the finished artwork, straight-on and cropped to the paper edges.
2. Save it as **`assets/fusion-artwork.jpg`**.
3. Open `index.html` and find the comment **`TO ADD OUR FINAL ARTWORK`** (Section 3). Change:
   ```html
   <img src="assets/fusion-artwork-placeholder.svg"
   ```
   to:
   ```html
   <img src="assets/fusion-artwork.jpg"
   ```
4. Update the **`alt`** text to describe the real artwork. Replace the caption *"Placeholder: planned composition…"* with a real one, for example *"Saraswati: Mysore Meets Madhubani. Watercolour and gold paint on paper, 2026."*
5. In **Section 5 (Materials)**, keep only the materials you actually used. If the artwork is digital, write the software name instead.
6. In **Section 7 (References)**, change the "Fusion artwork" line if needed.
7. Save, refresh the browser, and push to GitHub. Vercel updates the live site automatically.

### What still needs to be done for the assignment

- [ ] **Create the actual fusion artwork**: a Mysore-style Saraswati (veena, crown, jewellery, gold arch) surrounded by Madhubani-style fish, lotus flowers, birds, geometric patterns and a double-line border.
- [ ] Add its photo to the website (steps above).
- [ ] Confirm the **materials** you used (Section 5).
- [ ] **Reference images:** the two PDFs don't record where their images came from. If you know the original source of the two images used (website, book, artist), add it to the References section. One Madhubani image in the PDF is signed "Rajni Kumari". It isn't one of the two images used on the site, but note it if you use it later.

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

- “Mysore painting”, Wikipedia: https://en.wikipedia.org/wiki/Mysore_painting (history, Vijayanagara origins, Wodeyar patronage, gesso and gold technique, subjects)
- “Madhubani art”, Wikipedia: https://en.wikipedia.org/wiki/Madhubani_art (Mithila region, women painters, styles and motifs)
- Reference images: from the team's own reference documents `Mysore_images_2_pages.pdf` and `madhubani paintings.pdf`. The original artists and sources were not recorded in those documents.
