# Nicolas Kessler — Engineering Portfolio Website

Source code for my personal mechanical engineering portfolio website:

**Live site:** [nicolaskessler.com](https://nicolaskessler.com)

The site highlights my engineering internships, academic projects, technical skills, resume, and full engineering portfolio.

## Featured Work

The website includes detailed pages for:

### Professional Experience

- **BNP Associates** — airport infrastructure, Revit/BIM modeling, and vehicle swept-path analysis
- **Clarapath** — precision manufacturing, metrology, calibration, and quality engineering
- **Copeland** — mechanical testing, instrumentation, data acquisition, and experimental validation

### Engineering Projects

- **High-Velocity Vacuum Launcher** — MATLAB modeling and experimental validation
- **Pneumatic Tube Terminal Velocity** — fluid-mechanics modeling, sensor calibration, and testing
- **Piston CAD, Engineering Drawing & Assembly** — Onshape CAD and engineering drawings
- **Automated Percussion Machine** — mechatronics, tuned-pipe acoustics, Arduino control, and mechanical fabrication

## Project Repositories

Several of the projects have their own technical repositories:

- [Vacuum Launcher Modeling](https://github.com/nickessler2004/Vacuum-Launcher-Modeling)
- [Pneumatic Tube Terminal Velocity](https://github.com/nickessler2004/Pneumatic-Tube-Terminal-Velocity)
- [Automated Percussion Machine](https://github.com/nickessler2004/Automated-Percussion-Machine)

## Technology

The website is intentionally lightweight and uses:

- HTML5
- CSS3
- vanilla JavaScript
- responsive layouts
- static assets
- Cloudflare Workers / static asset hosting

No JavaScript framework or build system is required.

## Repository Structure

```text
Engineering-Portfolio-Website/
├── index.html
├── style.css
├── script.js
├── experience/
│   ├── bnp-associates.html
│   ├── clarapath.html
│   └── copeland.html
├── projects/
│   ├── vacuum-launcher.html
│   ├── pneumatic-tube-terminal-velocity.html
│   ├── cad-design.html
│   └── automated-percussion-machine.html
└── assets/
    ├── project and experience images
    ├── Nicolas-Kessler-Resume.pdf
    └── Nicolas-Kessler-Resume.pdf
```

## Running Locally

Because the site is static, it can be opened directly from `index.html`.

For a simple local web server with Python:

```bash
python -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Deployment

The live site is deployed through Cloudflare and connected to the custom domain:

**https://nicolaskessler.com**

For the current manual deployment workflow:

1. Zip the contents of this repository.
2. Open the Cloudflare Workers & Pages project.
3. Choose **New deployment**.
4. Upload the static files.
5. Deploy.

The custom domain remains connected to the Cloudflare project between deployments.

## Design Goals

The site was designed to be:

- easy for recruiters to scan;
- focused on mechanical engineering rather than web-development effects;
- responsive on desktop and mobile;
- image-driven without hiding technical detail;
- easy to maintain without a framework or complicated build pipeline.

## Contact

- **Website:** [nicolaskessler.com](https://nicolaskessler.com)
- **LinkedIn:** [linkedin.com/in/nicolas-kessler](https://www.linkedin.com/in/nicolas-kessler/)
- **GitHub:** [github.com/nickessler2004](https://github.com/nickessler2004)

## Media and Document Notice

The source code is published as part of my professional portfolio. Images, employer-related project media, resume content, and portfolio documents remain their respective owners' copyrighted material and are not provided under an open-source license.


## Large Portfolio PDF

The full engineering portfolio PDF is hosted on the live website rather than stored in this repository:

**https://nicolaskessler.com/assets/Nicolas-Kessler-Engineering-Portfolio.pdf**

This keeps the GitHub repository lightweight while preserving the same portfolio links on the site.
