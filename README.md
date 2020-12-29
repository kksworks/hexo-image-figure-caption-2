# hexo-image-figure-caption-2

해당 repo 는 기존 `hexo-image-figure-caption` 의 플러그인이 hexo 최신버젼과 `hexo-image-link` 플러그인을 사용했을때 정상적으로 동작하지 않던것을 수정하였다.

기존 모든 내용은 `hexo-image-figure-caption` 와 동일하다.

npm 에 upload 하지 않고, local 로만 제공한다.

## 설치방법

```sh
npm install ssh://git@github.com:kksworks/hexo-image-figure-caption-2.git
```

# hexo-image-figure-caption

wrap images in figures and add caption -- forked from wayou's [hexo-image-caption](https://github.com/wayou/hexo-image-caption)

[![build status](https://secure.travis-ci.org/wayou/hexo-image-caption.svg)](http://travis-ci.org/wayou/hexo-image-caption)
[![dependency status](https://david-dm.org/wayou/hexo-image-caption.svg)](https://david-dm.org/wayou/hexo-image-caption)

## Installation

```
npm install --save hexo-image-figure-caption
```

## Usage
adding following section to your hexo site `_config.yml` file to enable and config plugin.
```yml
# add caption for iamges
image_caption:
  enable: true #false to disable
  class_name: #if you wanna customize the style for the caption,you can assign a class name, default is 'image-caption'
```

Your images will be wrapped in a `figure` and the alt text will be placed in a `figcaption`. This way you have a bit more control over the layout and can keep the caption with the figure as you lay things out, e.g. when you want to put several images side-by-side.

## Credits
forked from [wayou/hexo-image-caption](https://github.com/wayou/hexo-image-caption)

## License

MIT
