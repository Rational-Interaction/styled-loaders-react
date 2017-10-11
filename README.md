# styled-loaders-react
Loaders for React built with Styled Components.

# Credits

This is React clone of @SaraVieira 's amazing [styled-loaders](https://github.com/SaraVieira/styled-loaders) which provides loaders for [Preact](https://preactjs.com/).

Huge thanks for all the hard work and letting me port it for React users.

Any new loaders that will be added in that original repository will be cloned here.

## Usage


```js
import React from 'react'
import { Cube } from 'styled-loaders-react'

const Page = ({ loading }) =>
    <div>
        { loading ?
            <Cube/>
            : 'Your Content'
        }
    </div>

```
### With Props

```js
import React from 'react'
import { Block } from 'styled-loaders-react'

const Page = ({ loading }) =>
    <div>
        { loading ?
            <Block color="red" size="60px" duration="5s" />
            : 'Your Content'
        }
    </div>

```

### Loaders

* Block
![Block](https://media.giphy.com/media/l378dJlRt7fvGHyfK/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px


* Circular
![Circular](https://media.giphy.com/media/l378y26cIAwgAVt4s/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * size - Size of the spinner default is 40px


* Cube
![Cube](https://media.giphy.com/media/3ov9jExQcWP6KTX1FS/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * size - Size of the spinner default is 40px
        * cubeSize - Size of the each cube default is 15
        * duration - Animation duration default is 1.2s


* CubeGrid
![CubeGrid](https://media.giphy.com/media/3ov9k9cASC7gCxpuLu/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * size - Size of the spinner default is 40px


* DotScale
![DotScale](https://media.giphy.com/media/l378c6525UOkzozVS/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px
        * dotSize - Size of the dots default is 18px


* Pulsate
![Pulsate](https://media.giphy.com/media/l378ar9YphdtfvkYg/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px


* RotateScale
![RotateScale](https://media.giphy.com/media/l378kTgu2VkGC8kyk/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px


* Scale
![Scale](https://media.giphy.com/media/l378mCuj3oh3HwMjm/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px


* Stretch
![Stretch](https://media.giphy.com/media/3ov9jHpaSIMfW0p19m/giphy.gif)
    * Props
        * color	- Background of the spinner default is #333
        * duration - Animation duration default is 1.2s
        * size - Size of the spinner default is 40px
        * rectWidth - Width of each rectangle default is 6px


## License

MIT