```python
#引入 Pillow,numpy库
from PIL import Image
import numpy as np

#打开图片将其转换为灰度显示
a=np.asarray(Image.open('1.jpg').convert('L'))

#格式改为uint8
im = Image.fromarray(a.astype('uint8'))
im.save('project1.jpg')
```

<img width="450" height="300" src=project-1/1.jpg /></img>
初始

<img width="450" height="300" src=project-1/project1.jpg/></img>
修改
