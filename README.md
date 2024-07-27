# jq themes

Customize the jq output.

##  How to test

Export the jq configuration variable:

```shell
export JQ_COLORS="0;90:0;37:0;37:0;37:0;32:1;37:1;37:1;34"
```

Print the demo.json file to see the new color scheme:

```shell
cat demo.json | jq
```

## How to install

Just add the configuration variable to your shell configuration file:

```shell
export JQ_COLORS="0;90:0;37:0;37:0;37:0;32:1;37:1;37:1;34"
```

## Themes

```
export JQ_COLORS="0;34:0;37:0;37:0;37:0;33:1;37:1;37:0;32"
```
<img src="https://github.com/isacben/jqthemes/blob/main/img/theme1.png" width="300">

```
export JQ_COLORS="0;90:0;37:0;37:0;37:0;36:1;37:1;37:1;35"
```

<img src="https://github.com/isacben/jqthemes/blob/main/img/theme2.png" width="300">


### Author

Isaac Benitez
2024
