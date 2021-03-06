# Class: Game_CommonEvent

## Game_CommonEvent ()

#### new Game_CommonEvent ()

The game object declare class for a common event. It contains functionality for running parallel process events.

##### Properties:

| Name | Type | Description |
| --- | --- | --- |
| `_commonEventId` | [Number](Number.md) |  |
| `_interpreter` | [Game_Interpreter](Game_Interpreter.md) |  |

<dl>
</dl>

### Methods

#### event () → {[RPG.CommonEvent](RPG.CommonEvent.md)}

Returns the common event information from the database.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>RPG.CommonEvent</a></span>
                </dd>
            </dl>

#### initialize ()

 オブジェクト生成時の初期化。
<dl>
</dl>

#### isActive () → {Boolean}

Returns true if the common event is active.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span>Boolean</span>
                </dd>
            </dl>

#### list () → {[Array](Array.md).<[RPG.EventCommand](RPG.EventCommand.md)>}

Returns the common event's list of event commands.
<dl>
</dl>

##### Returns:

<dl>
                <dt> Type </dt>
                <dd>
                    <span><a>Array</a>.&lt;<a>RPG.EventCommand</a>&gt;</span>
                </dd>
            </dl>

#### refresh ()

Refreshes the common event.
<dl>
</dl>

#### update ()

Updates the common event.
<dl>
</dl>
 <br>

  Documentation generated by [JSDoc 3.5.5](https://github.com/jsdoc3/jsdoc)
