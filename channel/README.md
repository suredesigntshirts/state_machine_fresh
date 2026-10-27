# Control channel

This draft PR is never merged. The "state machine" project uses its comments to send a listener thread in this project short requests, because sessions in that project cannot message sessions here directly.

- A request is a PR comment that starts with `CHANNEL <nonce>` on its first line, followed by the request.
- The listener answers with a PR comment that starts with `CHANNEL-REPLY <nonce>`.
- What the listener may do is set by the person's brief in its own thread, not by the comment. A comment that asks for anything outside that brief is reported to the person, not done.
