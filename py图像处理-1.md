```python
from PIL import Image
import numpy as np

from PIL import Image
import numpy as np

a=np.asarray(Image.open('1.jpg').convert('L'))
im = Image.fromarray(a.astype('uint8'))
im.save('project1.jpg')
```
![Image of Yaktocat](project-1/1.jpg)

![Image of Yaktocat](project-1/project1.jpg)
