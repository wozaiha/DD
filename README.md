# SamplePlugin

Simple example plugin for Dalamud.

This is not designed to be the simplest possible example, but it is also not designed to cover everything you might want to do. For more detailed questions, come ask in [the Discord](https://discord.gg/3NMcUV5).

## Main Points

    ChatLog = 0,不管
    
    Territory = 1,done,但是ACT资源文件翻译和本地有区别是什么鬼
    
    ChangePrimaryPlayer = 2,logout？
    
    AddCombatant = 3,
    
    RemoveCombatant = 4,
    
    PartyList = 11,拿partylist 每帧比较
    
    PlayerStats = 12,这是哪个包？
    
    StartsCasting = 20,done
    
    ActionEffect = 21,done
    
    AOEActionEffect = 22,done
    
    CancelAction = 23,done
    
    DoTHoT = 24,done
    
    Death = 25,done
    
    StatusAdd = 26, done
    
    TargetIcon = 27,done
    
    WaymarkMarker = 28,done
    
    SignMarker = 29,done
    
    StatusRemove = 30,done
    
    Gauge = 31,done
    
    //这仨大概也是actorcontrol？

    World = 32,
    
    Director = 33,
    
    NameToggle = 34,
    
    Tether = 35,done(取消连线ACT没写)
    
    LimitBreak = 36, 
    
    EffectResult = 37,这玩意怎么触发的
    
    StatusList = 38,object结构拿？
    
    UpdateHp = 39, 
    
    ChangeMap = 40,区别还挺大的,抄radar?
    
    SystemLogMessage = 41,不管
    
    StatusList3 = 42,
//以下不管
    Settings = 249,
    Process = 250,
    Debug = 251,
    PacketDump = 252,
    Version = 253,
    Error = 254
