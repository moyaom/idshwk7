## idshwk7
# 采用将信息隐藏在颜色中的方法来隐藏信息
# input.png是原图，test.png是input.png加入隐藏信息后得到的图片，info.txt是要隐藏的信息，my_info.txt是提取得到的信息
# 隐藏信息命令
  python LSBSteg.py encode -i input.png -o test.png -f info.txt
# 提取信息命令
  python LSBSteg.py decode -i test.png -o my_info.txt
