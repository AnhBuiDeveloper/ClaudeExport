# Troubleshooting

## Export controls are missing

Confirm the extension is enabled in `chrome://extensions` or `edge://extensions`. Open a signed-in conversation on claude.ai, reload the page and try the toolbar popup. Check whether browser policy has restricted the extension. Claude page changes can affect available controls.

## A feature in a website guide is missing

Check your installed version. The website describes scheduled 1.2 workflows while Chrome's listing showed 1.1.1 on 22 October 2026. Browser stores may publish at different times. See the [changelog](../CHANGELOG.md); do not install unverified packages to obtain an announced feature.

## An export is incomplete or looks different

Try a short conversation with invented sample text. Confirm the scope, artifact and thinking options. Compare another core format to identify whether the problem concerns content or layout. Complex tables, images and fonts may render differently by format or viewer. Report what is missing without posting the original conversation.

If your version offers a missing-image preview, try its recovery controls, supply a local replacement, or explicitly skip the image. Review any site-access request before granting it. Do not share image URLs that may contain private access tokens.

## A PDF did not save

In versions offering native printing, choose Save as PDF and finish the browser dialog. Opening or closing the dialog is not evidence that a file was saved. Check your browser's downloads or selected destination. Other installed versions can use a different PDF flow.

## Pro has not activated

Confirm you are using the browser profile that completed checkout. Follow the [activation guide](https://claude.export.anhbui.dev/activate), or use purchase restore with your purchase email and private verification code. Review existing devices through the purchase email's management link if necessary. A temporary network problem may affect activation; retain your purchase email and contact support if retrying does not help.

Never post your email verification code, license token, private management URL or purchase records publicly. Send account and billing questions to [support@anhbui.dev](mailto:support@anhbui.dev).

## A backup stopped

For the scheduled 1.2 backup workflow, keep the archive page and a signed-in Claude tab open, check browser download prompts and use Resume/retry where available. Review completed and failed items; do not assume all conversations were captured. Avoid reinstalling before preserving any local archive data you need.

## Still blocked?

Use the [bug report form](https://github.com/AnhBuiDeveloper/ClaudeExport/issues/new?template=bug_report.yml) with browser/version, extension version, operating system, format, safe reproduction steps and a sanitized error. See [SUPPORT.md](../SUPPORT.md) for private channels and information to exclude.

[Back to README](../README.md)
