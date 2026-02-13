---
title: "UM Geodynamics - One Page"
layout: default
excerpt: "UM Geodynamics one-page site"
sitemap: false
permalink: /onepage/
---

<div class="onepage col-sm-12">
  <section class="onepage-hero" id="top">
    <p class="onepage-kicker">University of Miami</p>
    <h1>Geodynamics Group</h1>
    <p>
      We are located within the Department of Marine Geoscience, at the
      <a href="https://www.rsmas.miami.edu">Rosenstiel School of Marine, Atmospheric, and Earth Science</a>,
      and led by <a href="https://people.miami.edu/profile/axh1305@miami.edu">Prof. Adam F. Holt</a>.
      We constrain the factors that govern plate and mantle deformation, and the rates and scales over which this deformation occurs.
    </p>
    <nav class="onepage-nav">
      <a href="#research">Research</a>
      <a href="#teaching">Teaching</a>
      <a href="#team">Team</a>
      <a href="#publications">Publications</a>
    </nav>
  </section>

  <figure class="onepage-banner">
    <img src="{{ site.url }}{{ site.baseurl }}/images/RSMAS_w_caption.png" alt="RSMAS campus">
  </figure>

  <section id="research" class="onepage-section">
    <h2>Research</h2>
    <p>
      We investigate the causes, rates, and scales of deformation at plate boundaries, within plates, and in the underlying mantle. We integrate geodynamic modeling techniques with geological and geophysical observations.
    </p>
    <ol>
      <li>
        <strong>Regional subduction dynamics.</strong> Analytical and numerical models linking mantle flow and pressure to near-surface deformation and tectonics
        ([Holt et al., 2017, GJI](/documents/papers/holt_et_al_gji2017.pdf);
        [Király et al., 2018, G-Cubed](/documents/papers/kiraly_et_al_g3-2018.pdf);
        [Faccenna et al., 2017, Tectonophys.](/documents/papers/faccenna_et_al_tectono2017.pdf);
        [Holt et al., 2018, EPSL](/documents/papers/holt_et_al_epsl2018.pdf)).
      </li>
      <li>
        <strong>Subduction zone thermal structure, metamorphism, and dehydration.</strong> Numerical models of feedbacks between slab geometry, convergence, thermal structure, and phase transformations
        ([Holt and Condit, 2021, G-Cubed](/documents/papers/holt-condit_g3-2021.pdf)).
      </li>
      <li>
        <strong>Plate tectonic analyses.</strong> Mechanical rules for present-day tectonic observations and tests of plate-reconstruction dynamic feasibility
        ([Clennett et al., 2023, Sci. Rep.](/documents/papers/clennett_et_al_scirep2023.pdf)).
      </li>
      <li>
        <strong>Global subduction and mantle dynamics.</strong> Analytical and global numerical models of slab-induced mantle flow and slab-dip distributions
        ([Holt and Royden, 2020, G-Cubed](/documents/papers/holt-royden_2020_g3.pdf);
        [Holt, 2022, GRL](/documents/papers/holt_grl2022.pdf)).
      </li>
    </ol>
  </section>

  <section id="teaching" class="onepage-section">
    <h2>Teaching</h2>
    <ul class="onepage-courses">
      <li>
        <strong>Natural Disasters: Hollywood vs. Reality (GSC 107)</strong>:
        Introductory science course on geologic hazards and societal response.
        [Syllabus](/documents/misc/Syllabus_GSC107.pdf)
      </li>
      <li>
        <strong>Geodynamics (MGS 724)</strong>:
        Graduate course on rheology, heat and mass transport, and numerical methods.
        [Lecture notes and exercises](https://github.com/AdamFHolt/MGS723_Geodynamics)
      </li>
      <li>
        <strong>Subduction Zone Geodynamics (MGS 710)</strong>:
        Literature-based overview of slab deformation, mantle flow, rheology, and subduction-induced topography.
        [Syllabus](/documents/misc/Syllabus_MGS710.pdf),
        [Schedule](/documents/misc/Schedule_MGS710.pdf)
      </li>
    </ul>
    <figure>
      <img src="{{ site.url }}{{ site.baseurl }}/images/MainCampus.png" alt="University of Miami Main Campus">
    </figure>
  </section>

  <section id="team" class="onepage-section">
    <h2>Team</h2>
    <h3>Current Members</h3>
    <div class="row onepage-team-grid">
      {% for member in site.data.team_members %}
      <article class="col-sm-6 onepage-team-card">
        <img src="{{ site.url }}{{ site.baseurl }}/images/teampic/{{ member.photo }}" alt="{{ member.name }}">
        <div>
          <h4>{{ member.name }}</h4>
          <p><em>{{ member.info }}</em><br>email: &lt;{{ member.email }}&gt;</p>
          {% if member.number_addit == 1 %}
          <p>{{ member.addit1 }}</p>
          {% endif %}
          {% if member.number_addit == 2 %}
          <p>{{ member.addit1 }}<br>{{ member.addit2 }}</p>
          {% endif %}
        </div>
      </article>
      {% endfor %}
    </div>

    <h3>Former Members</h3>
    <ul>
      <li>Sam Goldberg, NSF Postdoctoral Fellow, now UMiami faculty ([website](https://www.samgoldberg.org/))</li>
      <li>Yidan Wang, now in Guoqing Lin's seismology group ([poster](/documents/posters/yidan_ALW_poster.pdf))</li>
      <li>Jazmin Garza, Bachelor's Thesis ([poster](/documents/posters/jazmin_garza_poster.pdf))</li>
      <li>Chantal Newallo, Bachelor's Thesis ([poster](/documents/posters/chantal_newallo_poster.pdf))</li>
    </ul>
  </section>

  <section id="publications" class="onepage-section onepage-publications">
    <h2>Publications</h2>
    <p class="onepage-scholar"><a href="https://scholar.google.com/citations?user=hIU7K7IAAAAJ&hl=en">Google Scholar</a></p>
    <ol reversed>
      <li>Neuharth, D., Behr, W. M., and Holt, A. F., 2025. The role of along-strike variations in interface rheology on subduction dynamics: constraints from 3D numerical models. <em>Geophys. J. Int.</em>, 244, doi:10.1093/gji/ggaf515. ([PDF](/documents/papers/neuharth_et-al_gji2026.pdf))</li>
      <li>Stoner, R. K., Holt, A. F., Epstein, G. S., Guevara, V. E., and Condit, C. B., 2025. Emergent Feedbacks Between Progressive Serpentinization, Interface Weakening, and Subduction Rates. <em>Geochem., Geophys., Geosys.</em>, 26, doi:10.1029/2025GC012488. ([PDF](/documents/papers/stoner_et-al_g3-2025.pdf))</li>
      <li>Gianni, G. M., Guo, Z., Holt, A. F., and Faccenna, C., 2025. Non-collisional orogeny in northeast Japan driven by nearby same-dip double subduction. <em>Nature Geosc.</em>, doi:10.1038/s41561-025-01704-5. ([PDF](/documents/papers/gianni_et-al_ngeo2025.pdf))</li>
      <li>Conrad, E. M., Faccenna, C., Holt, A. F., and Becker, T. W., 2024. Tectonic reorganization of the Caribbean plate system in the Paleogene driven by Farallon slab anchoring. <em>Geochem., Geophys., Geosys.</em>, doi:10.1029/2024GC011499. ([PDF](/documents/papers/conrad_et-al_g3-2024.pdf))</li>
      <li>Epstein, G. S., Condit, C. B., Stoner, R. K., Holt, A. F., and Guevara, V., 2024. Evolving Subduction Zone Thermal Structure Drives Extensive Forearc Mantle Wedge Hydration. <em>AGU Advances</em>, 5, doi:10.1029/2023AV001121. ([PDF](/documents/papers/esptein_etal_advances_2024.pdf))</li>
      <li>Goldberg, S. L., and Holt, A. F., 2024. Characterizing the complexity of subduction zone flow with an ensemble of multiscale global convection models. <em>Geochem., Geophys., Geosys.</em>, 25, doi:10.1029/2023GC011134. ([PDF](/documents/papers/goldberg-holt_2024_g3.pdf))</li>
      <li>Turino, V., and Holt, A. F., 2024. Spatio-temporal variability in slab temperature within dynamic 3-D subduction models. <em>Geophys. J. Int.</em>, 236, doi:10.1093/gji/ggad489. ([PDF](/documents/papers/turino-holt_gji-2024.pdf))</li>
      <li>Clennett, E. J., Holt, A. F, Tetley, M. G., Becker, T. W., Faccenna, C., 2023. Assessing plate reconstruction models using plate driving force consistency tests. <em>Sci. Rep.</em>, 13, doi:10.1038/srep2300487. ([PDF](/documents/papers/clennett_et_al_scirep2023.pdf))</li>
      <li>Holt, A. F., 2022. The topographic signature of mantle pressure build-up beneath subducting plates: Insights from spherical subduction models. <em>Geophys. Res. Lett.</em>, 49, doi:10.1029/2022GL100330. ([PDF](/documents/papers/holt_grl2022.pdf))</li>
      <li>Behr, W. M., Holt, A. F., Becker, T. W., Faccenna, C., 2022. The effects of plate interface rheology on subduction kinematics and dynamics. <em>Geophys. J. Int.</em>, 230, doi:10.1093/gji/ggac075. ([PDF](/documents/papers/behr_etal_gji2022.pdf))</li>
      <li>Holt, A. F., and Condit, C. B., 2021. Slab temperature evolution over the lifetime of a subduction zone. <em>Geochem., Geophys., Geosys.</em>, 22, doi:10.1029/2020GC009476. ([PDF](/documents/papers/holt-condit_g3-2021.pdf))</li>
      <li>Faccenna, C., Becker, T. W., Holt, A. F., Brun, J. P., 2021. Mountain building, mantle convection, and supercontinents: Holmes (1931) revisited. <em>Earth Planet. Sci. Lett.</em>, 564, doi:10.1016/j.epsl.2021.116905. ([PDF](/documents/papers/faccenna_et_al_epsl2021.pdf))</li>
      <li>Royden, L. H., and Holt, A. F., 2020. Subduction dynamics and mantle pressure: (i) An Analytical Framework Relating Subduction Geometry, Plate Motion, and Asthenospheric Pressure. <em>Geochem., Geophys., Geosys.</em>, doi:10.1029/2020GC009032. ([PDF](/documents/papers/royden-holt_2020_g3.pdf))</li>
      <li>Holt, A. F., and Royden, L. H., 2020. Subduction dynamics and mantle pressure: (ii) Towards a Global Understanding of Slab Dip and Upper Mantle Circulation. <em>Geochem., Geophys., Geosys.</em>, doi:10.1029/2019GC008771. ([PDF](/documents/papers/holt-royden_2020_g3.pdf))</li>
      <li>Holt, A. F., Royden, L. H., Becker, T. W., Faccenna, C., 2018. Slab interactions in 3-D subduction settings: The Philippine Sea Plate region. <em>Earth Planet. Sci. Lett.</em>, 489, 72-83, doi:10.1016/j.epsl.2018.02.024. ([PDF](/documents/papers/holt_et_al_epsl2018.pdf))</li>
      <li>Király, A., Holt, A. F., Funiciello, C., Capitanio, F., Faccenna, C., 2018. Modeling slab-slab interactions: Dynamics of a double-sided subduction system. <em>Geochem., Geophys., Geosys.</em>, doi:10.1002/2017GC007199. ([PDF](/documents/papers/kiraly_et_al_g3-2018.pdf))</li>
      <li>Faccenna, C., Holt, A. F., Becker, T. W., Lallemand, S., Royden, L. H., 2017. Dynamics of the Ryukyu / Izu-Bonin-Mariana double subduction system. <em>Tectonophys.</em>, doi:10.1016/j.tecto.2017.08.011. ([PDF](/documents/papers/faccenna_et_al_tectono2017.pdf))</li>
      <li>Holt, A. F., Royden, L. H., Becker, T. W., 2017. The dynamics of double slab subduction. <em>Geophys. J. Int.</em>, 209, 250-265, doi:10.1093/gji/ggw496. ([PDF](/documents/papers/holt_et_al_gji2017.pdf))</li>
      <li>Faccenna, C., Oncken, O., Holt, A. F., Becker, T. W., 2017. Initiation of the Andean Orogeny by lower mantle subduction. <em>Earth Planet. Sci. Lett.</em>, 463, 189-201, doi:10.1016/j.epsl.2017.01.041. ([PDF](/documents/papers/faccenna_et_al_epsl2017.pdf))</li>
      <li>Holt, A. F., and Becker, T. W., 2016. The effect of a power-law mantle viscosity on trench retreat rate. <em>Geophys. J. Int.</em>, 208, 491-507, doi:10.1093/gji/ggw392. ([PDF](/documents/papers/holt-becker_gji2017.pdf))</li>
      <li>Holt, A. F., Buffett, B. A., Becker, T. W., 2015. Overriding plate thickness control on subducting plate curvature. <em>Geophys. Res. Lett.</em>, 42, 3802-3810, doi:10.1002/2015GL063834. ([PDF](/documents/papers/holt_et_al_grl2015.pdf))</li>
      <li>Jagoutz, O., Royden, L. H., Holt, A. F., Becker, T. W., 2015. Anomalously fast convergence of India and Eurasia caused by double subduction. <em>Nature Geosc.</em>, 8, 475-478, doi:10.1038/NGEO2418. ([PDF](/documents/papers/jagoutz_et_al_ngeo2015.pdf))</li>
      <li>Holt, A. F., Becker, T. W., Buffett, B. A., 2015. Trench migration and overriding plate stress in thermo-mechanical subduction models. <em>Geophys. J. Int.</em>, 201, 172-192, doi:10.1093/gji/ggv011. ([PDF](/documents/papers/holt_et_al_gji2015.pdf))</li>
      <li>Sun, D., Miller, M. S., Holt, A. F., Becker, T. W., 2014. Hot upwelling conduit beneath the Atlas Mountains, Morocco. <em>Geophys. Res. Lett.</em>, 41, 8037-8044, doi:10.1002/2014GL061884. ([PDF](/documents/papers/sun_et_al_grl2015.pdf))</li>
    </ol>
    <h3>Other</h3>
    <p>Holt, A. F., 2016. <em>Trench migration, slab bending, and mantle flow at subduction zones</em>, Ph.D. thesis, University of Southern California, Los Angeles CA. ([PDF](/documents/papers/holt_PhDThesis_2016.pdf))</p>
  </section>
</div>
