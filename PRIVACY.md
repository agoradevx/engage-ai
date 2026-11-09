# Engage AI Privacy Policy

**Effective Date:** November 9, 2026  
**Last Updated:** November 9, 2026  

Engage AI is an AI reply generator and social media writing assistant provided by Agora Devx. This Privacy Policy describes how Engage AI processes, stores, and protects your information.

## What Engage AI does

Engage AI helps you understand an individual social post, generate English reply drafts with Chinese translations, and polish your own Chinese or English draft. You decide whether to copy, insert, edit or publish a reply. The extension does not automatically comment, like, follow or message.

## Data processed

- The currently supported post's text, author name and handle, loaded comments and their author names, and relevant article context.
- Up to four loaded Reddit image attachments when using a compatible vision API.
- Your own draft when you request polishing.
- Your chosen AI API URL, model and API key.
- Tab IDs and URLs needed to connect the side panel to the current post and reconnect after navigation. The extension does not maintain a browsing-history database.
- Local diagnostic metadata: provider/model identifiers, request times, error categories and redacted provider explanations. Exports omit API keys and post/reply text; review exports before sharing them.

Posts or drafts can contain personal information or communications. Only request analysis of content you are comfortable sending to your chosen provider. The extension does not deliberately request health, financial or payment information, location, or general click/keystroke tracking.

## Where data goes

AI requests go directly from your browser to the AI API you configure. Requests include the relevant content above and authentication required by that provider. Image URLs may be sent to the model API; for Gemini, the extension downloads supported Reddit images and sends their bytes. Reddit image hosts receive the image request, not your AI key. Fetching a Substack comments page's associated article may use your existing site session.

The extension has no bundled developer AI key, account backend, advertising SDK, analytics service or publisher collection endpoint. It does not include AI credits. Provider access, charges, processing, retention and any use of data to improve models depend on your account, settings and provider terms. Check those terms before choosing a provider. Custom API operators can receive the same request data as named providers.

## Storage, retention and deletion

API settings and keys are saved in extension-local storage on your device, not Chrome Sync. Analysis results use browser-session storage and expire when that session ends. Diagnostics are bounded and stored locally. You can replace the API key and settings, clear diagnostics in Help & logs, or uninstall the extension to remove its local data. Clearing local extension data does not delete data already held by an AI provider; use that provider's controls.

## Permissions

Storage saves local settings, session results and diagnostics. Tabs connects the panel to supported posts. Scripting restores the packaged reader when needed and inserts a draft after your click. SidePanel displays the assistant beside the page. Social-site and image host access supports the readers and attachments. Provider host access sends AI requests. Optional HTTPS host access is requested for the custom API origin you configure.

## Limited use

The extension uses data solely to provide its stated post-understanding and reply-drafting features. The publisher does not sell user data, use it for advertising, or use it to determine creditworthiness or lending eligibility. Data transfer to your chosen AI API serves these user-requested features. No unrelated publisher data processing is implemented.

## Contact Us

If you have questions, feedback, or data privacy inquiries regarding Engage AI, please contact:
- **Publisher:** Agora Devx
- **Email:** agoradevx@gmail.com
- **Repository:** https://github.com/agoradevx/engage-ai
