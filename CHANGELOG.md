## 1.0.3
* Fixed #7 Shadow doesn't change size when child view gets smaller.

## 1.0.2

* Switched bitmap config from `Bitmap.Config.ARGB_8888` to `Bitmap.Config.ALPHA_8` to reduce generated shadow bitmap memory (x4 times)
* Removed `sl_fillColor` (now is always transparent)

## 1.0.1

* Fixed crash when view size was 0