<h1 align="center">
  Gatsby + API Platform
</h1>


## 🚀 Quick start

1.  **Create a Gatsby site.**

    Use the Gatsby CLI ([install instructions](https://www.gatsbyjs.com/docs/tutorial/part-0/#gatsby-cli)) to create a new site, specifying the hello-world starter.

    ```shell
    # create a new Gatsby site using the hello-world starter
    gatsby new my-app https://github.com/Enrico724/gatsby-api-platform-starter
    ```

1.  **Start developing.**

    Before starting, open the `/public/api/index.php`, and rewrite the autoloder into `require_once dirname(__DIR__).'/../api-platform/vendor/autoload_runtime.php';`

    Navigate into your new site’s directory and start it up.

    ```shell
    cd my-app/
    npm run develop
    ```

1.  **Open the source code and start editing!**

    Gatsby is now running at `http://localhost:8000`!
    
    Symfony is now running at `http://localhost:4000`!

    The source code is under the src Directory

## 🧐 What's inside?

A quick look at the top-level files and directories you'll see in a Gatsby project.

    .
    ├── bin
    ├── config
    ├── node_modules
    ├── public
    ├── src
    ├── static
    ├── var
    ├── vendor
    ├── .env
    ├── .gitignore
    ├── .prettierrc
    ├── composer.json
    ├── composer.lock
    ├── gatsby-config.js
    ├── LICENSE
    ├── package-lock.json
    ├── package.json
    ├── symfony.lock
    └── README.md

## 🛠 Build

This starter has been built in order to port your app in any enviroment using less devops possible. Once you have run `npm run build`, your app will be available inside build directory. public will be places as your public_html folder, and my-app folder will we placed in the root folder.

The only manual operation you have to do is opening the 'public/api/index.php' and edit the require file in order to it links you app souce code. This has to be done in order to make api-platform working.

## 🎓 Learning Gatsby

Looking for more guidance? Full documentation for Gatsby lives [on the website](https://www.gatsbyjs.com/). Here are some places to start:

- **For most developers, we recommend starting with our [in-depth tutorial for creating a site with Gatsby](https://www.gatsbyjs.com/tutorial/).** It starts with zero assumptions about your level of ability and walks through every step of the process.

- **To dive straight into code samples, head [to our documentation](https://www.gatsbyjs.com/docs/).** In particular, check out the _Guides_, _API Reference_, and _Advanced Tutorials_ sections in the sidebar.

#

[!["Buy Me A Coffee"](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/Enrico724)