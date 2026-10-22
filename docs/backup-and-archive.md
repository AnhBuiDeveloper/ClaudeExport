# Backup and archive

## Available bulk-export workflow

The published Chrome listing describes **Pro bulk export**: choose multiple accessible conversations and save them in a ZIP. Use the bulk-export controls present in your installed version and verify the resulting files. Do not assume every conversation or attachment is available simply because it exists in your Claude account.

A ZIP of exported documents is a portable copy for your own use. It is not a promise that conversations can be re-imported into Claude or that an entire account is reproduced.

## Scheduled 1.2: backup and local archive

The website's [backup guide](https://claude.export.anhbui.dev/help/backup-claude-conversations) describes a **1.2 Pro workflow**. Store availability is unconfirmed; Chrome showed 1.1.1 on 22 October 2026. These instructions apply only when the corresponding controls exist in your installed extension.

1. Keep a signed-in Claude tab open. Open Settings, then **Backup & local archive**.
2. Choose full or incremental backup and review the available filters and selected conversations.
3. Enable local retention/indexing only if you want copies in the browser's local archive.
4. Start the user-assisted backup and keep its page open. Confirm any browser download prompts.
5. Review completed items and use Resume/retry for interrupted work. Inspect saved files before assuming the backup is complete.

The public guide states that inventory is limited to the first 1,000 exposed conversations. Availability can change with Claude. These backups require browser participation and are not unattended writes to your filesystem.

The announced local archive offers content search, collections and deletion of retained records. It is separate from downloaded backup files and is not a hosted cloud archive. Removing the extension or browser profile can remove local records; keep independent copies of anything important. Deleting an archive record does not remove a file you already downloaded elsewhere.

## Protect backup files

Backups may contain private prompts, responses, artifacts and optional thinking. Store them somewhere appropriate for that content and review access before sharing. Never upload backups, conversation files or archive data to public GitHub issues. Use [private support](../SUPPORT.md) for sensitive problems.

[Privacy and data](privacy-and-data.md) · [Troubleshooting](troubleshooting.md) · [Back to README](../README.md)
