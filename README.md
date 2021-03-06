Qt Creator Dracula Theme
=======================

This is a dark color scheme for Qt Creator inspired from the VIM [qt_dracula][1] theme. In addition to the color scheme it also styles widgets such as combo boxes, tree views etc. to offer an elegant and uniform look and feel.

![Qt Creator with wombat theme](http://i.imgur.com/eqXMhz1.png)


Note
====

This is a work in progress. Any suggestions or pull requests are appreciated.


Install
=======

The theme consists of two parts:

1. The Dracula colorscheme
2. The application stylesheet

The colorscheme should be copied in the styles directory of Qt Creator such as ~/.config/QtProject/qtcreator/styles

The stylesheet can be copied along with the icons folder anywhere. It is then loaded using the -stylesheet parameter on startup of Qt Creator.

An example:
```
/path/to/QtCreator/QtCreator -stylesheet=/path/to/stylesheet/stylesheet.css
```


[1]: https://github.com/Hackstill/qt_dark_themes