# How to upload using the GitHub web interface

## If the `proof-room` folder does not exist yet

1. Go to `QuebecAI / QuebecAI.github.io`.
2. Click **Add file → Upload files**.
3. Drag the entire local folder named `proof-room` into the upload area.
4. Commit message: `Publish QUEBEC.AI Proof Room`.
5. Click **Commit changes**.

## If the `proof-room` folder already exists

1. Open the existing `proof-room` folder in GitHub.
2. Click **Add file → Upload files**.
3. Drag the contents from inside your local `proof-room` folder: `index.html`, `style.css`, `assets`, `dockets`, `proofbundles`, `capability-archive`, `review`, `data`, `templates`, and `docs`.
4. Commit message: `Upgrade QUEBEC.AI Proof Room`.
5. Click **Commit changes**.

Correct final path:

```text
proof-room/index.html
```

Avoid this wrong path:

```text
proof-room/proof-room/index.html
```
