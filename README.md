# marketing-brand-colors
Color palettes for Brand Foundations


## Installation

<p>
To start using marketing-brand-colors you need to install it with the package manager npm or yarn.
</p>

```ts
// To install using npm
npm install marketing-brand-colors -s

// To install using yarn
yarn add marketing-brand-colors
```

## Getting started

<p>
First we need to import the library
</p>

```scss
// If you use node or any frameworks like react or vue
@import '~marketing-brand-colors';

// You can also import the file colors.scss directly, as follows
@import 'index.scss';
```

### Basic colors
<p>
For basic colors, marketing-brand-colors provides a set of variable names, which can be used directly.
</p>

```scss
@import '~marketing-brand-colors';

.hero {
  background: $aloe;
}

.button {
   background: $mandarin;
   color: white;
}

.footer {
  background: $shopify-green;
  color: $off-white;
}
```

### Brand colors

<img width="808" alt="Screen Shot 2022-08-03 at 11 55 32 AM" src="https://user-images.githubusercontent.com/72214632/182654289-cd17ca75-5a75-41b6-9514-01f1abea8e48.png">


### Expressive colors

<img width="813" alt="Screen Shot 2022-08-03 at 12 27 23 PM" src="https://user-images.githubusercontent.com/72214632/182660571-8b9465df-7273-44da-a7ee-6e592bc7ce53.png">

### Functional colors

<img width="814" alt="Screen Shot 2022-08-03 at 12 28 11 PM" src="https://user-images.githubusercontent.com/72214632/182660657-f48e7bed-6b8e-4939-a35a-396c426cd681.png">

### Expanded color palette

<p>
For colors with shades, marketing-brand-colors provides a function that takes two parameters, the first one is the name of the palette, and the second is the value of the saturation.
</p>

```scss
@import '~marketing-brand-colors';

.hero {
   // First parameter receives the name of the color palette, and the second parameter requires the value of saturation
   // usage: get-color(color_palette, color_saturation)
   background: get-color(currant-palette, 10);
}
.button {
   background: $mandarin;
   color: white;
   border: 1px solid color(mandarin-palette, 70);
}
```

```scss
// usage: get-color(color_palette, color_saturation)
.circle {
   background: get-color(shopify-green-palette, 50);
}

.square {
   background: get-color(lime-palette, 30);
}

.triangle {
   background: get-color(pistachio-palette, 30);
}

```

<img width="817" alt="Screen Shot 2022-08-03 at 12 54 00 PM" src="https://user-images.githubusercontent.com/72214632/182665437-699f8250-17bd-4b37-a8b9-23d4d97c91d9.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 54 26 PM" src="https://user-images.githubusercontent.com/72214632/182665517-eaf2c57d-a67d-4132-ba57-de341da43d3c.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 54 46 PM" src="https://user-images.githubusercontent.com/72214632/182665581-02066c34-27b4-4906-83bd-43ff9c57db99.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 55 18 PM" src="https://user-images.githubusercontent.com/72214632/182665676-2a7d9785-5eb8-4111-8fa6-0b2d8a6c9830.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 55 47 PM" src="https://user-images.githubusercontent.com/72214632/182665775-f2ded156-d78b-402e-aec9-2f327037c76d.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 56 09 PM" src="https://user-images.githubusercontent.com/72214632/182665841-3fd066b8-348b-4ecf-9c29-4f1ff61f6aa8.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 56 34 PM" src="https://user-images.githubusercontent.com/72214632/182665932-b1ba62ee-3bab-4372-bac0-7f971ac60669.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 56 59 PM" src="https://user-images.githubusercontent.com/72214632/182666011-91fa8aef-4bd3-469a-a7af-603371c0a55f.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 57 38 PM" src="https://user-images.githubusercontent.com/72214632/182666138-2f72f05c-e546-4312-85db-977dfe544e57.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 58 27 PM" src="https://user-images.githubusercontent.com/72214632/182666276-4e929caf-49f3-4fb5-b002-c6367402314d.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 58 46 PM" src="https://user-images.githubusercontent.com/72214632/182666333-c20717fc-4c7e-4b34-850b-dd401ab99bf1.png">

<img width="817" alt="Screen Shot 2022-08-03 at 12 59 02 PM" src="https://user-images.githubusercontent.com/72214632/182666377-cae38060-a394-45b6-b81a-2fc69021bdd2.png">
<img width="817" alt="Screen Shot 2022-08-03 at 12 59 19 PM" src="https://user-images.githubusercontent.com/72214632/182666421-1f452c1d-3509-4cf3-a246-0c776bae1063.png">
