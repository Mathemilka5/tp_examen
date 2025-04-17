

### 1. Download `cecil.phar`
Download the `cecil.phar` file from the official [Cecil website](https://cecil.app).

### 2. Create a New Site
Run the following command to create a new site:
```shell
PS D:\LearnCecil> php cecil.phar new:site
```
## Configuration Prompts
Follow the prompts to configure your site:

* Title:

> Milka

* Description:

> This is my First site build with Cecil

* Base URL:

> http://localhost:8000

* Full Description:

> Learning platform using Markdown

* Author Name:

> Baraka

* Author URL:

> https://github.com/Baraka24

* Add Demo Content?:

> yes

Your new website is created in D:\LearnCecil.

### 3. Start the Server
Run the built-in server with:

```shell
PS D:\LearnCecil> php cecil.phar serve
```

Output
```shell
Building website...
Done 🎉
Starting server (http://localhost:8000)...
```
**Useful Commands**

* Preview your site: ```cecil.phar serve```
* Create a new page: ```cecil.phar new:page```

Visit Cecil documentation for further details [Cecil documentation](https://cecil.app/documentation/quick-start/).

Additionnally, you can build and deploy with [GitHub Actions](https://cecil.app/documentation/deploy/#continuous-build-hosting)

This demo site is live at: [first-cecil-project](https://baraka24.github.io/first-cecil-project/)
