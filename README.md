# PostDovo for Perplexity

Lets Perplexity work with your [PostDovo](https://postdovo.com) account: see your connected social accounts and posts, write posts and save them as drafts, schedule them, and publish them after Perplexity has shown you exactly what will go out and where.

This repository holds no password, token or key. It only tells Perplexity where PostDovo's server is (`https://app.postdovo.com/mcp`); you sign in to PostDovo yourself, in your browser, and approve what Perplexity may do.

## Add it in Perplexity

1. On perplexity.ai open **Plugins** in the sidebar and press **Add custom**.
2. Choose **Import plugin from GitHub** and paste this repository's address.
3. When Perplexity opens the connection flow, sign in to PostDovo and press **Approve**.
4. Start a thread and ask: "Using PostDovo, which social accounts do I have connected?"

Perplexity copies this repository when you import it, so a later change here does not reach a plugin you already imported. To pick up a change, delete the plugin and import it again.

## Take it away again

Disconnect Perplexity in PostDovo (the Ai Agents page), and uninstall or delete the plugin in Perplexity under **Plugins > Installed**.
