# Class: Scene_Skill

## Scene_Skill ()

#### new Scene_Skill ()

The scene class of the skill screen.

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_skillTypeWindow` | [Window_SkillType](Window_SkillType.md) |  |

<dl>
</dl>

### Extends

* [Scene_ItemBase](Scene_ItemBase.md)

### Methods

#### activateItemWindow ()

Activates the item window.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#activateItemWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### actor () → {[Game_Actor](Game_Actor.md)}

Returns the current game actor.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#actor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>

#### addChild (child) → {Object}

[super] 子オブジェクトを追加。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object |  追加するオブジェクト |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Stage#addChild</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

 追加されたオブジェクト
<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### addChildAt (child, index) → {Object}

[super] 指定位置に子オブジェクトを追加。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object |  追加するオブジェクト |
| `index` | [Number](Number.md) |  追加位置 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Stage#addChildAt</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

 追加されたオブジェクト
<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### addWindow (Window)

 ウィンドウレイヤーにウィンドウを追加。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `Window` |  |  追加するウィンドウ |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#addWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### applyItem ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#applyItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### attachReservation ()

 キューに予約を追加。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#attachReservation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### canUse () → {Boolean}

Returns true if the user (game actor) can use the item.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#canUse</a>
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

#### checkCommonEvent ()

Checks the common event set on the item.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#checkCommonEvent</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### checkGameover ()

 ゲームオーバー状態か検査。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#checkGameover</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### commandSkill ()

Handler for when a skill is selected/confirmed within the skill scene.
<dl>
</dl>

#### create ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#create</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### createActorWindow ()

Creates the actor window within the base item scene.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#createActorWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### createFadeSprite ()

 フェード用のスプライトを生成。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#createFadeSprite</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### createHelpWindow ()

Creates the help window.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#createHelpWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### createItemWindow ()

Creates the item window within the skill scene.
<dl>
</dl>

#### createSkillTypeWindow ()

Creates the window for skill types within the skill scene.
<dl>
</dl>

#### createStatusWindow ()

Creates the status window within the skill scene.
<dl>
</dl>

#### createWindowLayer ()

 ウィンドウレイヤー[WindowLayer](WindowLayer.md) を生成。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#createWindowLayer</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### detachReservation ()

 キューから予約を削除。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#detachReservation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### determineItem ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#determineItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### fadeOutAll ()

 全ての映像と音声を、遅い速度でフェードアウト。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#fadeOutAll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### fadeSpeed () → {[Number](Number.md)}

 フェード速度を返す。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#fadeSpeed</a>
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

#### hideSubWindow (window)

Hides the sub window.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `window` | [Window_Base](Window_Base.md) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#hideSubWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initialize ()

 オブジェクト生成時の初期化。
<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#initialize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isActive () → {Boolean}

 シーンがアクティブか。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#isActive</a>
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

#### isBusy () → {Boolean}

 フェード動作中か。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#isBusy</a>
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

#### isCursorLeft () → {Boolean}

Returns true if the cursor is left.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#isCursorLeft</a>
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

#### isItemEffectsValid () → {Boolean}

Returns true if the item effects are valid on the target(the user).
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#isItemEffectsValid</a>
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

#### isReady () → {Boolean}

 シーンの準備ができているか。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#isReady</a>
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

#### item () → {*}

Returns the item attached to the item window within the base item scene.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#item</a>
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

#### itemTargetActors () → {[Game_Actor](Game_Actor.md)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#itemTargetActors</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>

#### nextActor ()

Moves to the next actor in the party.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#nextActor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onActorCancel ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#onActorCancel</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onActorChange ()

Handler for when an an actor is changed within the skill scene.
<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#onActorChange</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onActorOk ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#onActorOk</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onItemCancel ()

<dl>
</dl>

#### onItemOk ()

<dl>
</dl>

#### playSeForItem ()

Plays a sound effect on item confirmation withiin the skill scene.
<dl>
</dl>

#### popScene ()

 シーンを引き出す(pop)。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#popScene</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### previousActor ()

Moves to the previous actor in the party.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#previousActor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### refreshActor ()

<dl>
</dl>

#### removeChild (child) → {Object}

[super] 子オブジェクトを取り除く。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `child` | Object |  取り除くオブジェクト |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Stage#removeChild</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

 取り除かれたオブジェクト
<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### removeChildAt (index) → {Object}

[super] 指定位置にある子オブジェクトを取り除く。

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.md) |  取り除く位置 |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Stage#removeChildAt</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

 取り除かれたオブジェクト
<dl>
                <dt> Type </dt>
                <dd>
                    <span>Object</span>
                </dd>
            </dl>

#### setBackgroundOpacity (opacity)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `opacity` | [Number](Number.md) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#setBackgroundOpacity</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### showSubWindow (window)

Shows the sub window.

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `window` | [Window_Base](Window_Base.md) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#showSubWindow</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### slowFadeSpeed () → {[Number](Number.md)}

 遅いフェード速度を返す。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#slowFadeSpeed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

Return the fade speed
<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### start ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#start</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### startFadeIn (duration opt, white opt)

 フェードインの要求。

##### Parameters:

| Name | Type | Attributes | Default | Description |
| --- | --- | --- | --- | --- |
| `duration` | [Number](Number.md) | <optional> | 30 |  フェードインにかける時間 |
| `white` | Boolean | <optional> | false |  白で[フェード]するか(falseだと黒) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#startFadeIn</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### startFadeOut (duration opt, white opt)

 フェードアウトの要求。

##### Parameters:

| Name | Type | Attributes | Default | Description |
| --- | --- | --- | --- | --- |
| `duration` | [Number](Number.md) | <optional> | 30 |  フェードアウトにかける時間 |
| `white` | Boolean | <optional> | false |  白で[フェード]するか(falseだと黒) |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#startFadeOut</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### stop ()

 シーンの停止。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#stop</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### terminate ()

 遷移前のシーン中断。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#terminate</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### update ()

 フレーム毎のアップデート。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#update</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateActor ()

Updates the current actor.
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_MenuBase#updateActor</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateChildren ()

 子オブジェクトのアップデート。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#updateChildren</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateFade ()

 フェードのアップデート。
<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_Base#updateFade</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### useItem ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#useItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### user () → {[Game_Actor](Game_Actor.md)}

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Scene_ItemBase#user</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>
 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
