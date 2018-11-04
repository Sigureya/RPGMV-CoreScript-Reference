# Class: Game_Battler

## Game_Battler ()

#### new Game_Battler ()

The superdeclare class of [Game_Actor](Game_Actor.html) and [Game_Enemy](Game_Enemy.html). It contains methods for sprites

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_actions` | [Array](Array.html).<[Game_Action](Game_Action.html)> |  |
| `_speed` | [Number](Number.html) |  |
| `_result` | [Game_ActionResult](Game_ActionResult.html) |  |
| `_actionState` | [String](String.html) |  |
| `_lastTargetIndex` | [Number](Number.html) |  |
| `_animations` | [Array](Array.html).<[MV.BattlerAnimation](MV.BattlerAnimation.html)> |  |
| `_damagePopup` | Boolean |  |
| `_effectType` | [String](String.html) |  |
| `_motionType` | [String](String.html) |  |
| `_weaponImageId` | [Number](Number.html) |  |
| `_motionRefresh` | Boolean |  |
| `_selected` | Boolean |  |

<dl>
</dl>

### Extends

* [Game_BattlerBase](Game_BattlerBase.html)

### Methods

#### action (index) → {[Game_Action](Game_Action.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Action</a></span>
                </dd>
            </dl>

#### actionPlusSet () → {[Array](Array.html).<[Number](Number.html)>}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#actionPlusSet</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### addBuff (paramId, turns)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |
| `turns` | [Number](Number.html) |  |

<dl>
</dl>

#### addDebuff (paramId, turns)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |
| `turns` | [Number](Number.html) |  |

<dl>
</dl>

#### addedSkills () → {[Array](Array.html).<[Number](Number.html)>}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#addedSkills</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### addedSkillTypes () → {[Array](Array.html).<[Number](Number.html)>}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#addedSkillTypes</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### addNewState (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#addNewState</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### addParam (paramId, value)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#addParam</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### addState (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
</dl>

#### allIcons () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#allIcons</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### allTraits () → {[Array](Array.html).<[RPG.Trait](RPG.Trait.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#allTraits</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Trait</a>&gt;</span>
                </dd>
            </dl>

#### appear ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#appear</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### attackElements () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackElements</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### attackSkillId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackSkillId</a>
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

#### attackSpeed () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackSpeed</a>
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

#### attackStates () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackStates</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### attackStatesRate (stateId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackStatesRate</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### attackTimesAdd () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#attackTimesAdd</a>
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

#### buff (paramId) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#buff</a>
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

#### buffIconIndex (buffLevel, paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `buffLevel` | [Number](Number.html) |  |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#buffIconIndex</a>
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

#### buffIcons () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#buffIcons</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### buffLength () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#buffLength</a>
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

#### canAttack () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canAttack</a>
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

#### canEquip (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canEquip</a>
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

#### canEquipArmor (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canEquipArmor</a>
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

#### canEquipWeapon (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canEquipWeapon</a>
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

#### canGuard () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canGuard</a>
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

#### canInput () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canInput</a>
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

#### canMove () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canMove</a>
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

#### canPaySkillCost (skill) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canPaySkillCost</a>
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

#### canUse (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#canUse</a>
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

#### chargeTpByDamage (damageRate)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `damageRate` | [Number](Number.html) |  |

<dl>
</dl>

#### clearActions ()


<dl>
</dl>

#### clearAnimations ()


<dl>
</dl>

#### clearBuffs ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#clearBuffs</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearDamagePopup ()


<dl>
</dl>

#### clearEffect ()


<dl>
</dl>

#### clearMotion ()


<dl>
</dl>

#### clearParamPlus ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#clearParamPlus</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearResult ()


<dl>
</dl>

#### clearStates ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#clearStates</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearTp ()


<dl>
</dl>

#### clearWeaponAnimation ()


<dl>
</dl>

#### collapseType () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#collapseType</a>
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

#### confusionLevel () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#confusionLevel</a>
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

#### consumeItem (item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
</dl>

#### currentAction () → {[Game_Action](Game_Action.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Action</a></span>
                </dd>
            </dl>

#### deathStateId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#deathStateId</a>
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

#### debuffRate (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#debuffRate</a>
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

#### decreaseBuff (paramId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#decreaseBuff</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### deselect ()

<dl>
</dl>

#### die ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#die</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### effectType () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### elementRate (elementId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `elementId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#elementRate</a>
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

#### eraseBuff (paramId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#eraseBuff</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### eraseState (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#eraseState</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### escape ()


<dl>
</dl>

#### forceAction (skillId, targetIndex)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |
| `targetIndex` | [Number](Number.html) |  |

<dl>
</dl>

#### gainHp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
</dl>

#### gainMp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
</dl>

#### gainSilentTp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
</dl>

#### gainTp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
</dl>

#### guardSkillId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#guardSkillId</a>
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

#### hide ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#hide</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### hpRate () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#hpRate</a>
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

#### increaseBuff (paramId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#increaseBuff</a>
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
                            <a>Game_BattlerBase#initialize</a>
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
                            <a>Game_BattlerBase#initMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initTp ()


<dl>
</dl>

#### isActing () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isActor () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isActor</a>
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

#### isAlive () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isAlive</a>
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

#### isAnimationRequested () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isAppeared () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isAppeared</a>
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

#### isAutoBattle () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isAutoBattle</a>
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

#### isBuffAffected (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isBuffAffected</a>
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

#### isBuffExpired (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isBuffExpired</a>
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

#### isBuffOrDebuffAffected (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isBuffOrDebuffAffected</a>
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

#### isChanting () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isConfused () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isConfused</a>
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

#### isDamagePopupRequested () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isDead () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isDead</a>
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

#### isDeathStateAffected () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isDeathStateAffected</a>
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

#### isDebuffAffected (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isDebuffAffected</a>
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

#### isDualWield () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isDualWield</a>
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

#### isDying () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isDying</a>
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

#### isEffectRequested () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isEnemy () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isEnemy</a>
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

#### isEquipAtypeOk (atypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `atypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isEquipAtypeOk</a>
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

#### isEquipTypeLocked (etypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `etypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isEquipTypeLocked</a>
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

#### isEquipTypeSealed (etypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `etypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isEquipTypeSealed</a>
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

#### isEquipWtypeOk (wtypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wtypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isEquipWtypeOk</a>
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

#### isGuard () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isGuard</a>
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

#### isGuardWaiting () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isHidden () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isHidden</a>
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

#### isInputting () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isMaxBuffAffected (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isMaxBuffAffected</a>
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

#### isMaxDebuffAffected (paramId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isMaxDebuffAffected</a>
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

#### isMotionRefreshRequested () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isMotionRequested () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isOccasionOk (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isOccasionOk</a>
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

#### isPreserveTp () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isPreserveTp</a>
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

#### isRestricted () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isRestricted</a>
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

#### isSelected () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isSkillSealed (stypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isSkillSealed</a>
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

#### isSkillTypeSealed (stypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stypeId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isSkillTypeSealed</a>
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

#### isSkillWtypeOk (skill) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isSkillWtypeOk</a>
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

#### isStateAddable (stateId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isStateAffected (stateId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isStateAffected</a>
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

#### isStateExpired (stateId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isStateExpired</a>
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

#### isStateResist (stateId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isStateResist</a>
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

#### isStateRestrict (stateId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isSubstitute () → {Boolean}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#isSubstitute</a>
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

#### isUndecided () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isWaiting () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isWeaponAnimationRequested () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### makeActions ()


<dl>
</dl>

#### makeActionTimes () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### makeSpeed ()


<dl>
</dl>

#### maxSlipDamage () → {[Number](Number.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxTp () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#maxTp</a>
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

#### meetsItemConditions (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.Item](RPG.Item.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#meetsItemConditions</a>
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

#### meetsSkillConditions (skill) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#meetsSkillConditions</a>
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

#### meetsUsableItemConditions (item) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#meetsUsableItemConditions</a>
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

#### mostImportantStateText () → {[String](String.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#mostImportantStateText</a>
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

#### motionType () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### mpRate () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#mpRate</a>
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

#### numActions () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### onAllActionsEnd ()

<dl>
</dl>

#### onBattleEnd ()

<dl>
</dl>

#### onBattleStart ()

<dl>
</dl>

#### onDamage (value)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
</dl>

#### onRestrict ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#onRestrict</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onTurnEnd ()

<dl>
</dl>

#### overwriteBuffTurns (paramId, turns)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |
| `turns` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#overwriteBuffTurns</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### param (paramId) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#param</a>
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

#### paramBase (paramId) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramBase</a>
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

#### paramBuffRate (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramBuffRate</a>
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

#### paramMax (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramMax</a>
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

#### paramMin (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramMin</a>
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

#### paramPlus (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramPlus</a>
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

#### paramRate (paramId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paramRate</a>
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

#### partyAbility (abilityId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `abilityId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#partyAbility</a>
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

#### paySkillCost (skill)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#paySkillCost</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performAction (action)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `action` | [Game_Action](Game_Action.html) |  |

<dl>
</dl>

#### performActionEnd ()


<dl>
</dl>

#### performActionStart (action)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `action` | [Game_Action](Game_Action.html) |  |

<dl>
</dl>

#### performCollapse ()


<dl>
</dl>

#### performCounter ()


<dl>
</dl>

#### performDamage ()


<dl>
</dl>

#### performEvasion ()


<dl>
</dl>

#### performMagicEvasion ()


<dl>
</dl>

#### performMiss ()


<dl>
</dl>

#### performRecovery ()


<dl>
</dl>

#### performReflection ()


<dl>
</dl>

#### performSubstitute (target)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `target` | [Game_Battler](Game_Battler.html) |  |

<dl>
</dl>

#### recoverAll ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#recoverAll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### refresh ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#refresh</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regenerateAll ()


<dl>
</dl>

#### regenerateHp ()


<dl>
</dl>

#### regenerateMp ()


<dl>
</dl>

#### regenerateTp ()


<dl>
</dl>

#### removeAllBuffs ()


<dl>
</dl>

#### removeBattleStates ()

<dl>
</dl>

#### removeBuff (paramId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
</dl>

#### removeBuffsAuto ()

<dl>
</dl>

#### removeCurrentAction ()


<dl>
</dl>

#### removeState (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
</dl>

#### removeStatesAuto (timing)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `timing` | [Number](Number.html) |  |

<dl>
</dl>

#### removeStatesByDamage ()

<dl>
</dl>

#### requestEffect (effectType)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `effectType` | [String](String.html) |  |

<dl>
</dl>

#### requestMotion (motionType)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `motionType` | [String](String.html) |  |

<dl>
</dl>

#### requestMotionRefresh ()

<dl>
</dl>

#### resetStateCounts (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#resetStateCounts</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### restriction () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#restriction</a>
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

#### result () → {[Game_ActionResult](Game_ActionResult.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_ActionResult</a></span>
                </dd>
            </dl>

#### revive ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#revive</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### select ()

<dl>
</dl>

#### setAction (index, action)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |
| `action` | [Game_Action](Game_Action.html) |  |

<dl>
</dl>

#### setActionState (actionState)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actionState` | [String](String.html) |  |

<dl>
</dl>

#### setHp (hp)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `hp` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#setHp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setLastTarget (target)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `target` | [Game_Battler](Game_Battler.html) |  |

<dl>
</dl>

#### setMp (mp)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `mp` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#setMp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setTp (tp)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `tp` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#setTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### shiftAnimation () → {[MV.BattlerAnimation](MV.BattlerAnimation.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>MV.BattlerAnimation</a></span>
                </dd>
            </dl>

#### skillMpCost (skill) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#skillMpCost</a>
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

#### skillTpCost (skill) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#skillTpCost</a>
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

#### slotType () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#slotType</a>
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

#### sortStates ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#sortStates</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### sparam (sparamId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `sparamId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#sparam</a>
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

#### specialFlag (flagId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `flagId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#specialFlag</a>
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

#### speed () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### startAnimation (animationId, mirror, delay)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `animationId` | [Number](Number.html) |  |
| `mirror` | Boolean |  |
| `delay` | [Number](Number.html) |  |

<dl>
</dl>

#### startDamagePopup ()


<dl>
</dl>

#### startWeaponAnimation (weaponImageId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `weaponImageId` | [Number](Number.html) |  |

<dl>
</dl>

#### stateIcons () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#stateIcons</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### stateMotionIndex () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#stateMotionIndex</a>
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

#### stateOverlayIndex () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#stateOverlayIndex</a>
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

#### stateRate (stateId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#stateRate</a>
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

#### stateResistSet () → {[Array](Array.html).<[Number](Number.html)>}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#stateResistSet</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### states () → {[Array](Array.html).<[RPG.State](RPG.State.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#states</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.State</a>&gt;</span>
                </dd>
            </dl>

#### tpRate () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#tpRate</a>
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

#### traitObjects () → {[Array](Array.html).<*>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitObjects</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;*&gt;</span>
                </dd>
            </dl>

#### traits (code) → {[Array](Array.html).<[RPG.Trait](RPG.Trait.html)>}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traits</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Trait</a>&gt;</span>
                </dd>
            </dl>

#### traitsPi (code, id) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |
| `id` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitsPi</a>
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

#### traitsSet (code) → {[Array](Array.html).<[Number](Number.html)>}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitsSet</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
                </dd>
            </dl>

#### traitsSum (code, id) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |
| `id` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitsSum</a>
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

#### traitsSumAll (code) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitsSumAll</a>
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

#### traitsWithId (code, id) → {[Array](Array.html).<[RPG.Trait](RPG.Trait.html)>}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `code` | [Number](Number.html) |  |
| `id` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#traitsWithId</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Trait</a>&gt;</span>
                </dd>
            </dl>

#### updateBuffTurns ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#updateBuffTurns</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### updateStateTurns ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#updateStateTurns</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### useItem (item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
</dl>

#### weaponImageId () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### xparam (xparamId) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `xparamId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_BattlerBase#xparam</a>
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