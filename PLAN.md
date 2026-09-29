Goal: batch-generate images from a prompt file; browsable gallery for designers
Input: prompts.txt (one per line, # comments) Output: runs/<timestamp>/{images/, manifest.jsonl,
gallery.html}
MVP: load prompts -> POST /images -> save by media_type -> manifest row -> gallery
Then: concurrency, --variations with seeds, skip done, cost summary. Stretch: contact sheet PNG