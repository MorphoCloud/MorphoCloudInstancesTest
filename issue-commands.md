### Supported Issue Commands

_The commands described below may be added as issue comments. Only one command
may be entered per comment._

| Command            | Description                                                   | Who                              |
| ------------------ | ------------------------------------------------------------- | -------------------------------- |
| `/shelve`          | Shelve the instance.                                          | Issue creator, Admin, GitHub App |
| `/unshelve`        | Unshelve the instance.                                        | Issue creator, Admin, GitHub App |
| `/encode_email`    | Update issue description obfuscating emails.                  | Issue creator, Admin, GitHub App |
| `/decode_email`    | Update issue description deobfuscating emails.                | Issue creator, Admin, GitHub App |
| `/email`           | Send email to _Issue creator_ with connection URL.            | Issue creator, Admin             |
| `/renew`           | Extend the instance lifespan if additional time is available. | Issue creator, Admin             |
| `/create`          | Create the instance and associated volume.                    | Admin                            |
| `/delete_instance` | Delete the instance.                                          | Admin, GitHub App                |
| `/delete_volume`   | Delete the volume.                                            | Admin, GitHub App                |
| `/delete_all`      | Delete the instance and volume.                               | Admin                            |
