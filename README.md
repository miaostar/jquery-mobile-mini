jquery-mobile-mini
==================

自定义的jQuery Mobile类库,只保留常用的组件

获取选中的组件

```js
var a = '';$('#builder input:checkbox:checked').each(function(){a += '#' + this.id + ', '});
```

当前已选的组件

```js
$('#jquery-mobile-animationComplete, #jquery-mobile-data, #jquery-mobile-defaults, #jquery-mobile-helpers, #jquery-mobile-init, #jquery-mobile-ns, #jquery-mobile-support, #jquery-mobile-support-orientation, #jquery-mobile-support-touch, #jquery-mobile-vmouse, #jquery-mobile-widget, #widgets-slash-page, #events-slash-navigate, #events-slash-orientationchange, #events-slash-throttledresize, #events-slash-touch, #jquery-mobile-events, #jquery-mobile-buttonMarkup, #jquery-mobile-fieldContain, #widgets-slash-controlgroup, #widgets-slash-forms-slash-button, #widgets-slash-forms-slash-checkboxradio, #widgets-slash-forms-slash-reset, #widgets-slash-forms-slash-select, #widgets-slash-forms-slash-textinput, #jquery-mobile-navigation, #navigation-slash-base, #navigation-slash-history, #navigation-slash-method, #navigation-slash-navigator, #navigation-slash-path, #widgets-slash-pagecontainer, #transitions-slash-concurrent, #transitions-slash-handlers, #transitions-slash-serial, #transitions-slash-transition, #jquery-mobile-degradeInputs, #jquery-mobile-links, #jquery-mobile-media, #jquery-mobile-zoom, #jquery-mobile-grid, #widgets-slash-addFirstLastClasses, #widgets-slash-fixedToolbar, #widgets-slash-listview, #widgets-slash-loader, #widgets-slash-navbar, #widgets-slash-popup, #widgets-slash-toolbar').prop('checked', true);
```
