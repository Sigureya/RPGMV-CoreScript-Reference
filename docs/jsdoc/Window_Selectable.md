# Class: Window_Selectable

## (abstract) Window_Selectable (x, y, width, height)

#### (abstract) new Window_Selectable (x, y, width, height)

コマンドカーソルの移動やスクロールを行うウィンドウオブジェクト。<br />
[Window_BattleEnemy](Window_BattleEnemy.md), [Window_BattleLog](Window_BattleLog.md), [Window_DebugEdit](Window_DebugEdit.md), [Window_DebugRange](Window_DebugRange.md), [Window_EquipSlot](Window_EquipSlot.md), [Window_NameInput](Window_NameInput.md), [Window_NumberInput](Window_NumberInput.md), [Window_SavefileList](Window_SavefileList.md), [Window_ShopBuy](Window_ShopBuy.md), [Window_ShopNumber](Window_ShopNumber.md), [Window_Status](Window_Status.md) および [Window_BattleStatus](Window_BattleStatus.md), [Window_MenuStatus](Window_MenuStatus.md), [Window_SkillList](Window_SkillList.md) および [Window_ItemList](Window_ItemList.md) および [Window_Command](Window_Command.md) のスーパークラス。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | ウィンドウ x座標(ピクセル) |
| `y` | [Number](Number.md) | ウィンドウ y座標(ピクセル) |
| `width` | [Number](Number.md) | ウィンドウ幅(ピクセル) |
| `height` | [Number](Number.md) | ウィンドウ高さ(ピクセル) |

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_index` | [Number](Number.md) | this is used to select items from the list within the window. |
| `_cursorFixed` | Boolean | The boolean property that determines if the cursor is fixed(locked to a position). |
| `_cursorAll` | Boolean |  |
| `_stayCount` | [Number](Number.md) |  |
| `_helpWindow` | * |  |
| `_handlers` | Object |  |
| `_touching` | Boolean |  |
| `_scrollX` | [Number](Number.md) |  |
| `_scrollY` | [Number](Number.md) |  |

<dl>
</dl>

### Extends

* [Window_Base](Window_Base.md)

### Methods

#### activate ()
[super]ウィンドウをアクティブにする。

<dl>
    <dt>Overrides:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base.html#activate-">Window_Base#activate</a>
            </li>
        </ul>
    </dd>
</dl>

#### actorName (actorIndex) → {[String](String.md)}
[super]指定された番号の[アクター]の名前を返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorIndex` | [Number](Number.md) | アクターの番号(1から始まる) |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base.html#actorname-actorindex--string">Window_Base#actorName</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### addChild (child) → {Object}
[super]  コンテナに子オブジェクトを追加し、追加されたオブジェクトを返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | [PIXI.DisplayObject](http://pixijs.download/release/docs/PIXI.DisplayObject.html) | 追加するオブジェクト |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window.html#addchild-child--object">Window#addChild</a>
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
[super] コンテナの指定位置に子オブジェクトを追加し、追加されたオブジェクトを返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | [PIXI.DisplayObject](http://pixijs.download/release/docs/PIXI.DisplayObject.html)  | 追加するオブジェクト |
| `index` | [Number](Number.md) | 追加位置 |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window.html#addchildat-child-index--object">Window#addChildAt</a>
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
[super] 背景とコンテンツの間に子オブジェクトを追加し、追加されたオブジェクトを返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | [PIXI.DisplayObject](http://pixijs.download/release/docs/PIXI.DisplayObject.html)  | 追加するオブジェクト |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window.html#addchildtoback-child--object">Window#addChildToBack</a>
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

#### bottomRow () → {[Number](Number.md)}
行数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### calcTextHeight (textState, all) → {[Number](Number.md)}
[super] 指定したテキストの表示時の高さ(ピクセル)を計算して返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) | 計算するテキストの情報 |
| `all` | Boolean | 複数行を加算するか |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#calctextheight-textstate-all--number">Window_Base#calcTextHeight</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### callCancelHandler ()
キャンセルのハンドラを呼ぶ。
<dl>
</dl>

#### callHandler (symbol)
指定したハンドラを呼ぶ。

##### Parameters:
| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.md) | ハンドラ名 |

<dl>
</dl>

#### callOkHandler ()
OKのハンドラを呼ぶ。
<dl>
</dl>

#### callUpdateHelp ()
ヘルプのアップデートを呼ぶ。
<dl>
</dl>

#### canvasToLocalX (x) → {[Number](Number.md)}
[super] 指定したCanvas の x座標を、ゲーム画面のローカルx座標に変換して返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | Canvas の x座標 |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#canvastolocalx-x--number">Window_Base#canvasToLocalX</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### canvasToLocalY (y) → {[Number](Number.md)}
[super] 指定したCanvas の y座標を、ゲーム画面のローカルy座標に変換して返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `y` | [Number](Number.md) | Canvas の y座標 |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#canvastolocaly-y--number">Window_Base#canvasToLocalY</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### changePaintOpacity (enabled)
[super] 背景を不透明にするか。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `enabled` | Boolean | true: 不透明(255), false: 半透明(160) |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#changepaintopacity-enabled">Window_Base#changePaintOpacity</a>
            </li>
        </ul>
    </dd>
</dl>

#### changeTextColor (color)
[super] 文字の色を設定。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `color` | [String](String.md) | 色(CSS形式) |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#changetextcolor-color">Window_Base#changeTextColor</a>
            </li>
        </ul>
    </dd>
</dl>

#### clearItem (index)
指定した番号の項目を削除。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | 項目番号 |

<dl>
</dl>

#### close ()
[super] ウィンドウを閉じる。
<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#close-">Window_Base#close</a>
            </li>
        </ul>
    </dd>
</dl>

#### contentsHeight () → {[Number](Number.md)}
[super] ウィンドウに含まれるコンテンツの高さを返す。
<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#contentsheight---number">Window_Base#contentsHeight</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### contentsWidth () → {[Number](Number.md)}
[super] ウィンドウに含まれるコンテンツの幅を返す。

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base#contentswidth---number">Window_Base#contentsWidth</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### convertEscapeCharacters (text) → {[String](String.md)}
[super] エスケープ文字を変換して返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.md) | 変換元の文字列 |

<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base.html#convertescapecharacters-text--string">Window_Base#convertEscapeCharacters</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a href="String.html">String</a></span>
                </dd>
            </dl>

#### createContents ()


Creates the contents of the window; this is the area of the window which text is drawn to.
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

#### crisisColor () → {[String](String.md)}


Returns the crisis color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### cursorAll () → {Boolean}
項目を全選択しているか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### cursorDown (wrap)
カーソルを下に移動。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean | リストの前後をつなぐか |

<dl>
</dl>

#### cursorFixed () → {Boolean}
カーソルが固定されているか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### cursorLeft (wrap)
カーソルを左に移動。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean | リストの前後をつなぐか |

<dl>
</dl>

#### cursorPagedown ()
カーソルを次ページに移動。
<dl>
</dl>

#### cursorPageup ()
カーソルを前ページに移動。
<dl>
</dl>

#### cursorRight (wrap)
カーソルを右に移動。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean | リストの前後をつなぐか |

<dl>
</dl>

#### cursorUp (wrap)
カーソルを上に移動。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wrap` | Boolean | リストの前後をつなぐか |

<dl>
</dl>

#### deactivate ()
非アクティブにする。
<dl>
    <dt>Overrides:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base.html#deactivate-">Window_Base#deactivate</a>
            </li>
        </ul>
    </dd>
</dl>

#### deathColor () → {[String](String.md)}


Returns the death color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### deselect ()
全項目を非選択。
<dl>
</dl>

#### dimColor1 () → {[String](String.md)}


Color 1 of the dimmer sprite bitmap. for the gradient.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### dimColor2 () → {[String](String.md)}


Color 2 of the dimmer sprite bitmap for the gradient.
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
                    <span><a href="String.html">String</a></span>
                </dd>
            </dl>

#### drawActorCharacter (actor, x, y)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |

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


Draws the actor class at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor face at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |
| `height` | [Number](Number.md) |  |

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


Draws the actor hp at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor icons at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor level at the specified x and y coordinates.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |

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


Draws the actor mp at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor name at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor nickname at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws a simple status for the game actor passed into the method at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the actor tp at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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
全[アイテム]を描画。
<dl>
</dl>

#### drawCharacter (characterName, characterIndex, x, y)


Draws a character (map sprites) at the specified x and y coordinate. CharacterName refers to character spritesheet, and characterIndex refers to the characterIndex on the spritesheet.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `characterName` | [String](String.md) |  |
| `characterIndex` | [Number](Number.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |

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


Draws the currency value given at the specified x and y coordinates within the width given. Useful if you want to write your own custom currency value.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.md) |  |
| `unit` | [String](String.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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


Draws the current and max number at the specified x and y coordinate within the given width. Color1 represents the current number and color2 represents the max number when the text is drawn.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `current` | [Number](Number.md) |  |
| `max` | [Number](Number.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |
| `color1` | [String](String.md) |  |
| `color2` | [String](String.md) |  |

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
| `faceName` | [String](String.md) |  |  |
| `faceIndex` | [Number](Number.md) |  |  |
| `x` | [Number](Number.md) |  |  |
| `y` | [Number](Number.md) |  |  |
| `width` | [Number](Number.md) | <optional> |  |
| `height` | [Number](Number.md) | <optional> |  |

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


Draws a gauge at the specified x and y coordinates within the given width. Color1 and Color2 represent the gradient as css color strings of the gauge.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |
| `rate` | [Number](Number.md) |  |
| `color1` | [String](String.md) |  |
| `color2` | [String](String.md) |  |

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


Draws an icon given the specified iconIndex at the specified x and y coordinates. The Width and Height of the icon is based on the _iconWidth and _iconHeight properties.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |

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
指定番号の[アイテム]を描画。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | アイテム番号 |

<dl>
</dl>

#### drawItemName (item, x, y, width)


Draws the item name at the specified x and y coordinates within the given width.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |

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

#### drawText (text, x, y, maxWidth, align)


Given text or a number, draws the content to the window's contents layer at the specified x and y coordinate within the max width. The text content can also be aligned with the align property. The possible alignments are: "left", "center", "right".

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | string |number |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `maxWidth` | [Number](Number.md) |  |
| `align` | [String](String.md) |  |

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

#### drawTextEx (text, x, y) → {[Number](Number.md)}


Draws text with text codes included; this will draw icons, increase text height, and more.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.md) |  |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |

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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### ensureCursorVisible ()
選択カーソルを表示。
<dl>
</dl>

#### fittingHeight (numLines) → {[Number](Number.md)}


Returns the fitting height given a number of lines based on the line height plus standard padding of the window. Default formula: numLines * lineHeight + standardPadding * 2

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `numLines` | [Number](Number.md) |  |

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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### gaugeBackColor () → {[String](String.md)}


Returns the gauage back color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### hide ()


Hides the window, making it invisible; the window is not closed when hidden.
<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a>Window_Base#hide</a>
            </li>
        </ul>
    </dd>
</dl>

#### hideBackgroundDimmer ()


Hides the background dimmer sprite.
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
ヘルプウィンドウを非表示。
<dl>
</dl>

#### hitTest (x, y) → {[Number](Number.md)}
指定座標が項目の範囲に含まれるか上から判定を行い、最初に適合した項目番号を返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | x座標(ピクセル) |
| `y` | [Number](Number.md) | y座標(ピクセル) |

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### hpColor (actor) → {[String](String.md)}


Returns the hp color as a css string.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |

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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### hpGaugeColor1 () → {[String](String.md)}


Returns the hp gauge color 1 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### hpGaugeColor2 () → {[String](String.md)}


Returns the hp gauge color 2 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### index () → {[Number](Number.md)}
選択中の項目の番号を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### initialize (x, y, width, height)

 オブジェクト生成時の初期化。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) |  |
| `y` | [Number](Number.md) |  |
| `width` | [Number](Number.md) |  |
| `height` | [Number](Number.md) |  |

<dl>
    <dt>Overrides:</dt>
    <dd>
        <ul>
            <li>
                <a>Window_Base#initialize</a>
            </li>
        </ul>
    </dd>
</dl>

#### isCancelEnabled () → {Boolean}
キャンセルが可能か。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isCancelTriggered () → {Boolean}
キャンセルが起動されたか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isClosed ()


Returns true if the window is completely closed (openness == 0).
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


Returns true if the window is currently closing.
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
指定座標がコンテンツの範囲内か。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | x座標(ピクセル) |
| `y` | [Number](Number.md) | y座標(ピクセル) |

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isCurrentItemEnabled () → {Boolean}
選択中の項目が利用可能か。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isCursorMovable () → {Boolean}
カーソルが動かせるか。
<dl>
</dl>

##### Returns:
<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isCursorVisible () → {Boolean}
カーソルが表示中か。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isHandled (symbol) → {Boolean}
指定されたハンドラが利用可能か。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.md) | ハンドラ名 |

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isHorizontal () → {Boolean}
縦一列のコマンド並びか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isOkEnabled () → {Boolean}
OKが可能か。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isOkTriggered () → {Boolean}
OKが起動されたか。
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


Returns true if the window is completely open (openness == 255).
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
ウィンドウが開いてアクティブか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isOpening () → {Boolean}


Returns true if the window is currently opening.
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
枠の内側をタッチされたか。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### isTouchOkEnabled () → {Boolean}
タッチ入力によるOKが可能か。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span>Boolean</span>
    </dd>
</dl>

#### itemHeight () → {[Number](Number.md)}
項目の高さ(ピクセル)を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### itemRect (index) → {[Rectangle](Rectangle.md)}
指定された項目の矩形範囲を返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | 項目番号 |

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Rectangle.html">Rectangle</a></span>
    </dd>
</dl>

#### itemRectForText (index) → {[Rectangle](Rectangle.md)}
指定された項目の文字列用の矩形範囲を返す。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | 項目番号 |

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Rectangle.html">Rectangle</a></span>
    </dd>
</dl>

#### itemWidth () → {[Number](Number.md)}
項目の幅(ピクセル)を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### lineHeight () → {[Number](Number.md)}
行の高さ(ピクセル)を返す。default: 36
<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a href="Window_Base.html#lineheight---number">Window_Base#lineHeight</a>
            </li>
        </ul>
    </dd>
</dl>

##### Returns:
<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### loadWindowskin ()


Loads the window skin from the img/system directory.
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


Makes the font bigger by a value of 12.
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


Makes the font smaller by a value of 12.
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

#### maxCols () → {[Number](Number.md)}
ウィンドウが持つ最大列(カラム)数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### maxItems () → {[Number](Number.md)}
ウィンドウが持つ最大項目数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### maxPageItems () → {[Number](Number.md)}
ページが持つ最大項目数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### maxPageRows () → {[Number](Number.md)}
ページが持つ最大行(ロー)数を返す。

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### maxRows () → {[Number](Number.md)}
ウィンドウが持つ最大行(ロー)数を返す。

<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### maxTopRow () → {[Number](Number.md)}
最後の最上部の行(ロー)数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### move (x, y, width, height)


Sets the x, y, width, and height all at once.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | The x coordinate of the window |
| `y` | [Number](Number.md) | The y coordinate of the window |
| `width` | [Number](Number.md) | The width of the window |
| `height` | [Number](Number.md) | The height of the window |

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

#### mpColor (actor) → {[String](String.md)}


Returns the mp color as a css color string.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |

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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### mpCostColor () → {[String](String.md)}


Returns the mp cost color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### mpGaugeColor1 () → {[String](String.md)}


Returns the mp gauge color 1 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### mpGaugeColor2 () → {[String](String.md)}


Returns the mp gauge color 2 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### normalColor () → {[String](String.md)}


Returns the normal color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### obtainEscapeCode (textState)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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


Obtains the escape parameters from text codes in the text state when drawTextEx is used to draw text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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
タッチの処理。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `triggered` | Boolean |  |

<dl>
</dl>

#### open ()


Opens the window.
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


Changes the text color based on the powerUpColor, powerDownColor and normal color. powerUpColor is any number greater than 0, powerDownColor is any color less than 0, otherwise normal color is returned.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `change` | [Number](Number.md) |  |

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

#### partyMemberName (partyMemberIndex) → {[String](String.md)}


Returns a party member name given an index; the index starts from 1.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `partyMemberIndex` | [Number](Number.md) |  |

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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### pendingColor () → {[String](String.md)}


Returns the pending color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### playBuzzerSound ()
入力が不正だった場合の音を再生。
<dl>
</dl>

#### playOkSound ()
入力が受領された場合の音を再生。
<dl>
</dl>

#### powerDownColor () → {[String](String.md)}


Returns the power down color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### powerUpColor () → {[String](String.md)}


Returns the power up color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### processCancel ()
キャンセルを処理。
<dl>
</dl>

#### processCharacter (textState)


Process each character in the text when drawTextEx is used to draw text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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
カーソルの移動を処理。
<dl>
</dl>

#### processDrawIcon (iconIndex, textState)


Processes drawing an icon when drawTextEx is used for drawing text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `iconIndex` | [Number](Number.md) |  |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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


Processes escape characters when drawTextEx is used for drawing text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [String](String.md) |  |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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
追加されたハンドラの処理。
<dl>
</dl>

#### processNewLine (textState)

Processes new line when drawTextEx is used to draw text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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


Processes new page when drawTexttEx is used to draw text.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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


Processes the normal characters in the text when drawTextEx is used to draw text. Normal characters are letters and numbers.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `textState` | [MV.TextState](MV.TextState.md) |  |

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
OKの処理。
<dl>
</dl>

#### processPagedown ()
ページダウンの処理。
<dl>
</dl>

#### processPageup ()
ページアップの処理。
<dl>
</dl>

#### processTouch ()
タッチ入力の処理。
<dl>
</dl>

#### processWheel ()
ホイール入力の処理。
<dl>
</dl>

#### redrawCurrentItem ()
現在の項目の再描画。
<dl>
</dl>

#### redrawItem (index)
指定した番号の項目の再描画。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | 項目番号 |

<dl>
</dl>

#### refresh ()
コンテンツの再描画。
<dl>
</dl>

#### refreshDimmerBitmap ()
Refreshes the bitmap attached to the dimmer sprite based on the window dimensions.
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
[super] Removes a child to the container.

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
[super] Removes a child from the specified index position.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | The index to get the child from |

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
項目の再選択。
<dl>
</dl>

#### reserveFaceImages ()
Reverses the face images of the game party members.
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


Resets the font settings of the window back to the default.
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
スクロールを初期化。
<dl>
</dl>

#### resetTextColor ()


Resets the text color of the window back to the default.
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

#### row () → {[Number](Number.md)}
現在の行(ロー)数を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### scrollDown ()
下にスクロール。
<dl>
</dl>

#### scrollUp ()
上にスクロール。
<dl>
</dl>

#### select (index)
指定した番号の項目を選択。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) | 項目番号 |

<dl>
</dl>

#### setBackgroundType (type)
Sets the background type of the window. 0 is 255 window opacity (standard). 1 is the window with background dimmer. Any other number changes the opacity to 0.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `type` | [Number](Number.md) |  |

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
下の行(ロー)を設定。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `row` | [Number](Number.md) | 行番号 |

<dl>
</dl>

#### setCursorAll (cursorAll)
全項目選択の状態を設定。
##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `cursorAll` | Boolean | 全選択か |

<dl>
</dl>

#### setCursorFixed (cursorFixed)
カーソルの固定状態を設定。

Sets the _cursorFixed property of the window.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `cursorFixed` | Boolean | カーソル固定か |

<dl>
</dl>

#### setCursorRect (x, y, width, height)


Sets the position of the command cursor.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `x` | [Number](Number.md) | The x coordinate of the cursor |
| `y` | [Number](Number.md) | The y coordinate of the cursor |
| `width` | [Number](Number.md) | The width of the cursor |
| `height` | [Number](Number.md) | The height of the cursor |

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
ハンドラを設定。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.md) | ハンドラ名 |
| `method` | Function | ハンドラ関数 |

<dl>
</dl>

#### setHelpWindow (helpWindow)
ヘルプウィンドウを設定。
##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `helpWindow` | [Window_Help](Window_Help.html) | ヘルプウィンドウ |

<dl>
</dl>

#### setHelpWindowItem (item)
ヘルプウィンドウの項目を設定。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | * | 設定する項目 |

<dl>
</dl>

#### setTone (r, g, b)


Changes the color of the background.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `r` | [Number](Number.md) | The red value in the range (-255, 255) |
| `g` | [Number](Number.md) | The green value in the range (-255, 255) |
| `b` | [Number](Number.md) | The blue value in the range (-255, 255) |

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
上の行(ロー)を設定。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `row` | [Number](Number.md) | 行番号 |

<dl>
</dl>

#### show ()


Shows the window, making it visible.
<dl>
    <dt>Inherited From:</dt>
    <dd>
        <ul>
            <li>
                <a>Window_Base#show</a>
            </li>
        </ul>
    </dd>
</dl>

#### showBackgroundDimmer ()


Shows the background dimmer sprite.
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
ヘルプウィンドウを表示。
<dl>
</dl>

#### spacing () → {[Number](Number.md)}
空白の量(ピクセル)を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### standardBackOpacity () → {[Number](Number.md)}


Returns the standard back opacity of the window; this is the opacity of the area behind the window's text content. Default is 192.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### standardFontFace () → {[String](String.md)}


Returns the standard font face of the game based on what language the game is in.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### standardFontSize () → {[Number](Number.md)}


Returns the standard font size of the text in window; default is 28.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### standardPadding () → {[Number](Number.md)}


Returns the standard padding of the window; default is 18.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### systemColor () → {[String](String.md)}


Returns the system color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### textColor (n) → {*}


Returns a text color given a numbered index as a css color string; this index maps directly to the img/system/window.png colors by default.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `n` | [Number](Number.md) |  |

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

#### textPadding () → {[Number](Number.md)}


Returns the text padding of the window; default is 6.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### textWidth (text) → {[Number](Number.md)}


Calculates the width of a text string and returns a number.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `text` | [String](String.md) |  |

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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### topIndex () → {[Number](Number.md)}
スクロールリストの上にある項目の番号を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### topRow () → {[Number](Number.md)}
上の行(ロー)の番号を返す。
<dl>
</dl>

##### Returns:

<dl>
    <dt> Type </dt>
    <dd>
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### tpColor (actor) → {[String](String.md)}


Returns the tp color as a css color string.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.md) |  |

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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### tpCostColor () → {[String](String.md)}


Returns the tp cost color as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### tpGaugeColor1 () → {[String](String.md)}


Returns the tp gauge color 1 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### tpGaugeColor2 () → {[String](String.md)}


Returns tp gauge color 2 as a css color string.
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
        <span><a href="String.html">String</a></span>
    </dd>
</dl>

#### translucentOpacity () → {[Number](Number.md)}


Returns the translucentOpacity for the window; The default is 160.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### update ()

<dl>
    <dt>Overrides:</dt>
    <dd>
        <ul>
            <li>
                <a>Window_Base#update</a>
            </li>
        </ul>
    </dd>
</dl>

#### updateArrows ()
スクロールアローをアップデート。
<dl>
</dl>

#### updateBackgroundDimmer ()


Updates the background dimmer sprite opacity based on the openness of the window.
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

#### updateBackOpacity () → {[Number](Number.md)}


Returns the inner content width of the window.
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
        <span><a href="Number.html">Number</a></span>
    </dd>
</dl>

#### updateClose ()


Updates the openness of the window when the _closing property is set to true. Openness is decreased.
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
カーソルをアップデート。
<dl>
</dl>

#### updateHelp ()
ヘルプウィンドウをアップデート。
<dl>
</dl>

#### updateInputData ()
入力データをアップデート。
<dl>
</dl>

#### updateOpen ()


Updates the openness of the window when the _opening property is set to true. Openness is increased.
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


Updates the window padding based on the standardPadding method.
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


Updates the tone of the window based on the game system window tone defined in the database.
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


 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
