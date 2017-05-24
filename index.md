---
title: Thoughts
tagline: 
description: Thoughts about interaction design and development
---
# David Bonnet

Hello!

```js
export const Component = compose(
	setPropTypes({
		_: PropTypes.func.isRequired,
	}),
)(function Component(props) {
	const {
		_,
	} = props;
	return $('p', null,
		_('Hello'),
	);
});
```