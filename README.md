# SmashingConf

## Project Aim

> To implement a new design of the [Smashing Conference website](https://smashingconf.com/sf-2020/), using [this](https://www.behance.net/gallery/29845175/CC-Global-Summit-2015) UI Design created by [Cindy Shin](https://www.behance.net/adagio07).

![screenshot](assets/images/screenshot.png)

## Project Implementation

The website contains three pages: Index, About and Tickets.

### Page Wrapper

Each page is placed within a wrapper with a **maximum width** of `1351px`.

There is a Header, Main and Footer section on all three pages. The contents of each section are placed in a **centered** container, which is set to a `max-width` of `1013px`.

#### Header

The first part of each page is the Header. It is hidden on screen sizes up to **768px**, and is only visible from **768px**.

The Header is divided into two sections, that are laid out using **flexbox**. To ensure there is a gap between the Logo and the Main Menu, in the second section, a **left margin** of `175px` is applied to the Main Menu. The links within the Menu are also made to **grow** and **shrink** on a scale of **1**, and given an initial width of **auto**, so that they respond to changes in screen size.

#### Main

Each page contains a Main to wrap sections specific to that page.

#### Footer

### Index

### About

### Tickets

## Tools & Technologies Used

- HTML5, CSS3.
- Github, Git, Visual Studio Code.
- Pesticide, Font Awesome, Unsplash, TinyPNG/JPG.
- [This](http://www.imageoptimizer.net/Pages/Home.aspx) Image Optimizer, and [this](https://border-image.com/) Border Image Generator.

## Live Demo

[Live Demo Link](https://raw.githack.com/cliftondavies/SmashingConf/feature/conf-page/index.html)

## Authors

👤 **Clifton Davies**

- Github: [@githubhandle](https://github.com/cliftondavies)
- Twitter: [@twitterhandle](https://twitter.com/cliftonaedavies)
- Linkedin: [linkedin](https://www.linkedin.com/in/clifton-davies-mbcs/)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!

Feel free to check the [issues page](https://github.com/cliftondavies/SmashingConf/issues).

## Show your support

Give a ⭐️ if you like this project!

## Acknowledgments

- The Corgis!
- [Cindy Shin](https://www.behance.net/adagio07)
- [Smashing Conference](https://smashingconf.com/sf-2020/)
- [Sam Goodgame](https://unsplash.com/photos/Pe5BC-EDtB4)
- [Basile Bedelek](https://unsplash.com/photos/SNjvN__sSec)
- [Ryan Moreno](https://unsplash.com/photos/w1_4YH5IhDg)

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.