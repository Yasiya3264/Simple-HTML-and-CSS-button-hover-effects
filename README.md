# Main Changes
Don't use my values for your website body tages. I used this for align my items to middle. If you are try to learn this you can use this body tag properties.
```
body{
    margin: 0;
    padding: 0;
    padding-top: 35vh;
    background-color: white;
    font-size: 20px;
    display: grid;
    place-items: center;
}
```
# Root Colors
Change ```--``` names like ```--name``` replace to ```name``` to what you like ```--borde | --footer | --text | --text-hover```.
Change colors what you like. You can use `Hex color` code and ``rgba colors`` or ``color names``.
```
:root{
    --main: green;
    --hover: white;
    --text: white;
    --text-hover: black;
    --border: green;
    --border-hover: black;
}
```

# More example for color codes
```
:root{
    --green: green; /* Green color name */
    --green: #00FF00; /* Green color hex color codes */
    --green: rgb(0,128,0); /* Green color RGBA color code */
}
```

# other changes

change transition values `transition: 1s;` you can use `seconds(s)` or `milliseconds(ms)`. If you are using milliseconds(ms) `1000ms = 1s`.
