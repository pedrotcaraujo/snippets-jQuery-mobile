#JQuery Mobile Snippets for Sublime

A set of [jQuery Mobile](http://jquerymobile.com/) snippets for make your life easier.

## Install

To install the snippets, download the package and click in `Browser Packages` in `Preferences` of sublime menu , it will open `Packages` directory, put all files inside it.

###Full path:

Windows: `C:\Users\{user}\AppData\Roaming\Sublime Text 2\Packages\`

Mac: `/Users/{user}/Library/Application Support/Sublime Text 2/Packages/`

Linux: `/home/{user}/.config/sublime-text-2/Packages/`

##Components

###[jbutton] Button
```html
<a href="${1:#}" data-role="button" id="${2:button}">${3:Button}</a>
```
###[jcheckbox] Checkbox
```html 
<label><input type="checkbox" name="${1:checkbox}" id="${2:checkbox}">${3:Checkbox}</label>
```

###[jcollapsible] Collapsible
```html 
	<div data-role="collapsible" id="${1:collapsible}">
		<h3>${2:Collapsible}</h3>
	</div>
```

###[jcollapsibleset] Collapsible Set
```html 
	<div data-role="collapsible-set" id="${1:collapsible-set}">
		<div data-role="collapsible" id="${2:collapsible}">
			<h3>${3:Collapsible}</h3>
		</div>
		<div data-role="collapsible" id="${4:collapsible0}">
			<h3>${5:Collapsible}</h3>
		</div>
		<div data-role="collapsible" id="${6:collapsible1}">
			<h3>${7:Collapsible}</h3>
		</div>
	</div>
```

###[jcontent] Content
```html 
<div data-role="content" id="${1:pageContent}">${2}</div>
```

###[jcontrolgroup] Control Group
```html 
<div data-role="controlgroup" id="${1:controlgroup}">${2}</div>
```

###[jdialog] Dialog
```html 
<div data-role="dialog" id="${1:dialog}">
	<div data-role="header" id="${2:header}">
		<h3>${3}</h3>
</div>
```

###[jfieldcontain] Field Container
```html 
<div data-role="fieldcontain" id="${1:fieldcontain}">${2}</div>
```

###[jfooter] Footer
```html 
<div data-role="footer" data-position="fixed" id="${1:footer}">
	<h3>${2}</h3>
</div>
```

###[jform] Form
```html 
<form id="${1:form}" action="${2}">${3}</form>
```

###[jgrid] Grid
```html 
<div class="ui-grid-a">
	<div class="ui-block-a">${1}</div>
	<div class="ui-block-b">${2}</div>
</div>
```

###[jheader] Header
```html 
<div data-role="header" id="${1:header}" data-position="fixed">
	<h3>${2}</h3>
</div>
```

###[jlabel] Label
```html 
<label id="${1:label}">${2:Label:}</label>
```

###[jlink] Link
```html 
<a href="#" id="${1:link}">${2:Link}</a>
```

###[jview] List View
```html 
<ul data-role="listview" id="${1:listview}" data-inset="true">
	<li data-role="list-divider" id="${2:divider}">${3:Divider}</li>
	<li id="${4:listitem}"><a href="#">${5}</a></li>
	<li id="${6:listitem0}"><a href="#">${7}</a></li>
	<li id="${8:listitem1}"><a href="#">${9}</a></li>
</ul>
```

###[jlistitem] List View Item
```html 
<li id="${1:listitem}"><a href="${2}" id="${3:item}">${4}</a></li>
```

###[jnavbar] NavBar
```html 
<div data-role="navbar" id="${1:navbar}">
	<ul>
		<li><a href="${2:#}" id="${3:item}">${4}</a></li>
		<li><a href="${5:#}" id="${6:item0}">${7}</a></li>
		<li><a href="${8:#}" id="${9:item1}">${10}</a></li>
	</ul>
</div>
```

###[jpage] Page
```html 
<div data-role="page" id="${1:page}">
	<div data-role="content">
		${2}
	</div>
</div>
```

###[jpanel] Panel
```html 
<div data-role="panel" id="${1:panel}">${2}</div>
```

###[jpopup] Popup
```html 
 <a href="${1:#popup}" data-rel="${2:popup}" id="${3:popup}">${4}</a>
<div data-role="${2:popup}" id="${5:popup0}">
	<h3>${6}</h3>
	<div>${7}</div>
</div>
```

###[jradio] Radio Button
```html 
<input type="radio"	name="radio-choice" id="${1:radio}" value="${2:radio}"><label for="${3:radio}">${4}</label>
```

###[jrangeslider] Range Slider
```html
<div data-role="rangeslider">
	<label for="${1:range-1a}">${2:Rangeslider:}</label>
	<input name="${1:range-1a}"	id="${3:range-1a}" min="0" max="100" value="40" type="range">
	<label for="${4:range-1b}">{5:Rangeslider:}</label>
	<input name="${4:range-1b}" id="${5:range-1b}" min="0" max="100" value="80" type="range">
</div>
```

###[jsearch] Search Input
```html 
<label for="${1:search}" id="${2:label}">${3}</label>
<input type="search" name="${1:search}" id="${4:search}">
```

###[jselect] Select Menu
```html 
<select name="${1:select}" id="${2:select}">
	<option	value="${3:select}">${4}</option>
</select>
```

###[jslider] Slider
```html 
<label for="${1:slider}">${2}</label>
<input type="range"	name="${1:slider}" id="${3:slider}" value="50" min="0" max="100">
```

###[jtable] Table
```html 
<table data-role="table" id="${1:table-reflow}" data-mode="reflow" class="ui-responsive table-stroke">
	<thead>
		<tr>
			<th data-priority="2">${2}</th>
			<th data-priority="1">${3}</th>
			<th data-priority="persist">${4}</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<th>${5}</th>
			<td>${6}</td>
			<td>${7}</td>
		</tr>
		<tr>
			<th>${8}</th>
			<td>${9}</td>
			<td>${10}</td>
		</tr>
	</tbody>
</table>
```

###[jtextarea] Text Area
```html 
<textarea id="${1:textarea}">${2}</textarea>
```

###[jtextinput] Text Input
```html 
<label for="${1:text}">${2}</label>
<input type="text" name="${1:text}" id="${3:text}">
```

###[jflip] Toogle Switch
```html 
<label for="${1:flip}">${2}</label>
<select	name="${1:flip}" id="${3:flip}" data-role="slider">
	<option	value="${4}">${5}</option>
	<option value="${6}">${7}</option>
</select>
```



## by
[Pedro Araujo](http://pedrotcaraujo.com)

[@pedrotcaraujo](http://twiter.com/pedrotcaraujo)

