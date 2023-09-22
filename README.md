# Sustain-the-groove
    Refactor Code

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://developer.mozilla.org/en-US/docs/Web/HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/CSS](https://developer.mozilla.org/en-US/docs/Web/CSS)      |   
| Git | [https://git-scm.com/](https://git-scm.com/)     |    

## Description 

[Visit the Deployed Site](https://abenedetti27.github.io/sustain-the-groove/)


The existing HTML for this website did not meet accessibilty standards, consisted of bugs, and did not have an appropriate title for an online business specializing in digital marketing. The following refactoring was applied:

In order to meet accessibility standards, semtantic elements replaced <div> where possible. This included the header, nav, main, aside, and footer. Additionally, alt image descriptions were added. A simple title of "Horiseon" was applied in place of "website. A closing image tag was removed. Comments were applied in-line for all refactoring.

The existing CSS for this website contained styling for the <div> elements that were refactored to semantic elements. Therefore, the corresponding styling components were also updated appropriately. Additionally, all class elements that contained the same styling components were combined to shorten the overall length of the overall CSS for ease of reading. Comments were applied in-line for all refactoring.

## Code Refactor Example

Below are examples of the HTML where non-semantic elements were crefactored to make this website more assessible using the step previously stated. 


```html
  <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
            <ul>
                <li>
                    <a href="#search-engine-optimization">Search Engine Optimization</a>
                </li>
                <li>
                    <a href="#online-reputation-management">Online Reputation Management</a>
                </li>
                <li>
                    <a href="#social-media-marketing">Social Media Marketing</a>
                </li>
            </ul>
        </nav>
    </header>
```


```html
<footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2023 Horiseon Social Solution Services, Inc.
        </p>
    </footer>

```

Below are examples of the CSS updates that were made as a result of the HTML refactoring to keep the overall styling and look of the website.

```css
aside {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}
.benefit-lead, .benefit-brand, .benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}    
```
## License

MIT License

Copyright (c) [2023] [Anna Rose Benedetti]


---