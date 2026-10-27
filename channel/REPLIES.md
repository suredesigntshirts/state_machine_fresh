# Reply channel

A draft PR that is never merged. The sandbox listener posts `CHANNEL-REPLY <nonce>` comments here; the state machine project subscribes to this PR to receive them. A PR delivers its events to one session at a time, so requests and replies use two PRs.
