#Usage


**init.lua**
```
require 'module'

import 'my_module'
local func = import('my_module', true).func --equivalent

func()
```

**my_module**

```
module()

function func()
  print 'Hello from my_module'
end
```
