# cholera

## 1. 파일 내려받기
```python
!git clone https://github.com/thiskorea81/cholera.git
```

## 2. 모듈 불러오기
```python
import numpy as np
import pandas as pd
import folium
from scipy.spatial.distance import cdist
```

## 3. 데이터 저장
```python
펌프위치 = pd.read_csv('/content/cholera/펌프 위치.csv')
콜레라환자 = pd.read_csv('/content/cholera/콜레라 환자.csv')
```

### 교과서 224 부록 참조
