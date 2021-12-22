# DOCUMENTATION FOR STTASK!

## Contents

- [\_\_init\_\_]()
  - [TaskOwner]()
    - [sttask.TaskOwner.tasks: list]()
    - [sttask.TaskOwner.scheduled: list]()
    - [sttask.TaskOwner.add(name: str, func, args: tuple = ()) -> int]()
    - [sttask.TaskOwner.task_list() -> list]()
    - [sttask.TaskOwner.schedule_list() -> list]()
    - [sttask.TaskOwner.sttask.TaskOwner.update() -> None]()
    - [sttask.TaskOwner.grab_task(name: str) -> int]()
    - [sttask.TaskOwner.grab_schedule(name: str) -> int]()
    - [sttask.TaskOwner.schedule(name: str, func, time: int, args: tuple = ()) -> int]()
    - [sttask.TaskOwner.play(task: str) -> None]()
    - [sttask.TaskOwner.pause(task: str) -> None]()
    - [sttask.TaskOwner.name_set(task: str, name: str) -> None]()
    - [sttask.TaskOwner.update_set(task: str, func) -> None]()
    - [sttask.TaskOwner.args_set(task: str, args: tuple) -> None]()
    - [sttask.TaskOwner.grab_output(task: str)]()
    - [sttask.TaskOwner.pop_task(task: str) -> None]()
    - [sttask.TaskOwner.play_schedule(schedule: str) -> None]()
    - [sttask.TaskOwner.pause_schedule(schedule: str) -> None]()
    - [sttask.TaskOwner.name_set_schedule(schedule: str, name: str) -> None]()
    - [sttask.TaskOwner.update_set_schedule(schedule: str, func) -> None]()
    - [sttask.TaskOwner.args_set_schedule(schedule: str, args: tuple) -> None]()
    - [sttask.TaskOwner.pop_schedule(schedule: str) -> None]()
  - [Task]()
    - [sttask.Task.name]()
    - [sttask.Task.update]()
    - [sttask.Task.paused]()
    - [sttask.Task.args]()
    - [sttask.Task.output]()
  - [Schedule]()
    - [sttask.Schedule.name]()
    - [sttask.Schedule.update]()
    - [sttask.Schedule.paused]()
    - [sttask.Schedule.args]()
    - [sttask.Schedule.time]()
  - [sttask.end: int]()
  - [sttask.pause: int]()
- [utils]()
  - [sttask.utils.convert(task, \*, schedule_time = 0)]()