---
# id: my-home-doc
slug: /
sidebar_position: 1
---

# Softprime Cosulting ERP Introduction

this is the introduction of our ERP system Modules that we will be using in our projects and we will be adding more modules as we go.

## How to create a new Doc?

- Create a new file in the `docs` folder.
- Add the following snippet to the top of the file:

```md
---
id: my-home-doc ## this is the id of the doc
slug: /
sidebar_position: this is the position of the doc in the sidebar
---
```

and then you can start writing your doc. if you want to add images to your doc, you can add them to the `docs/img` folder and then use them in your doc like this:

```Text
![image title](./img/image_name.png)
```

inside the `![]` you can add the title of the image, and inside the () you can add the path of the image.

## how to run the docs locally?

to run the docs locally, you need to install the dependencies first:

MacOS:

```Zsh
brew install node
```

Windows:

```Powershell
choco install nodejs
```

or you can download it from [Nodejs.org](https://nodejs.org/en/download/)

Linux:

```bash
sudo apt install nodejs
```

you can use the following command to start the docs locally:

by using `yarn`:

```terminal
yarn start
```

by using `npm`:

```terminal
npm run start
```
