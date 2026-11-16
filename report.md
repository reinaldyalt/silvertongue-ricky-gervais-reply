# Silvertongue dogfood: install the extension and publish only its generated text

- Google Chrome 157.0.8103.78 on Linux, Silvertongue 0.2.2 installed from the Chrome Web Store (extension id `lanedehejpgpanageefmjbfgaeppeidl`), kept installed through review.
- X account @clipperjosjis; published reply: https://x.com/clipperjosjis/status/2122184108331892883 (reply to https://x.com/auscaster/status/2120592516592681301).
- Voice: Ricky Gervais (Comedy). My own input: "Every brand launch reads exactly the same now. 'Thrilled to announce' is the new 'circle back' - you can tell a bot wrote it from the first three words." Exact generated output, copied character for character into the reply: "Thrilled to announce" is the new "circle back", isn't it? Every brand launch reads the same now. Three words in & you already know a robot wrote it because no human gives a shit.
- Installation worked (store page shows "Remove from Chrome"), rewriting worked (the extension returned a completed draft and I inserted it into the composer), publishing worked (the reply is live with the exact generated text, no edits).
- One problem: the generation dialog hides the original input once the draft is done, so the generation screenshot shows the completed output and the voice but not the input field; the input is quoted in full in the bullet above and in `evidence.json`.

## Evidence

- `voice_packet.json` — the Ricky Gervais voice profile used for the rewrite.
- `evidence.json` — reply URL, post data URL, screenshots, and the exact input/output pair.
- `compose_chrome.json` — browser/extension versions, target tweet, input, and generated output.
- `installation_screenshot.png` — Chrome Web Store page showing "Remove from Chrome" with the address bar and extension id visible.
- `generation_screenshot.png` — the extension dialog with the Ricky Gervais voice, "Done", and the readable completed output.
- `generation_input_view.png` — the same dialog with the options expanded, showing the original input and the voice.
