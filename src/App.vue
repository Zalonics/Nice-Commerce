<template>
	<router-view></router-view>
</template>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Lato:wght@100;300;400;700;900&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Averia+Libre:wght@300;400;700&display=swap');

:root {
	--primary-color: hsl(212, 100%, 61%);
	--primary-color-dark: hsl(212, 100%, 48%);
	--text-color: hsla(221, 68%, 17%, 0.7);
	--text-color-dark: hsl(221, 68%, 17%);
}

html {
	font-size: 62.5%;
}

* {
	margin: 0;
	box-sizing: border-box;
}

a,
a:focus,
a:hover {
	text-decoration: none;
	color: var(--text-color);
}

ul {
	list-style: none;
	padding: 0;
}

body {
	font-family: 'Lato', sans-serif;
	color: var(--text-color);
}
</style>
