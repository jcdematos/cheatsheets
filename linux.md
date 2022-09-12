# Linux
## Users
| Command | Description |
| - | - |
| `sudo useradd <username>` | Create user |
| `sudo useradd -m <username>` | Create user and home directory |
| `sudo useradd -m -d /home/dir/path <username>` | Create user with specified home directory | 
| `sudo useradd -u <uid> <username>` | Create user with specified uid |

<!---
Add user to group

sudo usermod -a -G groupname username

List groups a user is part of
groups

Prints information about user and it's groups
id

To get all groups look at
/etc/group 

Get all users from a group
getent group groupname
--->
