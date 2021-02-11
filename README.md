# Weather-Dashing

![Preview](https://nsa40.casimages.com/img/2021/02/11/210211055724260884.png)

## Description
Dashing/Smashing widget displaying current weather in your city.

## Dependencies
The following dependencies are required. Please add them to your dashing gemfile.
```
gem 'json'
```
Run `bundle install`

## Usage

To install this widget into you dashboard, add files weather.html, weather.scss and weather.coffee in widgets/weather/ and weather.rb in jobs/

Insert the HTML code in your `erb` file like this :
```
<li data-row="1" data-col="1" data-sizex="1" data-sizey="1">
  <div data-id="weather" data-view="Weather"></div>
</li>
```

Climacons is required for the good display of the widget.

## License

This widget is released under the [MIT License](http://www.opensource.org/licenses/MIT).

## NB

Feel free to leave comments for any improvements.
