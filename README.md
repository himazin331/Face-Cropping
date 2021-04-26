# 非推奨 Deprecated
このプログラムは欠陥が多いので、[こちら](https://github.com/himazin331/Face-Cropping-NEW)を使用することをおすすめします。

This program has a lot of flaws, I recommend you take advantage of [Here](https://github.com/himazin331/Face-Cropping-NEW).

# Face-Cropping
Cut out the face and resize it.

詳細は[こちら](https://qiita.com/hima_zin331/items/c4160c5c31888e2066a4)
*Not supported except in Japanese Language

___

## face_cut.py

**Command**  
```
python face_cut.py -d <IMG_DIR> -c <CASCADE>
                                (-o <OUT_PATH> -s <OUT_SIZE> -l <Index>)
                                                          
CASCADE   : ./haar_cascade.xml (Default)  
OUT_PATH  : ./result_crop (Default)
OUT_SIZE  : 32 (Default) *Output image size N x N.
Index     : 1 (Default) *Output image name index. Starting from dataN.jpg when you specify `-l N`.
```
