# CRISPY CSS

Crispy is an open source css framework built to get your webpages well structured as well as keep you in absolute control of your design. Crispy css provides you with just enough tools to enable you achieve any layout of your choice through the grid system and the flexbox model.

## Installation

Crispy css is in a single css file can be used both offline and online.

##### Use offline version

Use [this link](#) to download crispy.css.

##### Use online version

Simply copy and paste the line below to your HTML head tag.

```html
<link rel="stylesheet" type="text/css" href="https://" />
```

## Usage

To use Crispy CSS follow the cheat sheet below.

##### FlexBox

| CSS             |                                                                             CRISPY CLASS |
| :-------------- | ---------------------------------------------------------------------------------------: |
| display:flex    |                                                                                     flex |
| justify-content | jc-start <br/> jc-end <br/>jc-center <br/>jc-between <br/>jc-around <br/>jc-evenly <br/> |
| flex-direction  |              fd-row-reverse <br/> fd-row-reverse <br/> fd-column <br/> fd-column-reverse |
| flex-wrap       |                                                     wrap <br/> no-wrap <br> wrap-reverse |
| align-items     |                 ai-start <br/> ai-end <br/> ai-center <br/> ai-baseline <br/> ai-stretch |
| align-content   |   ac-start <br/> ac-end <br/> ac-center <br/> ac-between <br/> ac-around <br> ac-stretch |
| align-self      |                 as-start <br/> as-end <br/> as-center <br/> as-baseline <br/> as-stretch |

##### Grid System

Crispy css modifies the bootstrap grid system so a clear understanding of the bootstrap 12 columns rule is an addddvantage.
|Bootstrap|Crispy|
|---------|-------:|
|container|grid|
|row|row|
|col-lg-\<number of colums><br>col-lg-12<br>col-lg-5|lg-\<number of colums><br>lg-12<br>lg-5|
|col-md-\<number of colums><br>col-md-12<br>md-5|md-\<number of colums><br>md-12<br>md-5|
|col-sm-\<number of colums><br>col-sm-12<br>col-sm-5|sm-\<number of colums><br>sm-12<br>sm-5|
|col-xs-\<number of colums><br>col-xs-12<br>col-xs-5|xs-\<number of colums><br>xs-12<br>xs-5|
|col-md-offset-\<number of colums><br>col-md-12-offset-5|md-\<number of colums><br>md-12-offset-5|
|col-xs-pull-\<number of colums><br>col-xs-pull-12<br>col-lg-5|lg-\<number of colums><br>xs-pull-12<br>lg-pull-5|
|col-xs-push-\<number of colums><br/>col-lg-pull-5|xs-push-\<number of colums><br/>lg-push-5|

#### Others

| RULE           |                       CRISPY CLASS |
| -------------- | ---------------------------------: |
| full width     |                               full |
| half width     |                               half |
| text alignment | left<br>right<br>justify<br>center |
| hide overflow  |                           truncate |

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
