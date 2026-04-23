# 09 — Support

Section with a heading, two tabs (FAQ / Articles & Tutorials), a
right-hand sidebar with three contact rows, and two sets of
fallback content.

**Important — out of scope for this pass:**

- The **FAQ items** and **article cards** are loaded at runtime from
  `lucakaufmann.github.io/easymqtt/` (the same JSON the iOS app uses).
  The copy shown on the live page comes from there. The fallback copy
  below is only what ships hardcoded in the HTML and only appears if
  the remote fetch fails. Improving the *real* FAQs and article
  summaries means editing that other repo, not this file.
- "step‑by‑step" uses a non-breaking hyphen (U+2011).

---

### Section kicker

> Support

---

### Section title (H2)

"Here's every answer." is set in *italic serif* for display emphasis.

> Need help? *Start here.*

---

### Section lede

> Troubleshooting guides, setup tutorials, and direct support for real MQTT workflows.

---

### Tab labels

> FAQ
>
> Articles & Tutorials

---

### Sidebar — heading and lede

> ### Still stuck?
>
> Reach out and you'll hear back from the developer. Good support matters when you're debugging brokers, payloads, widgets, or automation flows.

---

### Sidebar row 1 — Email

> **support@easymqtt.app**
>
> Email support for setup and troubleshooting

---

### Sidebar row 2 — Discord

> **Community Discord**
>
> Compare setups, shortcuts, and widget ideas

---

### Sidebar row 3 — Documentation

> **Full documentation**
>
> Setup guides, MQTT tips, and feature walkthroughs

---

## Fallback FAQs — reference only

These only render if the remote JSON fails to load. The *live* FAQs
come from `lucakaufmann.github.io/easymqtt/en.json` → `faqSections`
and should be edited there. Listed here so the writer has the full
set of text the site can produce.

---

### Fallback FAQ 1

> **The app won't connect to my broker**
>
> First, try a known-good public broker like `broker.hivemq.com` to confirm the app can reach the network. If that works, check your host, port, credentials, TLS settings, and client ID. The most common problems are the wrong port, a TLS mismatch, or stale broker credentials.

---

### Fallback FAQ 2

> **How do I configure Siri Shortcuts?**
>
> Open the Shortcuts app, create a new shortcut, and search for **EasyMQTT**. You'll find actions for **Send Message**, **Send Favorite**, and **Fetch Message**. Pick a saved broker, enter a topic, and either hardcode a payload or pass one in from another action.

---

### Fallback FAQ 3

> **I can't see any brokers when setting up a Shortcut or Widget**
>
> Make sure the broker is saved in the app first. Add it from the Connect screen or under **Settings → Brokers**, give it a clear name, then save it. Saved brokers are what the app exposes to widgets and Shortcuts.

---

### Fallback FAQ 4

> **What do the Send Message and Fetch Message shortcuts do?**
>
> **Send Message** publishes a payload to a topic on a broker, with optional retain. **Fetch Message** subscribes to a topic and returns a message value so you can feed MQTT state into the rest of your Shortcut. It works best when the topic has a retained message available.

---

### Fallback FAQ 5

> **What types of widgets are there?**
>
> EasyMQTT supports MQTT widgets for quick-glance values and graph widgets for values over time. Plus unlocks richer multi-graph widgets with live update support inside the app, so you can build a small dashboard around the topics you watch most.

---

### Fallback FAQ 6

> **Does EasyMQTT support TLS / SSL?**
>
> Yes. EasyMQTT supports TLS/SSL, client certificates imported as PKCS#12 files, and MQTT over secure WebSockets. If your setup needs it, you can also allow untrusted certificates for brokers that are using self-signed or otherwise non-standard trust chains.

---

### Fallback FAQ 7

> **Is my data synced across devices?**
>
> Saved brokers, favorites, and remembered broker locations can sync through iCloud. Live messages stay on device, and connection history is stored locally on the device where it was recorded.

---

### Fallback FAQ 8

> **Does EasyMQTT run on Mac?**
>
> Yes. EasyMQTT runs on Mac with the same core broker, publish, subscribe, widget, and Shortcuts workflows available on iPhone and iPad through the Mac Catalyst build.

---

## Fallback article cards — reference only

Same story as above: the live article list comes from `articles.json`
in the support repo. These four only ship as fallbacks. Each card has
a small meta tag, an H4 title, and a summary paragraph.

---

### Fallback article 1

> Meta: **Tutorial**
>
> #### Graphing Zigbee2MQTT sensors with widgets
>
> Turn Zigbee2MQTT temperature, humidity, or power readings into glanceable MQTT widgets in a few minutes.

---

### Fallback article 2

> Meta: **Guide**
>
> #### Home Assistant + EasyMQTT: a quick start
>
> Connect EasyMQTT to your Home Assistant broker, subscribe to key topics, and trigger MQTT actions from Siri and Shortcuts.

---

### Fallback article 3

"good‑morning" uses a non-breaking hyphen (U+2011).

> Meta: **Tips**
>
> #### Five Siri Shortcuts we can't live without
>
> From good‑morning routines to retained-state checks and NFC actions, these are the automations MQTT users set up again and again.

---

### Fallback article 4

> Meta: **Reference**
>
> #### MQTT wildcards, explained with real topics
>
> When to use `+` versus `#`, with real MQTT topic examples from home automation and device debugging.

---

### "Read article" link label

Appears at the bottom of every article card.

> Read article
