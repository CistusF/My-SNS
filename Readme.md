<h1><img width="50" src="./icon.png" alt="icon" align="center" />My SNS</h1>
<h3>Easy to share your SNS</h3>
<h5>version : 0.2.3</h5>
<h5>preview : <a href="https://cistusf.github.io/My-SNS/">My-SNS</a></h5>

> How to use?  

edit `config.js`'s configuration

```typescript
const username = "Your name"; // Enter your name or nickname
const theme = "light"; // Enter theme name you want to use.
const profileSrc = "./userProfile.png"; 
/**
 * image url is allowed
 * if you want load your own profile image file from project.
 * edit profileSrc to const profileSrc = "./Yourfile.fileType";
*/
var SNS_List = [
    {
        link: "https://instagram.com/cistusf",
        type: "instagram",
        bio: "My public IG"
    },
    {
        link: "https://youtube.com/@cistusf",
        type: "youtube"
    },
    {
        link: "https://cistusf.vercel.app",
        bio: "My Portfolio"
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
