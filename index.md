---
layout: splash
author_profile: false

title: "Home"

#header:
#  image: /assets/images/GA_primary_logo.png
#  image_description: "Green Algorithms Initiative logo"

feature_row_1:
- image_path: /assets/images/GAapp_16x9.jpg
  alt: "Screenshot of the green algorithms calculator."
  title: "Online calculator"
  excerpt: 'Easily estimate the carbon footprint of a computation.<br><br><a href="/GAapp-overview/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-calculator" class="btn btn--success">GitHub</a>'
- image_path: /assets/images/dashboard-user_16x9.png
  alt: "Screenshot of the dashboard."
  title: "Dashboard"
  excerpt: 'Monitor the energy usage and carbon footprint of your HPC use.<br><br><a href="/dashboard/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard" class="btn btn--success">GitHub</a>'
- image_path: /assets/images/GA4HPC_16x9.jpg
  alt: "Screenshot of the green algorithms HPC tool."
  title: "GA4HPC"
  excerpt: 'A minimalist version of the dashboard for single user (no admin access needed).<br><br><a href="/GA4HPC/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/GreenAlgorithms4HPC" class="btn btn--success">GitHub</a>'

gallery_logos:
  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/cambridge-logo.png
  - url: "https://wellcome.org/"
    image_path: /assets/images/wellcome-logo.png
  - url: "https://cambridgebrc.nihr.ac.uk/"
    image_path: /assets/images/cambridge-nihr-brc-logo.png
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/HDRuk_gallery.png
---

<img src="{{ '/assets/images/GA_primary_logo.png' | relative_url }}" alt="Green Algorithms Initiative logo" style="display: block; margin: 2.5rem auto 2.5rem; max-width: 500px; width: 100%; height: auto;">

The Green Algorithms Initiative aims to promote more environmentally sustainable computational science. <br>
This page is a resource hub bringing together tools, documentation, and other resources to help digital researchers estimate the carbon footprint of their projects. For more related work, check out the [Cambridge Sustainable Computing Lab](https://cam-sustainablecomputing.org/).
{: .text-center}

## <i class="fa-solid fa-screwdriver-wrench"></i> The different tools 
{% include feature_row id="feature_row_1" %}

## <i class="fa-solid fa-users-viewfinder"></i> E-SCOUT: do carbon calculators incentivise sustainable behaviours?

Tools like the Green Algorithms online calculator have proven useful for researchers, research software engineers, and organisations to understand the environmental impacts of their work, but some important questions remain: To what extent does carbon tracking incentivise green computing practices? Or how can we make sure it does?

__The Environmentally Sustainable Computing User Trial of the Green Algorithms Initiative (E-SCOUT) aims to empirically evaluate the effectiveness of carbon reporting tools in reducing the environmental impacts of scientific computing.__ As part of the study, the effectiveness of different types of feedback will be compared for different user groups, leveraging a new [open source dashboard](https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard) for HPC.
Reflecting its user-centred approach, E-SCOUT will use co-design throughout all stages to ensure that the feedback interventions are tailored to the users’ needs, goals and constraints. The Lab is also planning to set up a steering group that brings together people with diverse perspectives for reflection and decision-making.

{% capture notice-text %}
If you work for a research performing organisation (RPO) that uses HPC and would be interested in getting involved, register your interest below. We also welcome interest from individuals for our steering group. 

<p>
  <a href="https://cam-sustainablecomputing.org/projects/e-scout" class="btn btn--primary" style="color: #fff;">Learn more</a>
  <a href="https://zcvf-zcmp.maillist-manage.eu/ua/Optin?od=12ba7ed0a72a&zx=14adf96b94&tD=1230131c7ae86159&sD=1230131c7af91a97" class="btn btn--success">Register interest</a>
</p>
{% endcapture %}

<div class="notice--info">
  {{ notice-text | markdownify }}
</div>

## How to cite this work and related publications 

If you are using one of these tools, please cite:

- Lannelongue, Loïc, Jason Grealey, and Michael Inouye. 2021. __‘Green Algorithms: Quantifying the Carbon Footprint of Computation’__. Advanced Science 8 (12): 2100707. [10.1002/advs.202100707](https://doi.org/10.1002/advs.202100707).

And you may also find these publications interesting (on how to use different carbon trackers, or examples of applications):
- Lannelongue, Loïc, and Michael Inouye. 2023. __‘Carbon Footprint Estimation for Computational Research’__. Nature Reviews Methods Primers 3 (1): 1. [10.1038/s43586-023-00202-5](https://doi.org/10.1038/s43586-023-00202-5).
- Grealey, Jason, Loïc Lannelongue, Woei-Yuh Saw, et al. 2022. __‘The Carbon Footprint of Bioinformatics’__. Molecular Biology and Evolution, February 10, msac034. [10.1093/molbev/msac034](https://doi.org/10.1093/molbev/msac034).
- Souter, Nicholas E., Chris Racey, Nikhil Bhagwat, et al. 2025. __‘Comparing the Carbon Footprint of fMRI Data Processing and Analysis Approaches’__. Imaging Neuroscience 3 (June): IMAG.a.36. [10.1162/IMAG.a.36](https://doi.org/10.1162/IMAG.a.36).


## <i class="fa-solid fa-circle-info"></i> About
The Green Algorithms Initiative is a project of the [Cambridge Sustainable Computing Lab](https://cam-sustainablecomputing.org/) led by [Dr Loïc Lannelongue](https://cam-sustainablecomputing.org/members/Loic-Lannelongue.html) from the University of Cambridge (UK). [Prof Michael Inouye](https://www.inouyelab.org) has been involved from the start. [Navirah Kamal](https://cam-sustainablecomputing.org/members/Navirah-Kamal.html) is the Research Software Engineer developing and maintaining these tools and [Dr Christina Bremer](https://cam-sustainablecomputing.org/members/Christina-Bremer.html) leads the E-SCOUT study.

<a href="{{ '/assets/images/CSCL-logo_small.png' | relative_url }}" style="display: block; text-align: center;">
  <img src="{{ '/assets/images/CSCL-logo_small.png' | relative_url }}" alt="CSCL logo" style="max-width: 400px; width: 100%; height: auto;">
</a>

### Other Contributors
- Past and current [members](https://cam-sustainablecomputing.org/team/) of the Cambridge Sustainable Computing Lab.
- [Dr Jason Grealey](https://scholar.google.com/citations?user=DiAlGKAAAAAJ&hl=en) (then: Baker Heart and Diabetes Institute, Melbourne, Australia) helped to start this project and led the survey of the carbon footprint of bioinformatics.
- Even Matencio ([GitHub](https://github.com/evenmatencio), [LinkedIn](https://www.linkedin.com/in/evenmatencio)) (then: French Department for the Environment, Paris, France) developed the v3.0 of the calculator and in particular the AI view.

### Funding 
This work was supported by funding from the Wellcome Trust, NetDRIVE and NERC. It was also made possible through core funding from the British Heart Foundation, the NIHR Cambridge Biomedical Research Centre[*] and Health Data Research UK, which is funded by the UK Medical Research Council, Engineering and Physical Sciences Research Council, Economic and Social Research Council, Department of Health and Social Care (England), Chief Scientist Office of the Scottish Government Health and Social Care Directorates, Health and Social Care Research and Development Division (Welsh Government), Public Health Agency (Northern Ireland), and British Heart Foundation and Wellcome. *The views expressed are those of the author(s) and not necessarily those of the NIHR or the Department of Health and Social Care.

<div class="logo-row-large">
  {% for item in page.gallery_logos %}
    <a href="{{ item.url }}" target="_blank" rel="noopener">
      <img src="{{ item.image_path | relative_url }}" alt="Logo">
    </a>
  {% endfor %}
</div>

<style>
.logo-row-large {
  display: flex;
  flex-wrap: nowrap;
  justify-content: space-evenly;
  align-items: center;
  gap: 0rem;
  margin: 3.5rem 0;
  width: 100%;
}

.logo-row-large a {
  flex: 1 1 0;
  display: flex;
  justify-content: center;
  align-items: center;
  padding: 0;
}

.logo-row-large img {
  width: 100%;
  max-width: 350px;
  height: 180px;
  object-fit: contain;
  border: none !important;
  box-shadow: none !important;
}

/* Tablet & Mobile layout */
@media (max-width: 850px) {
  .logo-row-large {
    flex-wrap: wrap;
    gap: 1.5rem 0.5rem;
  }
  .logo-row-large a {
    flex: 1 1 calc(50% - 0.5rem);
  }
  .logo-row-large img {
    height: 110px;
    max-width: 260px;
  }
}
</style>
