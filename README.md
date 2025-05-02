# Frontend-CSS

 This HTML and CSS web project is for Cuddles Petting Zoo. It allows users to navigate via a menu, and features responsive design of tables and forms using grid layout. This project demonstrates collapsible tables, navigation bar, and semantic HTML.

## Live Demo URL

Check out the web page [Frontend-with-CSS] (https://nubilaxl.github.io/Frontend-CSS/) 

## Technologies used


* CSS
* HTML

## Favorite Features

### Semantic HTML
* It was a challenge to place all elements into the semantic tags. Research was necessary to make sure of following best practice. The site was uploaded and validated on the W3C web site.
### Layout of page with grid
* Keeping all pages responsive at the various screen sizes was challenging. A large table with photos embedded was formatted with grid-layout which caused the table to collapse at small screen sizes. The form was formatted conditionally at the various screen sizes to ensure the form maintained its appearance.

## Code Snippets

### Usage of semantic HTML
```HTML

    <main class="home-page">
        <article>

            <h2>Dolly's Story</h2>
            <!--"Sheep" by Dani Mettler is licensed under CC BY-SA 2.0.-->
            <img width=300 src="images/dorper-medium.jpg" alt="picture of a sheep">
            <p>
                Dolly comes to us from a grazing farm in New Zealand. She is a pure breed dorper.
                She was born in tragedy, when her mother passed away giving birth. The farm's 
                owner did not have the facilities for weaning and that is where we stepped in for
                the rescue.
            </p>
    <!--This section uses an unordered list preceded by level 2 header-->
            <section>
                <h2>We welcome you to stop by:</h2>
                <ul>
                    <li>Our pets are safe and people friendly</li>
                    <li>Bring the whole family</li>
                    <li>Cuddle up with a new pet friend!</li>
                </ul>
            </section>
        </article>

```

### Usage of CSS styles
```CSS
    table, td, th, thead {
        display:grid;
       grid-template-columns: repeat(1, 2fr) ;
       text-align: center;
        font-size: x-small;
    
    }
    td:nth-last-of-type(4){
        grid-row: span 4;
    }
    td > img {
        width: 100%;
        grid-column: span 4;
    }
      .home-page{
        margin: 3px auto 3px;
        display: grid;
        gap: 2rem;
        grid-template-columns: repeat(1, 1fr);

```
## Installation

The local environment require node packet manager, and http server
Check your system using command: npm -v 
If no version install from nodejs.org
Then install http server using command: npm install -g http-server

To make a local copy of of the code, clone the repository
```
git clone https://nubilaxl.github.io/Frontend-CSS/
cd Frontend-CSS
```

Then within the project directory start http-server
```
http-server
```

The server will show the localhost url to plug into your browser

## Contributions
Pull requests, feature requests, and bug reports are welcome. Please open an issue first so that we may discuss.

## License
[MIT](https://choosealicense.com/licenses/mit/)

## Contact Info
Email: nubila.levon@outlook.com 
LinkedIn:  https://www.linkedin.com/in/nubila-levon/ 