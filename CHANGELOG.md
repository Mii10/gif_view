## 0.4.0

* Update `http`
* Update sdk min to `2.16.0`

## 0.3.1

* Adds `withOpacityAnimation` param.
* Fix for 'Null check operator used on a null value'. Thanks [oligazar](https://github.com/oligazar)!

## 0.3.0

* Adds `GifController`. Now you can control the gif with controller. Methods: `play({bool? inverted, int? initialFrame})`, `pause()`, `stop()`. (Fixing #9)
* Adds fade animation when showing.
BREAKING CHANGES:
- remove `isAnimated` now is `autoPlay` in `GifController`
- remove `invertedAnimation` now is `inverted` in `GifController`
- remove `loop` now is `loop` in `GifController`

## 0.2.2

* Adds `invertedAnimation` param. Thanks [viniciusoliverrs](https://github.com/viniciusoliverrs)

## 0.2.1

* fix: Error: Type 'Uint8List' not found. [PR #5](https://github.com/RafaelBarbosatec/gif_view/pull/5)
* feat: isAnimated. [PR #6](https://github.com/RafaelBarbosatec/gif_view/pull/6). Thanks [iamdiosilva](https://github.com/iamdiosilva)

## 0.2.0

* Update ImageCodec
* Adds web support

## 0.1.1

* Adds `package` and `bundle` params in `GifView.asset`
* Adds `scale` and `headers` params in `GifView.network`
* Adds `scale` param in `GifView.memory`


## 0.1.0

* Remove warn flutter 3.0.
* Improvements in frameRate.

## 0.0.1

* Support to load gif images from `network`, `assets`,`memmory`,
* Configurable frame rate.

