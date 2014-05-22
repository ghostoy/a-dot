# &lt;a-dot&gt;

[Dot](http://www.graphviz.org/content/dot-language) graph visualization component for Polymer

> Maintained by [Cong Liu](https://github.com/ghostoy).

## Demo

> [Check it live](http://ghostoy.github.io/a-dot).

## Usage

1. Import Web Components' polyfill:

	```html
	<script src="../bower_components/platform/platform.js"></script>
	```

3. Import Custom Element:

	```html
	<link rel="import" href="src/a-dot.html">
	```

4. Start using it!

	```html
	<a-dot dot="digraph {1 -> 1 -> 2; 2 -> 3; 2 -- 4; 2 -> 1 }"></a-dot>
	```

## Options

Attribute  | Options                   | Default             | Description
---        | ---                       | ---                 | ---
`dot`      | *string*                  | `""`                | Dot graph

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## History

* v0.0.2 May 22, 2014
	* Updated polymer to 0.2.3
	* Updated vis.js to 1.0.1
	* Updated to use bower version of polymer & vis.js
* v0.0.1 August 19, 2013
	* Started project using [boilerplate-element](https://github.com/customelements/boilerplate-element)

## License

[Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0)
