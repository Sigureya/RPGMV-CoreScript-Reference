# Class: Class

## [RPG](RPG.md).  Class ()

#### new Class ()

The data class for class. Define to [$dataClasses](global.html#$dataClasses) as Array.

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `id` | [Number](Number.md) | The ID. |
| `name` | [String](String.md) | The name. |
| `expParams` | [Array](Array.md).<[Number](Number.md)> | An array of values that decides the experience curve. The subscripts are as follows: 0: Base value 1: Extra value 2: Acceleration A 3: Acceleration B |
| `params` | [Array](Array.md).<[Array](Array.md).<[Number](Number.md)>> | The parameter development curve. A 2-dimensional array containing ordinary parameters according to level (Table). The format is params[param_id, level], and param_id is assigned as follows: 0: Maximum hit points 1: Maximum magic points 2: Attack power 3: Defense power 4: Magic attack power 5: Magic defense power 6: Agility 7: Luck |
| `learnings` | [Array](Array.md).<[RPG.Class.Learning](RPG.Class.Learning.md)> | The skills to learn. An array of RPG.Class.Learning. |
| `traits` | [Array](Array.md).<[RPG.Trait](RPG.Trait.md)> | The array of Trait data. |

<dl>
</dl>

### Extends

* [RPG.MetaData](RPG.MetaData.md)

### Classes

<dl>
                    <dt><a>Learning</a></dt>
                    <dd></dd>
                </dl>
 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
