# react-flag-svg

Simple react component with country or country state flag.
Now supporting all country flag, USA, Canada, Germany, Brazil, Australia state flag

### Usage

```bash
npm install react-flag-svg
```

```jsx
import React from 'react';
import Flag from 'react-flag-svg';

// Render image with flag
<Flag
  isoCode="us-tx"
  className="some-class"
  alt="alternative text for image"
/>;
```

### Props

| Prop        | Description                                                                                                                                         | Default      |
| ----------- | --------------------------------------------------------------------------------------------------------------------------------------------------- | ------------ |
| `isoCode`   | The code of te country or state, from [`List of ISO 3166 country codes`](https://en.wikipedia.org/wiki/List_of_ISO_3166_country_codes) alpha-2 code | Ukraine flag |
| `className` | class for component                                                                                                                                 |
| `alt`       | alternative text for image                                                                                                                          |
