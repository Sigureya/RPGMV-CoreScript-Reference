# Class: Game_Actor

## Game_Actor ()

#### new Game_Actor ()

[アクター]を定義したクラス。

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `level` | [Number](Number.html) | [read-only] Level |
| `_actorId` | [Number](Number.html) |  |
| `_name` | [String](String.html) |  |
| `_nickname` | [String](String.html) |  |
| `_profile` | [String](String.html) |  |
| `_classId` | [Number](Number.html) |  |
| `_level` | [Number](Number.html) |  |
| `_characterName` | [String](String.html) |  |
| `_characterIndex` | [Number](Number.html) |  |
| `_faceName` | [String](String.html) |  |
| `_faceIndex` | [Number](Number.html) |  |
| `_battlerName` | [String](String.html) |  |
| `_exp` | Object | {[classId: number]: number} |
| `_skills` | [Array](Array.html).<[Number](Number.html)> |  |
| `_equips` | [Array](Array.html).<[Game_Item](Game_Item.html)> |  |
| `_actionInputIndex` | [Number](Number.html) |  |
| `_lastMenuSkill` | [Game_Item](Game_Item.html) |  |
| `_lastBattleSkill` | [Game_Item](Game_Item.html) |  |
| `_lastCommandSymbol` | [String](String.html) |  |
| `_stateSteps` | Object | {[stateId: number]: number} |

<dl>
</dl>

### Extends

* [Game_Battler](Game_Battler.html)

### Methods

#### action (index) → {[Game_Action](Game_Action.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#action</a>
                        </li>
                    </ul>
                </dd>
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

#### actor () → {[RPG.Actor](RPG.Actor.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.Actor</a></span>
                </dd>
            </dl>

#### actorId () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### addBuff (paramId, turns)



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
                            <a>Game_Battler#addBuff</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### addDebuff (paramId, turns)



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
                            <a>Game_Battler#addDebuff</a>
                        </li>
                    </ul>
                </dd>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#addState</a>
                        </li>
                    </ul>
                </dd>
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

#### armors () → {[Array](Array.html).<[RPG.Armor](RPG.Armor.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Armor</a>&gt;</span>
                </dd>
            </dl>

#### attackAnimationId1 () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### attackAnimationId2 () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### attackElements () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#attackElements</a>
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

#### bareHandsAnimationId () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### bareHandsElementId () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### basicFloorDamage () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### battlerName () → {[String](String.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### benchMembersExpRate () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### bestEquipItem (slotId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `slotId` | [Number](Number.html) |  |

<dl>
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

#### calcEquipItemPerformance (item) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
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

#### changeClass (classId, keepExp)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `classId` | [Number](Number.html) |  |
| `keepExp` | Boolean |  |

<dl>
</dl>

#### changeEquip (slotId, item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `slotId` | [Number](Number.html) |  |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
</dl>

#### changeEquipById (etypeId, itemId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `etypeId` | [Number](Number.html) |  |
| `itemId` | [Number](Number.html) |  |

<dl>
</dl>

#### changeExp (exp, show)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `exp` | [Number](Number.html) |  |
| `show` | Boolean |  |

<dl>
</dl>

#### changeLevel (level, show)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `level` | [Number](Number.html) |  |
| `show` | Boolean |  |

<dl>
</dl>

#### characterIndex () → {[Number](Number.html)}

<dl>
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
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### chargeTpByDamage (damageRate)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `damageRate` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#chargeTpByDamage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### checkFloorEffect ()


<dl>
</dl>

#### clearActions ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearActions</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearAnimations ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearAnimations</a>
                        </li>
                    </ul>
                </dd>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearDamagePopup</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearEffect ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearEffect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearEquipments ()


<dl>
</dl>

#### clearMotion ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearMotion</a>
                        </li>
                    </ul>
                </dd>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearResult</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearStates ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearStates</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearTp ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearWeaponAnimation ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#clearWeaponAnimation</a>
                        </li>
                    </ul>
                </dd>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#consumeItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### currentAction () → {[Game_Action](Game_Action.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#currentAction</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Action</a></span>
                </dd>
            </dl>

#### currentClass () → {[RPG.Class](RPG.Class.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.Class</a></span>
                </dd>
            </dl>

#### currentExp () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### currentLevelExp () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#deselect</a>
                        </li>
                    </ul>
                </dd>
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

#### discardEquip (item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
</dl>

#### displayLevelUp (newSkills)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `newSkills` | [Array](Array.html).<[RPG.Skill](RPG.Skill.html)> |  |

<dl>
</dl>

#### effectType () → {[String](String.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#effectType</a>
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

#### equips () → {[Array](Array.html).<[RPG.EquipItem](RPG.EquipItem.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.EquipItem</a>&gt;</span>
                </dd>
            </dl>

#### equipSlots () → {[Array](Array.html).<[Number](Number.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Number</a>&gt;</span>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#eraseState</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### escape ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#escape</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### executeFloorDamage ()


<dl>
</dl>

#### expForLevel (level) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `level` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### faceIndex () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### faceName () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### finalExpRate () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### findNewSkills (lastSkills) → {[Array](Array.html).<[RPG.Skill](RPG.Skill.html)>}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `lastSkills` | [Array](Array.html).<[RPG.Skill](RPG.Skill.html)> |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Skill</a>&gt;</span>
                </dd>
            </dl>

#### forceAction (skillId, targetIndex)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |
| `targetIndex` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#forceAction</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### forceChangeEquip (slotId, item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `slotId` | [Number](Number.html) |  |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
</dl>

#### forgetSkill (skillId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |

<dl>
</dl>

#### friendsUnit () → {[Game_Party](Game_Party.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Party</a></span>
                </dd>
            </dl>

#### gainExp (exp)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `exp` | [Number](Number.html) |  |

<dl>
</dl>

#### gainHp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#gainHp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### gainMp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#gainMp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### gainSilentTp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#gainSilentTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### gainTp (value)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#gainTp</a>
                        </li>
                    </ul>
                </dd>
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

#### hasArmor (armor) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `armor` | [RPG.Armor](RPG.Armor.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasNoWeapons () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasSkill (skillId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasWeapon (weapon) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `weapon` | [RPG.Weapon](RPG.Weapon.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
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

#### index () → {[Number](Number.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### initEquips (equips)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `equips` | [Array](Array.html).<[Number](Number.html)> |  |

<dl>
</dl>

#### initExp ()


<dl>
</dl>

#### initialize (actorId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorId` | [Number](Number.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#initialize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initImages ()


<dl>
</dl>

#### initMembers ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#initMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### initSkills ()


<dl>
</dl>

#### initTp ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#initTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### inputtingAction () → {[Game_Action](Game_Action.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Action</a></span>
                </dd>
            </dl>

#### isActing () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isActing</a>
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

#### isActor () → {Boolean}

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isActor</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isAnimationRequested</a>
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

#### isBattleMember () → {Boolean}


<dl>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isChanting</a>
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

#### isClass (gameClass) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `gameClass` | [RPG.Class](RPG.Class.html) |  |

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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isDamagePopupRequested</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isEffectRequested</a>
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

#### isEquipChangeOk (slotId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `slotId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### isEquipped (item) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
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

#### isFormationChangeOk () → {Boolean}

<dl>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isGuardWaiting</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isInputting</a>
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

#### isLearnedSkill (skillId) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |

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

#### isMaxLevel () → {Boolean}


<dl>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isMotionRefreshRequested</a>
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

#### isMotionRequested () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isMotionRequested</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isSelected</a>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isSkillWtypeOk</a>
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

#### isSpriteVisible () → {Boolean}


<dl>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isStateAddable</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isStateRestrict</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isUndecided</a>
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

#### isWaiting () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isWaiting</a>
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

#### isWeaponAnimationRequested () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#isWeaponAnimationRequested</a>
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

#### isWtypeEquipped (wtypeId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `wtypeId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### lastBattleSkill () → {[RPG.Skill](RPG.Skill.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.Skill</a></span>
                </dd>
            </dl>

#### lastCommandSymbol () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### lastMenuSkill () → {[RPG.Skill](RPG.Skill.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.Skill</a></span>
                </dd>
            </dl>

#### learnSkill (skillId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skillId` | [Number](Number.html) |  |

<dl>
</dl>

#### levelDown ()


<dl>
</dl>

#### levelUp ()


<dl>
</dl>

#### makeActionList () → {[Array](Array.html).<[Game_Action](Game_Action.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Action</a>&gt;</span>
                </dd>
            </dl>

#### makeActions ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#makeActions</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### makeActionTimes () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#makeActionTimes</a>
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

#### makeAutoBattleActions ()


<dl>
</dl>

#### makeConfusionActions ()

<dl>
</dl>

#### makeSpeed ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#makeSpeed</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### maxFloorDamage () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxLevel ()


<dl>
</dl>

#### maxSlipDamage () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#maxSlipDamage</a>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#meetsUsableItemConditions</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#motionType</a>
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

#### name (name)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `name` | [String](String.html) |  |

<dl>
</dl>

#### nextLevelExp () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### nextRequiredExp () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### nickname () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### numActions () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#numActions</a>
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

#### onAllActionsEnd ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onAllActionsEnd</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onBattleEnd ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onBattleEnd</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onBattleStart ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onBattleStart</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onDamage (value)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `value` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onDamage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onPlayerWalk ()


<dl>
</dl>

#### onRestrict ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onRestrict</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onTurnEnd ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#onTurnEnd</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### opponentsUnit () → {[Game_Troop](Game_Troop.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Troop</a></span>
                </dd>
            </dl>

#### optimizeEquipments ()


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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#paramBase</a>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#paramMax</a>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#paramPlus</a>
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
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performAction</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performActionEnd ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performActionEnd</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performActionStart (action)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `action` | [Game_Action](Game_Action.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performActionStart</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performAttack ()


<dl>
</dl>

#### performCollapse ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performCollapse</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performCounter ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performCounter</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performDamage ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performDamage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performEscape ()


<dl>
</dl>

#### performEvasion ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performEvasion</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performMagicEvasion ()

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performMagicEvasion</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performMapDamage ()


<dl>
</dl>

#### performMiss ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performMiss</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performRecovery ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performRecovery</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performReflection ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performReflection</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performSubstitute (target)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `target` | [Game_Battler](Game_Battler.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#performSubstitute</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### performVictory ()


<dl>
</dl>

#### profile () → {[String](String.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
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
                            <a>Game_Battler#refresh</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regenerateAll ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#regenerateAll</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regenerateHp ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#regenerateHp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regenerateMp ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#regenerateMp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### regenerateTp ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#regenerateTp</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### releaseUnequippableItems (forcing)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `forcing` | Boolean |  |

<dl>
</dl>

#### removeAllBuffs ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeAllBuffs</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeBattleStates ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeBattleStates</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeBuff (paramId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `paramId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeBuff</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeBuffsAuto ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeBuffsAuto</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeCurrentAction ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeCurrentAction</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeState (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeState</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeStatesAuto (timing)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `timing` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeStatesAuto</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### removeStatesByDamage ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#removeStatesByDamage</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### requestEffect (effectType)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `effectType` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#requestEffect</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### requestMotion (motionType)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `motionType` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#requestMotion</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### requestMotionRefresh ()

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#requestMotionRefresh</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### resetStateCounts (stateId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `stateId` | [Number](Number.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#resetStateCounts</a>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#result</a>
                        </li>
                    </ul>
                </dd>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#select</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### selectNextCommand () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### selectPreviousCommand () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### setAction (index, action)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |
| `action` | [Game_Action](Game_Action.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#setAction</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setActionState (actionState)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actionState` | [String](String.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#setActionState</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setBattlerImage (battlerName)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `battlerName` | [String](String.html) |  |

<dl>
</dl>

#### setCharacterImage (characterName, characterIndex)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `characterName` | [String](String.html) |  |
| `characterIndex` | [Number](Number.html) |  |

<dl>
</dl>

#### setFaceImage (faceName, faceIndex)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `faceName` | [String](String.html) |  |
| `faceIndex` | [Number](Number.html) |  |

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

#### setLastBattleSkill (skill)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
</dl>

#### setLastCommandSymbol (symbol)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `symbol` | [String](String.html) |  |

<dl>
</dl>

#### setLastMenuSkill (skill)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `skill` | [RPG.Skill](RPG.Skill.html) |  |

<dl>
</dl>

#### setLastTarget (target)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `target` | [Game_Battler](Game_Battler.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#setLastTarget</a>
                        </li>
                    </ul>
                </dd>
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

#### setName (name)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `name` | [String](String.html) |  |

<dl>
</dl>

#### setNickname (nickname)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `nickname` | [String](String.html) |  |

<dl>
</dl>

#### setProfile (profile)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `profile` | [String](String.html) |  |

<dl>
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

#### setup (actorId)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorId` | [Number](Number.html) |  |

<dl>
</dl>

#### shiftAnimation () → {[MV.BattlerAnimation](MV.BattlerAnimation.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#shiftAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>MV.BattlerAnimation</a></span>
                </dd>
            </dl>

#### shouldDisplayLevelUp () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### showAddedStates ()


<dl>
</dl>

#### showRemovedStates ()


<dl>
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

#### skills () → {[Array](Array.html).<[RPG.Skill](RPG.Skill.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Skill</a>&gt;</span>
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
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#speed</a>
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

#### startAnimation (animationId, mirror, delay)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `animationId` | [Number](Number.html) |  |
| `mirror` | Boolean |  |
| `delay` | [Number](Number.html) |  |

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#startAnimation</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### startDamagePopup ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#startDamagePopup</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### startWeaponAnimation (weaponImageId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `weaponImageId` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#startWeaponAnimation</a>
                        </li>
                    </ul>
                </dd>
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

#### stepsForTurn () → {[Number](Number.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### testEscape (item)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
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

#### tradeItemWithParty (newItem, oldItem) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `newItem` | [RPG.EquipItem](RPG.EquipItem.html) |  |
| `oldItem` | [RPG.EquipItem](RPG.EquipItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### traitObjects () → {[Array](Array.html).<*>}

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#traitObjects</a>
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

#### turnEndOnMap ()

<dl>
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

#### updateStateSteps (state)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `state` | [RPG.State](RPG.State.html) |  |

<dl>
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

#### usableSkills () → {[Array](Array.html).<[RPG.Skill](RPG.Skill.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Skill</a>&gt;</span>
                </dd>
            </dl>

#### useItem (item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.UsableItem](RPG.UsableItem.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#useItem</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### weaponImageId () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Battler#weaponImageId</a>
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

#### weapons () → {[Array](Array.html).<[RPG.Weapon](RPG.Weapon.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Weapon</a>&gt;</span>
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