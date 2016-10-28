# granite-countdown

> A simple countdown element
> 
> Polymer 1.6 ready


## Doc & demo

[https://lostinbrittany.github.io/granite-countdown](https://lostinbrittany.github.io/granite-countdown)

## Usage example
<!--
```
<custom-element-demo>
  <template>
      <link rel="import" href="./granite-countdown.html">
  </template>    
</custom-element-demo>
```
-->
```
<granite-countdown value="42" digits="4" label="Time to go"></granite-countdown>
```


## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install LostInBrittany/granite-countdown --save
```

Or [download as ZIP](https://github.com/LostInBrittany/granite-countdown/archive/gh-pages.zip).## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.min.js"></script>
    ```

2. Import Custom Element:

    ```html
    <link rel="import" href="bower_components/granite-countdown/granite-countdown.html">
    ```

3. Start using it!

    ```html
    <granite-countdown value="42" digits="4" label="Time to go"></granite-countdown>
    ```


The following custom properties and mixins are also available for styling:

Custom property | Description | Default
----------------|-------------|----------
`--granite-countdown-digits` | Mixin applied to the digits | `{}`

## Attributes

Attribute     | Type      | Default  | Description
---           | ---       | ---      | ---
`value`       | *Number*  | `0`      | The current value of the countdown
`digits`      | *Number*  | `4`      | The number of digits to display


`value` must be a positive integer number, and it must fit into `digits` digits.
`digits` must be a positive integer value (of a reasonable size)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[MIT License](http://opensource.org/licenses/MIT)