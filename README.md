MaterialEditText
================

## About this fork
- NineOldAndroid is removed.
- minSdk now is 14.
- Ability to instantiate a view with a custom style is provided.
- Some master branch missing code has been synced with the published library sources.


![MaterialEditText](./images/material_edittext.png)

AppCompat v21 makes it easy to use Material Design EditText in our apps, but it's so limited. If you've tried that, you know what I mean. So I wrote MaterialEditText, the EditText in Material Design, with more features that [Google Material Design Spec](http://www.google.com/design/spec/components/text-fields.html) has introduced.

## Features
1. **Basic**

  ![Basic](./images/basic.png)
  
2. **Floating Label**
  
  normal:
  
  ![FloatingLabel](./images/floating_label.png)
  
  highlight:
  
  ![HighlightFloatingLabel](./images/highlight.png)

  custom floating label text:

  ![CustomFloatingLabelText](./images/custom_floating_label_text.png)
  
3. **Single Line Ellipsis**
  
  ![SingLineEllipsis](./images/ellipsis.png)
  
4. **Max/Min Characters**
  
  ![MaxCharacters](./images/max_characters.png)

  ![MinCharacters](./images/min_characters.png)

  ![MinAndMaxCharacters](./images/min_and_max.png)
  
5. **Helper Text and Error Text**

  ![HelperTextAndErrorText](./images/helper_error_text.png)

6. **Custom Base/Primary/Error/HelperText Colors**

  ![CustomColors](./images/custom_colors.png)

7. **Custom accent typeface**

  floating label, error/helper text, character counter, etc.

  ![CustomAccentTypeface](./images/custom_accent_typeface.png)

8. **Hide Underline**

  ![HideUnderLine](./images/hide_underline.png)

8. **Material Design Icon**

  ![MaterialDesignIcon](./images/material_design_icon.png)

gradle:

```groovy
compile 'com.shuhart.materialedittext:materialedittext:2.1.6'
```

## Usage

See on [Wiki Page](https://github.com/rengwuxian/MaterialEditText/wiki) or [中文看这里](http://www.rengwuxian.com/post/materialedittext)

## License

    Copyright 2014 rengwuxian

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    
