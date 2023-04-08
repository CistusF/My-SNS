# My SNS
Easy to share your SNS
------------------------------
<<<<<<< HEAD
#### version : 0.1.0
=======
#### version : 0.2.0
>>>>>>> parent of 046a3ba (Edit Readme.md)
#### preview : https://cistusf.github.io/My-SNS/

> How to use?  

edit `config.js`'s configuration

```typescript
const username = "Your name"; // Enter your name or nickname
const SNS_List = [
    {
        link: "https://instagram.com/cistusf",
        type: "instagram",
        alt: "My public IG"
    },
    {
        link: "https://youtube.com/@cistusf",
        type: "youtube"
    }
]; // Add your SNS list

interface SNS_List {
    link: string;
    type: SNS_ListType;
    alt?: string;
}[]; // SNS List type
```
And Enable GitHub Pages for main branch.

> Support SNS list

* Discord
* GitHub
* Youtube
* Facebook
* Instagram
* Twitter
* Steam
* Tik Tok

> License

[Font Awesome](https://fontawesome.com/license)