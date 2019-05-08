# iplocationzh
这是一个能够通过 Ip，获取该 IP 所在的位置，例如通过 ip：171.12.10.156 可以获得是 中国河南郑州，以及中国行政区划代码(支持到市级), 同样能获得国外的地址，但是没有国内详细。

# Usage
```
require 'vendor/autoload.php';  
use kqtec\iplocationzh\Ip;  
$add=Ip::get_real_ip()?:'171.12.10.156'
var_dump(Ip::find($add));
```
