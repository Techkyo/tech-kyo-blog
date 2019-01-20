
# Tech-Kyo Blog

## Working and living as developers in Tokyo

This is the source code for our blog. It was bootstrapped with [gatsby-starter-blog](https://github.com/gatsbyjs/gatsby-starter-blog).

## 🚀 How to

1.  **Install Gatsby CLI.**

    We recommend using Yarn and Node v. 10.15.0 for this project.

    ```sh
    # Install Gatsby CLI globally
    yarn global add gatsby-cli
    ```

1.  **Clone the project.**

    ```sh
    git clone https://github.com/Techkyo/tech-kyo-blog.git
    ```
    
1.  **Run it locally.**

    ```sh
    cd tech-kyo-blog
    gatsby develop
    ```
    
1.  **Open the source code and start editing!**

    The blog is now running at `http://localhost:8000`!

    _Note: You'll also see a second link: _`http://localhost:8000/___graphql`_. This is a tool you can use to experiment with querying your data. Learn more about using this tool in the [Gatsby tutorial](https://www.gatsbyjs.org/tutorial/part-five/#introducing-graphiql)._

    Open the `tech-kyo-blog` directory in your code editor of choice. Everything that can and should be edited is in the `src/` folder.
    All the changes in the `src/` folder will be reflected automatically in the browser. Changes in the `gatsby-***.js` files require a restart (ctrl + c, gatsby develop)
   
   
## What's inside?

A quick look at the top-level files and directories you'll see in this project.

    .
    ├── content
    ├── node_modules
    ├── src
    ├── static
    ├── .gitignore
    ├── .prettierrc
    ├── .eslintrc.js
    ├── .travis.yml
    ├── gatsby-browser.js
    ├── gatsby-config.js
    ├── gatsby-node.js
    ├── LICENSE
    ├── yarn-lock.json
    ├── package.json
    └── README.md
    
1.  **`/content`**: This folder holds assets (mainly images) and the markup files used as blog posts.

2.  **`/node_modules`**: This directory contains all of the modules of code that your project depends on (npm packages) are automatically installed.

3.  **`/src`**: This directory will contain all of the code related to what you will see on the front-end of your site (what you see in the browser) such as your site header or a page template. `src` is a convention for “source code”. More below.

4.  **`/static`**: This folder holds static assets. Read more about it here [Static folder](https://www.gatsbyjs.org/docs/static-folder/).

5.  **`.gitignore`**: This file tells git which files it should not track / not maintain a version history for.

6.  **`.prettierrc`**: This is a configuration file for [Prettier](https://prettier.io/). Prettier is a tool to help keep the formatting of your code consistent.

7.  **`.eslintrc.js`**: This is a configuration file for eslint.

8.  **`.travis.yml`**: This is a configuration file for Travis.

9. **`gatsby-browser.js`**: This file is where Gatsby expects to find any usage of the [Gatsby browser APIs](https://www.gatsbyjs.org/docs/browser-apis/) (if any). These allow customization/extension of default Gatsby settings affecting the browser.

10.  **`gatsby-config.js`**: This is the main configuration file for a Gatsby site. This is where you can specify information about your site (metadata) like the site title and description, which Gatsby plugins you’d like to include, etc. (Check out the [config docs](https://www.gatsbyjs.org/docs/gatsby-config/) for more detail).

11.  **`gatsby-node.js`**: This file is where Gatsby expects to find any usage of the [Gatsby Node APIs](https://www.gatsbyjs.org/docs/node-apis/) (if any). These allow customization/extension of default Gatsby settings affecting pieces of the site build process.

12.  **`LICENSE`**: Gatsby is licensed under the MIT license.

13. **`yarn-lock.json`** (See `package.json` below, first). This is an automatically generated file based on the exact versions of your npm dependencies that were installed for your project. **(You won’t change this file directly).**

14. **`package.json`**: A manifest file for Node.js projects, which includes things like metadata (the project’s name, author, etc). This manifest is how npm knows which packages to install for your project.

15. **`README.md`**: A text file containing useful reference information about your project.

## Source Folder Structure
- **components**: It holds reusable components.
- **pages**: Each one of the files in this folder becomes an actual page.
- **templates**: This folder holds templates, files that will be transformed in pages at runtime. The data of those pages is in the md files in in content/blog/**/.
- **utils**: This folder is for pretty much everything else.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.org/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.org/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.org/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.
