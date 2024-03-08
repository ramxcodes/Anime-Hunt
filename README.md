# Anime Hunt Website
Anime Hunt is a simple website showcasing popular anime and manga titles. It provides a clean and user-friendly interface to explore information about various series.
## Table of Contents
1. [Introduction](#introduction)
2. [Features](#features)
3. [Installation / Fork](#installation--fork)
4. [Star the GitHub Repo](#star-the-github-repo)
5. [Code of the Website](#code-of-the-website)

---

## Introduction

Anime Hunt is a simple website showcasing popular anime and manga titles. It provides a clean and user-friendly interface to explore information about various series.

<img src="https://drive.google.com/uc?export=view&id=1WV6P4dvyrlgvHhggvVvTkSs_j4R1kzNE" alt="Gojo Satoru Image" style="width: 100%; max-width: 600px; height: auto; margin: 20px 0;">
<a target="_blank" href="https://ramxcodes.github.io/Anime-Hunt/" target="_blank" style="display: inline-block; padding: 10px 20px; background-color: #3498db; color: #fff; text-decoration: none; border-radius: 5px; font-weight: bold; font-size: 16px; margin-bottom: 20px;">Visit Website ↗</a>


---

## Features

- **Navigation Menu:**
  - Easy-to-use navigation menu with quick access to different sections.
  - Weekly updates, best manga, anime news, and more.

- **Content Display:**
  - Display of popular anime titles with corresponding images.
  - Each title is presented in a visually appealing format.

- **Responsive Design:**
  - The website is designed to be responsive, providing a seamless experience across different devices.

---

## Installation / Fork

To set up the Anime Hunt website locally or fork it for your own modifications, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/anime-hunt.git
    ```

2. Open the `index.html` file in a web browser to view the website locally.

3. Customize the content, styles, or scripts according to your preferences.

4. Make sure to update the repository URL in the cloned version:
    ```bash
    git remote set-url origin https://github.com/your-username/anime-hunt.git
    ```

5. Push the changes to your GitHub repository:
    ```bash
    git push origin master
    ```

---

## Star the GitHub Repo

If you find the Anime Hunt website interesting or useful, consider starring the GitHub repository. Your support is highly appreciated!

---

## Code of the Website

Below is the HTML and CSS code that constitutes the Anime Hunt website. Feel free to explore and modify the code as needed.

### HTML (index.html)

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <link
    href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css"
    rel="stylesheet"
/>
    <title>Anime Hunt</title>
</head>
<body>
    <div id="main">
        <div id="nav">
            <div id="nav-part1">
                <div class="gola"></div>
                <div class="gola"></div>
            </div>
            <div id="nav-part2">
                <h4>JP<span> EN</span></h4>
                <h4>Weekly Update</h4>
                <h4>Best Manga</h4>
                <h4>Anime Hunt</h4>
                <h4>Anime News</h4>
                <h5><i class="ri-menu-4-line"></i></h5>
            </div>
        </div>
        <div id="nav2">
            <h3>News</h3>
            <h3>Upcoming</h3>
            <h3>Goodies</h3>
            <h3>Tiers</h3>
            <h3>Authors</h3>
            <h3>Swags</h3>
        </div>
        <div id="content">
            <div id="text-content">
                <div class="elem">
                    <h1>One Piece</h1>
                </div>
                <div class="elem">
                    <h1>Solo Leveling</h1>
                </div>
                <div class="elem">
                    <h1>Jujustu Kaisen</h1>
                </div>
                <div class="elem">
                    <h1>Attack on titan</h1>
                </div>
                <div class="elem">
                    <h1>Mashel OP</h1>
                </div>
                <div class="elem">
                    <h1>Dress up darling</h1>
                </div>
                <div class="elem">
                    <h1>Demon Slayer</h1>
                </div>
                <div class="elem">
                    <h1>Black Clover</h1>
                </div>
                <div class="elem">
                    <h1>Classroom of elite</h1>
                </div>
                <div class="elem">
                    <h1>Naruto</h1>
                </div>
            </div>
            <div id="image-content">
                <img src="https://c4.wallpaperflare.com/wallpaper/711/761/110/one-piece-kaido-one-piece-monkey-d-luffy-hd-wallpaper-preview.jpg" alt="">
                <img src="https://c4.wallpaperflare.com/wallpaper/8/911/690/solo-leveling-sung-jin-woo-hd-wallpaper-preview.jpg" alt="">
                <img src="https://c4.wallpaperflare.com/wallpaper/787/854/424/jujutsu-kaisen-satoru-gojo-anime-boys-anime-girls-hd-wallpaper-preview.jpg" alt="">
                <img src="https://cdn.mos.cms.futurecdn.net/UDh84pTx6fxiL3GNmG6nwh-650-80.jpg.webp" alt="">
                <img src="https://otakuusamagazine.com/wp-content/uploads/2023/07/mashle-season2.jpg" alt="">
                <img src="https://www.themarysue.com/wp-content/uploads/2022/11/my-dress-up-darling-.webp?w=1200&resize=1920%2C1004" alt="">
                <img src="https://www.dexerto.com/cdn-cgi/image/width=750,quality=75,format=auto/https://editors.dexerto.com/wp-content/uploads/2023/06/26/demon-slayer-hashira-training-arc.jpg" alt="">
                <img src="https://sm.ign.com/t/ign_in/screenshot/default/black-clover-m_u9bv.1280.jpg" alt="">
                <img src="https://fictionhorizon.com/wp-content/uploads/2022/08/CotE.jpg" alt="">
                <img src="https://wallpapers.com/images/featured/naruto-pictures-mlnh852tb7krwmzz.webp" alt="">
                
            </div>
        </div>
    </div>
</body>
</html>
```

### CSS (style.css)

```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'gilroy';
}

html,body{
    height: 100%;
    width: 100%;
    overflow: hidden;
}

#main{
    height: 100%;
    width: 100%;
    /* background: red; */
}

#nav{
    height: 80px;
    width: 100%;
    /* background-color: red; */
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 0 40px;
}

#nav-part1{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 2px;
}

#nav-part2{
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 40px;
}

#nav-part2 h4{
    font-size: 16px;
    font-weight: 600;
}

#nav h5{
    display: none;
}

#nav-part2 h4 span{
    color: blueviolet;
    margin-left: 10px;
}

.gola{
    height: 20px;
    width: 20px;
    background-color: black;
    border-radius: 50%;
}

#nav2{
    height: 70px;
    width: 100%;
    /* background-color: RED; */
    display: flex;
    align-items: center;
    gap: 60px;
    padding: 0px 30px;
}

#nav2 h3{
    font-size: 16px;
    text-transform: capitalize;
    font-weight: 700;
}

#content{
    height: calc(100% - 150px);
    width: 100%;
    /* background-color: aquamarine; */
}

#text-content{
    height: 40%;
    width: 100%;
    /* background-color: burlywood; */
    display: flex;
    flex-wrap: nowrap;
    overflow-x: auto;
}

#text-content::-webkit-scrollbar{
    background-color: transparent;
    height: 7px;
}

#text-content::-webkit-scrollbar-thumb{
    background-color: blueviolet;
}

.elem{
    flex-shrink: 0;
    height: 100%;
    width: 60%;
    /* background-color: red; */
    display: flex;
    align-items: center;
    justify-content: center;
}

.elem h1{
    font-size: 7vw;
    font-weight: 400;
}

#image-content{
    height: 60%;
    width: 100%;
    /* background-color: red; */
    display: flex;
    overflow-x: auto;
}

#image-content::-webkit-scrollbar{
    display: none;
}

#image-content img{
    flex-shrink: 0;
    height: 100%;
    width: 100%;
    object-fit: cover;
    object-position: center;
}

@media (max-width:600px) {

   
    #nav{
        height: 70px;
        padding: 0 20px;
    }
    
    #nav-part2{
        align-items: center;
        gap: 25px;
    }
    
    #nav-part2 h4{
        font-size: 13px;
        display: none;
        font-weight: 600;
    }

    #nav-part2 h4:nth-child(1){
        display: initial;
        margin-right: 20px;
    }
    
    #nav-part2 h4 span{
        color: blueviolet;
        margin-left: 10px;
    }
    
    .gola{
        height: 12px;
        width: 12px;
        background-color: black;
        border-radius: 50%;
    }

    #nav i{
        font-size: 20px;
    }
    
    #nav h5{
        display: initial;
    }

    #nav2{
        height: 70px;
        width: 100%;
        /* background-color: RED; */
        display: flex;
        align-items: center;
        justify-content: space-between;
        gap: 15px;
        padding: 0px 15px;
    }
    
    #nav2 h3{
        font-size: 2.8vw;
        text-transform: capitalize;
        font-weight: 500;
        color: #444;
    }
    
    #content{
        height: calc(100% - 140px);
        width: 100%;
        /* background-color: aquamarine; */
    }
    
    #text-content{
        height: 35%;
        width: 100%;
        /* background-color: burlywood; */
        display: flex;
        flex-wrap: nowrap;
        overflow-x: auto;
    }
    
    #text-content::-webkit-scrollbar{
        background-color: transparent;
        height: 5px;
    }
    
    #text-content::-webkit-scrollbar-thumb{
        background-color: blueviolet;
    }
    
    .elem{
        flex-shrink: 0;
        height: 100%;
        width: fit-content;
        margin-right: 30px;
        /* background-color: red; */
        display: flex;
        align-items: center;
        justify-content: center;
    }
    
    .elem h1{
        font-size: 15vw;
        white-space: nowrap;
        font-weight: 400;
    }
    
    #image-content{
        height: 65%;
        width: 100%;
        /* background-color: red; */
        display: flex;
        overflow-x: auto;
    }
    
    #image-content::-webkit-scrollbar{
        display: none;
    }
    
    #image-content img{
        flex-shrink: 0;
        height: 100%;
        width: 100%;
        object-fit: cover;
        object-position: center;
    }
    
}
```

---

Feel free to explore and customize the code to suit your preferences.

Made with ❤️ by [Ram](https://github.com/ramxcodes).
