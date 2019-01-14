* * *

layout: article language: 'en' version: '4.0' title: 'Phalcon\Mvc\Model\MetaData\Strategy\Introspection'

* * *

# Class **Phalcon\Mvc\Model\MetaData\Strategy\Introspection**

*implements* [Phalcon\Mvc\Model\MetaData\StrategyInterface](/4.0/en/api/Phalcon_Mvc_Model_MetaData_StrategyInterface)

<a href="https://github.com/phalcon/cphalcon/tree/v4.0.0/phalcon/mvc/model/metadata/strategy/introspection.zep" class="btn btn-default btn-sm">源码在GitHub</a>

Queries the table meta-data in order to introspect the model's metadata

## 方法

final public **getMetaData** ([Phalcon\Mvc\ModelInterface](/4.0/en/api/Phalcon_Mvc_ModelInterface) $model, [Phalcon\DiInterface](/4.0/en/api/Phalcon_DiInterface) $dependencyInjector)

The meta-data is obtained by reading the column descriptions from the database information schema

final public **getColumnMaps** ([Phalcon\Mvc\ModelInterface](/4.0/en/api/Phalcon_Mvc_ModelInterface) $model, [Phalcon\DiInterface](/4.0/en/api/Phalcon_DiInterface) $dependencyInjector)

Read the model's column map, this can't be inferred