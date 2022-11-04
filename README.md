# John-Leamy's Portfolio
[John Leamy's Portfolio](https://jwleamy.github.io/JWL-Portfolio/)

## Webpage Picture
![Image of my portfolio webpage](./assets/images/Portfolio%20Webpic.png)

## Description
The purpose of this repository was to create a portfolio that can store my future web-development projects. This portfolio will act as an open gallery for future employers to view my work, my resume, and find my contact information if needed. 

## Technologies Used
1. HTML - used to create and structure the given webpage
2. CSS - used to modify the presentation and style of the given webpage
3. Git - used to clone down the original code prior to making modifications
4. Github - used to create this repository, modify and eventually commit each change made, and ultimately deploy the fully edited webpage. 

## Code Snippet
```html
<body>
    <header>
        <h1>John W. Leamy</h1>
        <ul>
            <li>
                <a href="#ab">About Me</a>
            </li>
            <li>
                <a href="#w">Work</a>
            </li>
            <li>
                <a href="#c">Contact Me</a>
            </li>
            <li>
                <a href="">Resume</a>
            </li>
        </ul>
    </header>

    <Main>
        <section class="intro">
            <div></div>
            <section class ="ab" id="ab">
                <h2>About Me</h2>
                <p>Eventually, I will have this section to describe who I am, 
                what my background is, and the purpose and meaning behind 
                all of the following code projects. When I actually have projects to link, I will attach
                them in the squares below. Until then, I am using placeholder images. 
                </p>
            </section>
        </section>


        <section class="works" id="w">
            <h2>Works</h2>
            <section class="c">
                <section class="big">
                    <h2>
                        <a href="https://www.w3schools.com/" target="_blank">Work 1</a>
                    </h2>
                </section>
                <section class="card" id="one">
                    <h2>
                        <a href="https://newcp.net/en/" target="_blank">Work 2</a>
                    </h2>
                </section>
                <section class="card" id="two">
                    <h2>
                        <a href="https://www.poptropica.com/" target="_blank">Work 3</a>
                    </h2>
                </section>
                <section class="card" id="three">
                    <h2>
                        <a href="https://www.warnerbros.com/movies/lord-rings-fellowship-ring" target="_blank">Work 4</a>
                    </h2>
                </section>
                <section class="card" id="four">
                    <h2>
```
## Code Snippet CSS
```
:root {
    --primary: beige;
    --secondary: lightblue;
    --main:aliceblue;
    --borderstyle: 5px solid gray;
    --titlebackground: lightgray;
}

body {
    display: inline-block;
    background-color: var(--main);
}


header {
    display: flex;
    background-color: var(--primary);
    justify-content: space-between;
    width: 100%;
}

header h1 {
    margin-left: 10px;
}

header ul {
    display: flex;
    list-style: none;
    align-items: center;
}

header ul li {
    justify-content: space-around;
    margin-right: 25px;
    font-size: larger;
}

main {
    display: flex;
    flex-direction: column;
    column-width: auto;
}

.intro {
    display: flex;
    flex-direction: row;
    justify-content: space-evenly;
    align-items: center;
    margin: 15px;
    margin-right: 50px;
    background-color: var(--secondary);
    border-radius: 30px;
    
}

.intro div {
    content: url('../images/T03SVAX0QSD-U043Q33P1EU-9762b0499c2b-512.jpg');
    height: 250px;
    width: 250px;
    margin: 3%;
    border: var(--borderstyle);
    border-radius: 80px;
}
.ab {
    display: flex;
    width: 40%;
    align-items: center;
    background-color: var(--primary);
    padding: 10px;
    border: var(--borderstyle);
    border-radius: 20px;
}

.ab h2 {
    padding-right:30px;
    border-right: 3px solid navy;
    height: 130px;
    display: flex;
    align-items: center;
}
.ab p {
    display: flex;
    align-items: center;
    margin-left: 30px;
    height: 70%;
}

.works {
    margin: auto;
    display: inline-flex;
    padding: 10px;
    background-color: var(--primary);
    border: var(--borderstyle);
    border-radius: 40px;
}

.works h2 {
    padding-right: 30px;
    padding-left: 30px;
    display: flex;
    align-items: center;
}
```
