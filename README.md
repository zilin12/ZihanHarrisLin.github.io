# Harris Lin — Personal Academic Website

Academic portfolio for Zihan Harris Lin, an undergraduate robotics researcher at Purdue University interested in robot learning and autonomous systems.

The current checkout uses plain HTML and CSS, with no build step or Quarto source files. It retains the original academic template's reading layout, typography, and automatic light/dark appearance.

## Edit content

- `index.html`: biography, research themes, project summaries, experience, education, skills, publications, and CV availability.
- `projects/`: six dedicated project and investigation pages. Keep project summaries and status labels consistent with the homepage.
- `assets/styles.css`: shared responsive styles.

Use confirmed information only. The two hardware/perception projects have descriptive status labels because completion dates were not supplied. Memory-augmented RL and bimanual manipulation are ongoing; domain randomization and efficient perception are exploratory. Do not turn research goals into reported results.

## Personal assets and links

The homepage displays Harris's portrait from `assets/1757467432481.jfif`. The inherited `assets/photo.jpg`, `assets/cv.pdf`, and `assets/smartdata.jpg` are not linked or presented as Harris's materials.

Once verified materials are available:

- Replace `assets/cv.pdf` with Harris's actual academic CV, then add its download link to the CV section.
- Add confirmed email, GitHub, and academic-profile links to the profile.
- Add project media, repository links, and measured results to their relevant pages.
- Add publication entries only after verifying their bibliographic details and status. The supplied measurement manuscript is described on its project page without claiming publication.

## Local preview

From the repository directory, run:

```powershell
python -m http.server 8000 --bind 127.0.0.1
```

Open `http://127.0.0.1:8000`. No dependencies or build command are required.

## Hosting

The files are compatible with GitHub Pages. Keep the homepage, `projects/`, and `assets/` together when deploying so that their relative links resolve. `.nojekyll` is retained for static hosting.
