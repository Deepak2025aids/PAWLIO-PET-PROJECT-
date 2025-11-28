# Pawlio — Pet Adoption Project

This is the Pawlio pet adoption front-end project. It is a single-file HTML/CSS/JavaScript site (`index.html`) with local asset folders under `assets/`.

Quick start
- Open `index.html` in a browser (no build step required).
- Use the login panel to access gated content and the Adopt section.

Notes
- Asset paths are relative to the project root (e.g. `assets/Bruno/bruno.jpg`).
- Video placeholders are included; replace them with real `.mp4` files if desired.

Contributing
- If you want me to add GitHub Pages hosting or a short CI workflow, tell me and I can add it.

---
Generated and pushed by your assistant on request.

Project structure

Below is an overview of the repository and what each top-level folder/file contains. I did not modify any application features — only added hosting/dev metadata.

- `index.html`: The entire front-end UI (HTML, CSS, and JavaScript). This is the single entry point for the app.
- `assets/`: Local media for pets. Each pet has its own folder:
	- `assets/Bruno/` — `bruno.jpg`, `bruno.mp4`
	- `assets/Luna/` — `luna.jpg`, `luna.mp4`
	- `assets/Max/` — `max.jpg`, `max.mp4`
	- `assets/Pippin/` — `pippin.jpg`, `pippin.mp4`
	- `assets/Zoe/` — `zoe.jpg`, `zoe.mp4`
	- `assets/Rocky/` — `rocky.jpg`, `rocky.mp4`
	- `assets/Pip/` — `pip.jpg`, `pip.mp4`
- `Images/` : Misc images (for example `LOGO.jpg`).
- `videos/` : (Optional) repository-level video folder if you decide to centralize large files here.

Why these files matter
- `index.html` contains the data object `PETS_DATA`, the UI logic (`filterPets`, `showPetDetails`, auth handling), and the modal media code. Replacing files inside `assets/` with real images and mp4s updates what visitors see—no code changes required.

GitHub Pages
- I added a Pages workflow that will deploy the repository to GitHub Pages whenever you push to `main`. After the first successful run you should be able to access the site at:

	`https://<your-github-username>.github.io/PAWLIO-PET-PROJECT-/`

	Note: Pages enablement may require checking repository settings on GitHub; if you want I can help enable and verify it.

Security & size notes
- Large media files (MP4s) increase repository size. If you plan to keep large videos, consider hosting them externally (Cloud storage or an S3 bucket) and linking to them, or use a release asset/storage solution.

If you'd like, I can now:
- Enable and verify Pages (open the repo settings and confirm the Pages URL).
- Convert local videos to be referenced from an external host (I can add instructions or a script to update `PETS_DATA`).

# PAWLIO-PET-PROJECT-