---
id: routing
title: Routing
hide_title: false
---

Controllers are responsible for handling requests.

First of all, everything must be registered in the route file.

```javascript routes/web.ts

import { Router } from 'https://deno.land/x/atenas@stable/mod.ts'
import Controller from '../app/controllers/Controller.controller.ts'


- ̶R̶o̶u̶t̶e̶r̶.̶u̶s̶e̶(̶T̶e̶s̶t̶M̶i̶d̶d̶l̶e̶w̶a̶r̶e̶)̶.̶g̶e̶t̶(̶'̶/̶'̶,̶ ̶H̶e̶l̶l̶o̶C̶o̶n̶t̶r̶o̶l̶l̶e̶r̶.̶w̶o̶r̶l̶d̶)̶
+ Router.get('/routename', Controller.method)

export default Router

```

Be aware that this method will be changed soon, we are preparing updates in our framework so that this medium is extinguished.
