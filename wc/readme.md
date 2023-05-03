# Web Components
April 29, 2023 DKh

The **Web Components** (aka `WC`) is the fundamental technology for modern UI architecture.
We are going to **not use React, Vue, Angular** and other component-based technologies which are all artificial, instead we will build modern ui using Web Components (WCs) which are now inbuilt into all modern browsers. 

The benefits that WC provide are:

- Native browser support across since 2019
- Stable technology to stay around for 10s of years (a kin to Java Script)
- Work faster than React/Vue etc..
- Encapsulate complex sub-trees of markup (e.g. dialog box) via shadow DOM.
- Encapsulate markup even in developer tools view - make DOM easier to reason about 
- Build our applications against LOGICAL components that we own, not CSS or "divs" which are lower level primitives

Cons/limits:
- Requires Java Script - does not work with JS turned off
- No Server-side rendering (same as above)


Simple explanation, compare the two listings:
```html
 <div id="divToastFileSaved" class="middle center top info ok">
    <div class="shadow box white 2col">
        <div class="icon info greener">
            <span>Your file was saved successfully!</span>
        </div>
        <div class="close button right top"> X </div>
    </div>
 </div>

Versus Web component:

 <toast id="toastFileSaved" icon=info place=top>
    Your file was saved successfully!
 </toast>
```


## Fx for Web Components

### Lit
Stats:

tbd...

### Stencil
Stats:

tbd...


## Questions TBD
- Nesting WCs in shadow dom
- Styling v2020 https://css-tricks.com/styling-a-web-component/
- Styling Global V2022 https://www.matuzo.at/blog/2022/100daysof-day10/
- Styling V2022 https://javascript.works-hub.com/learn/web-components-api-how-yo-style-web-components-9d6a7
- Styling, Lit vs Stencil V2020 https://whoisryosuke.com/blog/2020/creating-a-design-system-using-web-components/