# Kodekloud-Docker
Here I am just sharing the Command used for Successfully Completing the Challenges.
| Server Name | IP             | Hostname                          | User    | Password   | Purpose                        |
|-------------|----------------|----------------------------------|---------|------------|--------------------------------|
| stapp01     | 172.16.238.10  | stapp01.stratos.xfusioncorp.com   | tony    | Ir0nM@n    | Nautilus App 1                |
| stapp02     | 172.16.238.11  | stapp02.stratos.xfusioncorp.com   | steve   | Am3ric@    | Nautilus App 2                |
| stapp03     | 172.16.238.12  | stapp03.stratos.xfusioncorp.com   | banner  | BigGr33n   | Nautilus App 3                |
| stlb01      | 172.16.238.14  | stlb01.stratos.xfusioncorp.com    | loki    | Mischi3f   | Nautilus HTTP LBR             |
| stdb01      | 172.16.239.10  | stdb01.stratos.xfusioncorp.com    | peter   | Sp!dy      | Nautilus DB Server            |
| ststor01    | 172.16.238.15  | ststor01.stratos.xfusioncorp.com  | natasha | Bl@kW      | Nautilus Storage Server       |
| stbkp01     | 172.16.238.16  | stbkp01.stratos.xfusioncorp.com   | clint   | H@wk3y3    | Nautilus Backup Server        |
| stmail01    | 172.16.238.17  | stmail01.stratos.xfusioncorp.com  | groot   | Gr00T123   | Nautilus Mail Server          |
| jump_host   | Dynamic        | jump_host.stratos.xfusioncorp.com | thor    | mjolnir123 | Jump Server to Access Stork DC |
| jenkins     | 172.16.238.19  | jenkins.stratos.xfusioncorp.com   | jenkins | j@rv!s     | Jenkins Server for CI/CD      |
---------------------------------------------------------------------------------------------------------------------------
Below are the `sshpass` command for each user to SSH into their respective servers:

1. SSH into `stapp01` as `tony`:
sshpass -p 'Ir0nM@n' ssh -o StrictHostKeyChecking=no tony@172.16.238.10

2. SSH into `stapp02` as `steve`:
sshpass -p 'Am3ric@' ssh -o StrictHostKeyChecking=no steve@172.16.238.11

3. SSH into `stapp03` as `banner`:
sshpass -p 'BigGr33n' ssh -o StrictHostKeyChecking=no banner@172.16.238.12

4. SSH into `stlb01` as `loki`:
sshpass -p 'Mischi3f' ssh -o StrictHostKeyChecking=no loki@172.16.238.14

5. SSH into `stdb01` as `peter`:
sshpass -p 'Sp!dy' ssh -o StrictHostKeyChecking=no peter@172.16.239.10

6. SSH into `ststor01` as `natasha`:
sshpass -p 'Bl@kW' ssh -o StrictHostKeyChecking=no natasha@172.16.238.15

7. SSH into `stbkp01` as `clint`:
sshpass -p 'H@wk3y3' ssh -o StrictHostKeyChecking=no clint@172.16.238.16

8. SSH into `stmail01` as `groot`:
sshpass -p 'Gr00T123' ssh -o StrictHostKeyChecking=no groot@172.16.238.17
