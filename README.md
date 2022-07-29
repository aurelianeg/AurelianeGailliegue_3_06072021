# Ohmyfood!

Ohmyfood![^1] is a company for online meal orders. Their concept allows users to compose their own menu on their website and therefore reduce their waiting time in restaurants because the food is ready when they arrive.

**Goal of this project**: Integration of the website design with HTML and CSS, and use of CSS animations.

## Load specifications

### Website designs

The target being people connected and in a hurry, the site will be developed using the mobile-first approach.
Only mobile designs will be produced, the website will have to be responsive for tablets and desktop, but their layout is free.
![Design for the home page](./design/home.png "Design for the home page")


### Technical constraints

- Development only with CSS, no JavaScript allowed.
- No framework, but use of Sass would be appreciated.
- No error on W3C validators for HTML or CSS.
- No CSS code applied with a style attribute in a HTML tag.

### Animations and features

- Each restaurant card is clickable, and user is redirected to the menu page for this restaurant.
- In the footer, when "Contact" is clicked, user is redirected to an e-mail.
- Buttons' colors are brighter on hover, and shadows is larger.
- Users should be able to save their favorite menus later by clicking on them. For now, the heart button is filled only on hover.
- A loading spinner for 1 to 3 seconds is needed when arriving on the home page. It takes the whole screen, and loader design is free.
- On menu pages, dished appear gradually (one by one, or group by group).
- For each dish, a check appears on hover from right to left. If dish title is too long, it is cropped with three dots.


## Launch

### GitHub Pages

The page is available at <https://aurelianeg.github.io/ohmyfood/> on GitHub Pages.

### Cloning

1. Clone the repository

```sh
git clone https://github.com/aurelianeg/ohmyfood.git
```

2. Launch the project with Live Server

```sh
live-server
```

It opens the website to view it in the browser. The page will reload when changes are made in the code.


[^1]: This is the 2nd project of the "Front-end developer (JS - React)" training by OpenClassrooms.