# blender-character-rigging
a detailed process on rigging character models!!!


# 3D Character Rigging & Pipeline Setup in Blender

A technical breakdown and showcase of my character rigging workflow in **Blender**, covering armature hierarchy setup, facial bone integration, joint alignment, and material/texture configuration.

> **Disclaimer:** To respect intellectual property and copyright guidelines, proprietary game assets (`.mesh`, `.mdf2`, and raw texture files) are excluded from this repository. This repo documents the technical pipeline, setup notes, and viewport results.

---

## 📸 Viewport Showcase

### 1. Full-Body Armature & Material Setup
*Full-body skeleton hierarchy aligned with the character mesh, including limb, torso, and hand/finger joints with configured shaders.*

![Full Body Rig](images/full-body-rig.png)

### 2. Facial Rig & Upper-Body Joint Breakdown
*Close-up view of the facial bone cluster and upper-body armature prepared for expression posing and deformation testing.*

![Facial Rig Breakdown](images/facial-rig-closeup.png)

---

## 🛠️ What I Learned & Implemented

* **Armature & Hierarchy Setup:** Imported and organized multi-part character armatures (`pl0000` / `pl0001`), verifying parent-child bone relationships across the spine, limbs, fingers, and face.
* **Facial Bone Structure:** Configured high-density facial control bones on a clay head mesh to prepare for localized facial deformation and expression testing.
* **Material & Texture Workflow:** Resolved texture import pipelines and assigned material slots (`Material 00`, `Material 01`) cleanly inside Blender's Shader workflow.
* **Viewport & Outliner Organization:** Structured collections and mesh/armature visibility for clean debugging and posing.

---

## 🚀 Next Steps

- [ ] Refine weight painting for smoother shoulder, elbow, and wrist deformations
- [ ] Build custom IK/FK control shapes for easier animation posing
- [ ] Set up drivers and shape keys for facial expressions
- [ ] Export a short idle/walk cycle test render

---

## 💻 Tools Used
* **Blender** (4.5 / 5.3)
* **3D Rigging & Armature Tools**

