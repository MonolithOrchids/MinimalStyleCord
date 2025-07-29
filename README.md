### Minimalist Theme for Discord
For now, this theme is very simplistic, it doesn’t change much, just the size of some bars, remove some useless stuff and that's it. It was mainly made for some friends and personal use, down the road I will try to add features included on my old theme, [MinimalNight](https://github.com/MonolithOrchids/MinimalNightTheme/tree/master).

### [**Vencord**](https://vencord.dev) or [**Vesktop**](https://github.com/Vencord/Vesktop):  
- ***Method 1***: 
	- Download [**MinimalNight.theme.css**](https://github.com/MonolithOrchids/MinimalStyleCord/blob/master/MinimalStyleCord.theme.css) and navigate to **Settings > Themes** and click **Open Themes Folder** or place the file in **%appdata%/Vencord/themes** and then enable **MinimalStyleCord**.    
- ***Method 2***: 
	- Navigate to **Settings > Themes** and go to **Online Themes** tab and in the input field paste in this URL:  
```https://monolithorchids.github.io/MinimalStyleCord/MinimalStyleCord.css```


Huge thanks and credits to [Nakki](https://instagram.com/nak.kiwi) from [UnShittify Discord](https://github.com/MaiRiosIPla/unshittify-discord) for the following imports:
```css
@import url("https://mairiosipla.github.io/unshittify-discord/UnShittifySource.theme.css");
```
```css 
@import url("https://mairiosipla.github.io/unshittify-discord/RoundIconsSource.theme.css");
```
## Recommended
Change **UI Density** at Appearance Settings to Compact.

Also, as optional, you can also change some of the sizes like it's showed below:
<img src="https://i.imgur.com/zSHQs2j.png" width=50% height=50%>

# Customizing the theme

MinimalNight has certain unique variables that can easily be modified to change the visibility and width of certain elements. The code can either be added to the **MinimalStyleCord.theme.css** or the **Custom CSS** menu in Discord settings:

```css
:root {
    --Reaction-Forward-Message-Hover: flex;		/* flex = ON, none = OFF */
}
```
