# Privacy and data

The [official Privacy Policy](https://claude.export.anhbui.dev/privacy) is the maintained source for data handling. This guide summarizes user-facing choices; newer website features may not exist in your store version. See [release status](../CHANGELOG.md).

## Standard exports stay local

Standard conversation-to-file processing takes place in your browser. Conversation content is not sent to Claude Export's service to create those files. Downloaded files, clipboard contents and any optional local archive can still contain sensitive information: check them before sharing and use suitable storage.

The extension needs access to the Claude content you choose to export. Local processing does not mean the extension requires no permissions or that every feature works without a network connection.

## Optional transfers and connections

- **Send to Notion (Pro):** you explicitly choose to transfer selected content directly to your Notion workspace using your integration token. Do not share that token.
- **Google Docs:** the website describes a conditional optional connection using Google authorization. If available and explicitly connected, chosen content goes directly to Google. It is not promised in currently published store builds.
- **Images:** obtaining an image can require a request to Claude or an image site. Review any additional site permission before allowing it. A local replacement image, where supported, is read from your device for the export.

A provider's own privacy terms apply to content you send there.

## Licensing, purchases and product events

Local document creation is separate from purchase and license services. The official policy describes purchase-email use, device information for license management, service diagnostics and product events. Payment providers handle checkout; do not send payment-card details to support.

The current website policy describes opt-in anonymous usage events, off by default, and newer Settings privacy controls. Do not assume every historical store version offers those same controls. Review your installed Settings and the official policy; contact support if a privacy choice is unclear.

## Local archive and deletion

The scheduled 1.2 workflow makes local archive retention/indexing optional. If your version supports it, manage retained records in **Backup & local archive**. This is browser-local storage, separate from downloaded files and optional provider transfers. Removing an extension or profile can remove local records. Keep copies of anything you need before removal.

Deleting local records does not delete downloaded files or copies sent to other providers. Manage those copies separately. For access, correction, deletion or other privacy requests involving Claude Export's service records, email **[support@anhbui.dev](mailto:support@anhbui.dev)**.

## Public support is public

Never post conversations, backups, personal information, purchase records, passwords, license or integration tokens, verification codes or payment details in issues, discussions or pull requests. Use invented sample content to demonstrate bugs. See [support](../SUPPORT.md) and [security reporting](../SECURITY.md).

[Back to README](../README.md)
