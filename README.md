# material-icons-react

[![Build Status](https://semaphoreci.com/api/v1/logtrace/material-icons-react/branches/master/shields_badge.svg)](https://semaphoreci.com/logtrace/material-icons-react)

## NOTE: Version 1.0.3 release

* Demo app added
* Fix for [#1](https://github.com/logtrace/material-icons-react/issues/1)
* Fix for [#11](https://github.com/logtrace/material-icons-react/issues/11)
* Fix for [#12](https://github.com/logtrace/material-icons-react/issues/12)
* Fix for [#13](https://github.com/logtrace/material-icons-react/issues/13)
* Passing in `className` prop will replace the default icon styles, defaultColor and inactive styles. Own styles for these should be provided if className prop is defined.

## Introduction

This package provides a convenient react component for using [Google's Material Icons](https://material.io/icons/) in your react application.

## Features

* Follows [Material design guidelines](https://google.github.io/material-design-icons/#icon-font-for-the-web)
* Highly customizable
* Supports Material UI [color palette](https://www.materialui.co/colors) off the shelf.

## Usage

Import module using the following statement.

```
import MaterialIcon, {colorPalette} from 'material-icons-react';
```

1. Rendering an icon is straightforward.

```
<MaterialIcon icon="dashboard" />
<MaterialIcon icon="alarm_on" />
```
2. Change the icon size by using the `size` property.

```
<MaterialIcon icon="dashboard" size='large' />
<MaterialIcon icon="dashboard" size={100} />
```
3. Invert the icon by using the invert property.
```
<MaterialIcon icon="dashboard" invert />
```
4. Make the icon inactivate by using the `inactive` property.
```
<MaterialIcon icon="dashboard" inactive />
```
5. Change the color of an icon.
* Using [Material UI color palette](https://www.materialui.co/colors).
```
<MaterialIcon icon="dashboard" color={colorPalette.amber._200} />
<MaterialIcon icon="dashboard" color={colorPalette.amber.A700} />
```
* Using a custom color.
```
<MaterialIcon icon="dashboard" color='#7bb92f' />
```


## Icon size matrix
| Alias | Size |
|-------|-----:|
| tiny  | 18px |
| small | 24px |
| medium| 36px |
| large | 48px |

## Contributions

Please feel free to create PR for any improvements and contributions.

## License

MIT
