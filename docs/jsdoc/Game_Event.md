# Class: Game_Event

## Game_Event ()

#### new Game_Event ()

 マップに配置する[イベント]を定義したオブジェクト。[実行内容]を得る [Game_Event#event](Game_Event.html#event) メソッドなどを含む。

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_mapId` | [Number](Number.html) |  |
| `_eventId` | [Number](Number.html) |  |
| `_moveType` | [Number](Number.html) |  |
| `_trigger` | [Number](Number.html) |  |
| `_starting` | Boolean |  |
| `_erased` | Boolean |  |
| `_pageIndex` | [Number](Number.html) |  |
| `_originalPattern` | [Number](Number.html) |  |
| `_originalDirection` | [Number](Number.html) |  |
| `_prelockDirection` | [Number](Number.html) |  |
| `_locked` | Boolean |  |

<dl>
</dl>

### Extends

* [Game_Character](Game_Character.html)

### Methods

#### advanceMoveRouteIndex ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#advanceMoveRouteIndex</a>
                        </li>
                    </ul>
                </dd>
                <dt>To Do:</dt>
                <dd>
                    <ul>
                        <li>&#x3053;&#x306E;&#x7528;&#x8A9E;&#x306E;&#x610F;&#x5473;&#x304C;&#x5206;&#x304B;&#x3063;&#x305F;&#x3089;&#x6559;&#x3048;&#x3066;&#x304F;&#x3060;&#x3055;&#x3044;</li>
                    </ul>
                </dd>
            </dl>

#### animationId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#animationId</a>
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

#### animationWait () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#animationWait</a>
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

#### balloonId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#balloonId</a>
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

#### blendMode () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#blendMode</a>
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

#### bushDepth () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#bushDepth</a>
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

#### canPass (x, y, d) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#canPass</a>
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

#### canPassDiagonally (x, y, horz, vert) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |
| `horz` | [Number](Number.html) |  横方向(テンキー対応) |
| `vert` | [Number](Number.html) |  縦方向(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#canPassDiagonally</a>
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

#### characterIndex () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#characterIndex</a>
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

#### characterName () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#characterName</a>
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

#### checkEventTriggerAuto ()


<dl>
</dl>

#### checkEventTriggerTouch (x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#checkEventTriggerTouch</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### checkEventTriggerTouchFront (d)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#checkEventTriggerTouchFront</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### checkStop (threshold) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `threshold` | [Number](Number.html) |  停止カウントの閾値(フレーム) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#checkStop</a>
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

#### clearPageSettings ()


<dl>
</dl>

#### clearStartingFlag ()


<dl>
</dl>

#### copyPosition (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Player](Game_Player.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#copyPosition</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### deltaXFrom (x) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#deltaXFrom</a>
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

#### deltaYFrom (y) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#deltaYFrom</a>
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

#### direction () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#direction</a>
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

#### distancePerFrame () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#distancePerFrame</a>
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

#### endAnimation ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#endAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### endBalloon ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#endBalloon</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### erase ()


<dl>
</dl>

#### event () → {[RPG.Event](RPG.Event.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.Event</a></span>
                </dd>
            </dl>

#### eventId () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### findDirectionTo (goalX, goalY) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `goalX` | [Number](Number.html) |  タイル数 |
| `goalY` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#findDirectionTo</a>
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

#### findProperPageIndex () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### forceMoveRoute (moveRoute)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `moveRoute` | [RPG.MoveRoute](RPG.MoveRoute.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#forceMoveRoute</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### hasStepAnime () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#hasStepAnime</a>
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

#### hasWalkAnime () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#hasWalkAnime</a>
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

#### increaseSteps ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#increaseSteps</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initialize ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#initialize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initMembers ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#initMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isAnimationPlaying () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isAnimationPlaying</a>
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

#### isBalloonPlaying () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isBalloonPlaying</a>
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

#### isCollidedWithCharacters (x, y) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#isCollidedWithCharacters</a>
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

#### isCollidedWithEvents (x, y) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#isCollidedWithEvents</a>
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

#### isCollidedWithPlayerCharacters (x, y) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isCollidedWithVehicles (x, y) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isCollidedWithVehicles</a>
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

#### isDashing () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isDashing</a>
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

#### isDebugThrough () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isDebugThrough</a>
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

#### isDirectionFixed () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isDirectionFixed</a>
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

#### isJumping () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isJumping</a>
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

#### isMapPassable (x, y, d) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isMapPassable</a>
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

#### isMovementSucceeded (x opt, y opt) → {Boolean}



##### Parameters:

| Name | Type | Attributes | Description |
| --- | --- | --- | --- |
| `x` | [Number](Number.html) | <optional> |  |
| `y` | [Number](Number.html) | <optional> |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isMovementSucceeded</a>
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

#### isMoveRouteForcing () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#isMoveRouteForcing</a>
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

#### isMoving () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isMoving</a>
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

#### isNearThePlayer () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isNearTheScreen () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isNearTheScreen</a>
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

#### isNormalPriority () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isNormalPriority</a>
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

#### isObjectCharacter () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isObjectCharacter</a>
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

#### isOnBush () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isOnBush</a>
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

#### isOnLadder () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isOnLadder</a>
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

#### isOriginalPattern () → {Boolean}


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#isOriginalPattern</a>
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

#### isStarting () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isStopping () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isStopping</a>
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

#### isThrough () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isThrough</a>
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

#### isTile () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isTile</a>
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

#### isTransparent () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#isTransparent</a>
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

#### isTriggerIn (triggers) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `triggers` | [Array](Array.html).<[Number](Number.html)> |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### jump (xPlus, yPlus)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `xPlus` | [Number](Number.html) | x方向の移動(タイル数) |
| `yPlus` | [Number](Number.html) | y方向の移動(タイル数) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#jump</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### jumpHeight () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#jumpHeight</a>
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

#### list () → {[Array](Array.html).<[RPG.EventCommand](RPG.EventCommand.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.EventCommand</a>&gt;</span>
                </dd>
            </dl>

#### locate (x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#locate</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### lock ()


<dl>
</dl>

#### maxPattern () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#maxPattern</a>
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

#### meetsConditions (page) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `page` | [RPG.EventPage](RPG.EventPage.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### memorizeMoveRoute ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#memorizeMoveRoute</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveAwayFromCharacter (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Character](Game_Character.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveAwayFromCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveAwayFromPlayer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveAwayFromPlayer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveBackward ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveBackward</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveDiagonally (horz, vert)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `horz` | [Number](Number.html) |  水平向き(4: 左, 6:右) |
| `vert` | [Number](Number.html) |  垂直向き(2: 下, 8: 上) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#moveDiagonally</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveForward ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveForward</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveFrequency () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#moveFrequency</a>
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

#### moveRandom ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveRandom</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveSpeed () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#moveSpeed</a>
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

#### moveStraight (d)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#moveStraight</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveTowardCharacter (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Character](Game_Character.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveTowardCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveTowardPlayer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#moveTowardPlayer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### moveTypeCustom ()


<dl>
</dl>

#### moveTypeRandom ()


<dl>
</dl>

#### moveTypeTowardPlayer ()


<dl>
</dl>

#### opacity () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#opacity</a>
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

#### page () → {[RPG.EventPage](RPG.EventPage.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.EventPage</a></span>
                </dd>
            </dl>

#### pattern () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#pattern</a>
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

#### pos (x, y) → {Boolean}



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
                            <a>Game_CharacterBase#pos</a>
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

#### posNt (x, y) → {Boolean}



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
                            <a>Game_CharacterBase#posNt</a>
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

#### processMoveCommand (command)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `command` | [RPG.MoveCommand](RPG.MoveCommand.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#processMoveCommand</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### processRouteEnd ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#processRouteEnd</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### realMoveSpeed () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#realMoveSpeed</a>
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

#### refresh ()


<dl>
</dl>

#### refreshBushDepth ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#refreshBushDepth</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regionId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#regionId</a>
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

#### requestAnimation (animationId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `animationId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#requestAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### requestBalloon (balloonId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `balloonId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#requestBalloon</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetPattern ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#resetPattern</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetStopCount ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#resetStopCount</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### restoreMoveRoute ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#restoreMoveRoute</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### reverseDir (d) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#reverseDir</a>
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

#### screenX () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#screenX</a>
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

#### screenY () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#screenY</a>
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

#### screenZ () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#screenZ</a>
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

#### scrolledX () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#scrolledX</a>
                        </li>
                    </ul>
                </dd>
                <dt>To Do:</dt>
                <dd>
                    <ul>
                        <li>&#x3053;&#x306E;&#x7528;&#x8A9E;&#x306E;&#x610F;&#x5473;&#x304C;&#x5206;&#x304B;&#x3063;&#x305F;&#x3089;&#x6559;&#x3048;&#x3066;&#x304F;&#x3060;&#x3055;&#x3044;</li>
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

#### scrolledY () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#scrolledY</a>
                        </li>
                    </ul>
                </dd>
                <dt>To Do:</dt>
                <dd>
                    <ul>
                        <li>&#x3053;&#x306E;&#x7528;&#x8A9E;&#x306E;&#x610F;&#x5473;&#x304C;&#x5206;&#x304B;&#x3063;&#x305F;&#x3089;&#x6559;&#x3048;&#x3066;&#x304F;&#x3060;&#x3055;&#x3044;</li>
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

#### searchLimit () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#searchLimit</a>
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

#### setBlendMode (blendMode)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `blendMode` | [Number](Number.html) | 0: 通常, 1: 加算, 2: 乗算, 3: スクリーン |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setBlendMode</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setDirection (d)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `d` | [Number](Number.html) |  向き(テンキー対応) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setDirection</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setDirectionFix (directionFix)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `directionFix` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setDirectionFix</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setImage (characterName, characterIndex)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `characterName` | [String](String.html) |  ファイル名 |
| `characterIndex` | [Number](Number.html) |  番号 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setImage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setMoveFrequency (moveFrequency)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `moveFrequency` | [Number](Number.html) | 1: 最低, 2: 低, 3: 通常, 4: 高, 5: 最高 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setMoveFrequency</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setMovementSuccess (success)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `success` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setMovementSuccess</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setMoveRoute (moveRoute)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `moveRoute` | [RPG.MoveRoute](RPG.MoveRoute.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#setMoveRoute</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setMoveSpeed (moveSpeed)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `moveSpeed` | [Number](Number.html) | 1: 1/8倍速, 2: 1/4倍速, 3: 1/2倍速, 4: 通常速, 5: 2倍速, 6: 4倍速 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setMoveSpeed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setOpacity (opacity)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `opacity` | [Number](Number.html) | 0〜255 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setPattern (pattern)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `pattern` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setPattern</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setPosition (x, y)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.html) |  タイル数 |
| `y` | [Number](Number.html) |  タイル数 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setPosition</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setPriorityType (priorityType)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `priorityType` | [Number](Number.html) | 0: 通常キャラの下, 1:通常キャラと同じ , 2: 通常キャラの上 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setPriorityType</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setStepAnime (stepAnime)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stepAnime` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setStepAnime</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setThrough (through)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `through` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setThrough</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setTileImage (tileId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `tileId` | [Number](Number.html) |  タイルID |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setTileImage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setTransparent (transparent)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `transparent` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setTransparent</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setupPage ()


<dl>
</dl>

#### setupPageSettings ()


<dl>
</dl>

#### setWalkAnime (walkAnime)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `walkAnime` | Boolean |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#setWalkAnime</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### shiftY () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#shiftY</a>
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

#### start ()


<dl>
</dl>

#### startAnimation ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#startAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### startBalloon ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#startBalloon</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### stopCountThreshold () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### straighten ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#straighten</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### swap (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Character](Game_Character.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#swap</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### terrainTag () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#terrainTag</a>
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

#### tileId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#tileId</a>
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

#### turn180 ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turn180</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnAwayFromCharacter (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Character](Game_Character.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnAwayFromCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnAwayFromPlayer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnAwayFromPlayer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnLeft90 ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnLeft90</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnRandom ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnRandom</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnRight90 ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnRight90</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnRightOrLeft90 ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnRightOrLeft90</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnTowardCharacter (character)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `character` | [Game_Character](Game_Character.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnTowardCharacter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### turnTowardPlayer ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#turnTowardPlayer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### unlock ()


<dl>
</dl>

#### update ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#update</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateAnimation ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#updateAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateAnimationCount ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#updateAnimationCount</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateJump ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#updateJump</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateMove ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#updateMove</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateParallel ()


<dl>
</dl>

#### updatePattern ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_CharacterBase#updatePattern</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateRoutineMove ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#updateRoutineMove</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateSelfMovement ()


<dl>
</dl>

#### updateStop ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Character#updateStop</a>
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