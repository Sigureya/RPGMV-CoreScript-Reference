# Class: Game_Picture

## Game_Picture ()

#### new Game_Picture ()

The game object class for a picture.

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_name` | [String](String.md) |  |
| `_origin` | [Number](Number.md) |  |
| `_x` | [Number](Number.md) |  |
| `_y` | [Number](Number.md) |  |
| `_scaleX` | [Number](Number.md) |  |
| `_scaleY` | [Number](Number.md) |  |
| `_opacity` | [Number](Number.md) |  |
| `_blendMode` | [Number](Number.md) |  |
| `_targetX` | [Number](Number.md) |  |
| `_targetY` | [Number](Number.md) |  |
| `_targetScaleX` | [Number](Number.md) |  |
| `_targetScaleY` | [Number](Number.md) |  |
| `_targetOpacity` | [Number](Number.md) |  |
| `_duration` | [Number](Number.md) |  |
| `_tone` | [Array](Array.md).<[Number](Number.md)> |  |
| `_toneTarget` | [Array](Array.md).<[Number](Number.md)> |  |
| `_toneDuration` | [Number](Number.md) |  |
| `_angle` | [Number](Number.md) |  |
| `_rotationSpeed` | [Number](Number.md) |  |

<dl>
</dl>

### Methods

#### angle () → {[Number](Number.md)}

Returns the angle of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### blendMode () → {[Number](Number.md)}

Returns the blend mode of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### erase ()

Erases the game picture.
<dl>
</dl>

#### initBasic ()

<dl>
</dl>

#### initialize ()

 オブジェクト生成時の初期化。
<dl>
</dl>

#### initRotation ()

<dl>
</dl>

#### initTarget ()

<dl>
</dl>

#### initTone ()

<dl>
</dl>

#### move (origin, x, y, scaleX, scaleY, opacity, blendMode, duration)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `origin` | [Number](Number.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `scaleX` | [Number](Number.md) |  |
| `scaleY` | [Number](Number.md) |  |
| `opacity` | [Number](Number.md) |  |
| `blendMode` | [Number](Number.md) |  |
| `duration` | [Number](Number.md) |  |

<dl>
</dl>

#### name () → {[String](String.md)}

Returns the name of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### opacity () → {[Number](Number.md)}

Returns the opacity of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### origin () → {[Number](Number.md)}

Returns the origin of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### rotate (speed)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `speed` | [Number](Number.md) |  |

<dl>
</dl>

#### scaleX () → {[Number](Number.md)}

Returns x scale of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### scaleY () → {[Number](Number.md)}

Returns the y scale of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### show (name, origin, x, y, scaleX, scaleY, opacity, blendMode)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `name` | [String](String.md) |  |
| `origin` | [Number](Number.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `scaleX` | [Number](Number.md) |  |
| `scaleY` | [Number](Number.md) |  |
| `opacity` | [Number](Number.md) |  |
| `blendMode` | [Number](Number.md) |  |

<dl>
</dl>

#### tint (tone, duration)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `tone` | [Array](Array.md).<[Number](Number.md)> |  |
| `duration` | [Number](Number.md) |  |

<dl>
</dl>

#### tone () → {[Array](Array.md).<[Number](Number.md)>}

Returns the tone of the game picture.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### update ()

Updates the game picture.
<dl>
</dl>

#### updateMove ()

Updates the movement of the game picture.
<dl>
</dl>

#### updateRotation ()

Updates the rotation of the game picture.
<dl>
</dl>

#### updateTone ()

Updates the tone of the game picture.
<dl>
</dl>

#### x () → {[Number](Number.md)}

Returns the picture x coordinate.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### y () → {[Number](Number.md)}

Returns the picture y coordinate.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>
 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
