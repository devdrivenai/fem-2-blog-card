# Frontendmentor's challenge | Blog Card

## Tech used

Simple HTML, CSS and a pinch of JS.

## Challenges & Lessons learned

* Self-hosted fonts: Not a big challenge, but honestly, knowing about Google Fonts, I had never even thought about the possibility to host your own fonts. But since this challenge provided the font files, I decided to research and study this and learned about the pros and cons of each.

* Variable fonts: like the previous one, it's not a huge challenge, especially for this pretty simple use case, but knowing about the benefits of using a single file for the whole set of fonts and hosting it yourself instead of relying on some other third party seemed very enticing. And they're not that difficult to set up actually!

* Responsive font sizes: this was by far the biggest challenge. When I saw the challenge requesting to achieve responsiveness in the font size without media queries, I immediately thought if I am not using the viewport's width for the media query, I can use it directly for the font size (with smth like `vw`). Turns out there's a lot of implications on accessibility (and not only just about inclusion for those with impaired vision, but also about multiple use cases of resizing screen, etc.) that made this way more nuanced than expected. Had to research a bit. Great sources that I recommend: 
  * [Responsive Type and Zoom](https://adrianroselli.com/2019/12/responsive-type-and-zoom.html)
  * [Addressing Accessibility Concerns With Using Fluid Type](https://www.smashingmagazine.com/2023/11/addressing-accessibility-concerns-fluid-type/)
  * [CSS min, max, and clamp](https://web.dev/articles/min-max-clamp#:~:text=Note%3A%20When%20using%20a%20calculation,how%20to%20use%20these%20functions.)
  * [Kevin Powell's video on viewport units](https://www.youtube.com/watch?v=G1buM51f09s)
  And resources upon reading those and understanding the problems and solutions:
    * [Utopia](https://utopia.fyi/)
    * [Fluid Style](https://fluid.style/type?min=2.25&max=4.5&min-bp=20&max-bp=77.5&unit=%22rem%22)

Although those were the challenges, there were more mini-lessons learned like `underline` and `overline` together fancy thing (whatever that's called) and a couple more.