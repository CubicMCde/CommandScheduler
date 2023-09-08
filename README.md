# CommandScheduler

> [!IMPORTANT]
> Plugin can pose a security issue, therefore, care must be taken with the permissions.
> Plugin runs commands as **console**!

### Permissions
| Command  | Permission[^1] | Description |
| ------------- | ------------- | ------------- |
| `/commandscheduler`  | commandscheduler.scheduler  | Open gui of all schedulers |
| `/commandscheduler reload`  | commandscheduler.scheduler.reload  | Reloads the config |
| `/commandscheduler start [NAME]` | commandscheduler.scheduler.start | Starts a scheduler |
| `/commandscheduler stop [NAME]` | commandscheduler.scheduler.stop | Stops a scheduler |

[^1]: The permission format is PLUGIN_NAME.ROOT_COMMAND_NAME[.SUB_COMMAND_NAME]
