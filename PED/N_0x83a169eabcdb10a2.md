---
ns: PED
---
## _0x83A169EABCDB10A2

```c
// 0x83A169EABCDB10A2
void _0x83A169EABCDB10A2(Ped ped, Any colorID);
```
This function sets the mobile phone case color (created with CreateMobilePhone() )

Phone color IDs:
0 = "Blue"
1 = "Green"
2 = "Red"
3 = "Orange"
4 = "Gray"
5 = "Purple"
6 = "Pink"

## Parameters
* **ped**: The ped ID that you want to apply the phone case to.
* **colorID**: the color that you want on the phone case.


## Examples

```lua
N_0x83a169eabcdb10a2(PlayerPedId(), 0) --sets the player's ped phone case color to Blue
```
