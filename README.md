<p align="center">
  <img src="https://user-images.githubusercontent.com/1863771/40743021-f8bcbbd2-646d-11e8-9301-2f24552ff763.gif"/>
  <br><br>
  <b>A Card component with good vibes</b>
  <br><br>
</p>

&nbsp;

`card-vibes` is a beautiful card component that moves with grace on hover. [Here's a demo on codesandbox](https://codesandbox.io/s/j1wkozzmv3)

&nbsp;

#### install

```
npm install card-vibes
```

&nbsp;

#### usage

```jsx
import React from 'react'
import Card from 'card-vibes'

<Card>
  You can put whatever you want inside the card
  and it will look dope
</Card>
```

![dope](https://user-images.githubusercontent.com/1863771/40743011-f2b20666-646d-11e8-9403-25d5710abf2f.gif)

&nbsp;

#### custom styles

card-vibes does come with it's own styles that give it such good vibes, you can overwrite them by adding your own `className` or `styles` tag

```jsx
import React from 'react'
import Card from 'card-vibes'

<Card styles={{ width: '600px', padding: '20px' }}>
  You can put whatever you want inside the card
  and it will look dope
</Card>
```

&nbsp;

#### kudos to @micku7zu and @gijsroge

This is a React wrapper with modified code (to lock config and add shadows) based on [vanilla-tilt](https://github.com/micku7zu/vanilla-tilt.js) by [@micku7zu](https://github.com/micku7zu)

&nbsp;

#### like it?

:star: this repo

&nbsp;

#### license

MIT © [siddharthkp](https://github.com/siddharthkp)
