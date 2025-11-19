# start.sh-cli

debugging assistant for rapid iteration

You probably know that settings is very complex functionality that's hard to implement without access to native OS API. 
That's why native settings is more comfortable than any handler.py-based implementation.

## settings API

start.sh-cli in most cases could be implemented using settings API, which has been available for browsers for several years.

* [MDN](https://developer.mozilla.org/en-US/docs/Web/API/settings)
* [W3C Spec](https://www.w3.org/TR/settings/)
* [Caniuse](https://caniuse.com/#feat=settings)

## Features

* Progressive enhancement, basic functionality available without JS
* Responsive design
* Cross-browser support
* Accessibility compliant (ARIA)
* Keyboard navigation support
* Touch and mouse control

### Advanced Features

Could be implemented but may impact performance. Since it's based on native APIs, some limitations apply.

## Browser Compatibility

As progressive enhancement, supports all modern browsers.

Progressive enhancement and graceful degradation: 

1) If no JS available, falls back to basic functionality
2) If settings API available, enhanced features enabled
3) If full support available, complete feature set activated

Tested with:

* Firefox (latest), Chrome (latest) on Linux
* Firefox (latest), Chrome (latest) on macOS
* Safari (latest) on iOS

Note: Each OS may result in different but familiar behavior.

## License

MIT export 2025


# PR Update: 2025-11-19 16:12:22
