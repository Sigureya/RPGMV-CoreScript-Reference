# Class: Game_Party

## Game_Party ()

#### new Game_Party ()

The game object class for the party. Information such as gold and items is included. Use as global variable [$gameParty](global.html#$gameParty)

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `ABILITY_ENCOUNTER_HALF` | [Number](Number.html) | [static] |
| `ABILITY_ENCOUNTER_NONE` | [Number](Number.html) | [static] |
| `ABILITY_CANCEL_SURPRISE` | [Number](Number.html) | [static] |
| `ABILITY_RAISE_PREEMPTIVE` | [Number](Number.html) | [static] |
| `ABILITY_GOLD_DOUBLE` | [Number](Number.html) | [static] |
| `ABILITY_DROP_ITEM_DOUBLE` | [Number](Number.html) | [static] |
| `_gold` | [Number](Number.html) |  |
| `_steps` | [Number](Number.html) |  |
| `_lastItem` | [Game_Item](Game_Item.html) |  |
| `_menuActorId` | [Number](Number.html) |  |
| `_targetActorId` | [Number](Number.html) |  |
| `_actors` | [Array](Array.html).<[Game_Actor](Game_Actor.html)> |  |
| `_items` | Object | {[itemId: number]: number} |
| `_weapons` | Object | {[itemId: number]: number} |
| `_armors` | Object | {[itemId: number]: number} |

<dl>
</dl>

### Extends

* [Game_Unit](Game_Unit.html)

### Methods

#### addActor (actorId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorId` | [Number](Number.html) |  |

<dl>
</dl>

#### agility () → {[Number](Number.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#agility</a>
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

#### aliveMembers () → {[Array](Array.html).<[Game_Battler](Game_Battler.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#aliveMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Battler</a>&gt;</span>
                </dd>
            </dl>

#### allItems () → {[Array](Array.html).<[RPG.BaseItem](RPG.BaseItem.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.BaseItem</a>&gt;</span>
                </dd>
            </dl>

#### allMembers () → {[Array](Array.html).<[Game_Actor](Game_Actor.html)>}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Actor</a>&gt;</span>
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

#### battleMembers () → {[Array](Array.html).<[Game_Actor](Game_Actor.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Actor</a>&gt;</span>
                </dd>
            </dl>

#### canInput () → {Boolean}

<dl>
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
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### charactersForSavefile () → {[Array](Array.html).<[Array](Array.html).<*>>}


<dl>
</dl>

##### Returns:


<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Array</a>.&lt;*&gt;&gt;</span>
                </dd>
            </dl>

#### clearActions ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#clearActions</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### clearResults ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#clearResults</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### consumeItem (item)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

#### deadMembers () → {[Array](Array.html).<[Game_Battler](Game_Battler.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#deadMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Battler</a>&gt;</span>
                </dd>
            </dl>

#### discardMembersEquip (item, amount)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.EquipItem](RPG.EquipItem.html) |  |
| `amount` | [Number](Number.html) |  |

<dl>
</dl>

#### equipItems () → {[Array](Array.html).<[RPG.EquipItem](RPG.EquipItem.html)>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.EquipItem</a>&gt;</span>
                </dd>
            </dl>

#### exists () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### facesForSavefile () → {[Array](Array.html).<[Array](Array.html).<*>>}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Array</a>.&lt;*&gt;&gt;</span>
                </dd>
            </dl>

#### gainGold (amount)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `amount` | [Number](Number.html) |  |

<dl>
</dl>

#### gainItem (item, amount, includeEquip)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |
| `amount` | [Number](Number.html) |  |
| `includeEquip` | Boolean |  |

<dl>
</dl>

#### gold () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### hasCancelSurprise () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasDropItemDouble () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasEncounterHalf () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasEncounterNone () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasGoldDouble () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasItem (item, includeEquip) → {Boolean}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |
| `includeEquip` | Boolean |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasMaxItems (item) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### hasRaisePreemptive () → {Boolean}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### highestLevel () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### inBattle () → {Boolean}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#inBattle</a>
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
</dl>

#### initAllItems ()

<dl>
</dl>

#### initialize ()


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#initialize</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### isAllDead () → {Boolean}

<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#isAllDead</a>
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

#### isAnyMemberEquipped (item) → {Boolean}



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

#### isEmpty () → {Boolean}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### itemContainer (item) → {[Array](Array.html).<[RPG.BaseItem](RPG.BaseItem.html)>}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.BaseItem</a>&gt;</span>
                </dd>
            </dl>

#### items () → {[Array](Array.html).<[RPG.Item](RPG.Item.html)>}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.Item</a>&gt;</span>
                </dd>
            </dl>

#### lastItem () → {[RPG.BaseItem](RPG.BaseItem.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.BaseItem</a></span>
                </dd>
            </dl>

#### leader () → {[Game_Actor](Game_Actor.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>

#### loseGold (amount)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `amount` | [Number](Number.html) |  |

<dl>
</dl>

#### loseItem (item, amount, includeEquip)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |
| `amount` | [Number](Number.html) |  |
| `includeEquip` | Boolean |  |

<dl>
</dl>

#### makeActions ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#makeActions</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### makeMenuActorNext ()

<dl>
</dl>

#### makeMenuActorPrevious ()

<dl>
</dl>

#### maxBattleMembers () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxGold () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### maxItems (item) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### members () → {[Array](Array.html).<[Game_Actor](Game_Actor.html)>}


<dl>
                <dt>Overrides:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#members</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Actor</a>&gt;</span>
                </dd>
            </dl>

#### menuActor () → {[Game_Actor](Game_Actor.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>

#### movableMembers () → {[Array](Array.html).<[Game_Battler](Game_Battler.html)>}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#movableMembers</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>Game_Battler</a>&gt;</span>
                </dd>
            </dl>

#### name () → {[String](String.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>String</a></span>
                </dd>
            </dl>

#### numItems (item) → {[Number](Number.html)}



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### onBattleEnd ()


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#onBattleEnd</a>
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
                            <a>Game_Unit#onBattleStart</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### onPlayerWalk ()


<dl>
</dl>

#### partyAbility (abilityId) → {Boolean}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `abilityId` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### performEscape ()


<dl>
</dl>

#### performVictory ()


<dl>
</dl>

#### randomDeadTarget () → {[Game_Battler](Game_Battler.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#randomDeadTarget</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Battler</a></span>
                </dd>
            </dl>

#### randomTarget () → {[Game_Battler](Game_Battler.html)}


<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#randomTarget</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Battler</a></span>
                </dd>
            </dl>

#### ratePreemptive (troopAgi) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `troopAgi` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### rateSurprise (troopAgi) → {[Number](Number.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `troopAgi` | [Number](Number.html) |  |

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### removeActor (actorId)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actorId` | [Number](Number.html) |  |

<dl>
</dl>

#### removeBattleStates ()


<dl>
</dl>

#### requestMotionRefresh ()


<dl>
</dl>

#### reviveBattleMembers ()


<dl>
</dl>

#### select (activeMember)



##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `activeMember` | [Game_Battler](Game_Battler.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#select</a>
                        </li>
                    </ul>
                </dd>
            </dl>

#### setLastItem (item)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `item` | [RPG.BaseItem](RPG.BaseItem.html) |  |

<dl>
</dl>

#### setMenuActor (actor)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
</dl>

#### setTargetActor (actor)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `actor` | [Game_Actor](Game_Actor.html) |  |

<dl>
</dl>

#### setupBattleTest ()


<dl>
</dl>

#### setupBattleTestItems ()


<dl>
</dl>

#### setupBattleTestMembers ()


<dl>
</dl>

#### setupStartingMembers ()


<dl>
</dl>

#### size () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### smoothDeadTarget (index) → {[Game_Battler](Game_Battler.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#smoothDeadTarget</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Battler</a></span>
                </dd>
            </dl>

#### smoothTarget (index) → {[Game_Battler](Game_Battler.html)}

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index` | [Number](Number.html) |  |

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#smoothTarget</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Battler</a></span>
                </dd>
            </dl>

#### steps () → {[Number](Number.html)}


<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Number</a></span>
                </dd>
            </dl>

#### substituteBattler () → {[Game_Battler](Game_Battler.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#substituteBattler</a>
                        </li>
                    </ul>
                </dd>
            </dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Battler</a></span>
                </dd>
            </dl>

#### swapOrder (index1, index2)

##### Parameters:

| Name | Type | Description |
| --- | --- | --- |
| `index1` | [Number](Number.html) |  |
| `index2` | [Number](Number.html) |  |

<dl>
</dl>

#### targetActor () → {[Game_Actor](Game_Actor.html)}

<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Game_Actor</a></span>
                </dd>
            </dl>

#### tgrSum () → {[Number](Number.html)}

<dl>
                <dt>Inherited From:</dt>
                <dd>
                    <ul>
                        <li>
                            <a>Game_Unit#tgrSum</a>
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