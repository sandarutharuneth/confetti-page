# Confetti Animation
<a href="https://imgur.com/Fxs9QXU"><img src="https://i.imgur.com/Fxs9QXU.png" title="source: imgur.com" /></a>

## Installation
### Step 1
```sh
Download confetti.js file
```

### Step 2
Link the `confetti.js` file to your `html` page
```html
<script src="confetti.js"></script>
```

### Step 3
Place this code inside `<body>`
```js
<script>
        const start = () => {
            setTimeout(function() {
                confetti.start()
            }, 1000); // 1000 is time that after 1 second start the confetti ( 1000 = 1 sec)
        };

        //  for stopping the confetti 

        const stop = () => {
            setTimeout(function() {
                confetti.stop()
            }, 30000); // 5000 is time that after 5 second stop the confetti ( 5000 = 5 sec)
        };
        start();
        stop();
</script>
```

### Step 4
All done! Preview the page now.
Should look like [this](https://confetti-preview.netlify.app)

<hr>

<h6 align="center">©️ Project Razer</h6>
