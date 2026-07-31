# Task 4 — Real-World Project (Mini Project): Mechanical Domain

## Brief
Prepare a complete AutoCAD project in the mechanical domain: a 3D assembly drawing of at least 3–4 parts. Submit final drawing files + a project report (2–3 pages explaining workflow and output).

## Assembly: Universal Coupling

A universal coupling (flange/pin-and-fork type) is a mechanical joint used to connect two rotating shafts whose axes are not perfectly aligned, allowing torque to be transmitted while accommodating a degree of angular misalignment. This is a standard mechanical-drawing assembly exercise, built here as a genuine multi-part CATIA assembly rather than a single fused solid.

## Components (5 parts — exceeds the 3–4 part minimum)
| Part file | Component |
|---|---|
| `centre-block.catpart` | Centre block — the sliding/pivoting core that links both forks |
| `fork.catpart` | Fork — U-shaped yoke keyed to the shaft, straddling the centre block |
| `collar.catpart` | Collar — retains/locates the shaft-to-fork connection |
| `pin.catpart` | Pin — the pivot connecting fork to centre block |
| `taper-pin.catpart` | Taper pin — secondary locking pin (shaft-to-fork or shaft-to-collar retention) |

## Files
```
4.Task_4/
├── cad-files/
│   ├── centre-block.catpart
│   ├── collar.catpart
│   ├── fork.catpart
│   ├── pin.catpart
│   ├── taper-pin.catpart
│   ├── universal-coupling.catproduct   ← top-level assembly (native CATIA)
│   ├── universal-coupling.stp          ← neutral STEP export
│   ├── universal-coupling.igs          ← neutral IGES export
│   └── universal-coupling.3dxml        ← lightweight 3D viewer format
└── renders/
    ├── render-01-closed-view.jpg
    └── render-02-exploded-angle.jpg
```



## Status
 complete (5 parts, native + neutral formats, renders provided) — **project report still required** for full compliance with CodeAlpha's Task 4 criteria.
