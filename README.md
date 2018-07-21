## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [License](#license)

## Installation

``` bash
npm install carousel-vue
```

or if you prefer yarn

``` bash
yarn add carousel-vue
```

## Usage

Include the carousel directly into your component using import:

``` js
import { Carousel, CarouselItem } from 'carousel-vue';

export default {
  ...
  components: {
    Carousel,
    CarouselItem
  }
  ...
};
```

### Configuration
| Property                  | Type    | Default | Description                                                                                                                                                                                                                                                                           |
|:--------------------------|:--------|:--------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| visibleItem                    | Number  | 7    | visible item number                                                                                                                                                                                   |
| reduce                    | Number  | 10       | adjoin item reduce px  

### HTML Structure

Once the **Carousel** and **Slide** components are installed globally or imported, they can be used in templates in the following manner:

``` html
  <carousel>
    <carousel-item :index="0">
      item 1 Content
    </carousel-item>
    <carousel-item :index="1">
      item 2 Content
    </carousel-item>
  </carousel>
```

## Development

A sandboxed dev environment is provided by [vue-play](https://github.com/vue-play/vue-play). Changes made to the component files will appear in real time in the sandbox. 

To begin development, run:

``` bash
npm install 
npm run dev
```

or, if you prefer yarn

``` bash
yarn install 
yarn dev
```

then navigate to `http://localhost:8080`

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.