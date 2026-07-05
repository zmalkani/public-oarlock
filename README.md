# public-oarlock

A community collection of DIY 3D-printable rowing oarlock designs. Browse existing designs, print your own, and share what you've made.

---

## Using the Designs

1. **Browse** the folders in this repository — each folder contains one oarlock design.
2. **Download** the files you need:
   - `.f3d` — Fusion 360 source file (edit and customise the design).
   - `.step` — neutral CAD format (import into any CAD tool).
3. **Slice and print** the model with your preferred slicer. Adjust scale, infill, and supports to suit your printer and material.

---

## Contributing a Design

Everyone is welcome to add their own oarlock design. Please follow the guidelines below so the repository stays consistent and useful.

### Requirements

| Requirement | Details |
|---|---|
| **One folder per design** | Create a new folder with a short, descriptive name (e.g. `swivel-pin-oarlock`). |
| **Fusion 360 source file** | Include the `.f3d` file so others can modify the design. |
| **STEP file** | Include a `.step` export so the design is usable in any CAD application. |
| **README (optional but encouraged)** | Add a `README.md` inside your folder describing the design, intended use, print settings, and any assembly notes. |

### Folder structure example

```
my-oarlock-design/
├── my-oarlock-design.f3d
├── my-oarlock-design.step
└── README.md          ← optional but appreciated
```

### Steps to contribute

1. **Fork** this repository.
2. Create a new branch: `git checkout -b my-oarlock-design`.
3. Add your design folder containing at minimum the `.f3d` and `.step` files.
4. **Commit** your changes: `git commit -m "Add my-oarlock-design"`.
5. Open a **Pull Request** against `main` and describe your design in the PR description.

Pull requests that are missing either the `.f3d` or `.step` file will be asked to provide the missing file before merging.

---

## License

All designs in this repository are shared under the [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) license unless a design folder specifies otherwise.
