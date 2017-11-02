+++
# Date this page was created.
date = "2016-04-27"

# Project title.
title = "Summer Intern"

# Project summary to display on homepage.
summary = "Constraining the nature of the LLSVPs using observations of geoid and dynamic topography"

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "llsvp/tomo.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["summer-intern","LLSVP","geoid","dynamic-topography"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "llsvp/origin.png"
caption = "[**Interpretations of LLSVPs,Garnero,2016**](http://www.nature.com/ngeo/journal/v9/n7/abs/ngeo2733.html)"

+++

Origin of the two LLSVPs inside the lower mantle is heavily debated,from purely thermal to purely compositional. These features are presumably very important for modulating Earth’s long-term evolution such as the main heat source for generating mantle plumes and surface volcanism. We want to place better constraints on these mantle structures through examining their geodynamic properties.

With the finite element code [CitcomS](https://geodynamics.org/cig/software/citcoms/), I built a thermal chemical model to explore the response of different viscosity profile (and LVV,lateral viscosity variation) , scaling between tomography and density and chemical buoyancy. Some progress has been made but now I am still trying to seek a best fit to observation in my model.

You can get more information from my {{% staticref "summer-intern/Report.pdf" %}}report{{% /staticref %}} and {{% staticref "summer-intern/Figure.pdf" %}}figures{{% /staticref %}} (too much figures, divided version is more reading-friendly).
