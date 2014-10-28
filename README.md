# &lt;open-badges-showcase&gt;

A web component to display open badges

## Demo

[Check it live!](http://mfpierre.github.io/open-badges-showcase/)

## Usage

1. Import Web Components' polyfill:

    ```html
    <script src="bower_components/platform/platform.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/open-badges-showcase/dist/open-badges-showcase.html">
    ```

3. Start using it!

    ```html
    <open-badges-showcase user="39965" group="40053" width="100"></open-badges-showcase>
    ```

## Options

Attribute     | Options     | Default      | Description
---           | ---         | ---          | ---
`user`        | *string*    | `39965`      | Your open badges User ID.
`group`       | *string*    | `40053`      | The open badges group you want to display.
`width`       | *string*    | `100`        | The width of the badge image


## Development

In order to run it locally you'll need to fetch some dependencies and a basic server setup.

* Install [Bower](http://bower.io/) & [Grunt](http://gruntjs.com/):

    ```sh
    $ [sudo] npm install -g bower grunt-cli
    ```

* Install local dependencies:

    ```sh
    $ bower install && npm install
    ```

* To test your project, start the development server and open `http://localhost:8000`.

    ```sh
    $ grunt server
    ```

* To build the distribution files before releasing a new version.

    ```sh
    $ grunt build
    ```

* To provide a live demo, send everything to `gh-pages` branch.

    ```sh
    $ grunt deploy
    ```

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)
