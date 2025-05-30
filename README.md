# Segment Anything 2 Video for Label Studio – Mac M1 Quick Fix

## What is this?

Just a quick-and-dirty adaptation of the Segment Anything 2 Video integration for Label Studio, made to work on my Mac M1 (Apple Silicon).
 Maybe the official repo has fixed it already, but if you ever run into similar issues on an M1, this might save you some time.

## Why?

Because sometimes libraries don’t play nice with Apple Silicon and I needed it working fast.
 I tweaked a few dependencies, changed some settings, and it worked for me on my MacBook M1.

## How to use

1. Clone this repo.

2. Set up a virtual environment (always a good idea).

3. Install requirements:

   ```bash
   pip install -r requirements.txt
   ```

4. If something breaks, try updating/reinstalling `torch` or `opencv` for M1 (see comments in the code or Google your error).

5. Use with Label Studio as you normally would.

## Disclaimer

- This is **not** an official fork, just a working copy for Mac M1.
- Check the [original repo](https://github.com/your-upstream-repo) for updates, maybe they fixed it by now.
