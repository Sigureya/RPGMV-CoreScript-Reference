# Class: Window_BattleItem

## Window_BattleItem (x, y, width, height)

#### new Window_BattleItem (x, y, width, height)

The window for selecting an item to use on the battle screen.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `height` | [Number](Number.html) |  |

<dl>
</dl>

### Extends

* [Window_ItemList](Window_ItemList.html)

### Methods

#### activate ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#activate</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### actorName (actorIndex) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorIndex` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#actorName</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### addChild (child) → {Object}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object | The child to add |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#addChild</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### addChildAt (child, index) → {Object}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object | The child to add |
| `index` | [Number](Number.html) | The index to place the child in |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#addChildAt</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### addChildToBack (child) → {Object}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object | The child to add |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#addChildToBack</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### bottomRow () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#bottomRow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### calcTextHeight (textState, all) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |
| `all` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#calcTextHeight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### callCancelHandler ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#callCancelHandler</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### callHandler (symbol)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#callHandler</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### callOkHandler ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#callOkHandler</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### callUpdateHelp ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#callUpdateHelp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### canvasToLocalX (x) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#canvasToLocalX</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### canvasToLocalY (y) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#canvasToLocalY</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### changePaintOpacity (enabled)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `enabled` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#changePaintOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### changeTextColor (color)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `color` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#changeTextColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearItem (index)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#clearItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### close ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#close</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### contentsHeight () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#contentsHeight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### contentsWidth () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#contentsWidth</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### convertEscapeCharacters (text) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#convertEscapeCharacters</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### createContents ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#createContents</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### crisisColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#crisisColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### cursorAll () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorAll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### cursorDown (wrap)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorDown</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### cursorFixed () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorFixed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### cursorLeft (wrap)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorLeft</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### cursorPagedown ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorPagedown</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### cursorPageup ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorPageup</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### cursorRight (wrap)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorRight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### cursorUp (wrap)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#cursorUp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### deactivate ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#deactivate</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### deathColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#deathColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### deselect ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#deselect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### dimColor1 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#dimColor1</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### dimColor2 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#dimColor2</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### drawActorCharacter (actor, x, y)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorClass (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorClass</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorFace (actor, x, y, width, height)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `height` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorFace</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorHp (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorHp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorIcons (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorIcons</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorLevel (actor, x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorLevel</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorMp (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorMp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorName (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorName</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorNickname (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorNickname</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorSimpleStatus (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorSimpleStatus</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawActorTp (actor, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawActorTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawAllItems ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#drawAllItems</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawCharacter (characterName, characterIndex, x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `characterName` | [String](String.html) |  |
| `characterIndex` | [Number](Number.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawCurrencyValue (value, unit, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |
| `unit` | [String](String.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawCurrencyValue</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawCurrentAndMax (current, max, x, y, width, color1, color2)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `current` | [Number](Number.html) |  |
| `max` | [Number](Number.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `color1` | [String](String.html) |  |
| `color2` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawCurrentAndMax</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawFace (faceName, faceIndex, x, y, width opt, height opt)

##### Parameters:

| Name | Type | Attributes | Description |
| --- | --- | --- | --- |
| `faceName` | [String](String.html) |  |  |
| `faceIndex` | [Number](Number.html) |  |  |
| `x` | [Number](Number.html) |  |  |
| `y` | [Number](Number.html) |  |  |
| `width` | [Number](Number.html) | <optional> |  |
| `height` | [Number](Number.html) | <optional> |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawFace</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawGauge (x, y, width, rate, color1, color2)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `rate` | [Number](Number.html) |  |
| `color1` | [String](String.html) |  |
| `color2` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawGauge</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawIcon (iconIndex, x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawIcon</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawItem (index)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#drawItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawItemName (item, x, y, width)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawItemName</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawItemNumber (item, x, y, width)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#drawItemNumber</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawText (text, x, y, maxWidth, align)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | string |number |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `maxWidth` | [Number](Number.html) |  |
| `align` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawText</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### drawTextEx (text, x, y) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#drawTextEx</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### ensureCursorVisible ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#ensureCursorVisible</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### fittingHeight (numLines) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `numLines` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#fittingHeight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### gaugeBackColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#gaugeBackColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### hide ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#hide</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### hideBackgroundDimmer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#hideBackgroundDimmer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### hideHelpWindow ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#hideHelpWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### hitTest (x, y) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#hitTest</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### hpColor (actor) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#hpColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### hpGaugeColor1 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#hpGaugeColor1</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### hpGaugeColor2 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#hpGaugeColor2</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### includes (item)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#includes</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### index () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#index</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### initialize (x, y, width, height)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `height` | [Number](Number.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#initialize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isCancelEnabled () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isCancelEnabled</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isCancelTriggered () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isCancelTriggered</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isClosed ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#isClosed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isClosing () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#isClosing</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isContentsArea (x, y) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isContentsArea</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isCurrentItemEnabled () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#isCurrentItemEnabled</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isCursorMovable () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isCursorMovable</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isCursorVisible () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isCursorVisible</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isHandled (symbol) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isHandled</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isHorizontal () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isHorizontal</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isOkEnabled () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isOkEnabled</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isOkTriggered () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isOkTriggered</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isOpen ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#isOpen</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isOpenAndActive () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isOpenAndActive</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isOpening () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#isOpening</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isTouchedInsideFrame () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isTouchedInsideFrame</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isTouchOkEnabled () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#isTouchOkEnabled</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### item () → {[RPG.BaseItem](RPG.BaseItem.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#item</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.BaseItem</a></span>
                </dd>
            </dl>

#### itemHeight () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#itemHeight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### itemRect (index) → {[Rectangle](Rectangle.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#itemRect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Rectangle</a></span>
                </dd>
            </dl>

#### itemRectForText (index) → {[Rectangle](Rectangle.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#itemRectForText</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Rectangle</a></span>
                </dd>
            </dl>

#### itemWidth () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#itemWidth</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### lineHeight () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#lineHeight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### loadWindowskin ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#loadWindowskin</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### makeFontBigger ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#makeFontBigger</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### makeFontSmaller ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#makeFontSmaller</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### makeItemList (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#makeItemList</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### maxCols () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#maxCols</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxItems () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#maxItems</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxPageItems () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#maxPageItems</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxPageRows () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#maxPageRows</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxRows () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#maxRows</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxTopRow () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#maxTopRow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### move (x, y, width, height)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) | The x coordinate of the window |
| `y` | [Number](Number.html) | The y coordinate of the window |
| `width` | [Number](Number.html) | The width of the window |
| `height` | [Number](Number.html) | The height of the window |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#move</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### mpColor (actor) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#mpColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### mpCostColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#mpCostColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### mpGaugeColor1 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#mpGaugeColor1</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### mpGaugeColor2 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#mpGaugeColor2</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### needsNumber () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#needsNumber</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### normalColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#normalColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### numberWidth () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#numberWidth</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### obtainEscapeCode (textState)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#obtainEscapeCode</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### obtainEscapeParam (textState) → {number|string}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#obtainEscapeParam</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>number</span> | <span>string</span>
                </dd>
            </dl>

#### onTouch (triggered)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `triggered` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#onTouch</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### open ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#open</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### paramchangeTextColor (change)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `change` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#paramchangeTextColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### partyMemberName (partyMemberIndex) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `partyMemberIndex` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#partyMemberName</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### pendingColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#pendingColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### playBuzzerSound ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#playBuzzerSound</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### playOkSound ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#playOkSound</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### powerDownColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#powerDownColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### powerUpColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#powerUpColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### processCancel ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processCancel</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processCharacter (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processCursorMove ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processCursorMove</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processDrawIcon (iconIndex, textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.html) |  |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processDrawIcon</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processEscapeCharacter (code, textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [String](String.html) |  |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processEscapeCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processHandling ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processHandling</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processNewLine (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processNewLine</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processNewPage (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processNewPage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processNormalCharacter (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#processNormalCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processOk ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processOk</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processPagedown ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processPagedown</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processPageup ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processPageup</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processTouch ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processTouch</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processWheel ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#processWheel</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### redrawCurrentItem ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#redrawCurrentItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### redrawItem (index)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#redrawItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### refresh ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#refresh</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### refreshDimmerBitmap ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#refreshDimmerBitmap</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeChild (child) → {Object}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object | The child to remove |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#removeChild</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### removeChildAt (index) → {Object}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) | The index to get the child from |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#removeChildAt</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### reselect ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#reselect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### reserveFaceImages ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#reserveFaceImages</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetFontSettings ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#resetFontSettings</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetScroll ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#resetScroll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetTextColor ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#resetTextColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### row () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#row</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### scrollDown ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#scrollDown</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### scrollUp ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#scrollUp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### select (index)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#select</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### selectLast ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#selectLast</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setBackgroundType (type)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `type` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#setBackgroundType</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setBottomRow (row)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `row` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setBottomRow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setCategory (category)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `category` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#setCategory</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setCursorAll (cursorAll)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `cursorAll` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setCursorAll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setCursorFixed (cursorFixed)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `cursorFixed` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setCursorFixed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setCursorRect (x, y, width, height)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) | The x coordinate of the cursor |
| `y` | [Number](Number.html) | The y coordinate of the cursor |
| `width` | [Number](Number.html) | The width of the cursor |
| `height` | [Number](Number.html) | The height of the cursor |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#setCursorRect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setHandler (symbol, method)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.html) |  |
| `method` | * |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setHandler</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setHelpWindow (helpWindow)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `helpWindow` |  |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setHelpWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setHelpWindowItem (item)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | * |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setHelpWindowItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setTone (r, g, b)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `r` | [Number](Number.html) | The red value in the range (-255, 255) |
| `g` | [Number](Number.html) | The green value in the range (-255, 255) |
| `b` | [Number](Number.html) | The blue value in the range (-255, 255) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#setTone</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setTopRow (row)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `row` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#setTopRow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### show ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#show</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### showBackgroundDimmer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#showBackgroundDimmer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### showHelpWindow ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#showHelpWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### spacing () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#spacing</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### standardBackOpacity () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#standardBackOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### standardFontFace () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#standardFontFace</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### standardFontSize () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#standardFontSize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### standardPadding () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#standardPadding</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### systemColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#systemColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### textColor (n) → {*}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `n` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#textColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>*</span>
                </dd>
            </dl>

#### textPadding () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#textPadding</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### textWidth (text) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#textWidth</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### topIndex () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#topIndex</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### topRow () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#topRow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### tpColor (actor) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#tpColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### tpCostColor () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#tpCostColor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### tpGaugeColor1 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#tpGaugeColor1</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### tpGaugeColor2 () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#tpGaugeColor2</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### translucentOpacity () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#translucentOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### update ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#update</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateArrows ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#updateArrows</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateBackgroundDimmer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updateBackgroundDimmer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateBackOpacity () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updateBackOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### updateClose ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updateClose</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateCursor ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#updateCursor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateHelp ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_ItemList#updateHelp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateInputData ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Selectable#updateInputData</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateOpen ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updateOpen</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updatePadding ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updatePadding</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateTone ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window_Base#updateTone</a>
                        </li>
                    </ul>
                </dd>
            </dl>
 <details>

## [Home](index.html)

### Classes

* [Array](Array.html)
* [AudioManager](AudioManager.html)
* [BattleManager](BattleManager.html)
* [Bitmap](Bitmap.html)
* [CacheEntry](CacheEntry.html)
* [CacheMap](CacheMap.html)
* [ConfigManager](ConfigManager.html)
* [DataManager](DataManager.html)
* [Decrypter](Decrypter.html)
* [Game_Action](Game_Action.html)
* [Game_ActionResult](Game_ActionResult.html)
* [Game_Actor](Game_Actor.html)
* [Game_Actors](Game_Actors.html)
* [Game_Battler](Game_Battler.html)
* [Game_BattlerBase](Game_BattlerBase.html)
* [Game_Character](Game_Character.html)
* [Game_CharacterBase](Game_CharacterBase.html)
* [Game_CommonEvent](Game_CommonEvent.html)
* [Game_Enemy](Game_Enemy.html)
* [Game_Event](Game_Event.html)
* [Game_Follower](Game_Follower.html)
* [Game_Followers](Game_Followers.html)
* [Game_Interpreter](Game_Interpreter.html)
* [Game_Item](Game_Item.html)
* [Game_Map](Game_Map.html)
* [Game_Message](Game_Message.html)
* [Game_Party](Game_Party.html)
* [Game_Picture](Game_Picture.html)
* [Game_Player](Game_Player.html)
* [Game_Screen](Game_Screen.html)
* [Game_SelfSwitches](Game_SelfSwitches.html)
* [Game_Switches](Game_Switches.html)
* [Game_System](Game_System.html)
* [Game_Temp](Game_Temp.html)
* [Game_Timer](Game_Timer.html)
* [Game_Troop](Game_Troop.html)
* [Game_Unit](Game_Unit.html)
* [Game_Variables](Game_Variables.html)
* [Game_Vehicle](Game_Vehicle.html)
* [Graphics](Graphics.html)
* [Html5Audio](Html5Audio.html)
* [ImageCache](ImageCache.html)
* [ImageManager](ImageManager.html)
* [Input](Input.html)
* [JsonEx](JsonEx.html)
* [Math](Math.html)
* [AudioParameters](MV.AudioParameters.html)
* [BattleLogMethod](MV.BattleLogMethod.html)
* [BattlerAnimation](MV.BattlerAnimation.html)
* [BattleRewards](MV.BattleRewards.html)
* [CommandItem](MV.CommandItem.html)
* [ConfigData](MV.ConfigData.html)
* [DatabaseFile](MV.DatabaseFile.html)
* [Matrix](MV.Matrix.html)
* [Motion](MV.Motion.html)
* [PluginSettings](MV.PluginSettings.html)
* [SaveContents](MV.SaveContents.html)
* [SaveFileInfo](MV.SaveFileInfo.html)
* [TextState](MV.TextState.html)
* [TouchInputEvents](MV.TouchInputEvents.html)
* [Number](Number.html)
* [PluginManager](PluginManager.html)
* [Point](Point.html)
* [Rectangle](Rectangle.html)
* [RequestQueue](RequestQueue.html)
* [ResourceHandler](ResourceHandler.html)
* [Actor](RPG.Actor.html)
* [Animation](RPG.Animation.html)
* [Timing](RPG.Animation.Timing.html)
* [Armor](RPG.Armor.html)
* [AudioFile](RPG.AudioFile.html)
* [BaseItem](RPG.BaseItem.html)
* [BattleEventPage](RPG.BattleEventPage.html)
* [Conditions](RPG.BattleEventPage.Conditions.html)
* [Class](RPG.Class.html)
* [Learning](RPG.Class.Learning.html)
* [CommonEvent](RPG.CommonEvent.html)
* [Damage](RPG.Damage.html)
* [Effect](RPG.Effect.html)
* [Enemy](RPG.Enemy.html)
* [Action](RPG.Enemy.Action.html)
* [DropItem](RPG.Enemy.DropItem.html)
* [EquipItem](RPG.EquipItem.html)
* [Event](RPG.Event.html)
* [EventCommand](RPG.EventCommand.html)
* [EventPage](RPG.EventPage.html)
* [Conditions](RPG.EventPage.Conditions.html)
* [Image](RPG.EventPage.Image.html)
* [Item](RPG.Item.html)
* [Map](RPG.Map.html)
* [Encounter](RPG.Map.Encounter.html)
* [MapInfo](RPG.MapInfo.html)
* [MetaData](RPG.MetaData.html)
* [MoveCommand](RPG.MoveCommand.html)
* [MoveRoute](RPG.MoveRoute.html)
* [Skill](RPG.Skill.html)
* [State](RPG.State.html)
* [System](RPG.System.html)
* [AttackMotion](RPG.System.AttackMotion.html)
* [Terms](RPG.System.Terms.html)
* [TestBattler](RPG.System.TestBattler.html)
* [Vehicle](RPG.System.Vehicle.html)
* [Tileset](RPG.Tileset.html)
* [Trait](RPG.Trait.html)
* [Troop](RPG.Troop.html)
* [UsableItem](RPG.UsableItem.html)
* [Weapon](RPG.Weapon.html)
* [Scene_Base](Scene_Base.html)
* [Scene_Battle](Scene_Battle.html)
* [Scene_Boot](Scene_Boot.html)
* [Scene_Debug](Scene_Debug.html)
* [Scene_Equip](Scene_Equip.html)
* [Scene_File](Scene_File.html)
* [Scene_GameEnd](Scene_GameEnd.html)
* [Scene_Gameover](Scene_Gameover.html)
* [Scene_Item](Scene_Item.html)
* [Scene_ItemBase](Scene_ItemBase.html)
* [Scene_Load](Scene_Load.html)
* [Scene_Map](Scene_Map.html)
* [Scene_Menu](Scene_Menu.html)
* [Scene_MenuBase](Scene_MenuBase.html)
* [Scene_Name](Scene_Name.html)
* [Scene_Options](Scene_Options.html)
* [Scene_Save](Scene_Save.html)
* [Scene_Shop](Scene_Shop.html)
* [Scene_Skill](Scene_Skill.html)
* [Scene_Status](Scene_Status.html)
* [Scene_Title](Scene_Title.html)
* [SceneManager](SceneManager.html)
* [ScreenSprite](ScreenSprite.html)
* [ShaderTilemap](ShaderTilemap.html)
* [SoundManager](SoundManager.html)
* [Sprite](Sprite.html)
* [Sprite_Actor](Sprite_Actor.html)
* [Sprite_Animation](Sprite_Animation.html)
* [Sprite_Balloon](Sprite_Balloon.html)
* [Sprite_Base](Sprite_Base.html)
* [Sprite_Battler](Sprite_Battler.html)
* [Sprite_Button](Sprite_Button.html)
* [Sprite_Character](Sprite_Character.html)
* [Sprite_Damage](Sprite_Damage.html)
* [Sprite_Destination](Sprite_Destination.html)
* [Sprite_Enemy](Sprite_Enemy.html)
* [Sprite_Picture](Sprite_Picture.html)
* [Sprite_StateIcon](Sprite_StateIcon.html)
* [Sprite_StateOverlay](Sprite_StateOverlay.html)
* [Sprite_Timer](Sprite_Timer.html)
* [Sprite_Weapon](Sprite_Weapon.html)
* [Spriteset_Base](Spriteset_Base.html)
* [Spriteset_Battle](Spriteset_Battle.html)
* [Spriteset_Map](Spriteset_Map.html)
* [Stage](Stage.html)
* [StorageManager](StorageManager.html)
* [String](String.html)
* [TextManager](TextManager.html)
* [Tilemap](Tilemap.html)
* [TilingSprite](TilingSprite.html)
* [ToneFilter](ToneFilter.html)
* [ToneSprite](ToneSprite.html)
* [TouchInput](TouchInput.html)
* [Member](Troop.Member.html)
* [Utils](Utils.html)
* [Weather](Weather.html)
* [WebAudio](WebAudio.html)
* [Window](Window.html)
* [Window_ActorCommand](Window_ActorCommand.html)
* [Window_Base](Window_Base.html)
* [Window_BattleActor](Window_BattleActor.html)
* [Window_BattleEnemy](Window_BattleEnemy.html)
* [Window_BattleItem](Window_BattleItem.html)
* [Window_BattleLog](Window_BattleLog.html)
* [Window_BattleSkill](Window_BattleSkill.html)
* [Window_BattleStatus](Window_BattleStatus.html)
* [Window_ChoiceList](Window_ChoiceList.html)
* [Window_Command](Window_Command.html)
* [Window_DebugEdit](Window_DebugEdit.html)
* [Window_DebugRange](Window_DebugRange.html)
* [Window_EquipCommand](Window_EquipCommand.html)
* [Window_EquipItem](Window_EquipItem.html)
* [Window_EquipSlot](Window_EquipSlot.html)
* [Window_EquipStatus](Window_EquipStatus.html)
* [Window_EventItem](Window_EventItem.html)
* [Window_GameEnd](Window_GameEnd.html)
* [Window_Gold](Window_Gold.html)
* [Window_Help](Window_Help.html)
* [Window_HorzCommand](Window_HorzCommand.html)
* [Window_ItemCategory](Window_ItemCategory.html)
* [Window_ItemList](Window_ItemList.html)
* [Window_MapName](Window_MapName.html)
* [Window_MenuActor](Window_MenuActor.html)
* [Window_MenuCommand](Window_MenuCommand.html)
* [Window_MenuStatus](Window_MenuStatus.html)
* [Window_Message](Window_Message.html)
* [Window_NameEdit](Window_NameEdit.html)
* [Window_NameInput](Window_NameInput.html)
* [Window_NumberInput](Window_NumberInput.html)
* [Window_Options](Window_Options.html)
* [Window_PartyCommand](Window_PartyCommand.html)
* [Window_SavefileList](Window_SavefileList.html)
* [Window_ScrollText](Window_ScrollText.html)
* [Window_Selectable](Window_Selectable.html)
* [Window_ShopBuy](Window_ShopBuy.html)
* [Window_ShopCommand](Window_ShopCommand.html)
* [Window_ShopNumber](Window_ShopNumber.html)
* [Window_ShopSell](Window_ShopSell.html)
* [Window_ShopStatus](Window_ShopStatus.html)
* [Window_SkillList](Window_SkillList.html)
* [Window_SkillStatus](Window_SkillStatus.html)
* [Window_SkillType](Window_SkillType.html)
* [Window_Status](Window_Status.html)
* [Window_TitleCommand](Window_TitleCommand.html)
* [WindowLayer](WindowLayer.html)

### Namespaces

* [MV](MV.html)
* [RPG](RPG.html)

### Global

* [$dataActors](global.html#$dataActors)
* [$dataAnimations](global.html#$dataAnimations)
* [$dataArmors](global.html#$dataArmors)
* [$dataClasses](global.html#$dataClasses)
* [$dataCommonEvents](global.html#$dataCommonEvents)
* [$dataEnemies](global.html#$dataEnemies)
* [$dataItems](global.html#$dataItems)
* [$dataMap](global.html#$dataMap)
* [$dataMapInfos](global.html#$dataMapInfos)
* [$dataSkills](global.html#$dataSkills)
* [$dataStates](global.html#$dataStates)
* [$dataSystem](global.html#$dataSystem)
* [$dataTilesets](global.html#$dataTilesets)
* [$dataTroops](global.html#$dataTroops)
* [$dataWeapons](global.html#$dataWeapons)
* [$gameActors](global.html#$gameActors)
* [$gameMap](global.html#$gameMap)
* [$gameMessage](global.html#$gameMessage)
* [$gameParty](global.html#$gameParty)
* [$gamePlayer](global.html#$gamePlayer)
* [$gameScreen](global.html#$gameScreen)
* [$gameSelfSwitches](global.html#$gameSelfSwitches)
* [$gameSwitches](global.html#$gameSwitches)
* [$gameSystem](global.html#$gameSystem)
* [$gameTemp](global.html#$gameTemp)
* [$gameTimer](global.html#$gameTimer)
* [$gameTroop](global.html#$gameTroop)
* [$gameVariables](global.html#$gameVariables)
* [$plugins](global.html#$plugins)
* [$testEvent](global.html#$testEvent)

</details>
 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)