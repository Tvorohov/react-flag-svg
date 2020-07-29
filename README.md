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

## Status and contribution

The project is supported by Halo lab development team, we're not working on it regularly, but trying to invest in it when we have time between clients' project. <br />
Though, feel free to open issues and you're very welcome to contribute.
<br />
<br />
<a href="https://www.halo-lab.com/?utm_source=github-brifinator-3000">
<img src="http://api.halo-lab.com/wp-content/uploads/dev_halo.svg" alt="Developed in Halo lab" height="60">
</a>
