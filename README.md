# IPEM Lab | ELEE 4710 — Interactive Courseware

## Open a course

| Website | Open online |
| --- | --- |
| Original Magnetic Circuit Analysis lecture | **[Open the original lecture →](https://jinye1985.github.io/elee4710/)** |
| Complete course: all eight chapters | **[Open the complete course →](https://jinye1985.github.io/elee4710/course/)** |

The original homepage also includes an **Open Complete Course** button. Both versions are available through the same GitHub Pages site after this upload is deployed.

## Complete course

The complete course includes interactive demonstrations, worked examples, chapter navigation, and a reference companion for each chapter.

| Chapter | Open online |
| --- | --- |
| 01 | [Introduction to Power Engineering](https://jinye1985.github.io/elee4710/course/chapter-01/index.html) |
| 02 | [Magnetic Circuit Analysis](https://jinye1985.github.io/elee4710/course/chapter-02/index.html) |
| 03 | [Review of AC Circuit Analysis](https://jinye1985.github.io/elee4710/course/chapter-03/index.html) |
| 04 | [Operational Characteristics of Transformers](https://jinye1985.github.io/elee4710/course/chapter-04/index.html) |
| 05 | [Principles of Electromechanical Energy Conversion](https://jinye1985.github.io/elee4710/course/chapter-05/index.html) |
| 06 | [DC Machines](https://jinye1985.github.io/elee4710/course/chapter-06/index.html) |
| 07 | [Induction Machines](https://jinye1985.github.io/elee4710/course/chapter-07/index.html) |
| 08 | [Synchronous Machines](https://jinye1985.github.io/elee4710/course/chapter-08/index.html) |

[Open the reference library](https://jinye1985.github.io/elee4710/course/references.html)

**Knowledge Point** labels definitions and principles. **Interactive Demonstration** labels teaching models. **Example** headings open worked solutions. Each reference companion documents sources, assumptions, and relevant corrections.

## Read offline

[Download the main branch as a ZIP](https://github.com/jinye1985/elee4710/archive/refs/heads/main.zip) and extract it.

- Open the extracted root `index.html` for the original lecture.
- Open `course/index.html` for the complete course.

Keep each page with its folders and assets. No installation, server, or start script is needed. External reading and video links require an internet connection. See [the course usage guide](course/README.txt) for annotation controls.

## Original lecture

The original homepage retains its lecture slide viewer, magnetic-core simulator, air-gap experiment, and practice quiz. It uses the existing `styles.css`, `app.js`, and `assets/` files. The new navigation button links to the complete course.

The original magnetic-core and air-gap models use simplified assumptions: uniform paths and cross sections, linear material properties, and neglected leakage, saturation, and fringing where stated on the page.

## Publishing and updates

Use **Settings → Pages → Deploy from a branch → main → /(root)**. Both versions are published together from this source.

- Root `index.html`: original lecture with the complete-course navigation button.
- `course/index.html`: complete-course homepage.
- `course/chapter-01/` through `course/chapter-08/`: individual chapters.
- `course/references.html`: reference library.

Update `main/course/` to publish changes to the complete course. The separate `slides-complete-course` branch can be retained for development; changes there do not automatically update `main/course/`.

[GitHub Pages publishing-source guide](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

Original lecture PDFs and figures retain their existing copyrights. Third-party software license files accompany each complete-course chapter.
