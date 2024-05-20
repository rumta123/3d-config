# Информация о репозетории

Запуск с помощью OPen With live server

 <script type="importmap">
        {
            "imports": {
                "three": "https://unpkg.com/three@0.139.0/build/three.module.js",
                "OrbitControls": "https://unpkg.com/three@0.139.0/examples/jsm/controls/OrbitControls.js",
                "GLTFLoader": "https://unpkg.com/three@0.139.0/examples/jsm/loaders/GLTFLoader.js",
                "RectAreaLightHelper": "https://unpkg.com/three@0.139.0/examples/jsm/helpers/RectAreaLightHelper.js",
                "RectAreaLightUniformsLib": "https://unpkg.com/three@0.139.0/examples/jsm/lights/RectAreaLightUniformsLib.js"
            }
        }
    </script>
```
Так в html мы подгружаем файлы с облака. Затем в JS импортируем:

```js

import * as THREE from 'three';
import { OrbitControls } from 'OrbitControls';
import { GLTFLoader } from 'GLTFLoader';
import { RectAreaLightHelper } from 'RectAreaLightHelper'
import { RectAreaLightUniformsLib } from 'RectAreaLightUniformsLib';
```

```
