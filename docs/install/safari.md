# Safari install guide

Safari uses an Xcode project conversion flow. You need to donwload Xcode from the AppStore.

1. Clone the repo and install dependencies.
```bash
git clone https://github.com/Noah4ever/ai-chat-speed-booster
npm i
```
2. Run:

```bash
npm run safari:setup
```

3. Open the generated Xcode project (if not opened automatically):

```bash
open "safari-app/AI Chat Speed Booster/AI Chat Speed Booster.xcodeproj"
```

4. In Xcode, select the macOS app target and click the **Run**-icon to the left (▶).

![Select macOS app target in Xcode](../../assets/docs/xcode-target.png)

5. After it builds it will run the app and prompt you to enable the extension in Safari settings with this popup:

![Extension popup](../../assets/docs/extension-popup.png)


6. Verify the extension popup appears in Safari.

![Enable extension in Safari settings](../../assets/docs/safari-extension.png)

7. Allow the extension to run on your AI chat sites.