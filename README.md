# Image Grid Layout

A responsive-minded image gallery built with **HTML** and **CSS Grid**. Six images are arranged in a 3 × 3 grid, with some images spanning two rows for a staggered look.

[roadmap.sh](https://roadmap.sh/projects/image-grid)

## Layout

```
+---------+---------+---------+
|         |  img 2  |         |
|  img 1  +---------+  img 3  |
|         |         |         |
+---------+  img 4  +---------+
|  img 5  |         |  img 6  |
+---------+---------+---------+
```

## Tech Used

- HTML5
- CSS3 (Grid, `object-fit`)

## Run Locally

1. Clone or download this repository.
2. Put your six images in the `images/` folder as `grid-img1.jpg` to `grid-img6.jpg`.
3. Open `index.html` in a browser.

## Folder Structure

```
├── index.html
├── style.css
├── images/
│   └── grid-img1.jpg ... grid-img6.jpg
└── README.md
```

## What I Learned

- Defining a grid container with `grid-template-columns` and `grid-template-rows`
- Spanning items across rows and columns with `grid-row` and `grid-column`
- Spacing items with `gap`
- Keeping images from stretching with `object-fit: cover`

## Author

Kunal Guhagarkar