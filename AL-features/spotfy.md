# Spotify Feature on your Anilist by Chris (SaikoKurami)
*Warning: This will replace on your Genres section.*
<br><br><img width="500px" src="https://i.imgur.com/SN7R6Q3.png"></br></br>
**Instruction**
1.  Go to this **[spotify-github-profile site](https://spotify-github-profile.vercel.app/api/login)** to grant permission to get your markdown code of your Spotify.
2. Choose theme **nateemo-re** and select your bar color that you want.
3. Then copy the url, not the whole mark down but only the code that I underlined on the image bellow.
<br><br><img width="450px" src="https://i.imgur.com/9Jcww7z.png"></br></br>
4. After copying the url, paste it on **--spotfy-url-profile** and just add the color that you want on the theme, change the font size of the title or the border length.
```css
@import url("https://saikokurami.github.io/css/spotfy.css");

:root{
    --spotfy-url-profile: url('');
    --spotfy-bacground-color: rgb('');
    --spotfy-logo-color: rgb('');
    --spotfy-border: 2px solid rgb('');
    --spotfy-font-title: 1.4rem; /*don't change the font size if you have the same as the original*/
}
```
5. This is a **sample** on how it looks like when it's completely filled out.🙀
```css
@import url("https://saikokurami.github.io/css/spotfy.css");

:root{
    --spotfy-url-profile: url(https://spotify-github-profile.vercel.app/api/view?uid=5aez4z9lwf4gdfda53jag&cover_image=true&theme=natemoo-re&bar_color=73becb&bar_color_cover=false);
    --spotfy-bacground-color: rgb(45, 45, 45);
    --spotfy-logo-color: rgb(254, 121, 0);
    --spotfy-border: 2px solid rgb(254 121 0);
    --spotfy-font-title: 1.4rem;
}
```
6. Now you're done! all you have to do is copy and paste on your **custom CSS**.
I hope you like it! ✨


