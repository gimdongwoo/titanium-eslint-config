# titanium-eslint-config

ESLint environment to improve development efficiency of Axway(Appcelerator) Titanium.


## How to use

1. Run ``npm init`` to create package.json in your titanium project.

2. Install eslint and config.

	```console
	$ npm install --save-dev eslint-config-airbnb-base eslint-plugin-import eslint@3
	```

3. You can copy [.eslintrc](https://github.com/gimdongwoo/titanium-eslint-config/blob/master/.eslintrc) and [.eslintignore](https://github.com/gimdongwoo/titanium-eslint-config/blob/master/.eslintignore) from this repository and put them in the project root.


## Disabling Rules with Inline Comments

1. Disabling Block

	```javascript
	/* eslint-disable */

	alert('foo');

	/* eslint-enable */
	```

2. Disabling Line

	```javascript
	alert('foo'); // eslint-disable-line
	```

See the [eslint documentation](http://eslint.org/docs/user-guide/configuring.html#disabling-rules-with-inline-comments) for more.


## Sample

1. [appc-sample-ti520](https://github.com/gimdongwoo/titanium-eslint-config/tree/master/appc-sample-ti520)

	(Based on appc-sample-ti520, we made very little convention changes.)


## Reference

1. [eslint-config-airbnb-base](https://www.npmjs.com/package/eslint-config-airbnb-base#eslint-config-airbnb-baselegacy)
