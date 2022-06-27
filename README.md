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
