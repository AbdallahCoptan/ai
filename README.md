# Abdallah Ibrahim, PhD

My personal Page ... !

## Install

You should have a new git repo:
 - do it on github.com, then
 - clone it:
 ```sh
 git clone <your git repo directory>
 cd <your git repo directory>
```

Make sure that you have the Gatsby CLI program installed:

```sh
npm install --global gatsby-cli
```
And run from your CLI:

```sh
gatsby new <site-name> https://github.com/anubhavsrivastava/gatsby-starter-resume
```

Then you can run it by:

```sh
cd <site-name>
npm install
```

For starting the development:

```sh
gatsby develop
```

## Personalization & editing files

Edit `config.js` to put up your details

```javascript
module.exports = {
  siteTitle: 'Abdallah Ibrahim Resume', // <title>
  ...
  firstName: 'Abdallah',
  lastName: 'Ibrahim',
  // social
  socialLinks: [
    {
      icon: 'fa-github',
      name: 'Github',
      url: 'https://github.com/abdallahcoptan',
    }
    ...
  ],
};
```

## Push changes to the git
```sh
git push -u origin master
```

## Building your website

This will let your website is ready for publishing, to do so by:

```sh
gatsby build [or] npm run build
```

### Publishing on the github pages

In order to publish the website on the github pages:

```sh
npm run deploy
```

The final index.html file will be on a new branch named gh-pages and with this you can access the website by:

```
https://abdallahcoptan.github.io/<your git repo directory>
```



