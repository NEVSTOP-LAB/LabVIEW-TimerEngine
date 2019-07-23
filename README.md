# LabVIEW-TimerEngine

使用 UserEvent 实现的 Timer 功能。后台使用一个 Timed Loop 进行定时，到达指定时间后，使用 UserEvent 通知订阅 Timer 的模块。

## API：

 - `Register.vi` : 订阅 Timer
    - Name：Timer 名称
    - TimerPeroid： 时间间隔
    - `Start?`: 是否立即启用

 - `unRegister.vi` 取消订阅 Timer
    - Name：Timer 名称

 - `Enable.vi` 启用 Timer
    - Name：Timer 名称
    - Enable：是否启用

 - `Rename.vi` 重命名 Timer
    - Name：Timer 名称
    - NewName: 新名称


