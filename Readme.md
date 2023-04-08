# My SNS
Easy to share your SNS
------------------------------
#### version : 0.1.1
#### preview : https://cistusf.github.io/My-SNS/

> How to use?  

edit `script.js`'s configuration

```typescript
const username = "Your name"; // Enter your name or nickname
const theme = "light"; // Enter theme name you want to use.
const profileSrc = "./userProfile.png"; 
/**
 * image url is allowed
 * if you want load your own profile image file from project.
 * edit profileSrc to const profileSrc = "./Yourfile.fileType";
*/
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

interface ThemeList {
    theme: string<"light","dark","blue","red","purple","dev">;
} 
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
