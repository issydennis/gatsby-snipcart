
<h1 align="center">
  Gatsby and Snipcart e-commerce starter
</h1>

Create a simple and effective e-commerce shop using this starter.   
This starter uses Snipcart to create an easy-to-use shopping cart for an e-commerce site. Use this as a boilerplate to create your own Snipcart powered Gatsby shop!

For a walkthrough and tutorial using this starter see my [blog](https://www.frontendstumbles.com/gatsby-and-snipcart-ecommerce-tutorial/).

---
## 🚀 Quick start

1.  **Create a Gatsby site using the starter.**

    Use the Gatsby CLI to create a new site, specifying the snipcart starter.

    ```sh
    # create a new Gatsby site using the snipcart starter
    gatsby new my-shop-starter https://github.com/gatsbyjs/gatsby-starter-blog
    ```  

1. **Create a Snipcart account.**

    Go to [snipcart.com](https://snipcart.com/) and make an account. When using the test environment in Snipcart, everything is free and fake transactions can be made to test all aspects of your shop.
    You will be able to access a test public API from your dashboard. This will be needed in the `gatsby-config.js` file.  

1.  **Open up the source files using a code editor.**

    Navigate into your new site’s directory, install, and start it up.

    ```sh
    cd my-blog-starter/
    npm install
    gatsby develop
    ```  

1.  **Add your own Snipcart data!**

    Your site is now running at `http://localhost:8000`!

    Open the `my-shop-starter` directory in your code editor of choice and edit `gatsby-config.js` to change the API key to your own public test API key (you can find this in your Snipcart account).


---
## 🔍 What does it use?

This starter uses the following major packages to make it easy to use:

- **Snipcart**  
  Snipcart provides an out-of-the-box shopping cart and checkout for e-commerce websites and works brilliantly with static sites. Some comments have been added to the files in this starter to provide some information and explanation. See the [Snipcart documentation](https://docs.snipcart.com/) for extra guidance.
- **Styled Components**  
  SC is used in this project. Components are styled at the top of each component file. A basic theme is used for colours and a global style component is used to apply a reset. See the [Styled Components documentation](https://www.styled-components.com/docs) if you're unsure how to use this. Alternatively, you can remove all references to styled-components and use your own method of applying styles and css.

---
## 📁 Important files

  There are a few important files to take note of:
  
  - `src/pages/index.js`  
    This file is the homepage of your shop. 

  - `src/templates/item.js`  
    This file is the template used for the programmatically generated item pages in your shop.

  - `src/components/layout.js`  
    This file provides a basic layout to all the pages of your shop.

  - `src/styles/theme.js`  
    This file is used by the styled-components package to provide a theme to the entire site. It contains three colours that are used throughout the site. To easily change the color scheme, you can change the colours in this file.

  - `src/styles/globalStyle.js`  
    This file is used by the styled-components package to reset styles and provide some basic global styling to your shop via the layout  file described above.

  - `content/items`  
    This **folder** contains all the markdown files representing items in your shop. Each item consists of a folder containing a markdown file (`index.md`) and an image. Edit or create more of these with the same markdown structure to change/add items to the shop.

---
## 💫 Deploy

[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/issydennis/gatsby-snipcart)

