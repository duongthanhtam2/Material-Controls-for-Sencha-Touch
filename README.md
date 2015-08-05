# Material Design Controls For Sencha Touch

This project wants to create easy to use Sencha Touch controls using the look and feel of the [Google Material Design](http://www.google.com/design/spec/material-design/introduction.html) guidelines.

Please feel free to make any pull requests.

Component List
-----
- [x] Button
- [x] TextField
- [x] Progress
- [x] Select
- [x] Slider
- [x] Toggle
- [x] TabBar
- [x] List
- [x] MessageBox
- [x] Checkbox
- [x] DatePicker

#### Button
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Button.gif">
</p>

#### TextField
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/TextField.gif">
</p>

#### Progress
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Progress.gif">
</p>

#### Select
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Select.gif">
</p>

#### Slider
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Slider.gif">
</p>

#### Toggle
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Toggle.gif">
</p>

#### TabBar
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Tab.gif">
</p>

#### List
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/List.gif">
</p>

#### MessageBox
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Messagebox.gif">
</p>

#### Checkbox
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/Checkbox.gif">
</p>

#### DatePicker
<p align="center">
<img style="-webkit-user-select: none;" src="https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/blob/master/Images/DatePicker.gif">
</p>

# Get Started
<p>1. Copy Material package into Pakages folder of your Sencha Touch project</p>
<p>2. Add a new line into your app.scss, something like bellow;</p>
<p style="margin-left:30px">
	*@import 'sencha-touch/default';*
	*@import 'sencha-touch/default/all';*
	**_@import '../../packages/Material/sass/src/Material.scss';_**
	**_@include md-ripple;_**
	And 'mixin' of which control you want to use
	**_@include md-button;_**
	**_@include md-text-field;_**
	**_@include md-toggle;_**
	**_@include md-slide;_**
	**_@include md-tab;_**
	**_@include md-checkbox;_**
	**_@include md-message-box;_**
	**_@include md-progress-circular;_**
	**_@include md-toolbar;_**
	**_@include md-select;_**
	**_@include md-date-picker;_**
</p>
<p style="margin-left:30px">
	**_sencha package build_**
</p>
<p>3. Run package build command from Material package folder</p>
<p style="margin-left:30px">
	**_sencha package build_**
</p>
<p>4. And build your application again</p>
**_sencha app build_**
<p>After this, all of default control in your project should be change to Material style</p>
<p>See sample project for more details</p>

# Full controls documentation
Please go to [Wiki](https://github.com/fpt-software/Material-Controls-for-Sencha-Touch/wiki) to see how to use and customize each control.

Provided by [FPT Software](http://www.fpt-software.com/)
