# Steady Hand Tool

**A stabilizing pick-and-place arm for precision SMD assembly.**

Steady Hand Tool is a manual SMD (Surface Mount Device) assembly stabilizer designed to help makers and professionals prototype PCBs with high precision. Originally created to overcome physical challenges—specifically hand tremors caused by Parkinson’s disease—this tool makes high-accuracy soldering accessible to everyone.

## 🌟 Key Features

* **Stabilized 4-DOF Movement:** Keeps your hand on a steady track while allowing full vertical and horizontal reach.
* **Near-Zero Friction:** Equipped with **14 high-quality metal bearings** and carbon fiber rods for smooth, silent, and effortless operation.
* **Modular Magnetic Coupler:** Features a quick-swap magnetic system for changing tool heads (tweezers, vacuum tips, etc.) in seconds.
* **Purely Mechanical:** No power required, no cables, and no noise. It's always ready to work when you are.
* **Heavy-Duty Base:** A weighted **680g (1.5 lb)** base ensures the arm remains stable even at full extension.
* **Open Source:** Designed to be hacked and customized. Create your own tool heads to suit your specific workflow.

## 🛠 Technical Specifications

* **Reach:** Approximately 250 mm (9.8 in) vertical and horizontal travel.
* **Construction:** 3D-printed components (optimized for PETG/Carbon Fiber) and 8mm carbon fiber rods.
* **Bearings:** MR128ZZ precision shielded bearings.
* **Compatibility:** Includes a pair of specialized reverse tweezers optimized for 0805-size components and smaller.

> [!TIP]
> **Looking to build it?** Check out our [Assembly Guide](https://www.google.com/search?q=assembly-guide.md) for step-by-step instructions.

## 📂 Repository Structure

```
steady-hand-tool/
├── .github/                # Issue templates and GitHub-specific config
├── hardware/               # All physical design files
│   ├── models/             # 3D models for printing
│   │   ├── stl/            # Ready-to-print files (standard)
│   │   ├── step/           # High-fidelity files for CAD software
│   │   └── community/      # User-submitted tool heads
│   ├── electronics/        # (Optional) If you ever add sensors/LEDs
│   └── reference/          # Technical drawings or dimension sheets
├── docs/                   # Documentation and guides
│   ├── assembly-guide.md   # Step-by-step build instructions
│   ├── images/             # Photos and GIFs used in the guides
│   └── calibration.md      # How to tune the arm for smooth movement
├── media/                  # High-res logos and marketing photos
├── .gitignore              # Tells Git which files to ignore (like temp CAD files)
├── BOM.md                  # Bill of Materials (the "Shopping List")
├── CONTRIBUTING.md         # How others can help
├── LICENSE                 # MIT License text
└── README.md               # The front page of your project
```

## 🤝 Our Mission & Support

My personal experience with Parkinson's disease inspired the creation of this tool. We believe that physical limitations shouldn't limit creativity.

---

## License

This project is licensed under the **MIT License** - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details. You are free to use, modify, and distribute this design for any purpose, provided the original copyright is maintained.

---

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
