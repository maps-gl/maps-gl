**MapsGL** is a community fork derived from [mapbox-gl-js](https://github.com/mapbox/mapbox-gl-js), which as of Dec 8, 2020 is no longer open source.

[<img width="200" alt="MapsGL" src="https://user-images.githubusercontent.com/223277/101580282-7534f700-397e-11eb-8b58-687f52e2a8cf.png">](http://mapsgl.org)

To **contribute in the early stages, [chat on gitter](https://gitter.im/maps-gl/maps-gl)**, file issues, or email hackerswelcome@mapsgl.org. 

Anyone with a stake in a healthy community fork is welcome to help us figure out our next steps. In the short term, we'll be very open to granting project leadership/commit privileges. When in doubt, we favour including everyone (with some github/gitlab/other reputation we can verify) affected by the license change, with the **goal of minimizing fragmentation**.

### Avoiding Fragmentation

If you are a company or project depending on an open source `mapbox-gl-js`, please consider joining our effort instead of starting your own fork! We would *much* rather have "one project" rather than "our way" ;-) 

If you know of other forks, please contribute to a coherent future by reaching out to them, or file an issue on `maps-gl` for us to reach out to them... or both.

### Migrating from mapbox-gl

In your `package.json`, simply replace:
```
`"mapbox-gl": "^1.13.0"
```
with
```
`"@maps-gl/maps-gl": ">=1.13.0.rc.3"
```

## License

MapsGL is licensed under the [3-Clause BSD license](./LICENSE.txt).

[![Join the chat at https://gitter.im/maps-gl/maps-gl](https://badges.gitter.im/maps-gl/maps-gl.svg)](https://gitter.im/maps-gl/maps-gl?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
