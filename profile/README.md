# SuCCESs Integrated Assessment Model 

<!--

**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->

This is the home of the SuCCESs integrated assessment model (IAM) and it's land-use module CLASH.

SuCCESs is a lightweight, global IAM that covers energy, land-use, materials and climate. It's an intertemporal partial equilibrium model that finds the minimum cost solution to satisfy projected demands for energy, transportation, materials and food, while also satisfying other constraints, like climate targets. The model runs from 2020 to 2100 in 10-year time steps.

Both SuCCESs and CLASH are written in GAMS, and you additionally need an optimization solver (preferably an LP solver) to run SuCCESs. CLASH is not primarily meant to run stand-alone, but linked to an IAM (as it in our case is with SuCCESs).

[SuCCESs IAM is available here](https://github.com/SuCCESsIAM/SuCCESsIAM) and is described in the paper [SuCCESs – a global IAM for exploring the interactions between energy, materials, land-use and climate systems in long-term scenarios](https://gmd.copernicus.org/preprints/gmd-2024-196/) (preprint).

[A python toolbox](https://github.com/SuCCESsIAM/SuCCESsIAM-toolbox) is also available for post-processing and plotting results from the model. This should give ideas and a starting point for new users for what the model can do.

[CLASH is available here](https://github.com/SuCCESsIAM/CLASH) and described in detail in the paper ["CLASH - Climate-responsive Land Allocation model with carbon Storage and Harvests", published in Geoscientific Model Development](https://gmd.copernicus.org/articles/17/3041/2024/).
