# The Qs — Home Network Notes

Subnet: `192.168.40.x` (machines from `.103` up, reserved in the router)

| Name | IP | Role | Status |
|---|---|---|---|
| **Boss** | 192.168.40.103 | Main work computer. Main repository lives on its mapped `Q:` drive. Voice features being set up here. | Active |
| **Mini** (hostname `HPmini1`) | ? | Future 24/7 server, file server, overnight worker. Will host the Q share as `\\HPmini1\Q`. | Being configured |
| **Boss 2** | ? | Spoke through its speaker in an earlier session. | Off — not needed now |
| **Linux machine** | ? | Older Linux install. Already uses the Q share. | Partly broken — separate project |
| *(fifth machine)* | ? | ? | ? |

## Shared drive

- Windows: mapped as `Q:`
- Network path (planned): `\\HPmini1\Q`
- Move from Boss to Mini: in progress

## To do

- [ ] Finish setting up Mini as server (file share, always-on)
- [ ] Move the Q share from Boss to Mini
- [ ] Decide: put the main repository on GitHub (`reidar54-hub/claude`)?
- [ ] Voice features on Boss
- [ ] Fix the Linux machine
- [ ] Turn off "quiet hours" (find where it's set)
- [ ] Fill in missing IPs and the fifth machine

## Notes

- Cloud Claude sessions (claude.ai/code) cannot reach `192.168.40.x`.
  To work on files on the Qs, use Claude Desktop (Code tab) on that machine,
  or `claude remote-control` in a terminal there.
