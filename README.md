# SmashingConf

## Project Aim

> To implement a new design of the [Smashing Conference website](https://smashingconf.com/sf-2020/), using [this](https://www.behance.net/gallery/29845175/CC-Global-Summit-2015) UI Design created by [Cindy Shin](https://www.behance.net/adagio07).

![screenshot](assets/images/screenshot.png)

## Project Implementation

The website contains three, navigatable pages: Index, About and Tickets.

### Page Wrapper

Each page is placed within a wrapper with a **maximum width** of `1351px`.

There is a Header, Main and Footer section on all three pages. A **centered** container, set to a `max-width` of `1013px`, is used within each section, to wrap its contents.

#### Header

The first part of each page is the Header. It is hidden on **screen sizes** up to `768px`, and is only visible from `768px`.

The Header is divided into two sections, that are laid out using **flexbox**. To ensure there is a gap between the Logo and the Main Menu, in the second section, a **left margin** of `175px` is applied to the Main Menu. The links within the Menu are also made to **grow** and **shrink** on a scale of **1**, and given an initial width of **auto**, so that they respond to changes in screen size.

An **absolute-positioned** Side Menu is added to the second section of the Header, for the Tickets and About pages.

#### Main

Each page contains a Main to wrap sections specific to that page.

#### Footer

**Flexbox** is used to lay out the contents of the Footer, with the Text block made to **shrink** at four times that of the Logo block.

### Index

There are four sections specific to the Index page: Intro, Schedule, Speakers and Partners. Similar to the Header, Main and Footer, **centered** containers, having a `max-width` of `1013px`, are used to wrap the contents of each **section**.

All **sections**, with the exception of Intro, are given an `id` and **linked** to with `#`.

#### Intro

The contents of Intro are structured using **flexbox**. This **section** takes up the rest of the **viewport height** (minus the Header) from `768px`.

A **linear gradient** overlaying a normal **image**, creates the `background` of this **section**. For the effect on the main heading, a `background-image`, **clipped** around the **text**, is applied.

#### Schedule

**Flexbox** is primarily used to lay out the five activities within Schedule. They stack in one **column** on mobile, and adopt a 5x1 grid layout from `768px`. The final **link** within Schedule interchanges as you move between small and medium screens.

#### Speakers

**Grid** is mainly employed within Speakers. On mobile there are only two speakers visible - one stacked on top of another - alongside a view more **button**. From medium screens, this **button** disappears, and a 2x3 grid is revealed.

A `border-image` is included for the effect on each photo.

#### Partners

The logos in this **section** are also laid out using **flexbox**, with the logos allowed to **wrap** on mobile.

### About

There are three sections unique to the About page: Conf Info, Conf Logo, and Past Events. Here, a **centered** container, set to a `max-width` of `810px`, is used within each section, to wrap its contents.

#### Conf Info

The most important thing to note here, is the text added above the main heading from `768px`.

#### Past Events

Both past events are also built with **flexbox**. They appear stacked on mobile, and side by side from medium screens.

### Tickets

The Main part of the Tickets page is made up of a **form** with two sections: Pricing and Meal. Like the About page, a **centered** container, set to a `max-width` of `810px`, is used within each **section**, to wrap its contents.

#### Pricing

Pricing contains a single **table**. It is wrapped in a `div` which serves two purposes. Firstly, with an **overflow** value of **auto**, the `div` provides a **horizontal scroll** and ensures the table is responsive on mobile. Furthermore, it allows for a `border-image` to be set, since the **table borders** are **collapsed**.

#### Meal

The last **section** of the Ticket page Main is made up of two similar tables. A **display** of **block** is applied to both tables, and their internal elements, to allow for the one-column arrangement on mobile.

Finally, two icons are used to create the diamond at the intersection of Pricing and Meal. Both icons have an **absolute position**, with the square icon **rotated** forty-five degrees.

## Tools & Technologies Used

- HTML5, CSS3.
- Github, Git, Visual Studio Code.
- Pesticide, Font Awesome, Unsplash, TinyPNG/JPG.
- [This](http://www.imageoptimizer.net/Pages/Home.aspx) Image Optimizer, and [this](https://border-image.com/) Border Image Generator.

## Live Demo

[Live Demo Link](https://raw.githack.com/cliftondavies/SmashingConf/feature/conf-page/index.html)

## Project Presentation

[Video Recording](https://www.loom.com/share/832c503eec354c7e8ffde430ddfef942)

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

- The Corgis: Actionable Feedback
- [Cindy Shin](https://www.behance.net/adagio07): UI Design
- [Smashing Conference](https://smashingconf.com/sf-2020/): Website Content and Assets
- [Sam Goodgame](https://unsplash.com/photos/Pe5BC-EDtB4): Intro Section Background Image
- [Basile Bedelek](https://unsplash.com/photos/SNjvN__sSec): Intro Heading Background Image
- [Ryan Moreno](https://unsplash.com/photos/w1_4YH5IhDg): Schedule Background Image

## 📝 License

This project is [MIT](https://opensource.org/licenses/MIT) licensed.