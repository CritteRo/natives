---
ns: HUD
aliases: ["0xC78E239AC5B2DDB9"]
---
## PAUSE_MENU_SET_BUSY_SPINNER

```c
// 0xC78E239AC5B2DDB9 0x6C67131A
void PAUSE_MENU_SET_BUSY_SPINNER(BOOL toggle, int justifyType, Any p2);
```

## Parameters
* **toggle**: Toggles the pause menu busy spinner. 
* **columnID**: 0 = left-justify / 1 = center-justify / 2 = right-justify. For 3-column menus, the busy spinner will always land in the middle of the column.
* **p2**: 


```lua
RegisterCommand('pause', function()
    ActivateFrontendMenu("FE_MENU_VERSION_MP_PAUSE", false, -1)
    Citizen.Wait(100)
    PauseMenuSetBusySpinner(true, 1, 0) --busy spinner in the middle of the map.
end)
```
