# Development

<details id="platform--node-js-lts">
	<summary>
		<a
			href="#platform--node-js-lts"
			title="Platform: Node.js LTS">
			<img
				src="https://img.shields.io/badge/Node.js-LTS-black?logo=Node.js&logoColor=lightgreen&color=2a2a2a&labelColor=black"
				alt="Platform: Node.js LTS" />
		</a>
	</summary>
	<div align="left">
		<br />
		<a
			target="_blank"
			title="Node.js Release Schedule"
			href="https://github.com/nodejs/release#release-schedule">
			<strong>Supported Node.js Environments</strong>
		</a><br /><br />

- [ ] v12：Erbium (Er)
- [x] v14：Fermium (Fm)
- [x] v16：Gallium (Ga)
- [x] v18：Hydrogen (H) <!-- TODO
- [x] v20: Iron (Fe) -->

	</div>
</details>

This project depends on various tooling packages that prefer running on
[supported versions of Node.js](#platform--node-js-lts). All tooling may
be acquired for free via the **`npm`**, **`pnpm`**, or **`yarn`** command
line apps that come bundled with Node.js (available thru Corepack).

If you’re already good to go (have the correct runtime version installed and
feeling courageous), running the following command line in a shell with a
working directory located at the root of this project’s source tree; all of the
below steps may be accomplished in one go.

```console
npm i; npm t; npm start;
```

## Installation

### Install the Dependencies

```console
npm install
```

## Usage

### Run the Tests

```console
npm test
```

### Run the App

```console
npm start
```
