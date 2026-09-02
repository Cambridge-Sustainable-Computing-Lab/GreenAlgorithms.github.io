---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults

last_modified_at: 07/07/2023


layout: splash
author_profile: false

header:
  overlay_image: 
  overlay_filter:
  text_color: rgb(80, 80, 80)
  image: /assets/images/primary_logo.png

permalink: /
title: ""
excerpt: "Towards environmentally sustainable computational science"

feature_row_1:
- image_path: /assets/images/GAapp_16x9.jpg
  alt: "Screenshot of the green algorithms calculator."
  title: "Calculator"
  excerpt: 'Easily estimate the carbon footprint of a computation.<br><br><a href="/GAapp-overview/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-calculator" class="btn btn--success">GitHub</a>'
- image_path: /assets/images/dashboard/user.png
  alt: "Screenshot of the dashboard."
  title: "Dashboard"
  excerpt: 'Monitor the energy usage and carbon footprint of your HPC use.<br><br><a href="/dashboard/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard" class="btn btn--success">GitHub</a>'
- image_path: /assets/images/GA4HPC_16x9.jpg
  alt: "Screenshot of the green algorithms HPC tool."
  title: "GA4HPC"
  excerpt: 'Calculate the carbon footprint of all computations run on an HPC platform.<br><br><a href="/GA4HPC/" class="btn btn--primary">Learn more</a> <a href="https://github.com/Cambridge-Sustainable-Computing-Lab/GreenAlgorithms4HPC" class="btn btn--success">GitHub</a>'

feature_training:
- image_path: /assets/images/placeholder_16x9.jpg
  alt: "Placeholder."
  title: "Including sustainability in computational training."
  excerpt: "How can we include sustainability in training sessions, from undergraduates to post-docs."
  url: /resources/
  btn_label: "Learn more"
  btn_class: "btn--primary"

gallery_logos:
  - url: "https://www.phpc.cam.ac.uk"
    image_path: /assets/images/cambridge-logo.png
  - url: "https://wellcome.org/"
    image_path: assets/images/wellcome-logo.png
  - url: "https://cambridgebrc.nihr.ac.uk/"
    image_path: assets/images/cambridge-nihr-brc-logo.png
  - url: "https://www.hdruk.ac.uk"
    image_path: /assets/images/HDRuk_gallery.png
---


<!-- __Are you looking for the online calculator?__ It's been moved to [calculator.green-algorithms.org](http://calculator.green-algorithms.org)
{: .notice--success} -->

<!-- __:hourglass: This website is a work in progress, and we will keep adding content in the coming weeks/months!__ Comments/suggestions can be made [here](https://github.com/GreenAlgorithms/GreenAlgorithms.github.io/issues).
{: .notice--warning} -->

<!-- __:bust_in_silhouette: We are recruiting!__ Interested in joining the Green Algorithms Initiative? We have a postdoctoral position available, more details [here](http://www.lannelongue-group.org/join/).
{: .notice--info} -->

<!-- __:tada: The Green Algorithms project has won the [2024 Susannah Boddie Impact of the Year Award](https://www.hdruk.ac.uk/news/winners-announced-2024-hdr-uk-annual-prizes/){:target="_blank"} at the Health Data Research UK annual conference!__ “The panel applauded the work’s clear impact on policy in a short time frame. The panel were impressed by the direct and tangible environmental impacts of these efforts, and recognised the pioneering role of this collaborative effort in raising awareness and providing tools for carbon footprint estimation in computational research.”
{: .notice--success} -->

<!-- __:mega: We are starting a Community of Practice around Environmentally Sustainable Computational Science!__ Interested in joining it or just seeing how this goes? __Just fill in [this form](https://forms.gle/pftpt2YEFsQqayut6).__
{: .notice--info} -->

<center>The Green Algorithms Initiative aims to promote more environmentally sustainable computational science.<br>
This page is a resource hub bringing together tools, documentation, and other resources to help digital researchers estimate the carbon footprint of their projects.</center>
<br>

<!-- TODO add news -->

<!-- TODO do the google SEO -->

<!-- ## Estimating the carbon footprint of algorithms -->

<!-- {% include feature_row id="feature_row_1" type="left"  %} -->
{% include feature_row id="feature_row_1" %}

<!-- ## From measuring to reducing the environmental impacts of our work

{% include feature_row id="feature_training" %} -->

## Resources

Publications related to the Green Algorithms Initiatives and related resources from the developers

- [‘GREENER principles for environmentally sustainable computational science’](https://rdcu.be/dfpLM), L. Lannelongue, H.-E. G. Aronson, A. Bateman, E. Birney, T. Caplan, M. Juckes, J. McEntyre, A. D. Morris, G. Reilly and M. Inouye, Nat Comput Sci, vol. 3, no. 6, pp. 514–521, Jun. 2023, doi: 10.1038/s43588-023-00461-y.
- [‘Carbon footprint estimation for computational research’](https://rdcu.be/c5KPJ), L. Lannelongue and M. Inouye, Nat Rev Methods Primers, vol. 3, no. 1, Art. no. 1, Feb. 2023, doi: 10.1038/s43586-023-00202-5.
- [‘Ten simple rules to make your computing more environmentally sustainable’](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1009324), L. Lannelongue, J. Grealey, A. Bateman, and M. Inouye, PLoS Computational Biology, vol. 17, no. 9, p. e1009324, Sept. 2021, doi: 10.1371/journal.pcbi.1009324.
- [‘Green Algorithms: Quantifying the Carbon Footprint of Computation’](https://www.green-algorithms.org/assets/publications/2023_GREENER_NatCompSci.pdf), L. Lannelongue, J. Grealey, and M. Inouye, Advanced Science, vol. 8, no. 12, p. 2100707, July 2021, doi: 10.1002/advs.202100707.

## About

The Green Algorithms Initiative is led by [Dr Loïc Lannelongue](https://cam-sustainablecomputing.org/members/Loic-Lannelongue.html), [Prof Michael Inouye](https://www.inouyelab.org/), and the [Cambridge Sustainable Computing Lab](https://cam-sustainablecomputing.org/) from the University of Cambridge (United Kingdom).

__Other Contributors__
- [Dr Jason Grealey](https://scholar.google.com/citations?user=DiAlGKAAAAAJ&hl=en) (then: Baker Heart and Diabetes Institute, Melbourne, Australia) helped to start this project and led the survey of the carbon footprint of bioinformatics.
- Even Matencio ([GitHub](https://github.com/evenmatencio), [LinkedIn](https://www.green-algorithms.org/about/www.linkedin.com/in/evenmatencio)) (then: French Department for the Environment, Paris, France) developed the v3.0 of the calculator and in particular the AI view.

This work was supported by core funding from the British Heart Foundation (RG/13/13/30194; RG/18/13/33946) and the NIHR Cambridge Biomedical Research Centre (BRC-1215-20014) [*]. *The views expressed are those of the author(s) and not necessarily those of the NIHR or the Department of Health and Social Care.

This work was also supported by Health Data Research UK, which is funded by the UK Medical Research Council, Engineering and Physical Sciences Research Council, Economic and Social Research Council, Department of Health and Social Care (England), Chief Scientist Office of the Scottish Government Health and Social Care Directorates, Health and Social Care Research and Development Division (Welsh Government), Public Health Agency (Northern Ireland), and British Heart Foundation and Wellcome.

This work was performed using resources provided by the Cambridge Service for Data Driven Discovery (CSD3) operated by the University of Cambridge Research Computing Service (www.csd3.cam.ac.uk), provided by Dell EMC and Intel using Tier-2 funding from the Engineering and Physical Sciences Research Council (capital grant EP/P020259/1), and DiRAC funding from the Science and Technology Facilities Council (www.dirac.ac.uk).

__More Credits__<br>
Project-specific credits can be found on their respective GitHub repositories (e.g. [calculator](https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-calculator), [dashboard](https://github.com/Cambridge-Sustainable-Computing-Lab/Green-Algorithms-HPCdashboard), [GA4HPC](https://github.com/Cambridge-Sustainable-Computing-Lab/GreenAlgorithms4HPC)).

This website is powered by [Jekyll](https://jekyllrb.com/) & [Minimal Mistakes](https://mademistakes.com/work/minimal-mistakes-jekyll-theme/).

## Supported by

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

[![CC BY 4.0][cc-by-image]][cc-by]&nbsp;&nbsp; All the work on this website is licensed under a [Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png