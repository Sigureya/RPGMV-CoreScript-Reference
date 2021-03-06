# Class: ConfigManager

The static class that manages the configuration data.

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `bgmVolume` | [Number](Number.md) | [static] |
| `bgsVolume` | [Number](Number.md) | [static] |
| `meVolume` | [Number](Number.md) | [static] |
| `seVolume` | [Number](Number.md) | [static] |

<dl>
</dl>

### Members

#### (static) alwaysDash :Boolean

##### Type:

* Boolean

<dl>
</dl>

#### (static) commandRemember :Boolean

##### Type:

* Boolean

<dl>
</dl>

### Methods

#### (static) applyData (config)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `config` | [MV.ConfigData](MV.ConfigData.md) |  |

<dl>
</dl>

#### (static) load ()

<dl>
</dl>

#### (static) makeData () → {[MV.ConfigData](MV.ConfigData.md)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>MV.ConfigData</a></span>
                </dd>
            </dl>

#### (static) readFlag (config, name) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `config` | [MV.ConfigData](MV.ConfigData.md) |  |
| `name` | [String](String.md) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### (static) readVolume (config, name) → {[Number](Number.md)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `config` | [MV.ConfigData](MV.ConfigData.md) |  |
| `name` | [String](String.md) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### (static) save ()

<dl>
</dl>


 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
