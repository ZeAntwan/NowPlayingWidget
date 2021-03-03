# NowPlayingWidget
 An animated stream widget to display the current playing track
![Screenshot](screenshot.png)

## Requirement
- Tuna

## How to use
- In Tuna, activate "Host/receive information on local webserver with port"
- Set the port to "1608"

## Customization
If you are savy or better at HTML, JS and CSS than me, feel free to change the file to your liking.

Otherwise, here are some "easy" parameters you cas set in the "Custom CSS" section of the Browser Source :

```css
html {
    font-family: 'XXX'; /* Replace with any font of your choice  */
    color: white; /* Set the base color for all texts */
}

#musicbg {
    fill : white; /* This set the rotating disc color */
}

#track {
    color: inherit; /* Set the "Track" text color */
}
#album {
    color: inherit; /* Set the "Track" text color */
}
#artist {
    color: inherit; /* Set the "Track" text color */
}
```