# Sass Tutorial Full Course

- This repo has a contents what I learned about Sass.

- The main instructor, who is offered to this lecture course, is the CoderCoder (Youtuber)

- If you want to follow her lecture course, please visit her lecture video (https://youtu.be/jfMHA8SqUL4)


## Compiling Sass with VS Code extensions

### Initial file structure

- At the beginning of this lecture, you should set file structure like below.

```
responsive-design-beginners
	ㄴ app
	|	ㄴ js
	|	ㄴ scss
	|		ㄴ style.scss
	ㄴ .gitattributes
	ㄴ index.html
	ㄴ LICENSE 
```

### Step 1. Install "live sass compiler" extension, which is made by "Glenn Marks"


### Step 2. Adding setting code in "open setting"

\[Notice\] All about the below explations are based on Window OS User

- Press "Ctrl + Shift + P"

- Click on "Preferences: Open User Settings (JSON)"

- Add these code lines at the end of the your settings

```JSON
"liveSassCompile.settings.formats": [
    {
      "format": "compressed",
      "extensionName": ".css",
      "savePath": "/dist",
      "savePathReplacementPairs": null
    }
  ]
```

- Save "settings.json" file and close it

### Step 3. Install "Live Server" extension, which is made by "Ritwick Dey"


### Step 4. Check these extensions installed well

- Click on "index.html"

- If you can see the "Watch Sass" and "Go Live" words on the bottom bar of the VS Code, then these extensions are installed well.

- If you're not, press "Ctrl + Shift + P" and type "reload window" on setting input

- After reloading VS Code, looking for "Watch Sass" and "Go Live" on the bottom bar of VS Code in your "index.html" file

### Step 5. Valifying Sass Compiler

- After click on "Watch Sass", you can see that the "dist" folder was generated.

- To make it sure, type or paste below code on "style.scss"

```scss
// This code is temporary testing code.
// It could be replaced whatever you want!
body {
  font-family: Arial, Helvetica, sans-serif;
  background-color: hsl(0, 0%, 26%);
  color: hsl(0, 0%, 100%);
}

```

- Click on your "style.css" file in "dist" folder

- If the code in "style.css" equals to the code in "style.scss", then it works well!

### Step 6. Go live

- Open "index.html" file in VS Code

- Click the "Go Live" button on the bottom bar of VS Code

- Automatically opened your browser and you can see the web page what you type on "index.html"

-----------

