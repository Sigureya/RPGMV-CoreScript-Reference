# Class: Window_Base

## (abstract) Window_Base (x, y, width, height, _iconWidth, _iconHeight, _faceWidth, _faceHeight, _opening, _closing)

#### (abstract) new Window_Base (x, y, width, height, _iconWidth, _iconHeight, _faceWidth, _faceHeight, _opening, _closing)

The superclass of [Window_EquipStatus](Window_EquipStatus.html), [Window_Gold](Window_Gold.html), [Window_Help](Window_Help.html), [Window_MapName](Window_MapName.html), [Window_Message](Window_Message.html), [Window_NameEdit](Window_NameEdit.html), [Window_ScrollText](Window_ScrollText.html), [Window_ShopStatus](Window_ShopStatus.html), [Window_SkillStatus](Window_SkillStatus.html) and [Window_Selectable](Window_Selectable.html)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |
| `width` | [Number](Number.html) |  |
| `height` | [Number](Number.html) |  |
| `_iconWidth` | [Number](Number.html) | The standard icon width. default : 32 |
| `_iconHeight` | [Number](Number.html) | The standard icon height. default : 32 |
| `_faceWidth` | [Number](Number.html) | The standard face width. default : 144 |
| `_faceHeight` | [Number](Number.html) | The standard face height. default : 144 |
| `_opening` | Boolean | The opening property; determines if the window is opening. |
| `_closing` | Boolean | The closing property; determines if the window is closing. |

<dl>
</dl>

### Extends

* [Window](Window.html)

### Methods

#### activate ()


<dl>
</dl>

#### actorName (actorIndex) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorIndex` | [Number](Number.html) |  |

<dl>
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

#### calcTextHeight (textState, all) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |
| `all` | Boolean |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### canvasToLocalX (x) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  |

<dl>
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
</dl>

#### changeTextColor (color)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `color` | [String](String.html) |  |

<dl>
</dl>

#### close ()


<dl>
</dl>

#### contentsHeight () → {[Number](Number.html)}


<dl>
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
</dl>

#### crisisColor () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### deactivate ()


<dl>
</dl>

#### deathColor () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### dimColor1 () → {[String](String.html)}


<dl>
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
</dl>

#### drawActorLevel (actor, x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
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
</dl>

#### drawIcon (iconIndex, x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
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
</dl>

#### drawTextEx (text, x, y) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.html) |  |
| `x` | [Number](Number.html) |  |
| `y` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### fittingHeight (numLines) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `numLines` | [Number](Number.html) |  |

<dl>
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
</dl>

#### hideBackgroundDimmer ()


<dl>
</dl>

#### hpColor (actor) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
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
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
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
                            <a>Window#initialize</a>
                        </li>
                    </ul>
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

#### isOpening () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### lineHeight () → {[Number](Number.html)}


<dl>
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
</dl>

#### makeFontBigger ()


<dl>
</dl>

#### makeFontSmaller ()


<dl>
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
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### normalColor () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### obtainEscapeCode (textState)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### obtainEscapeParam (textState) → {number|string}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>number</span> | <span>string</span>
                </dd>
            </dl>

#### open ()


<dl>
</dl>

#### paramchangeTextColor (change)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `change` | [Number](Number.html) |  |

<dl>
</dl>

#### partyMemberName (partyMemberIndex) → {[String](String.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `partyMemberIndex` | [Number](Number.html) |  |

<dl>
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
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### powerDownColor () → {[String](String.html)}


<dl>
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
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### processCharacter (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### processDrawIcon (iconIndex, textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.html) |  |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### processEscapeCharacter (code, textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [String](String.html) |  |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### processNewLine (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### processNewPage (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### processNormalCharacter (textState)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.html) |  |

<dl>
</dl>

#### refreshDimmerBitmap ()


<dl>
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

#### reserveFaceImages ()


<dl>
</dl>

#### resetFontSettings ()


<dl>
</dl>

#### resetTextColor ()


<dl>
</dl>

#### setBackgroundType (type)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `type` | [Number](Number.html) |  |

<dl>
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

#### show ()


<dl>
</dl>

#### showBackgroundDimmer ()


<dl>
</dl>

#### standardBackOpacity () → {[Number](Number.html)}


<dl>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Window#update</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateBackgroundDimmer ()


<dl>
</dl>

#### updateBackOpacity () → {[Number](Number.html)}


<dl>
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
</dl>

#### updateOpen ()


<dl>
</dl>

#### updatePadding ()


<dl>
</dl>

#### updateTone ()


<dl>
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