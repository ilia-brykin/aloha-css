# ALOHA - CSS FRAMEWORK #

## Display `display` ##
+ .a_d_inline
+ .a_d_inline_block
+ .a_d_block
+ .a_d_grid
+ .a_d_table
+ .a_d_table_cell
+ .a_d_table_row
+ .a_d_flex
+ .a_d_inline_flex
+ .a_d_none

## Grid ##
+ `.a_columns` -> container
+ `.a_column` -> element
```
<div class="a_columns">
  <div class="a_column">
    First column
  </div>
  <div class="a_column">
    Second column
  </div>
  <div class="a_column">
    Third column
  </div>
  <div class="a_column">
    Fourth column
  </div>
</div>
```

### Columns gap ###
+ .a_columns_gab_1 -> `0.25rem`
+ .a_columns_gab_2 -> `0.5rem`
+ .a_columns_gab_3 -> `0.75rem`
+ .a_columns_gab_4 -> `1rem`
+ .a_columns_gab_5 -> `1.25rem`
+ .a_columns_gab_6 -> `1.5rem`
+ .a_columns_gab_7 -> `1.75rem`
+ .a_columns_gab_8 -> `2rem`
```
<div class="a_columns a_columns_gab_6">
  <div class="a_column">
    First column
  </div>
  <div class="a_column">
    Second column
  </div>
  <div class="a_column">
    Third column
  </div>
  <div class="a_column">
    Fourth column
  </div>
</div>
```

### Column sizes ###
#### for `.a_columns` ####
+ .a_columns_count_1 -> `--columnCount: 1;`
+ .a_columns_count_2 -> `--columnCount: 2;`
+ .a_columns_count_3 -> `--columnCount: 3;`
+ .a_columns_count_4 -> `--columnCount: 4;`
+ .a_columns_count_5 -> `--columnCount: 5;`
+ .a_columns_count_6 -> `--columnCount: 6;`
+ .a_columns_count_7 -> `--columnCount: 7;`
+ .a_columns_count_8 -> `--columnCount: 8;`
+ .a_columns_count_9 -> `--columnCount: 9;`
+ .a_columns_count_10 -> `--columnCount: 10;`
+ .a_columns_count_11 -> `--columnCount: 11;`
+ .a_columns_count_12 -> `--columnCount: 12;`

#### for `.a_column` ####
```
width: calc(100% / var(--columnCount) * 8);
```
+ .a_column_1
+ .a_column_2
+ .a_column_3
+ .a_column_4
+ .a_column_5
+ .a_column_6
+ .a_column_7
+ .a_column_8
+ .a_column_9
+ .a_column_10
+ .a_column_11
+ .a_column_12

#### Offset ####
```
margin-left: calc(100% / var(--columnCount) * 1);
```
+ .a_column_offset_1
+ .a_column_offset_2
+ .a_column_offset_3
+ .a_column_offset_4
+ .a_column_offset_5
+ .a_column_offset_6
+ .a_column_offset_7
+ .a_column_offset_8
+ .a_column_offset_9
+ .a_column_offset_10
+ .a_column_offset_11

## Colors ##

### Variables ###
+ --a_color_primary: #47b883;
+ --a_color_secondary: red;
+ --a_color_text: red;
+ --a_color_info: #0DCAF0FF;
+ --a_color_success: #198754FF;
+ --a_color_warning: #FFC107FF;
+ --a_color_danger: #DC3545FF;
+ --a_color_link: blue;
+ --a_color_white: #fff;
+ --a_color_black: #000;

### Color `color` ###
+ .a_color_primary
+ .a_color_secondary
+ .a_color_text
+ .a_color_info
+ .a_color_success
+ .a_color_warning
+ .a_color_danger
+ .a_color_link
+ .a_color_white
+ .a_color_black

### Background `background-color` ###
+ .a_bg_primary
+ .a_bg_secondary
+ .a_bg_text
+ .a_bg_info
+ .a_bg_success
+ .a_bg_warning
+ .a_bg_danger
+ .a_bg_link
+ .a_bg_white
+ .a_bg_black

## Display flex ##

### Direction `flex-direction` ###
+ a_flex_row -> `row`
+ a_flex_column -> `colum`
+ a_flex_row_reverse -> `row-reverse`
+ a_flex_column_reverse -> `column-reverse`

### Justify content `justify-content` ###
+ .a_justify_content_start -> `flex-start`
+ .a_justify_content_end -> `flex-end`
+ .a_justify_content_center -> `center`
+ .a_justify_content_between -> `space-between`
+ .a_justify_content_around -> `space-around`
+ .a_justify_content_evenly -> `space-evenly`

### Align items `align-items` ###
+ .a_align_items_start -> `flex-start`
+ .a_align_items_end -> `flex-end`
+ .a_align_items_center -> `center`
+ .a_align_items_baseline -> `baseline`
+ .a_align_items_stretch -> `stretch`

### Align self `align-self` ###
+ .a_align_self_auto -> `auto`
+ .a_align_self_start -> `flex-start`
+ .a_align_self_end -> `flex-end`
+ .a_align_self_center -> `center`
+ .a_align_self_baseline -> `baseline`
+ .a_align_self_stretch -> `stretch`

### Wrap `flex-wrap` ###
+ .a_flex_wrap -> `wrap`
+ .a_flex_nowrap -> `nowrap`
+ .a_flex_wrap_reverse -> `wrap-reverse`


### Align content `align-content` ###
+ .a_align_content_start -> `flex-start`
+ .a_align_content_end -> `flex-end`
+ .a_align_content_center -> `center`
+ .a_align_content_between -> `space-between`
+ .a_align_content_around -> `space-around`
+ .a_align_content_stretch -> `stretch`

## Text ##

### Alignment `text-align` ###
+ .a_text_start -> `left`
+ .a_text_center -> `center`
+ .a_text_end -> `right`

### Wrapping ###
+ .a_text_wrap -> `white-space: normal`
+ .a_text_nowrap -> `white-space: nowrap`
+ .a_text_break -> `word-wrap: break-word; word-break: break-word`

### Transform ###
+ .a_text_lowercase -> `text-transform: lowercase`
+ .a_text_uppercase -> `text-transform: uppercase`
+ .a_text_capitalize -> `text-transform: capitalize`
+ .a_text_underline -> `text-decoration: underline`
+ .a_text_italic -> `font-style: italic`
+ .a_text_bold -> `font-weight: 700`
+ .a_text_bolder -> `font-weight: bolder`
+ .a_text_semibold -> `font-weight: 600`
+ .a_text_light -> `font-weight: 300`
+ .a_text_lighter -> `font-weight: lighter`
+ .a_text_normal -> `font-style: normal; text-decoration: none; text-transform: none; font-weight: normal`

### Font size `font-size` ###
+ .a_fs_1 -> `2.5rem`
+ .a_fs_2 -> `2rem`
+ .a_fs_3 -> `1.75rem`
+ .a_fs_4 -> `1.5rem`
+ .a_fs_5 -> `1.25rem`
+ .a_fs_6 -> `1rem`
+ .a_fs_7 -> `0.75rem`

## Screen reader ##
+ .a_sr_only
+ .a_sr_only_focusable
```
<h2 class="a_sr_only">Info for screen readers</h2>
<a class="a_sr_only_focusable" href="#content">Skip to main content</a>
<div class="a_sr_only_focusable">A container with a <a href="#">focusable element</a>.</div>
```

## Position ##
### `position` ###
+ .a_position_static -> `static`
+ .a_position_relative -> `relative`
+ .a_position_absolute -> `absolute`
+ .a_position_absolute_all -> `position: absolute; top: 0; right: 0; bottom: 0; left: 0;`
+ .a_position_fixed -> `fixed`
+ .a_position_sticky -> `sticky`

### `top` ###
+ .a_top_0 -> `0`
+ .a_top_50 -> `50%`
+ .a_top_100 -> `100%`

### `bottom` ###
+ .a_bottom_0 -> `0`
+ .a_bottom_50 -> `50%`
+ .a_bottom_100 -> `100%`

### `left` ###
+ .a_start_0 -> `0`
+ .a_start_50 -> `50%`
+ .a_start_100 -> `100%`

### `right` ###
+ .a_end_0 -> `0`
+ .a_end_50 -> `50%`
+ .a_end_100 -> `100%`

### `transform: translate()` ###
+ .a_translate_middle -> `transform: translate(-50%, -50%)`
+ .a_translate_middle_x -> `transform: translateX(-50%)`
+ .a_translate_middle_y -> `transform: translateY(-50%)`

## List ##
+ .a_list_without_styles -> `padding-left: 0; list-style: none;`
```
<ul class="list-unstyled">
  <li>item 1</li>
  <li>item 2</li>
  <li>item 3</li>
</ul>  
```
+ .a_list_inline -> `padding-left: 0; list-style: none;`
+ .a_list_inline_item -> `display: inline-block; margin-right: 0.5rem;`
+ .a_list_inline_item_comma -> `:not(:last-child):after { content: ","; }`

### DL ###
+ .a_list_dl

## Styles for `<body>` ##

## Buttons ##
+ .a_btn
+ .a_btn_primary
+ .a_btn_secondary
+ .a_btn_success
+ .a_btn_danger
+ .a_btn_warning
+ .a_btn_info
+ .a_btn_link
+ .a_btn_lg
+ .a_btn_sm

### Button close ###
+ .a_btn_close

## Pagination ##
+ .a_pagination
+ .a_pagination__item
+ .a_pagination__item__link

## Float ##
+ .a_float_start
+ .a_float_end
+ .a_float_none

## Alert ##
+ .a_alert
+ .a_alert_dismissible
+ .a_alert_primary
+ .a_alert_secondary
+ .a_alert_success
+ .a_alert_info
+ .a_alert_warning
+ .a_alert_danger
+ .a_alert_light
+ .a_alert_dark

## Modal ##
+ .a_modal_open
+ .a_modal
+ .a_modal_show
+ .a_modal_dialog
+ .a_modal_content
+ .a_modal_dialog_scrollable
+ .a_modal_header
+ .a_modal_title
+ .a_modal_body
+ .a_modal_footer
+ .a_modal_small
+ .a_modal_large
+ .a_modal_xl
+ .a_modal_fullscreen
+ .a_modal_backdrop
+ .a_modal_backdrop_show
