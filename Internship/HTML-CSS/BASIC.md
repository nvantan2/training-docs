# Front End Training: First Week For All Languages
Tìm hiểu về Git, HTML, CSS, JavaScript + jQuery, Bootstrap

## Mục tiêu
- Thực tập sinh hiểu được cơ bản về Git, HTML, CSS, JavaScript + jQuery
- Làm quen với các tool: Browser Dev Tools, [Visual Studio Code](https://code.visualstudio.com)
- Sử dụng Git để gửi bài tập cho Mentor

## Tài liệu
-  [Git Basic](https://backlog.com/git-tutorial/what-is-git/)
-  [w3schools](https://www.w3schools.com)
-  [JavaScript](http://eloquentjavascript.net)
- Chrome Dev Tools
-  [Inspect element & style](https://developers.google.com/web/tools/chrome-devtools/inspect-styles)
-  [Console](https://developers.google.com/web/tools/chrome-devtools/console/)
-  [Convert PSD to HTML, CSS](https://www.youtube.com/watch?v=Lj2PeRbVHrs)

## Ngày 1 - Git cơ bản
-  **Git clone**
`git clone https://github.com/user/repository.git`
-  **Git pull**
`git pull origin master`
-  **Liệt kê remote urls**
`git remote -v`
-  **Thay đổi url**
`git remote set-url origin https://github.com/user/repository.git`
-  **Kiểm tra status working tree**
`git status`
-  **Git add**
`git add .`
-  **Git commit**
`git commit -m"Your message"`
-  **Git push**
`git push origin your-branch`
-  **Create new branch**
`git branch your-branch`
-  **Git checkout**
`git checkout your-branch`
-  **Create new branch && Git checkout**
`git checkout -b your-branch`
-  **Git fetch**
`git fetch orgin`
-  **Git conflict là gì?**

> Bài tập cho Git
>  - Tạo 1 repository mới trên Github với tên `stu-yourname`
>  - Tạo ra 1 file với tên `stu.text` và push code lên Github với branch `master` có nội dung:
> ```
> Hello 
> ```
>  - Tạo 1 branch mới với tên `yourname-demo1` và checkout sang branch vừa tạo
>  - Sửa nội dung trong file `stu.text` sau đó push code lên Github, không merge:
> ```
> Hello 
> I am new member
> ```
>  - Tạo 1 branch mới với tên `yourname-demo2` và checkout sang branch vừa tạo
>  - Sửa nội dung trong file `stu.text` sau đó push code lên Github, không merge:
> ```
> Hello 
> My name is **your-name**
> ```

## Ngày 2 - HTML5 && CSS3
### HTML5
- [HTML là gì](https://www.w3schools.com/html/html5_intro.asp)
- [Khái niệm tag, attribute](https://www.w3schools.com/html/html_attributes.asp)
- [Heading](https://www.w3schools.com/html/html_headings.asp)
- [Text](https://www.w3schools.com/html/html_paragraphs.asp)
- [Form](https://www.w3schools.com/html/html_forms.asp)
	- [Form Elements](https://www.w3schools.com/html/html_form_elements.asp)
	- [Input Types](https://www.w3schools.com/html/html_form_input_types.asp)
	- [Input Attributes](https://www.w3schools.com/html/html_form_attributes.asp)
- [Table](https://www.w3schools.com/html/html_tables.asp)
- [List](https://www.w3schools.com/html/html_lists.asp)
- [Image](https://www.w3schools.com/html/html_images.asp)
- [Link](https://www.w3schools.com/html/html_links.asp)
- [Block && Inline](https://www.w3schools.com/html/html_blocks.asp)
- [Iframe](https://www.w3schools.com/html/html_iframe.asp)
- [Head](https://www.w3schools.com/html/html_head.asp)
- [Responsive](https://www.w3schools.com/html/html_responsive.asp)
- [Layout](https://www.w3schools.com/html/html_layout.asp)
- [Style Guide and Coding Conventions](https://www.w3schools.com/html/html5_syntax.asp)

### CSS
- [CSS là gì?](https://www.w3schools.com/css/css_intro.asp)
- [Khái niệm selector, property](https://www.w3schools.com/css/css_attribute_selectors.asp)
- [Font](https://www.w3schools.com/css/css_font.asp)
- [Color](https://www.w3schools.com/css/css_colors.asp)
- [Background](https://www.w3schools.com/css/css_background.asp)
- [Box model](https://www.w3schools.com/css/css_boxmodel.asp)
- [Position](https://www.w3schools.com/css/css_positioning.asp)
- [Flex layout](https://www.w3schools.com/css/css3_flexbox.asp)
- [Grid Layout](https://www.w3schools.com/css/css_grid.asp)
- [Animation](https://www.w3schools.com/css/css3_animations.asp)
- [Transitions](https://www.w3schools.com/css/css3_transitions.asp)
- [Transforms](https://www.w3schools.com/css/css3_3dtransforms.asp)
- [Box Shadow](https://www.w3schools.com/css/css3_shadows.asp)
- [Form](https://www.w3schools.com/css/css_form.asp)
- [:before, :after](https://www.w3schools.com/css/css_pseudo_elements.asp)
- [Pseudo-classes](https://www.w3schools.com/css/css_pseudo_classes.asp)
- [Responsive Web Design](https://www.w3schools.com/css/css_rwd_intro.asp)
- [Normalize là gì](https://github.com/necolas/normalize.css)

> Bài tập cho HTML5 && CSS3
>   - Tạo 1 repository trên Github với tên `stu-yourname-html-css`
>   - Sử dụng HTML5 và CSS3 để Design trang [Contact]
>   - Push code lên repository vừa tạo và gửi link Github cho Mentor

## Ngày 3 - Bootstrap 4.2
- [Bootstrap là gì? How to use Bootstrap in source code?](https://getbootstrap.com/docs/4.2/getting-started/introduction)
- [Layout](https://getbootstrap.com/docs/4.2/layout/overview)
	-	[Gird](https://getbootstrap.com/docs/4.2/layout/grid)
- [Typography](https://getbootstrap.com/docs/4.2/content/typography)
- [Table](https://getbootstrap.com/docs/4.2/content/tables)
- Component 
	- [Alerts](https://getbootstrap.com/docs/4.2/components/alerts)
	- [Breadcrumb](https://getbootstrap.com/docs/4.2/components/breadcrumb)
	- [Buttons](https://getbootstrap.com/docs/4.2/components/buttons)
	- [Card](https://getbootstrap.com/docs/4.2/components/card)
	- [Carousel](https://getbootstrap.com/docs/4.2/components/carousel)
	- [Dropdowns](https://getbootstrap.com/docs/4.2/components/dropdowns)
	- [Forms](https://getbootstrap.com/docs/4.2/components/forms)
	- [Modal](https://getbootstrap.com/docs/4.2/components/modal)
	- [Navbar](https://getbootstrap.com/docs/4.2/components/navbar)
	- [Pagination](https://getbootstrap.com/docs/4.2/components/pagination)
	- [Spinners](https://getbootstrap.com/docs/4.2/components/spinners)
	- [Toasts](https://getbootstrap.com/docs/4.2/components/toasts)
- Utilities
	- [Colors](https://getbootstrap.com/docs/4.2/utilities/colors)
	- [Flex](https://getbootstrap.com/docs/4.2/utilities/flex)
	- [Spacing](https://getbootstrap.com/docs/4.2/utilities/spacing)
	- [Text](https://getbootstrap.com/docs/4.2/utilities/text)
	- [Icons](https://getbootstrap.com/docs/4.2/extend/icons)

> Bài tập cho Bootstrap
>   - Tạo 1 repository trên Github với tên `stu-yourname-bootstrap`
>   - Sử dụng HTML5, CSS3 và Bootstrap để Design trang [IOT Coworking Space](http://iotcoworkingspace.com)
>   - Push code lên repository vừa tạo và gửi link Github cho Mentor

## Ngày 4 - Javascript && Jquery, Ajax
### Javascript
- [JavaScript là gì?](https://www.w3schools.com/js/default.asp)
- [Data Types](https://www.w3schools.com/js/js_datatypes.asp)
- [Operators](https://www.w3schools.com/js/js_operators.asp)
- [Variables](https://www.w3schools.com/js/js_variables.asp)
- [Function](https://www.w3schools.com/js/js_functions.asp)
- [Object](https://www.w3schools.com/js/js_objects.asp)
- [Events](https://www.w3schools.com/js/js_events.asp)
- [String Methods](https://www.w3schools.com/js/js_string_methods.asp)
- [Number Methods](https://www.w3schools.com/js/js_number_methods.asp)
- [Array Methods](https://www.w3schools.com/js/js_array_methods.asp)
- [Conditions](https://www.w3schools.com/js/js_if_else.asp)
- [Loop For](https://www.w3schools.com/js/js_loop_for.asp)
- [Type Conversion](https://www.w3schools.com/js/js_type_conversion.asp)
- [ECMAScript 6 - ES6](https://www.w3schools.com/js/js_es6.asp)

### Jquery
- [What is jQuery?](https://www.w3schools.com/jquery/default.asp)
- [Syntax](https://www.w3schools.com/jquery/jquery_syntax.asp)
- [Selector](https://www.w3schools.com/jquery/jquery_selectors.asp)
- [Events](https://www.w3schools.com/jquery/jquery_ref_events.asp)
- [Effects](https://www.w3schools.com/jquery/jquery_ref_effects.asp)

### Ajax && JSON
- [Ajax](https://www.w3schools.com/jquery/jquery_ref_ajax.asp)

### JSON
- [Json](https://www.w3schools.com/js/js_json_intro.asp)
- [Data Types](https://www.w3schools.com/js/js_json_datatypes.asp)
- [Parse](https://www.w3schools.com/js/js_json_parse.asp)
- [Stringify](https://www.w3schools.com/js/js_json_stringify.asp)

> Bài tập cho Javascript && Jquery, Ajax
>   - Tạo 1 repository trên Github với tên `stu-yourname-javascript`
>   - Thiết kế 1 Website có sử dụng Javascript (Slider, Go to top, Dropdown Menu, Validation Form, Ajax)
>   - Push code lên repository vừa tạo và gửi link Github cho Mentor

## Ngày 5 - Design A Website
> Bài tập cho First Week
>   - Tạo 1 repository trên Github với tên `stu-yourname-firstweek`
>   - Sử dụng tất cả những gì bạn biết để thiết kế trang [STU]
>   - Push code lên repository vừa tạo và gửi link Github cho Mentor