# STELLAR anonymous project page

This repository is the static project page for **Structure-Aware Progressive
Refinement for Localized Text-Guided Point Cloud Editing (STELLAR)**. It is
intended for an anonymous submission. The site does not identify authors or
institutions.

## Materials and paper mapping

| Site section | Supplied material | Paper location |
| --- | --- | --- |
| Introduction | Author-supplied Introduction text | Introduction |
| Experimental Results, Table 1 | Values transcribed from the author-supplied manuscript | Experiments, Table 1: ShapeTalk quantitative evaluation |
| Experimental Results, Table 2 | Values transcribed from the author-supplied manuscript | Experiments, Table 2: STELLAR ablation |
| Overview | `assets/pdf/overview.pdf` and its PNG preview | Figure 1, Introduction |
| Workflow | `assets/pdf/workflow.pdf` and its PNG preview | Figure 2, Method |
| Supplementary figures | `assets/pdf/supplementary-1.pdf` through `supplementary-6.pdf` and PNG previews | Supplementary visualizations |
| Homepage rotating examples | `assets/animations/chair.gif`, `table.gif`, `lamp.gif` | Supplementary visualizations |

The PNG files in `assets/figures/` are raster previews of the corresponding
author-supplied PDF figures. The three GIF files are copied from the supplied
animations without altering their content. The page uses the supplied title,
Introduction text, Figure 1/2 captions, and manuscript Table 1/2 values.
The two result tables reproduce the values in the supplied manuscript draft;
the website does not independently validate the underlying evaluations. They
appear after the workflow and immediately before supplementary visualizations.
Schematic figures are not presented as experimental outputs.

## View locally

Open `index.html` in a browser. No build step or external dependency is needed.
For GitHub Pages, serve the root of the `main` branch.

## Reproducibility scope

The supplied package for this site contains figures and animations, not the
manuscript PDF, executable code, model checkpoints, dataset manifests, or
evaluation scripts. Consequently the page does not offer a paper download or
claim that experiments can be reproduced from this repository alone. Add and
verify those materials separately before advertising a reproduction procedure.

## Source filenames

- `overview.pdf` was supplied as `easy_figure.pdf`.
- `workflow.pdf` was supplied as `stellar_main_workflow.pdf.pdf`.
- `supplementary-1.pdf` through `supplementary-6.pdf` correspond to the
  supplied `1.pdf` through `6.pdf`, in order.
- The animations correspond to the supplied chair, table, and lamp rotation
  GIFs, respectively.
